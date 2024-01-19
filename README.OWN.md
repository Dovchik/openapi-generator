# How to use

* Build the project, so `modules/openapi-generator-cli/target/openapi-generator-cli.jar` is present, see README.md in root

* Use config(/specs/config.yaml) to generate and adjust when needed with command below


```bash
java -jar modules/openapi-generator-cli/target/openapi-generator-cli.jar generate -c config.yaml
```
where -c is path of config file
