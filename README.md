# Takari Maven Timeline

## How to generate a timeline for your project

To generate a timeline for your project add this section to your `pom.xml`:

```xml
<extensions>
  <extension>
    <groupId>io.takari.maven</groupId>
    <artifactId>maven-timeline</artifactId>
    <version>1.8</version>
  </extension>
</extensions>
```


Once your project has run you will have a `target/timeline/timeline.html` in the top-level of your project. The output will look something like the following:

![Maven Timeline](maven-timeline.png)
