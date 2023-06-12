# Logging in python

In this meetup we will cover how to do logging in Python.

[01-simple](01-simple) will go through some simple usage of logger. In [02-namespaces](02-namespaces) we will go through how to use namespaces to configure loggers at different levels and how to set the level of loggers within the same namespace. This further extended to a package in [03-namespace-as-package](04-handlers-and-formatters) we go through how to set up handlers and formatters and finally in [05-configuration](05-configuration) we show different ways of configuring the loggers.



## Additional resources

- Basic and advanced tutorial: https://docs.python.org/3/howto/logging.html
- Logging cookbook: https://docs.python.org/3/howto/logging-cookbook.html
- API documentation: https://docs.python.org/3/library/logging.html
- PEP282: https://peps.python.org/pep-0282/

## Other libraries
There are also a large number of libraries for doing logging and which might be easier an more suitable for your use case. Here I list some of them

- [`structlog`](https://www.structlog.org/en/stable/)
- [`loguru`](https://github.com/Delgan/loguru)
- [`daiquiri`](https://github.com/Mergifyio/daiquiri)
- [`picologging`](https://github.com/microsoft/picologging)