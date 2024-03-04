## DNS as Code for codinger.net

[![OctoDNS Plan](https://github.com/diamondzxd/dns-as-code/actions/workflows/plan.yaml/badge.svg?branch=main)](https://github.com/diamondzxd/dns-as-code/actions/workflows/plan.yaml)

After setting up the environment : 

### To plan changes
```bash
octodns-sync --config-file=./production.yaml
```

### To commit changes
```bash
octodns-sync --config-file=./production.yaml --doit
```

### TODO : 
- Move to a separate organization
- Implement CI with GitHub Actions