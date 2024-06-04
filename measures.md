# Measures
* [Security Code Review](#security-code-review)

## Security code review
Things to consider while performing security code review

### Credentials
* Hardcoded credentials
* How credentials are generated, stored, transmitted, validated
  
### Logging
* Is the logging sufficient
* Are any PII or credentials unintentionally logged

### Data Query construction
* Is the query concatenated with user supplied input
* Is the user supplied input properly validated/sanitized
