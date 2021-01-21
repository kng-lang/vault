# vault
Vault is kng's native package manager

## packages
Packages are simply kng modules that are available for anyone to install



## usage

The following usage guidelines apply to vault 0.1a

### installing packages
to install a package, use the i argument
```
vault -i [package name]
```
optionally, provide a uri
```
vault -i [package uri]
```

### updating packages
to update a package, use the u argument
```
vault -u [package name]
```

### removing packages
to remove a package, use the r argument
```
vault -r [package name]
```

## deploying packages
to deploy a packge, use the d argument
```
vault -d [package directory]
```
example package
```
example_package/
    package.json
    module/
        build.kng
        main.kng
        file1.kng
        file2.kng
    
```
example package.json
```
{
    id : "example_package_id",
    name : "example package",
    description : "an amazing packge you should use",
    version : "0.0.1",
    author : "james clarke"
}
```