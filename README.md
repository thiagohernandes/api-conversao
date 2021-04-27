### Instruções
```
docker image build -t kalatunga/api-conversao-thiago:v1 .
docker container run -d -p 8081:8081  kalatunga/api-conversao-thiago:v1
-> acessar: http://localhost:8081/api-docs/
```