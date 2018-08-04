# snapshotalyzer-3000
AWS EC2 snapshot management

## Configuring

shotty uses the configuration file created by the AWS cli. e.g.

`aws configure --profile shotty`

## Running

`pipenv run python shotty/shotty.py <command> <--project=PROJECT>`

*command* is list, stop, or start
*project* is optional
