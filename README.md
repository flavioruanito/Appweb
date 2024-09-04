Aplicação Web

Usando:

Três réplicas

Um container balanceado,cpu e memória

Conexão da porta 80 para local 8080

Um arquivo deploy para atualizar e gerenciar os PODs

Um arquivo services para manter a comunicação "protocolo TCP", utilizando o LoadBalancer

Um arquivo configmap armazendo o BD de formato postgreslq

Um arquivo secrets agrupando,usuário e senha repassados ​​(informação sensível)

COMANDO PARA APLICARR O DEPLOYMENT 

kubectl apply -f deployment.yaml

Sistema Operacional Ubuntu 22.04.4 LTS

Ferramenta - kind version 0.22.0
Kubernetes Client Version: v1.29.2
Docker version 27.1.1, build 6312585


