# goexpert-cli


## Setup
``` shell
go install github.com/spf13/cobra-cli@latest
```

## Modo de uso
``` shell
sqlite3 db.sqlite 'create table categories (id string, name string, description string);'
go run main.go category create --name "lang" --description "go"
```
