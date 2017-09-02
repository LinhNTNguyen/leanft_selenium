# leanft_selenium
What is LeanFT and how to combine LeanFT with Selenium
# Add the LeanFT and Selenium libraries 
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">

    <modelVersion>4.0.0</modelVersion>
    <groupId></groupId>
    <artifactId></artifactId>
    <version>1.0</version>
    <name>LeanFT Application Model</name>
    <description>LeanFT Application Model</description>

    <dependencies>
        <dependency>
            <groupId>com.hp.lft</groupId>
            <artifactId>sdk</artifactId>
            <version>14.0.0</version>
        </dependency>

        <dependency>
            <groupId>com.hp.lft</groupId>
            <artifactId>sdk</artifactId>
            <version>14.0.0</version>
            <classifier>javadoc</classifier>
        </dependency>
        <!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java -->
        <dependency>
            <groupId>org.seleniumhq.selenium</groupId>
            <artifactId>selenium-java</artifactId>
            <version>3.5.3</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-server -->
        <dependency>
            <groupId>org.seleniumhq.selenium</groupId>
            <artifactId>selenium-server</artifactId>
            <version>3.5.3</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/commons-io/commons-io -->
        <dependency>
            <groupId>commons-io</groupId>
            <artifactId>commons-io</artifactId>
            <version>2.5</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/org.beanshell/bsh -->
        <dependency>
            <groupId>org.beanshell</groupId>
            <artifactId>bsh</artifactId>
            <version>2.1b5</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/cglib/cglib-nodep -->
        <dependency>
            <groupId>cglib</groupId>
            <artifactId>cglib-nodep</artifactId>
            <version>3.2.5</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/commons-codec/commons-codec -->
        <dependency>
            <groupId>commons-codec</groupId>
            <artifactId>commons-codec</artifactId>
            <version>1.10</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/commons-io/commons-io -->
        <dependency>
            <groupId>commons-io</groupId>
            <artifactId>commons-io</artifactId>
            <version>2.5</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/org.apache.commons/commons-exec -->
        <dependency>
            <groupId>org.apache.commons</groupId>
            <artifactId>commons-exec</artifactId>
            <version>1.3</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/commons-logging/commons-logging -->
        <dependency>
            <groupId>commons-logging</groupId>
            <artifactId>commons-logging</artifactId>
            <version>1.2</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/com.google.code.gson/gson -->
        <dependency>
            <groupId>com.google.code.gson</groupId>
            <artifactId>gson</artifactId>
            <version>2.8.1</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/com.google.guava/guava -->
        <dependency>
            <groupId>com.google.guava</groupId>
            <artifactId>guava</artifactId>
            <version>23.0</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/org.hamcrest/hamcrest-core -->
        <dependency>
            <groupId>org.hamcrest</groupId>
            <artifactId>hamcrest-core</artifactId>
            <version>1.3</version>
            <scope>test</scope>
        </dependency>
        <!-- https://mvnrepository.com/artifact/org.hamcrest/hamcrest-library -->
        <dependency>
            <groupId>org.hamcrest</groupId>
            <artifactId>hamcrest-library</artifactId>
            <version>1.3</version>
            <scope>test</scope>
        </dependency>
        <!-- https://mvnrepository.com/artifact/org.apache.httpcomponents/httpclient -->
        <dependency>
            <groupId>org.apache.httpcomponents</groupId>
            <artifactId>httpclient</artifactId>
            <version>4.5.3</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/org.apache.httpcomponents/httpcore -->
        <dependency>
            <groupId>org.apache.httpcomponents</groupId>
            <artifactId>httpcore</artifactId>
            <version>4.4.6</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/org.apache.httpcomponents/httpmime -->
        <dependency>
            <groupId>org.apache.httpcomponents</groupId>
            <artifactId>httpmime</artifactId>
            <version>4.5.3</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/com.beust/jcommander -->
        <dependency>
            <groupId>com.beust</groupId>
            <artifactId>jcommander</artifactId>
            <version>1.72</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/net.java.dev.jna/jna -->
        <dependency>
            <groupId>net.java.dev.jna</groupId>
            <artifactId>jna</artifactId>
            <version>4.4.0</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/net.java.dev.jna/jna-platform -->
        <dependency>
            <groupId>net.java.dev.jna</groupId>
            <artifactId>jna-platform</artifactId>
            <version>4.4.0</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/junit/junit -->
        <dependency>
            <groupId>junit</groupId>
            <artifactId>junit</artifactId>
            <version>4.12</version>
            <scope>test</scope>
        </dependency>
        <!-- https://mvnrepository.com/artifact/io.netty/netty -->
        <dependency>
            <groupId>io.netty</groupId>
            <artifactId>netty</artifactId>
            <version>3.10.6.Final</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/com.github.detro.ghostdriver/phantomjsdriver -->
        <dependency>
            <groupId>com.github.detro.ghostdriver</groupId>
            <artifactId>phantomjsdriver</artifactId>
            <version>1.1.0</version>
        </dependency>
        <!-- https://mvnrepository.com/artifact/org.testng/testng -->
        <dependency>
            <groupId>org.testng</groupId>
            <artifactId>testng</artifactId>
            <version>6.11</version>
            <scope>test</scope>
        </dependency>

    </dependencies>

    <repositories>
        <!--<repository>
                <id>Your repository's ID</id>
                <name>Your repository's name</name>
                <url>URL of the repository containing the LeanFT jar files</url>
            </repository>-->
    </repositories>

    <build>
        <plugins>
            <plugin>
                <groupId>org.apache.maven.plugins</groupId>
                <artifactId>maven-compiler-plugin</artifactId>
                <configuration>
                    <source>1.7</source>
                    <target>1.7</target>
                </configuration>
            </plugin>

            <plugin>
                <groupId>org.codehaus.mojo</groupId>
                <artifactId>build-helper-maven-plugin</artifactId>
                <version>1.10</version>
                <executions>
                    <execution>
                        <id>add-source</id>
                        <phase>generate-sources</phase>
                        <goals>
                            <goal>add-source</goal>
                        </goals>
                        <configuration>
                            <sources>
                                <source>appmodels</source>
                            </sources>
                        </configuration>
                    </execution>
                </executions>
            </plugin>
        </plugins>
        <pluginManagement>
            <plugins>
                <!--This plugin's configuration is used to store Eclipse m2e settings only. It has no influence on the Maven build itself.-->
                <plugin>
                    <groupId>org.eclipse.m2e</groupId>
                    <artifactId>lifecycle-mapping</artifactId>
                    <version>1.0.0</version>
                    <configuration>
                        <lifecycleMappingMetadata>
                            <pluginExecutions>
                                <pluginExecution>
                                    <pluginExecutionFilter>
                                        <groupId>
                                            org.codehaus.mojo
                                        </groupId>
                                        <artifactId>
                                            build-helper-maven-plugin
                                        </artifactId>
                                        <versionRange>
                                            [1.10,)
                                        </versionRange>
                                        <goals>
                                            <goal>add-source</goal>
                                        </goals>
                                    </pluginExecutionFilter>
                                    <action>
                                        <ignore></ignore>
                                    </action>
                                </pluginExecution>
                            </pluginExecutions>
                        </lifecycleMappingMetadata>
                    </configuration>
                </plugin>
            </plugins>
        </pluginManagement>
    </build>
</project>
