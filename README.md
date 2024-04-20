# Awesome FHIR

Community curated list of FHIR related artifacts.

You are welcome to send in a pull request with FHIR work!

## Menu

### Libraries

See official list of reference libraries
[here (fhir.org)](https://www.hl7.org/fhir/downloads.html) or
[here (fhir wiki)](http://wiki.hl7.org/index.php?title=Open_Source_FHIR_implementations)

* Java
  * [Client/Server](https://github.com/hapifhir/hapi-fhir)
* C#
  * [Client](https://github.com/FirelyTeam/fhir-net-api)
  * [UCUM metrics conversion](https://github.com/FirelyTeam/Fhir.Metrics)
  * [Server](https://github.com/FirelyTeam/spark)
  * [Generator](https://github.com/Aidbox/fhirsharp) - Early steps
* JavaScript
  * [Client fhir.js](https://github.com/FHIR/fhir.js)
  * [Client FHIRKit](https://www.npmjs.com/package/fhir-kit-client)
  * [Client SMART on FHIR](https://github.com/smart-on-fhir/client-js)
  * [FHIRKit create-react-app template](https://github.com/Vermonster/fhir-kit-create-react)
  * [FHIRPath implementation](https://github.com/hl7/fhirpath.js/)
  * [FHIR Dosage Utils](https://github.com/jy95/fhir-dosage-utils)
* XML
  * [Tools](https://www.hl7.org/fhir/fhir-3.0.1-XMLTools-0.01.zip)
* Pascal
  * [Server & Lib](http://github.com/grahamegrieve/fhirserver)
* Swift
  * [Official](https://github.com/smart-on-fhir/Swift-FHIR)
* Ruby
  * [Client](https://github.com/fhir-crucible/fhir_client)
* Python
  * [Client SMART on FHIR](https://github.com/smart-on-fhir/client-py)
  * [FHIR-PY](https://github.com/beda-software/fhir-py) - FHIR client for python
* SQL
  * [PostgreSQL/fhirbase](https://www.health-samurai.io/fhirbase)
* Go - ?
* Objective-C - ?
* PHP - ?
* C/C++ - ?
* Rust - ?
* Haskel - ?
* Scala - ?
* Kotlin
  * [Android FHIR SDK](https://github.com/google/android-fhir) - a set of Kotlin libraries for building offline-capable, mobile-first healthcare applications using FHIR on Android.
* Lua
  * [XML ⟷ JSON converter](https://github.com/vadi2/fhir-formats)

### SMART on FHIR

### Test Servers

Here is a list of [Publicly  Available FHIR Servers](http://wiki.hl7.org/index.php?title=Publicly_Available_FHIR_Servers_for_testing) for testing

#### Dockerized examples servers

* [SMART on FHIR - HAPI example](https://github.com/smart-on-fhir/hapi)

### Open Source Servers

* [HAPI](http://hapifhir.io/) -HAPI FHIR is a simple-but-powerful library for adding FHIR messaging to your application. It is pure Java (1.6+ compatible), and licensed under the business-friendly Apache Software License, version 2.0.
* [MS FHIR server](https://github.com/microsoft/fhir-server) - FHIR Server for Azure is an open-source implementation of the emerging HL7 Fast Healthcare Interoperability Resources (FHIR) specification designed for the Microsoft cloud.
* [Spark](https://github.com/firelyTeam/spark) - Spark FHIR Server is an open-source C# implementation (.NET Framework 4.6.1+, .NET Standard 2.0 and .NET Core compatible). Supports DSTU2, STU3 and R4 versions of the specification.
* [Node on FHIR](https://github.com/symptomatic/node-on-fhir) - JavaScript Meteor-based stack, with server and application using many of the other available Javascript libraries
* [IBM FHIR server](https://github.com/IBM/FHIR) - The IBM FHIR Server is a modular Java implementation of version 4

### Proprietary Servers

* [Aidbox](https://www.health-samurai.io/aidbox) - Advanced FHIR backend built on top of fhirbase

### Terminology servers

* [Ontoserver](https://ontoserver.csiro.au)

### Profiling

* [fhir shorthands](https://github.com/HL7/fhir-shorthand) - FHIR Shorthand (FSH) is a specially-designed language for defining the content of FHIR Implementation Guides
* [igpop](https://github.com/HealthSamurai/igpop) YAML (data) DSL for FHIR profiles

## Databases

[SQL on FHIR](https://github.com/FHIR/sql-on-fhir/blob/master/sql-on-fhir.md) draft specification.

[Zulip Chat](https://chat.fhir.org/#narrow/stream/179219-analytics-on.20FHIR)

* BigQuery - Load FHIR data into [BigQuery](https://github.com/fhir-fuel/fhir-storage-and-analytics-track/tree/master/bigquery)
* PostgreSQL
  * [Fhirbase](https://www.health-samurai.io/fhirbase) is an open source toolkit for storing and working with FHIR data, built on top of PostgreSQL.
* MongoDB
* Spark
  * [Bunsen](https://github.com/cerner/bunsen) - Bunsen lets users load, transform, and analyze FHIR data with Apache Spark
* Hadoop
* MS SQL
* Oracle
* MySQL
* Neo4J

### Test FHIR

[Source](http://wiki.hl7.org/index.php?title=FHIR_Testing_Platforms)

The following systems provide support for automated testing of FHIR clients and/or servers, including leveraging the TestScript and TestReport resources:

* [https://projectcrucible.org/ Crucible] open source testing tools for FHIR
* [http://touchstone.com/ Touchstone] testing FHIR Client or Servers using Test-Driven-Development (TDD)
* [Wind.Tunnel](https://github.com/FirelyTeam/Wind.Tunnel) - Performance & stress testing for your FHIR server.
* [stresty](https://github.com/Aidbox/stresty) - simple yaml based tests for REST (FHIR) servers

### Data Sets

* [synthea](https://github.com/synthetichealth/synthea) - Synthetic Patient Population Simulator
* [Dockerized synthea](https://github.com/smart-on-fhir/synthea) - Static contenerized version of Synthea
* [FHIR Examples](https://www.hl7.org/fhir/downloads.html) - Examples coming with FHIR distribution

### Profiling for DB

### JSON Schema

### CDS Hooks

### Bulk Data


### HL7v2 to FHIR

### CDA(CCD) to FHIR

### Mapping

* [JUTE](https://github.com/HealthSamurai/jute.js) - mapping language in js with examples for HL7v2->FHIR transformations

### FHIRpath

* [fhirpath.js](https://github.com/hl7/fhirpath.js/) - implementation of FHIRPath in javascript - [demo](https://hl7.github.io/fhirpath.js/)
* [fhirpath.clj](https://github.com/HealthSamurai/fhirpath.clj) - FHIRPath in clojure

### CQL

## Books

* [Principles of Health Interoperability](https://www.springer.com/gp/book/9783319303680)

## Blogs

* [Health Intersections](http://www.healthintersections.com.au/) - Healthcare Interoperability by Grahame Grieve
* [Healthcare Exchange Standards](https://healthcaresecprivacy.blogspot.com/)
* [fhirblog](https://fhirblog.com/) - by David Hay
* [niquola](https://medium.com/@niquola) - by Nikolai Ryzhikov
