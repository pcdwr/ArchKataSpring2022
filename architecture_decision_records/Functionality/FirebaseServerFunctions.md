# Firebase Server Functions

## Status
Accepted

## Context
Should the business functionality be implemented in server functions vs micro-services?

## Decision
The functionality will be implemented using cloud functions. This processing is available in the Firebase project on a pay as you go basis.

## Consequences

### Pros
* Reduced development time and effort.
* Very flexible approach as object functions may be triggered from a variety of events.

### Cons
* As the application grows this becomes harder to maintain.
* As transaction volume increases this can be an expensive approach
* Performance can be unpredictable (possibly even unsatisfactory) in real time situations