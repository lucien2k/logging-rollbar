# logging-rollbar

This version of the standard python logging library that has built in support for rollbar (http://www.rollbar.com)

Usage is similar to normal logging:

> import logging_rollbar as logging

> logging.basicConfig(filename='LOG_FILE', rollbar_access_token='ROLLBAR_ACCESS_TOKEN', rollbar_environment='production')

> logging.error('this is an error')

> logging.error('this is an error with an exception', exc_info=1)

# logging-rollbar v0.1

First version of python logging with rollbar

Similar interface to https://docs.python.org/2/library/logging.html

This code is contributed by RazorSecure for use with the Rollbar system