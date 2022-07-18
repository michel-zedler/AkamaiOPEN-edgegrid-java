# Change log

## 4.1.1 (February 17, 2022)

### Enhancements

* Added OWASP dependency check plugin to maven pipeline.

### Fixes

* Fix multiple CVE vulnerabilities by upgrading logback and netty dependencies.
* Fix Travis build by updating Java version to 8.
* Correct README.md inconsistencies.

## 4.1.0 (August 26, 2021)

### Enhancements

* Upgrade project dependencies.
* Ensure compatibility with Java >= v9.

## 4.0.1

### Fixes

* Fix Issue #35, a broken unit test.
* Use [URI#getRawPath()](https://docs.oracle.com/javase/8/docs/api/java/net/URI.html#getRawPath--) when constructing a signature.

## 4.0

### BREAKING CHANGES

* Split the edgerc file reader into new module [edgerc-reader](edgerc-reader).
* Drop dependency on commons-configuration2 from edgegrid-signer-core.
* Drop dependency on commons-lang3.
* Drop dependency on commons-codec (use Base64 methods from JDK instead).
* Use maven-bundle-plugin to add OSGi headers to MANIFEST.MF.

## 3.0

### BREAKING CHANGES

* Minimum Java version is now 8.

### Improvements

* Adding binding for Async HTTP Client.
* Adding binding for Gatling.

## 2.1

### Improvements

* Adding binding for Apache HTTP Client.
* Splitting README.md between relevant modules.

## 2.0

### Improvements

* Signing algorithm tweaks
* Separating binding for Google HTTP Client Library for Java from core
* Adding binding for REST-assured
* Unit tests with TestNG
* Publishing to Maven Central!