## Desafio DevSecOps

### Problema
Você acaba de ser contratado pela Cervejaria Ambev para cuidar da maior reestruturação de segurança da cia. Em um histórico de mais de 10 anos trabalhando com softwares terceiros existe a necessidade eminente da consolidação dos produtos em um único repositório. Ao longo dos anos nenhuma metodologia de devSECops foi utilizada e atualmente sua implantação é necessária para garantir um nível adequado de segurança nas pipelines dos mais de 100 produtos. 

Falhas na qualidade ou segurança dos produtos são constantes, assim aumentando demais o TTM e deixando o negócio de cabelo em pé. O time de desenvolvimento acredita não ter nem as ferramentas, nem o conhecimento adequado para adaptar a pipeline de produtos ou mesmo garantir que o software em produção está saudável. 

### Sua Missão 
A nova conta AZURE, em que os recursos serão alocados está totalmente vazia, sem nenhum recurso, ou seja, não existe infraestrutura básica para subir a aplicação. Lembre-se de requisitos básicos de segurança (ex: não deixar o banco de dados acessível via internet) ao modelar essa nova infraestrutura.  

Sua missão é desenhar a arquitetura genérica de segurança para esse grupo de desenvolvedores. Considere todo o tipo de aplicações de monolitos a microserviços, e as mais diversas abordagens de segurança que considerar adequada, SAST, DAST entre outras ferramentas para criar um ambiente seguro do desenvolvimento a produção.  

### Entregáveis
Sua missão é propor uma arquitetura utilizando componentes da AZURE que atendam aos requisitos acima citados. Seus entregáveis devem ser: 
1. Um diagrama AZURE mostrando sua arquitetura.  
2. Um ou mais templates (IaC - infrastructure as a code) da sua infra-estrutura feito em Terraform. 
3. Uma breve explicação da sua solução. 
