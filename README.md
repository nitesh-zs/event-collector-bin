# Event-Collector-Bin

This repository contains binaries for event-collector's boh-check process intended to be used by QA team for testing of the event-collector project.

## How to use the project:

- Clone this repository.
- Create a file `.local.env` under the `configs` folder.
- Copy the internally shared eventhub credentials in `.local.env`.
- Run the application as:

    ```./ec_part2_amd64 assortment-status```

