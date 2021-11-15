Validation
```
custodian validate rds.yaml
```

Dry run:
```
custodian run --dryrun -s . rds-1-define.yaml
```

Run:
```
custodian run -s ./c7n-out -v rds-02-list-unencrypted.yaml
```
