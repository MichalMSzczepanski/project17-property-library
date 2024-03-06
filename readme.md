# Property Library

This is a maven project that contains common properties for the presentday project:

- kafka topics
- credentials

## Prerequisites

- maven

## Building locally

In order to add this library as a dependency to any presentday service do the following:

1. install the library package to your local .m2:

`mvn install`

2. add dependency to project (those requiring should have it added)

```xml
<dependency>
    <groupId>work.szczepanskimichal</groupId>
    <artifactId>property-library</artifactId>
    <version>1.0.0</version>
</dependency>
