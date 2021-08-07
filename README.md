## Packer

### Build
```
$ packer build example.json
```

#### Build with variables file
```
$ packer build -var-file=variables.json example.json 
```

#### Build with variables in command line
```
$ packer build -var="<variable>=<value>" [-var="<variable2>=<value2>"] example.json 
```

### Validate
```
$ packer validate example.json
```

### Inspect
```
$ packer inspect example.json
```

## References:
- Packer mini course playlist: https://www.youtube.com/playlist?list=PL8VzFQ8k4U1Jp6eWgHSXHiiRWRvPyCKRj