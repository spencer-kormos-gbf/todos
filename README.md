# TODOs

Basic TODO style app to validate and test the [Goa Design](https://goa.design/) app generator within Bread. 

## Intention

To create a TODOs style API app that supports RESTful JSON over HTTP, and Protobufs over GRPC, using [GOA Design Generator](https://github.com/goadesign/goa).

The end result should have a project structure similar to:

```
todos
  + api
    + client
    + design
    - go.mod
  + service
    + cmd
    + internal
    - go.mod
  - README.md

```

## Exhaustive Setup and First Run

From your the directory containing all your project:
- `mkdir -p todos/api/design`
- `mkdir -p todos/service
- `cd todos/api`
- `go mod init <module>/<root>/todos/api`
- `go get -u goa.design/goa/v3/...@v3`
-  