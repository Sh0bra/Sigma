# Sigma
My Journey to learning Sigma detection

## Install
```
pip3 install sigma-cli
```

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
