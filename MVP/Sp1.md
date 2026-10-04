# 📌 MVP - [Projeto API - Mapeamento do Ecossistemaa Produtivo de SJC]

## 🎯 Objetivo do MVP
> Descrever de forma clara qual é o propósito do MVP:  
- Qual problema resolve?
  
Atende à necessidade da Secretaria de Desenvolvimento Econômico de São José dos Campos na organização das informações produtivos do município, trabalhando inicialmente com as extração e o filtro dos dados locais relevantes.
- Qual hipótese será validada?
  
A de que a organização e o tratamento prévio dos dados públicis da Relação Anual de Informações Sociais (RAIS), aliados à categorização dos códigos CNAE, fornecerão uma base sólida e estruturada das atividades econômicas da região.
- Qual valor será entregue ao usuário final?  

Uma base de dados limpa, extraída e segmenteda, que garante a rastreabilidade técnica dos scripts e possibilita visualizarr os primeiros resultados sobre os estabelicimentos e vínculis ativos do mercado formal em SJC.

---

## 📝 Descrição da Solução
> Breve explicação do que será desenvolvido e entregue nesta etapa.  
- Funcionalidades principais incluídas: Extração e filtragem dos registros da RAIS para São José dos Campos utilizando VS CODE E EXCEL; tratamento dos códigos CNAE; categorização das empresas nos grupos Aeroespacial, Automotivo, Químico, TI, Logística e Serviços Especializados; e criação do repositório público no GitHub.

- Limitações conhecidas: A análise nesta etapa inicial restringe-se exclusivamente à estruturação  dos dados e do mercado de trabalho formal. Não inclui interfaces gráficos, painéis ou mapas interativos.

- Escopo reduzido: O foco é puramente a preparação técnica e base de dados tratada, contendo apenas o essencial(extração,filtragem e categorização) para viabilizar as etapas futuras. 

---

## 👥 Personas / Usuários-Alvo
- **Persona 1:**  Tomador de Decisões de Políticas Públicas. Necessita extrair e filtrar os registros locais da base da RAIS para realizar a análise segmentada do ecossistema produtivo e compreender o peso econômico dos setores em São José dos Campos, executando as tarefas planejadas no backlog.
- **Persona 2:**   Secretaria de Desenvolvimento Econômico de SJC. Necessita organizar as informações gerais sobre a estrutura produtiva do município para acompanhar o mercado de trabalho formal, subsidiar estudos e orientar as políticas locais a longo prazo.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | Como tomador de decisões de políticas públicas, eu quero extrair e filtrar os registros de bases pública da RAIS referente exclusivamente ao município de São José dos Campos utilizando VS CODE E EXCEL, para trabalhar apemaas com os dedos locais relevantes do projeto.         | Alta       | 5 pontos   |
| US2 | Como tomador de decisões de políticas públicas, eu quero tratar os dados de CNAE e categorizar as empresas nos grandes grupos do ecossistema(Aeroespacial, Automotivo, Químico, TI, Logística e Serviços Especializados), para permitir a análise segmentada do perfil produtivo.         | Alta      | 5 pontos   |
| US3 | Como tomador de decisões de política públicas, eu quero criar e visionar o repositório público do projeto no GitHub, para garantir a rastreabilidade dos scripts de tratamento e organizações da documentação técnica.         | Média      | 3 pontos   |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Extração e filtro (VS CODE e EXCEL); Tratamento CNAE; Classificação nos 6 grupos econômicos; Criação do GitHub.                        | Concluído|

---

## 📊 Critérios de Aceitação
- O MVP deve garantir que a base de dados extraída contenha registros correspondentes exclusivamente ao município de São José dos Campos.
- O sistema deve registrar as empresas devidamente categorizadas nos grandes grupos de ecossistemas definidos no escopo.
- Métricas coletadas: Os scripts de tratamento e a documentação técnica devem estar estruturados e rastreáveis publicamente no repositório do GitHub.

---

## 📈 Métricas de Validação
- Geração e entrega de seis bases setoriais limpas, mapeando com sucesso 11.168 estabelecimentos e 45.929 vínculos empregatícios ativos dentro do recorte municipal.
 
- Processamento bem-sucedido da base nacional bruta (de aproximadamente 3 GB), com a filtragem geográfica validada pela integridade das 47.339 linhas resultantes para São José dos Campos.

- Rastreabilidade comprovada através da estruturação do repositório no GitHub, contendo os scripts de extração, limpeza e segmentação desenvolvidos ao longo da sprint.
---

## 🚀 Próximos Passos
- Construção de um painel analítico no Power BI com KPIs (total de empresas, volume de empregos e representatividade), utilizando as bases setorizadas definidas no escopo.
 
- Comparação de indicadores de desempenho entre os setores aeroespacial, automotivo e de tecnologia.
 
---

## 📂 Anexos / Evidências
- [Acesso à Pasta das Bases Tratadas e Setorizadas](COLE_O_LINK_DA_PASTA_AQUI)
- [Repositório Público do Projeto no GitHub](COLE_O_LINK_DO_GITHUB_AQUI)
- [Documentação Técnica da Sprint 1](COLE_O_LINK_DA_DOCUMENTACAO_AQUI)
