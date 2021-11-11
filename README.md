Overall, this repository is structured as follows:

```
├── set01                # Code examples for Set 1.
├── set02                # Code examples for Set 2.
├── ...
├── .pre-commit-config.yaml  # Pre-commit config for the CI.
├── CHANGELOG.md             # Changelog detailing updates to the code.
├── LICENSE                  # Code license.
├── README.md                # This readme.
└── requirements.txt         # CI dependencies.
```

The *setXX* directories contain the code examples for each specific Chapter.

Code for each Set is generally structured something like follows:

```
├── dags                  # Airflow DAG examples (+ other code).
├── docker-compose.yml    # Docker-compose file used for running the Chapter's containers.
└── readme.md             # Readme with Chapter-specific details, if any.
```

### Usage

Details for running specific Set examples are available in the corresponding set's readme. In general, most code examples are run using docker-compose, together with the provided docker-compose.yml file in each set. This docker-compose file will take care of spinning up the required resources and start an Airflow instance for you. Once everything is running, you should be able to run the examples in Airflow using your local browser.

Some later Sets (such as Sets 11 and 13) may require a bit more setup. The details for doing so are described in the corresponding readme's and in the Chapter's themselves.
