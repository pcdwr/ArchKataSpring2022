# Alerting

## Status
Accepted

## Context
Based on the toolkit used for logging and monitoring the system will need a method of proactively observing issues.

## Decision
Since the system will utilize Firebase, the Firebase Performance Monitoring alerting tool will be used to generate alerts.

## Consequences

### Pros
Easy and free to implement.

### Cons
If the decision is made to use something other than Firebase this will need to be revisited.