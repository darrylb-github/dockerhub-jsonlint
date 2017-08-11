# darrylb/jsonlint

Based on node with jsonlint tool installed for validating json files. 

See https://github.com/zaach/jsonlint 

### Usage

#### Gitlab CI

    image: darrylb/jsonlint
    stage: validate
    script:
      - jsonlint my.json
