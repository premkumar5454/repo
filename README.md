# <project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>
	<groupId>pl.piomin</groupId>
	<artifactId>sample-spring-microservices</artifactId>
	<version>1.0-SNAPSHOT</version>
	<packaging>pom</packaging>

	<parent>
		<groupId>org.springframework.cloud</groupId>
		<artifactId>spring-cloud-starter-parent</artifactId>
		<version>Brixton.RELEASE</version>
	</parent>

	<properties>
		<spring.boot>1.4.2.RELEASE</spring.boot>
		<spring.boot.eureka>1.2.2.RELEASE</spring.boot.eureka>
		<java.version>1.8</java.version>
	</properties>

	<modules>
		<module>discovery-service</module>
		<module>account-service</module>
		<module>gateway-service</module>
		<module>customer-service</module>
		<module>zipkin-service</module>
	</modules>

</project>
