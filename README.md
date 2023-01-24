# Joernada DevOps de Elite
- [Joernada DevOps de Elite](#joernada-devops-de-elite)
- [Aula 1](#aula-1)
  - [Instalando `kind`](#instalando-kind)
  - [Instalando `kubctl`](#instalando-kubctl)
- [Links](#links)

# Aula 1
## Instalando `kind`
- Instalação (execute no powershell como administrador)
```
choco install kind
```
- Verificando Instalação
```
kind -version
```
## Instalando `kubctl`
- Fazendo download da versão atual do `kubctl`
```shell
curl.exe -LO "https://dl.k8s.io/release/v1.26.0/bin/windows/amd64/kubectl.exe"
```
- Movendo arquivo para `system32`
```
move kubectl.exe c:\Windows\System32
```
- Verificando versão do `kubctl`
```
kubectl version --client --output=yaml
```


# Links
- **Aula 1**: https://www.devopspro.com.br/jornada-aula1
