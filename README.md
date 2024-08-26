Aplicação Web

Usando:

Três réplicas

Um container balanceado,cpu e memória

Conexão da porta 80 para local 8080

Um aquivo deploy para atualizar e gerenciar os PODs

Um arquivo services para manter a comunicação "protocolo TCP", utilizando o LoadBalancer

Um arquivo configmap armazendo o BD de formato postgreslq

Um arquivo secrets agrupando,usuário e senha repassados ​​(informação sensível)
