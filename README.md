# clojure-pom

A generic parent pom.xml for Clojure projects, based on mikera-pom

### Motivation

I needed a generic parent pom.xml for my increasing collection of Clojure projects.

This pom is fairly minimal, and just includes the basics needed to get up and running effectively.

### Some design decisions

 - Currently using `clojure-maven-plugin`
 - I will always update to use the latest released version of Clojure (currently 1.4)
 - I've included  `src/main/clojure` and `src/test/clojure` as resource directories. This is so that you can load .clj files at runtime as resources.