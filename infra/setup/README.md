# aws vault
access
```bash
aws-vault list 
aws-vault exec mark.demo --duration=8h
```

# run setup 

```bash
docker compose run --rm terraform -chdir=setup init 
```

# run deploy

```bash
docker compose run --rm terraform -chdir=deploy  init 
```
