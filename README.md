# springboot-3rd-edition

<img src="https://github.com/mario1980miranda/springboot-3rd-edition/assets/13603605/24e2656a-8a97-41c5-ba30-d0a988892c66" width="600"/>

## Maven Frontend Plugin

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
```
