# Test-To-Senior-Java-Developer

**Desafio Técnico para o Grupo "****"**

### Contexto
A Porto Seguro é uma empresa que se destaca no setor de seguros no Brasil, oferecendo uma vasta gama de produtos e serviços, desde seguros de automóveis até planos de saúde, além de serviços financeiros e consórcios. Para atender às demandas tecnológicas e melhorar a experiência dos seus clientes, a Porto Seguro está buscando profissionais altamente qualificados em desenvolvimento de software.

### Descrição do Desafio
Você foi contratado para desenvolver um serviço de seguro de automóveis que permita aos clientes da Porto Seguro realizarem a contratação, consulta e cancelamento de apólices de seguro através de uma API RESTful. Este serviço deverá ser desenvolvido com as seguintes especificações técnicas e boas práticas.

### Requisitos Técnicos

1. **Desenvolvimento Java 11 ou superior com Maven:**
   - Utilize Java 11 ou superior para desenvolver o projeto.
   - Configure o projeto utilizando o gerenciador de dependências Maven.

2. **Spring Boot:**
   - O serviço deve ser desenvolvido utilizando o framework Spring Boot.

3. **Servidores de Aplicação WAS/WebLogic:**
   - O serviço deve ser implantado em um servidor de aplicação WAS ou WebLogic.

4. **API Gateway:**
   - Integre o serviço com um API Gateway (Sensedia ou Mulesoft) para gerenciamento e roteamento de APIs.

5. **JPA e Hibernate:**
   - Utilize JPA e Hibernate para a persistência de dados.

6. **Serviços REST:**
   - Crie endpoints RESTful para as operações de contratação, consulta e cancelamento de apólices de seguro.

7. **SQL e Banco de Dados Relacional:**
   - Utilize SQL e um banco de dados relacional (ex. PostgreSQL ou MySQL) para armazenar os dados das apólices.

8. **Testes Unitários com JUnit:**
   - Escreva testes unitários utilizando JUnit para garantir a qualidade do código.

9. **Boas Práticas de Desenvolvimento de Software:**
   - Aplique as boas práticas de desenvolvimento, como SOLID, Clean Code e versionamento de código com Git.
   - Realize code reviews para garantir a qualidade do código.

10. **Arquitetura de Software Distribuído:**
    - Desenvolva a aplicação seguindo padrões de arquitetura de software distribuído.

11. **Ambiente de Nuvem:**
    - Prepare o serviço para ser implantado em um ambiente de nuvem (AWS, Google Cloud ou Azure).

12. **Docker:**
    - Utilize Docker para containerizar a aplicação, facilitando o deployment e a escalabilidade.

13. **Documentação Técnica:**
    - Elabore diagramas de arquitetura e documentação técnica detalhada do serviço desenvolvido.

### Tarefas Específicas

1. **Configuração do Projeto:**
   - Configure um novo projeto Maven com as dependências necessárias para Spring Boot, JPA, Hibernate, JUnit e integração com API Gateway.

2. **Desenvolvimento dos Endpoints RESTful:**
   - Crie os seguintes endpoints:
     - `POST /api/apolices` - para contratar uma nova apólice de seguro.
     - `GET /api/apolices/{id}` - para consultar uma apólice de seguro pelo ID.
     - `DELETE /api/apolices/{id}` - para cancelar uma apólice de seguro pelo ID.

3. **Persistência de Dados:**
   - Implemente a persistência dos dados das apólices utilizando JPA e Hibernate.

4. **Testes Unitários:**
   - Desenvolva testes unitários para os serviços e endpoints criados utilizando JUnit.

5. **Integração com API Gateway:**
   - Configure o serviço para integração com um API Gateway (Sensedia ou Mulesoft).

6. **Containerização:**
   - Crie um Dockerfile para containerizar a aplicação.

7. **Implantação na Nuvem:**
   - Prepare a aplicação para implantação em um ambiente de nuvem (AWS, Google Cloud ou Azure).

8. **Documentação Técnica:**
   - Elabore diagramas UML para ilustrar a arquitetura do sistema.
   - Crie uma documentação técnica detalhada, incluindo instruções de instalação, configuração e uso dos serviços.

### Entregáveis

1. Código fonte do projeto, versionado em um repositório Git.
2. Testes unitários com cobertura adequada.
3. Dockerfile e instruções para criação da imagem Docker.
4. Instruções detalhadas para implantação na nuvem.
5. Documentação técnica e diagramas de arquitetura.

### Critérios de Avaliação

1. **Qualidade do Código:**
   - Clareza e organização do código.
   - Adesão às boas práticas de desenvolvimento (SOLID, Clean Code).

2. **Funcionalidade:**
   - Correta implementação dos requisitos.
   - Cobertura e qualidade dos testes unitários.

3. **Documentação:**
   - Qualidade e clareza da documentação técnica.
   - Correção e clareza dos diagramas de arquitetura.

4. **Integração e Implantação:**
   - Correta configuração e integração com o API Gateway.
   - Funcionalidade da containerização e implantação na nuvem.

### Observações Finais
Este desafio visa avaliar suas habilidades técnicas, capacidade de seguir boas práticas de desenvolvimento e sua capacidade de documentar e comunicar de forma clara. Boa sorte!
