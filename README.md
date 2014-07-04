# Overview

Official SDK: [http://www.maximintegrated.com/en/products/ibutton/software/sdk/sdks.cfm](http://www.maximintegrated.com/en/products/ibutton/software/sdk/sdks.cfm)

Official documentation: [http://files.maximintegrated.com/sia_bu/softdev/owapi/](http://files.maximintegrated.com/sia_bu/softdev/owapi/)

# Using

 * Just add in your pom.xml **repository**:
    ```xml
    <repository>
        <id>owapi-mvn-repo</id>
        <url>https://raw.github.com/creepid/owapi/mvn-repo/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
    ```
    
    and **dependency**:
    ```xml
    <dependency>
			<groupId>com.dalsemi.onewire</groupId>
			<artifactId>owapi</artifactId>
			<version>1.10</version>
	</dependency>
    ```

* For git maven repo deploy:
    ```xml
    	mvn clean deploy
    ```
