# Sigma
My Journey to learning [Sigma](https://github.com/SigmaHQ) detection.

## Install
```
pip3 install sigma-cli
```
## Creating new Sigma rule
Use the template.yaml file as a template to start creating new detection rule

## Converting Sigma rule to SIEM
```
sigma convert --target <TARGET SIEM> --pipeline <SIEM_OS> <PATH_TO_RULE>
```

## Useful Commands
To list locally available targets
```
sigma list targets
sigma plugin list
sigma plugin install <plugin>
```
