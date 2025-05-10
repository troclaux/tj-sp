
# prova discursiva

[formatos de prova discursiva](https://www.estrategiaconcursos.com.br/blog/formatos-prova-discursiva-cobrados-bancas/)

- filtros tec concursos (9 questões):
  - Matéria: TI - Redes de Computadores
  - Matéria: TI - Segurança da Informação
  - Matéria: TI - Engenharia de Software
  - Matéria: TI - Desenvolvimento de Sistemas
  - Matéria: TI - Banco de Dados
  - Banca: VUNESP
  - Ano: 2021
  - Ano: 2022
  - Ano: 2023
  - Ano: 2024
  - Ano: 2025
  - Escolaridade: Superior

## questão discursiva

- responder de maneira mais objetiva possível a pergunta no enunciado, entre 15 a 20 linhas
- não adianta enrolar a banca
- mencione a pergunta na resposta, para remover ambiguidade sobre qual questão será respondida
  - banca prefere assim, pois facilita a correção
- de preferência, responder cada item da questão em um parágrafo diferente

exemplo:

```
Pergunta: "Quais são os fundamentos da República Federativa do Brasil, segundo a Constituição Federal de 1988?"
Resposta: "Segundo a Constituição Federal de 1988, os fundamentos da República Federativa do Brasil são a soberania, a cidadania, a dignidade da pessoa humana, os valores sociais do trabalho e da livre iniciativa e o pluralismo político."
```

## estudo de caso

> banca apresenta situação hipotética para que você analise e responda

- mais longo que a questão discursiva, entre 40 a 60 linhas (as vezes até 90 linhas)
- banca fará mais de uma pergunta no enunciado
- será avaliado:
  - conteúdo
  - habilidade de escrita
  - administração de tempo
- estrutura: mistura de redação e da questão discursiva
  - introdução
    - [exemplos](~/Documents/personal/template_study_case.md)
  - desenvolvimento
    - deixe claro para a banca o item a que você está respondendo
  - conclusão (opcional se você adicionar o fechamento no último parágrafo de desenvolvimento)

---

## resolução de questões discursivas

### questão 2

A respeito de Data Warehouse, responda ao que se pede.

a) Há diversos fatores que justificam a implementação de um Data Warehouse. Cite três desses fatores, apresentando uma justificativa sucinta para cada fator apresentado.

a) Os fatores que justificam a implementação de um Data Warehouse são:

Gestão de dados: o Data Warehouse permite armazenar e organizar dados de diversas fontes, facilitando a sua gestão e análise.

Tomadas de decisão: o Data Warehouse fornece informações relevantes para a tomada de decisões estratégicas, auxiliando as organizações a alcançar seus objetivos.

Inovação: o Data Warehouse pode ser utilizado para a criação de novos produtos e serviços, bem como para a melhoria dos já existentes.

b) Uma das etapas fundamentais no projeto de um Data Warehouse é composta pelos formatos denominados ETL / ELT. Descreva essa etapa destacando as diferenças existentes entre ambos os formatos (ETL ou ELT).

b) A etapa de ETL/ELT é responsável por extrair dados de diversas fontes, transformá-los para atender às necessidades da organização e carregá-los para o Data Warehouse.

No formato ETL (Extract, Transform, Load), os dados são extraídos das fontes, transformados em um formato padronizado e carregados para o Data Warehouse. O processo de transformação é realizado em um servidor separado do Data Warehouse, o que pode aumentar o tempo de processamento, especialmente para grandes volumes de dados.

No formato ELT (Extract, Load, Transform), os dados são extraídos das fontes e carregados diretamente para o Data Warehouse. As transformações são realizadas no Data Warehouse, o que pode reduzir o tempo de processamento.

#### my answer

- entity 1
  - atribute 1 of entity 1
  - atribute 2 of entity 1
  - atribute 3 of entity 1
  - atribute 4 of entity 1
  - atribute 5 of entity 1
  - relationships:
    - 0..1 with entity 2
    - 0..* with entity 3
- entity 2
  - atribute 1 of entity 2
  - atribute 2 of entity 2
  - atribute 3 of entity 2
  - relationships:
    - 1 with entity 1
- entity 3
  - atribute 1 of entity 3
  - atribute 2 of entity 3
  - relationships:
    - 1 with entity 1

Tomadas de decisão: o Data Warehouse fornece informações relevantes para a tomada de decisões estratégicas, auxiliando as organizações a alcançar seus objetivos.

Inovação: o Data Warehouse pode ser utilizado para a criação de novos produtos e serviços, bem como para a melhoria dos já existentes.

integração de dados de múltiplas fontes

melhoria no desempenho das consultas analíticas

- Extract: extração dos dados
- Transform: transforma, padroniza e limpa os dados para análise posterior
  - operações como discretização ou remoção de outliers são feitas para facilitar análises futuras dos dados
- Load: carrega os dados no data warehouse, que é feito em batches(?)

ETL transforma os dados antes deles entrarem no data warehouse,
ELT transforma os dados dentro do data warehouse
