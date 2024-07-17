# helm_values
Helm common values yamls for all applications

* All values yaml input should be reffered from this repo only. Directory structure should be as below.
````bash
|-- tibco
|   |   |-- app-01
|   |   |   |-- configmap.yaml
|   |   |   |-- environments
|   |   |   |   |-- reg-values.yaml
|   |   |   |   `-- stg-values.yaml
|   |   |   `-- values.yaml
|   |   `-- app-02
|   |       |-- configmap.yaml
|   |       |-- environments
|   |       |   |-- reg-values.yaml
|   |       |   `-- stg-values.yaml
|   |       `-- values.yaml
|   `-- environments
|        |-- reg-values.yaml
|       `-- stg-values.yaml
|-- nodejs
|   |   |-- app-01
|   |   |   |-- configmap.yaml
|   |   |   |-- environments
|   |   |   |   |-- reg-values.yaml
|   |   |   |   `-- stg-values.yaml
|   |   |   `-- values.yaml
|   |   `-- app-02
|   |       |-- configmap.yaml
|   |       |-- environments
|   |       |   |-- reg-values.yaml
|   |       |   `-- stg-values.yaml
|   |       `-- values.yaml
|   `-- environments
|       |-- reg-values.yaml
|       `-- stg-values.yaml
````
