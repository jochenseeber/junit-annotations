# JUnit Annotations

This project contains [external annotations](https://wiki.eclipse.org/JDT_Core/Null_Analysis/External_Annotations) for
[JUnit](http://junit.org/junit4/) version 4.12.

These annotations allow Eclipse to perform null analysis.

## Usage

To build the annotations JAR, run

```bash
gradle build
```

This will create the file `junit-annotations-4.12-r.4.jar`. Attach this file to the
JUnit library entry in your build path to have Eclipse use the annotations.