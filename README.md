# composite-testing
Composite pom containing common test dependencies.  Since 2.1 this is based on TestNG rather than Junit.

Example use:

Make sure to remember to use *type* *pom*

```xml

    <dependency>
      <groupId>org.avaje.composite</groupId>
      <artifactId>composite-testing</artifactId>
      <version>2.1</version>
      <type>pom</type>  <!-- Remember type pom !! -->
      <scope>test</scope>
    </dependency>

```
