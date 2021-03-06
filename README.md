# gpi for corporate java client [![Build Status](https://travis-ci.com/swiftinc/gpi-tracker-g4c-java.svg?branch=master)](https://travis-ci.com/swiftinc/gpi-tracker-g4c-java)

## Overview

The client classes are generated by swagger-codegen, we added unit tests, example tests and a helper class to help you consume the GPI for corporate API.


## Installation

To install the API client library to your local Maven repository, simply execute:

```shell
mvn install
```

### Maven users

Add this dependency to your project's POM:

```xml
<dependency>
    <groupId>com.swift.gpi.tracker</groupId>
    <artifactId>g4csdk</artifactId>
    <version>1.0.0</version>
    <scope>compile</scope>
</dependency>
```

### Others

At first generate the JAR by executing:

    mvn package

Then manually install the following JARs:

* target/g4csdk-1.0.0.jar


## Example for API Endpoints

All URIs are relative to *https://sandbox.swift.com/api-tracker-for-corporates-pilot/v2*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*SearchingForCorporatePaymentTransactionsApi* | [**getCorporatePaymentTransactionsPost**](docs/SearchingForCorporatePaymentTransactionsApi.md#getCorporatePaymentTransactionsPost) | **POST** /get_corporate_payment_transactions | Searching for corporate payment transactions


## Documentation for Models

 - [ActiveOrHistoricCurrencyAndAmount](docs/ActiveOrHistoricCurrencyAndAmount.md)
 - [CamtA0800101](docs/CamtA0800101.md)
 - [CamtA0800201](docs/CamtA0800201.md)
 - [ChargeBearerType3Code](docs/ChargeBearerType3Code.md)
 - [CurrencyExchange8](docs/CurrencyExchange8.md)
 - [DateTimePeriodDetails](docs/DateTimePeriodDetails.md)
 - [ErrorCode](docs/ErrorCode.md)
 - [ErrorCodeStatus](docs/ErrorCodeStatus.md)
 - [GetCorporatePaymentTransactionsRequest](docs/GetCorporatePaymentTransactionsRequest.md)
 - [GetCorporatePaymentTransactionsResponse](docs/GetCorporatePaymentTransactionsResponse.md)
 - [PaymentEvent6](docs/PaymentEvent6.md)
 - [PaymentReason2Code](docs/PaymentReason2Code.md)
 - [PaymentStatus4](docs/PaymentStatus4.md)
 - [PaymentTransaction75](docs/PaymentTransaction75.md)
 - [TransactionIndividualStatus5Code](docs/TransactionIndividualStatus5Code.md)


## Documentation for Authorization

All endpoints do not require authorization.
Authentication schemes defined for the API:

## Recommendation

It's recommended to create an instance of `ApiClient` per thread in a multithreaded environment to avoid any potential issues.

## Author

Hassan.MOLLAH@swift.com

