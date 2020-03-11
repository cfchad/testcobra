# testcobra
repository to be used as example for testing golang library cobra

## Commands run to get started
```shell script
➜ cobra init --pkg-name github.com/cfchad/testcobra
➜ cobra add serve
➜ cobra add config
➜ cobra add create -p 'configCmd'
```

## Usage
```shell script
➜ go run main.go serve
  serve called
➜ go run main.go config
  config called
➜ go run main.go config create
  create called
➜ go run main.go help serve
  A longer description that spans multiple lines and likely contains examples
  and usage of using your command. For example:
  
  Cobra is a CLI library for Go that empowers applications.
  This application is a tool to generate the needed files
  to quickly create a Cobra application.
  
  Usage:
    testcobra serve [flags]
  
  Flags:
    -h, --help   help for serve
  
  Global Flags:
        --config string   config file (default is $HOME/.testcobra.yaml)
```
