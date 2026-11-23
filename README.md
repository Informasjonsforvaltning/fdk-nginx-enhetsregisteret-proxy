> [!IMPORTANT]
> This repository is archived. fdk-nginx-enhetsregisteret-proxy is deployed by Flux from
> [Informasjonsforvaltning/fdk-infra](https://github.com/Informasjonsforvaltning/fdk-infra/tree/main/apps/base/fdk-nginx-enhetsregisteret-proxy);
> make changes there.

The goal of the proxy is provide common access point for using Enhetsregisteret service. 

Demo:

```
#run proxy
docker-compose up -d nginx-enhetsregisteret-proxy

#test
curl http://localhost:8130/enhetsregisteret/api/enheter/899183932
```
