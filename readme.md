- oapi-codegen -package=authSpec -generate "types,spec,gin" authServerBackend/auth-server-api.yml > authServerBackend/auth-server-api.gen.go
- oapi-codegen -package=noteSpec -generate "types,spec,gin" noteServerBackend/note-api.yml > noteServerBackend/note-backend-api.gen.go

TODO:
1) Сделать build в github (перегенерация)
2) Сделать job release в github