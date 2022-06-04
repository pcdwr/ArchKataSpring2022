# Micro-Services

## Status
Accepted

## Context
Should the business functionality be implemented in server functions vs micro-services?

## Decision
The functionality will be implemented using cloud functions. A micro service requires significant planning and investment even for a minimal implementation.

## Consequences

### Pros
* More predicatable
* More control of implementation
* More control of performance

### Cons
* Less flexibility after initial implementation
* Significant monitoring and alerting must be defined
* Significant skill set required to maintain over time
* More difficult to create a pay as you go implementation