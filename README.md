# acguru-snapshots

Demo project to practice AWS EC2 instance snapshots

## About

This is a demo, and uses boto3 to manage AWS EC2 instance snapshots

## Configuring

shotty uses the configuration file created by the AWS CLI

`aws configure --profile shotty`

## Running

`pipenv run python shotty/shotty.py <command> <subcommand> <--project=PROJECT>`

*command* is instances, volumes, snapshots
*subcommand* is list, start, stop, snapshot depending on command
*project* is optional
