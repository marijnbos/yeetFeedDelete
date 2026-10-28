
# yeetFeedDelete

A POC on how to reduce cloud cost by filtering incoming OTEL data.


## Features (todo)

* EPIC: filtering of otel data for certain 'SeverityNumber'
* EPIC: grouping logs and traces to reduce input in storage for certain confurable time period

| SeverityNumber range | Range name | Meaning                                                                                 |
| -------------------- | ---------- | --------------------------------------------------------------------------------------- |
| 1-4                  | TRACE      | A fine-grained debugging event. Typically disabled in default configurations.           |
| 5-8                  | DEBUG      | A debugging event.                                                                      |
| 9-12                 | INFO       | An informational event. Indicates that an event happened.                               |
| 13-16                | WARN       | A warning event. Not an error but is likely more important than an informational event. |
| 17-20                | ERROR      | An error event. Something went wrong.                                                   |
| 21-24                | FATAL      | A fatal error such as application or system crash.                                      |

[source](https://opentelemetry.io/docs/specs/otel/logs/data-model/)

## Authors

- [@marijnbos](https://github.com/marijnbos)


## Demo

todo :D


## Run Locally
### prerequisites
See : https://aspire.dev/get-started/prerequisites/


Clone the project

```bash
  git clone https://github.com/marijnbos/yeetFeedDelete
```

Go to the project directory

```bash
  cd /workspaces/yeetFeedDelete/AspireApp
```
Run aspire run
```
aspire run
```


## Documentation

[Documentation](https://github.com/marijnbos/yeetFeedDelete/wiki)


## License
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

