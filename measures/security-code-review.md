# Security code review
Things to consider while performing security code review

## Credentials
* Hardcoded credentials
* How credentials are generated, stored, transmitted, validated
  
## Logging
* Is the logging sufficient
* Are any PII or credentials unintentionally logged

## File path construction
* Is the path constructed from the user supplied value

## Data Query construction
* Is the query concatenated with user supplied input
* Is the user supplied input properly validated/sanitized

## Third-party dependencies
* Are third-party dependencies up to date
* Any vulnerable components
* Any violation of licenses
