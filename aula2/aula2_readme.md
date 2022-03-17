## Aula 2

Desafio: Utilizar um processo para elaborar uma arquitetura de um sistema de pequeno porte


O que preciso saber?

* o que é uma arquitetura
* como elaborar uma arquitetura
* o que eu preciso saber para fazer uma arquitetura
* como saber qual a arquitetura mais adequada
* quais as limitações na hora de manter uma arquitetura

### Processo de elaboração de arquitetura

* Entender os requisitos funcionais e identificar os não funcionais
* Elaborar uma ou mais arquiteturas preliminares
* Selecionar uma arquitetura
* Detalhar a arquitetura selecionada para cada componente
  * Definir tipo de aplicação
  * selecionar tecnologia
  * Selecionar estilo arquitetal
* Documentar
* Acompanhar o desenvolvimento 

### Solicitação

Dashboard para monitorar o status de funcionamento de cameras registradas:
* Coletar dados de funcionamento das câmeras
* formatar dados coletados
* Apresentar dados visualmente para que o usuário saiba exatamente o que está acontecendo com cada câmera
* Permite que o usuário faça consultas customizadas dessas informações

### Step-2-Step

Dados Requisitos Funcionais
* Receber dados sobre o funcionamento das câmeras
* Armazenar os dados
* Consultar os dados

Perguntas chaves
* Quantas Coletas de dados concorrentes no máximo? 1000
* Qual é o tamanho dos dados a serem armazenados? 500bytes (180Gb/ano)
* Quantas coletas de dados por dia? 1 milhão
* Qual é a taxa de perda de mensagens permitida? 5%
* Quantos usuários? 100
* Quantos usuários simultâneos? 33
* Qual é o uptime mínimo? 99,7% (+/-0,2)

Escolher o padrão arquitetural

* Client-Server
* Layered
  * Presentation: UI (Provider)
  * Business: Logic (Formatter) (Reader)
  * Data: Data Acess
  * Logging
* Cross-Cutting

Selecionar as tecnilogias
* AWS,Azure,GCloud
* Qual servico de mensagens
* .NET Core, Java, Node
* SQL Server, Oracle, PostgreSQL, NoSQL

Tipo de Aplicação
* Reader: Web API
* Formatter: Console
* Provider: Web API + Web App
* Logger: Console ou Serviço

---

## PBL - Engage

### Big Idea

* Conceito Amplo
* Importante para a comunidade global
  * Comunidade
  * Violência
  * Água
  * Relacionamentos Pessoais
  * Criatividade
  * Pós-Verdade
  * Feminismo
  * Ignorância
  * Saúde
  * Catástrofes
  * Democracia
  * Inteligência Artificial

Questionametno Essencial
* Muitas questões importantes a partir da Big Idea
* Enumear a maior quantidade possível
* Escolher alguma(s)

Desafio objetivos de curto-médio prazo (dependendo da ocasião até longo prazo)
