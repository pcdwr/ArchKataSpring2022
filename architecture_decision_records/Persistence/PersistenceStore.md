# Persistence Store

## Status
Completed

## Context
A persistent data store is required for the application. The following choices were considered:

* RDBMS
    * Hosted server
    * Managed service
* NoSql
    * Hosted server
    * Managed service

## Decision
A NoSQL managed service is to be utillized. The determining factors were:
* Hosted servers were dismissed due to cost and long term maintenance costs
* A managed RDBMS was dismissed as the long term maintenance costs of changin schemas is considered overkill
* A managed NoSQL database was chosen as this can be flexible during initial development
* Google Firestore was chosen as it is priced based on usage and is supported concurrently in multiple regions eliminating the need for backups. Backups are only required when/if records can be deleted by users.

## Consequences

### Pros

### Cons
