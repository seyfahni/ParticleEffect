ParticleEffect
==============

This a library which allows you to display particle effects with Bukkit/Spigot. See http://bukkit.org/threads/1-8-particleeffect-v1-6.154406/ for more information about this project!

Documentation here: http://ci.sinndevelopment.com/job/ParticleEffect%20Library/javadoc/

## Maven Dependency Information:
```
        <repository>
            <id>seyfahni-repo</id>
            <url>https://https://maven.seyfahni.de/repository/snapshots/</url>
        </repository>
        
        <dependency>
            <groupId>com.darkblade12</groupId>
            <artifactId>particleeffect</artifactId>
            <version>1.7.1-SNAPSHOT</version>
        </dependency>
        
        <plugin>
            <groupId>org.apache.maven.plugins</groupId>
            <artifactId>maven-shade-plugin</artifactId>
            <version>2.4.1</version>
            <configuration>
                <artifactSet>
                    <includes>
                        <include>com.darkblade12:*</include>
                    </includes>
                </artifactSet>
            </configuration>
            <executions>
                <execution>
                    <phase>package</phase>
                    <goals>
                        <goal>shade</goal>
                    </goals>
                </execution>
            </executions>
        </plugin>
```
