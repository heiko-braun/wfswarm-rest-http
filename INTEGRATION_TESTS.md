
# Running the integrations tests 

To run the integration tests use the following steps:

## Deploy the booster

```
mvn -Popenshift fabric8:deploy
```

### Run the integration tests

```
mvn -Popenshift-it verify
```

### Undeploy the booster

```
mvn -Popenshift fabric8:undeploy
```

