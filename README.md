# Currency Fetcher Library

**Currency Fetcher** is a Java library designed to fetch and parse currency data from an external API. It supports retrieving both the latest and historical currency rates.

## Features

- Fetch the latest currency rates.
- Fetch historical currency rates for specific dates.
- Handle future dates by retrieving the latest available rate.

## Installation

### Maven

Add the following dependency to your `pom.xml`:

```xml
<dependency>
    <groupId>com.pdp</groupId>
    <artifactId>currency-fetcher</artifactId>
    <version>1.0.0</version>
</dependency>
```
Gradle
Add the following to your build.gradle:

gradle
Copy code
```text
dependencies {
    implementation 'com.pdp:currency-fetcher:1.0.0'
}
```
Usage

Fetch Latest Currency Rate
Use the CurrencyFetcher.getCurrency(CurrencyType currencyType) method to get the latest rate for a specified currency.
Fetch Currency Rate for a Specific Date
Use the CurrencyFetcher.getCurrency(CurrencyType currencyType, LocalDate date) method to get the rate for a specific date. If the date is in the future, the method will return the latest available rate.
License

This library is licensed under the MIT License. See the LICENSE file for details.

vbnet
Copy code

This version of the `README.md` provides an overview of the library's features, installation instructions, usage, and license information without diving into Java code examples.