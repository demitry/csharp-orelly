## Abstract Factory Problem

- App needs to support multiple DB types.
    - SQL Server, Oracle, MySQL
- Measurement data comes from different sources
    - Serial port, Eth, device driver
- Needs to create different report types
    - PDF, Word, doc.

## Abstract Factory Pattern
- Provides an abstract class
    - Generalized interface
    - Hides details from rest of application
    - Factory class creates an instance of a class that inherits or implements the abstract class
    - In conjunction with Factory Method Pattern

## Example
- Database abrstract class
    - Connection property (System.Data.Common.DBConnection)
    - Command property (System.Data.Common.DBCommand)

- Abstract class cannot be instantiated
    - Instant classes must inherit from it

