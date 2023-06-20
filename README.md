# Maven Frontend Plugin

Adds Node.js actions to Maven`s lifecycle.

```
<plugin>
	<groupId>com.github.eirslett</groupId>
	<artifactId>frontend-maven-plugin</artifactId>
	<version>1.12.1</version>
	<executions>
		<execution>
			<goals>
				<goal>install-node-and-npm</goal>
			</goals>
		</execution>
	</executions>
	<configuration>
		<nodeVersion>v16.14.2</nodeVersion>
	</configuration>
</plugin>
```

```bash
mvn generate-resources
```# springboot-3rd-edition
