# LAI Skills

## Inteligência Artificial aplicada à análise de recursos administrativos da Lei de Acesso à Informação

> Projeto de pesquisa, desenvolvimento e gestão do conhecimento voltado ao uso de Inteligência Artificial como ferramenta de apoio à análise de pedidos e recursos da Lei de Acesso à Informação (LAI).

---

# Sobre o projeto

O **LAI Skills** nasceu a partir de uma necessidade real identificada durante as atividades desenvolvidas na Ouvidoria do Ministério do Meio Ambiente e Mudança do Clima (MMA).

Ao longo da análise de pedidos e recursos da Lei de Acesso à Informação, tornou-se evidente que boa parte do trabalho exigia consultar simultaneamente diferentes fontes de informação, como:

* legislação;
* decretos;
* competências administrativas;
* estruturas regimentais;
* orientações da Controladoria-Geral da União (CGU);
* precedentes administrativos;
* modelos de resposta;
* documentos internos.

Embora essas informações fossem públicas ou institucionalmente disponíveis, elas encontravam-se distribuídas em diversos documentos, tornando a consulta repetitiva e aumentando o tempo necessário para cada análise.

A partir dessa demanda surgiu a proposta de desenvolver uma base estruturada de conhecimento capaz de organizar essas informações e utilizá-las juntamente com Grandes Modelos de Linguagem (LLMs) como ferramenta de apoio ao processo analítico.

O objetivo nunca foi substituir a análise realizada pelos servidores.

O projeto foi concebido para apoiar a organização das informações, aumentar a consistência das análises, reduzir erros recorrentes e facilitar a elaboração de minutas, mantendo obrigatoriamente a revisão humana em todas as etapas.

---

# Origem do projeto

O desenvolvimento do LAI Skills foi motivado por demandas reais observadas durante o tratamento de pedidos e recursos da Lei de Acesso à Informação na Ouvidoria do MMA.

A iniciativa foi construída de forma incremental, incorporando documentos, matrizes de competência, fluxos administrativos e conhecimentos acumulados durante as análises realizadas no setor.

Com o amadurecimento da metodologia, a estrutura desenvolvida passou a ser utilizada como base para dezenas de espaços de trabalho temáticos (chats especializados), permitindo organizar diferentes áreas do conhecimento relacionadas à LAI.

Atualmente a base já apoia **mais de 40 chats especializados**, utilizados para organizar diferentes conjuntos documentais e fluxos de análise.

Os resultados obtidos também motivaram discussões internas sobre o potencial de evolução da metodologia para futuras soluções institucionais de apoio à gestão do conhecimento.

---

# Objetivos

* Organizar uma base estruturada de conhecimento sobre a Lei de Acesso à Informação.
* Centralizar legislação, precedentes e documentação administrativa.
* Estruturar um fluxo padronizado para análise de pedidos e recursos.
* Apoiar a identificação da unidade administrativa competente.
* Melhorar a consistência das análises produzidas com apoio de IA.
* Consolidar boas práticas para elaboração de respostas e minutas.
* Pesquisar aplicações de Inteligência Artificial na Administração Pública.

---

# Arquitetura do conhecimento

A base de conhecimento integra diferentes conjuntos documentais utilizados durante as análises administrativas.

* Legislação
* Decretos
* Estruturas Regimentais
* Competências Administrativas
* Matrizes de Competência
* Guias e Manuais da CGU
* Precedentes Administrativos
* Casos de estudo
* Modelos de resposta
* Fluxos de análise
* Prompts especializados
* Documentação técnica

Esses elementos são utilizados em conjunto para fornecer contexto aos modelos de IA durante as análises.

---

# Metodologia

Cada análise segue um fluxo estruturado.

```text
Recebimento do pedido

        ↓

Identificação da demanda

        ↓

Classificação conforme a LAI

        ↓

Verificação da competência administrativa

        ↓

Consulta à legislação

        ↓

Consulta às matrizes de competência

        ↓

Pesquisa de precedentes

        ↓

Construção da análise

        ↓

Elaboração da minuta

        ↓

Revisão crítica humana

        ↓

Resposta final
```

---

# Estrutura do repositório

```text
docs/
    documentação geral

legislacao/
    leis, decretos e normas

competencias/
    matrizes de competência administrativa

prompts/
    prompts especializados

modelos/
    modelos de respostas e minutas

controle/
    planilhas e materiais de apoio

casos/
    estudos e validação da metodologia
```

---

# Tecnologias

* ChatGPT
* Google NotebookLM
* GitHub
* Markdown
* Microsoft Excel

---

# Resultados

Entre os principais resultados alcançados pelo projeto destacam-se:

* estruturação de uma base integrada de conhecimento sobre a LAI;
* padronização do fluxo de análise de pedidos e recursos;
* organização de matrizes de competência administrativa;
* redução do tempo gasto na localização de informações;
* apoio à elaboração de análises e minutas;
* utilização da metodologia em mais de **40 chats especializados**, organizados por tema e finalidade.

---

# Situação do projeto

O projeto permanece em desenvolvimento contínuo.

As atividades atuais concentram-se em:

* expansão da base documental;
* aperfeiçoamento da metodologia;
* melhoria dos prompts;
* organização das matrizes de competência;
* validação em novos casos;
* documentação técnica.

---

# Aviso

Este repositório possui finalidade de pesquisa, desenvolvimento e demonstração técnica.

A Inteligência Artificial é utilizada exclusivamente como ferramenta de apoio à análise administrativa.

Nenhuma resposta produzida pelo sistema substitui manifestação oficial da Administração Pública ou decisão administrativa.

Todas as análises devem ser revisadas por servidor responsável antes de qualquer utilização.

---

## Minha principal sugestão

Eu **tiraria completamente a palavra "chatbot" do README**.

Depois de ver a estrutura do projeto, ela diminui o valor do que você fez. O núcleo do LAI Skills não é um chatbot: é uma **plataforma de gestão do conhecimento com apoio de IA**. O chatbot é apenas a interface de interação.

Essa mudança de enquadramento faz o projeto parecer muito mais próximo de iniciativas de transformação digital e governança da informação do que de um simples experimento com IA.
