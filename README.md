# 🔗 Redirecionador de URLs  

Este projeto é responsável por acessar a URL original associada a um UUID encurtado. Ele consulta o **AWS S3** para obter a URL salva e, em seguida, redireciona o usuário para o endereço original.  

O projeto está implantado no **AWS Lambda**, oferecendo um ambiente serverless para consultas rápidas e escaláveis.  

## 🚀 Funcionalidades  

- **Consulta pelo UUID**: Localiza no **AWS S3** a URL original associada ao UUID fornecido.  
- **Redirecionamento**: Redireciona o usuário para a URL original recuperada.  
- **Execução Serverless**: Utiliza o **AWS Lambda** para gerenciar as solicitações de forma eficiente e escalável.  

## 🛠️ Tecnologias Utilizadas  

- **Java**: Linguagem principal do projeto.  
- **AWS Lambda**: Para execução do código em ambiente serverless.  
- **AWS S3**: Para armazenamento e consulta das URLs originais associadas aos UUIDs.  
