
# leg 00

## Plataform Digital do Poder Judiciário Brasileiro (PDPJ-Br)

- unifica vários sistemas existentes
- segue as diretrizes da [LGPD](https://github.com/troclaux/notes/blob/main/lgpd.md)
- adota soluções que abrangem:
  - microsserviços
  - autenticação uniformizada
  - portabilidade
  - acessibilidade
  - segurança da informação
  - computação em nuvem
  - interoperabilidade
  - mobilidade
  - usabilidade
  - adequação à LGPD
  - 

### política de governança e gestão da PDPJ-Br


### gestão da PDPJ-Br

- PDPJ-Br irá oferecer aplicações/microsserviços através da "nuvem nacional"
- "nuvem nacional"
  - centraliza todas as bases de dados, documentos a aplicações

- CNJ (Conselho Nacional de Justiça): órgão responsável por aperfeiçoar o trabalho do judiciário e aumentar a transparência
  - garante que os tribunais cumpram os deveres constitucionais
  - funções
    - fiscaliza atuação administrativa e financeira dos tribunais
    - zelar pela autonomia do judiciário
    - promover boas práticas de gestão e inovação
    - criar normas para sistemas como PDPJ-Br

- ato da presidência do CNJ: norma interna do CNJ que define regras sobre temas relacionados ao CNJ

- CNJ coordena todas as etapas apra contratação e implatanção da nuvem nacional
  - define os custos de processamento de microsserviços
  - armazenamento das bases de dados

## 396/2021 Estratégia Nacional de SEgurança da informação e Cibernética do Poder Judiciário (ENSEC-PJ)

> garante a proteção dos sistemas e dados dos órgãos do PJ, com exceção do STF

- instituída pela resolução 396/2021

- objetivos
  - aumentar segurança cibernética do Judiciário
  - aumentar a resiliência às ameaças cibernéticas
  - estabelecer governança de segurança cibernética
  - permitir manutenção e continuidade dos serviços ou seu reestabelecimento em menor tempo possível
  - fortalecer a gestão e coordenação integrada de ações de segurança cibernética

- ações
  - fortalecer as ações de governança cibernética
  - elevar o nível de segurança das infraestruturas críticas
  - estabelecer rede de cooperação do judiciário para segurança cibernética
  - estabelecer modelo centralizado de governança cibernética nacional

- Comitê Gestor de Segurança da Informação do Poder Judiciário (CGSI-PJ)
  - responsável por assessorar o CNJ sobre segurança da informação
  - competências
    - estabelecer requisitos para implementação da gestão de risco dos ativos da informação do PJ
    - aprovar políticas sobre segurança da informação do PJ
    - implementar programas sobre segurança da informação para conscientizar e capacitar servidores do PJ
  - integrantes:
    - 2 especialistas do STF
    - 2 especialistas do CNJ
    - 2 especialistas dos tribunais de justiça estaduais
    - 1 do STJ
    - 1 do TSE
    - 1 do TST
    - 1 do CJF
    - 1 do STM
    - 1 do CSJT
  - pode convidar representantes de:
    - órgãos de segurança pública
    - ministério público
    - forças armadas
    - especialistas técnicos de outros órgãos públicos ou privados

- rede de cooperação do judiciário
  - objetivo:
    - promover ambiente participativo, colaborativo e seguro entre os órgãos do PJ
    - fortalecer o Centro de Prevenção, Tratamento e Resposta a Incidentes Cibernéticos (CPTRIC-PJ)
    - compartilhar informações sobre incidentes e vulnerabilidades cibernéticas
    - realizar parcerias com outros setores para aumentar segurança cibernética

- Política de SEgurança Cibernética (PSEC-PJ)
  - garante a segurança cibernética no PJ

---

# leg 01

## rede de governança da plataforma judicial do poder judiciário brasileiro

- composta por
  - comissão permanente de tecnologia da informação e infraestrutura do cnj: coordena toda a rede de governança da plataforma
  - comitê gestor nacional da PDPJ
    - cada tribunal tem seu comitê gestor
  - comitês gestores dos tribunais
  - gerência executiva da PDPJ
  - grupos de trabalho

> [!IMPORTANT]
> comitê gestor nacional da PDPJ != comitês gestores dos tribunais

### comitê gestor nacional da PDPJ-Br

- presidente do cnj: responsável pela indicação dos membros

- composição do comitê gestor nacional da PDPJ-Br
  - conselheiro do cnj: preside o comitê
  - 2 juízes auxiliares da presidência do cnj
  - 3 representantes da justiça estadual
  - representante da justiça federal
  - representante da justiça militar
  - representante da justiça do trabalho
  - representante da justiça eleitoral
  - representante da procuradoria-geral da república
  - representante da ordem dos advogados do brasil (OAB)

- responsabilidades:
  - propor políticas de tecnologia da informação
  - homologar e ajustar projetos de microsserviços
    - homologar: aprovação de algo para uma autoridade judicial ou administrativa
  - ratificar decisões da gerência executiva
    - ratificar: confirmar oficialmente uma decisão que já foi tomada por outra pessoa/grupo
      - composta por juízes do CNJ
  - propor normas regulamentadoras
  - sugerir modelo de rateio de custos
    - rateio de custos: dividir os custos de algo entre os envolvidos
  - deliberar sobre questões autorizadas pela presidência

### comitês gestores dos tribunais

- responsabilidades:
  - avaliar necessidades de evulução e correção dos microsserviços e módulos
  - propor uma organização para lidar com as demandas dos usuários
  - divulgar as ações da PDPJ-Br
  - apresentar o plano de ação ao Comitê Gestor Nacional
  - acompanhar a execução do plano de ação
  - monitorar e avaliar os resultados

### gerência executiva do PDPJ-Br

- responsabilidades:
  - gerenciar as atividades de desenvolvimento, sustentação e evulução dos módulos e serviços
  - definir os tribunais resposáveis pelo desenvolvimento de módulos e serviços
  - designar líderes técnicos e gerentes de projetos
  - facilitar a comunicação e resolver impedimentos
  - criação e manutenção de Grupos Nacionais

## grupo nacional de gerenciamento, desenvolvimento e sustentação

## grupo nacional de requisitos de negócio

- responsabilidades:
  - analizar e organizar demandas de evolução ou melhoria da PDPJ-Br
  - 

## portaria nº253 de 2020

- classificação dos serviços integrados à plataforma
  - serviços estruturantes: funcionalidades básicas e essenciais para processos eletrônicos/integração/interoperabilidade da plataforma
    - interoperabilidade da plataforma: capacidade de diferentes sistemas, aplicações ou componentes de uma plataforma trabalharem juntos de forma integrada/eficiente
  - serviços negociais: soluções que atendem necessidades do negócio
    - e.g. distribuição de processos, controle de custas e agendamento de audiências
  - serviços de integração com sistemas externos: permitem que o PJ se conecte com sistemas de outras instituições
  - soluções e aplicações da comunidade externa ao judiciário: serviços desenvolvidos por entes externos ao judiciário, voltados para atender às suas necessidades

### arquitetura

- PDPJ-Br está em transição do monelo monolítico para o de **microsserviços**
- modelados preferencialmente seguindo a metodologia Domain Driven Design (DDD)
- comunicação através de um MessageBroker

processo de transição:

1. identificar domínio que será convertido do sistema monolítico para o de microsserviços
1. modelagem da API dentro do sistema monolítico, mas que futuramente será convertido para microsserviço independente
1. adaptação do sistema monolítico para usar a nova API no lugar dos serviços antigos
1. desacoplar o banco de dados do sistema monolítico, migrando ele para um banco de dados exclusivo do novo microsserviço
1. CNJ fornece módulos estruturantes para evitar redundâncias nas APIs repetidas nos sistemas antigos

- os microsserviços da PDPJ-Br usarão java com a framework Spring Boot
  - apesar de java ser o padrão, é possível usar outras linguagens/frameworks

### segurança

- autenticação e autorização com OAuth2
- serviço oferecido pelo Single-Sign-On (SSO) da PDPJ-Br
  - será possível autenticar com o SSO em diversos sistemas com uma única autenticação

### características

- stateless
- escalabilidade horizontal
- CI/CD
- TTD (Test Driven Development)
- APIs devem seguir o padrão OpenAPI 3.0
- uso de MessageBroker
- APIs devem ser acessadas através de um gateway

### nuvem e inteligência artificial

- órgãos participantes têm flexibilidade para escolher onde manter suas soluções (nuvem ou "on premise")
- conteinerização de código aberto

## portaria nº 131 de 2021

- institui o grupo revisor de código-fonte para PDPJ-Br e PJe
  - grupo revisor de código-fonte: responsável por revisar as mudanças feitas no código-fonte dos sistemas do PDPJ-Br e PJe
- garante que as implementação da CNJ e dos tribunais sejam de qualidade
- responsabilidades
  - testar código
  - realizar sprints quinzenais
- não é responsável por
  - escolher projetos
- composto por
  - 5+ servidores indicados pelos tribunais de justiça estaduais
  - 5+ servidores indicados pelo conselho da justiça federal
  - 5+ servidores indicados pelo TSE
  - 5+ servidores indicados pelo conselho superior da justiça do trabalho

---

- Poder Judiciário (PJ)
- Conselho Nacional de Justiça (CNJ)
- Processo Judicial Eletrônico (PJe): sistema desenvolvido pelo CNJ e diversos tribunais brasileiros para automatizar a tramitação de processos judiciais
  - tramitação de processo judicial: conjunto de procedimentos que um processo percorre do início até a decisão final do poder judiciário
- Plataform Digital do Poder Judiciário Brasileiro (PDPJ-Br)
- Departamento de Tecnologia da Informação (DTI)

- portaria: ato administrativo que especifica como leis e normas serão implementadas
  - ato administrativo: decisão de um órgão ou servidor público
- governança: conjunto de práticas, regras, processos e estruturas usadas para tomar decisões e controlar uma organização/sistema
- corregedoria: órgão responsável por fiscalizar, orientar e disciplinar a atuação de servidores ligados ao poder judiciário
  - não tem autoridade sobre os ministro do STF
  - órgão: parte de uma organização maior
