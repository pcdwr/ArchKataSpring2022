# WebCDN

## Status
Completed

## Context
The assets for the web browser must be accessible from a well known URL. This URL and a CDN for edge distribution are required. Developing as a responsive app also provides the ability to access the UI from a mobile phone.

## Decision
The web assets will be distrubuted through the CDN provided in the Firebase subscription.

## Consequences

### Pros
Least expensive option which is accessible from all devices.

### Cons
Other alternatives will have to be explored if the Firebase subscription is not kept current.
