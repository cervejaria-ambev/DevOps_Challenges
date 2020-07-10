## Desafio SRE

### Problema
Você acaba de ser contratado pelo time de plataforma da Cervejaria Ambev para cuidar de um produto complexo usando micro serviços. O projeto consiste em diversas micro aplicações e você foi designado a configurar seu cluster destino. Pela alta complexidade do produto, a solução deve considerar um banco de dados relacional MySQL e também um banco não relacional MongoDB, bem como espaço de storage que possa ser usado dentro das micro aplicações. Suportar a arquitetura baseada em eventos,  ferramentas mínimas de gerenciamento do cluster e de observablidade também são parte do seu desafio. 

### Sua Missão 
A nova conta Azure, em que os recursos serão alocados está totalmente vazia, sem nenhum recurso, ou seja, não existe infraestrutura básica para subir a aplicação. Lembre-se de requisitos básico  de segurança (ex: não deixar nenhum recurso acessível via internet) ao modelar essa nova infraestrutura. 

A infraestrutura dessas aplicações depende do seu trabalho. Faça os diagramas necessários para ander essa demanda da melhor maneira possível.  

### Entregáveis
Sua missão é propor uma arquitetura utilizando componentes da Azure que atendam os requisitos acima citados. Seus entregáveis devem ser: 
1. Um diagrama Azure mostrando sua arquitetura. Recomendamos usar: https://cloudcraft.co/  
2. Um ou mais templates (IaC - infrastructure as a code) da sua infra-estrutura feito Terraform. 
3. Dockerfile de uma aplicação Hello em python para o primeiro teste no cluster. 




