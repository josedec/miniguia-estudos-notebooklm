# miniguia-estudos-notebooklm
# Caderno Temático NotebookLM: O Profissional de TI 50+ no Mercado Atual

## 🎯 Contexto e Objetivos

O mercado de Tecnologia da Informação enfrenta um paradoxo: ao mesmo tempo que sofre com o déficit de talentos, muitas vezes demonstra barreiras de etarismo para profissionais maduros. Este projeto foi desenvolvido como parte do Desafio Prático da **DIO (Digital Innovation One)**, utilizando o **Google NotebookLM** como ferramenta de aprendizagem ativa.

O objetivo deste caderno temático é cruzar dados estatísticos, relatórios de mercado e tendências corporativas para mapear o cenário atual, a presença em cargos de liderança e as oportunidades de reinvenção para o profissional de TI com mais de 50 anos (50+).

## 📚 Curadoria de Fontes

Para alimentar o NotebookLM com dados confiáveis e de alta qualidade (priorizando o cenário nacional), foram utilizadas as seguintes fontes:
1. **Relatório Afferolab / Pezco Economics (Baseado na RAIS):** Análise do crescimento de contratações formais 50+ em setores de alta tecnologia. [Disponível em Viva Carreira](https://viva.com.br).
2. **Diagnóstico Comportamental de TI (IT Mídia):** Levantamento apontando que 55% dos diretores de TI em grandes empresas têm mais de 50 anos. [Disponível na Revista Exame](https://exame.com/carreira/sem-etarismo-pesquisa-aponta-que-55-dos-diretores-de-ti-tem-mais-de-50-anos/).
3. **Pesquisa InfoJobs (Diversidade Geracional):** Análise do comportamento do candidato maduro e os desafios do preconceito etário. [Whitepaper Oficial InfoJobs](https://materiais.infojobs.com.br/material-rico-o-mercado-de-trabalho-para-profissionais-40).
4. **Estudo "Mercado de Trabalho Tech: Raio X e Tendências" (Datafolha & Ford):** Investigação detalhando que 98% das empresas enfrentam apagão de talentos. [Disponível no Estúdio Folha](https://estudio.folha.uol.com.br/ford/2026/04/escassez-de-talentos-em-tecnologia-atinge-98-das-empresas-no-brasil-aponta-pesquisa-datafolha-e-ford.shtml).
---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Aqui está o registro do raciocínio e da evolução dos testes de prompts com o NotebookLM para extrair os melhores insights.

### Teste 1: O Prompt Genérico (Baixo resultado)
* **Prompt:** *Me fale sobre o profissional de TI de 50 anos.*
* **Resposta da IA:** Deu uma resposta genérica sobre mercado de trabalho e envelhecimento da população, sem focar nos dados específicos das fontes anexadas.
* **Cicatriz/Dificuldade:** O NotebookLM precisa de guias claros para focar estritamente nos documentos carregados e não no conhecimento geral da internet.

### Teste 2: O Prompt Estruturado (Refinamento)
* **Prompt:** *Com base estritamente nas fontes fornecidas, qual é o principal paradoxo enfrentado pelo profissional de TI 50+ no mercado de trabalho brasileiro atual? Estruture a resposta em tópicos citando números.*
* **Resposta da IA:** Excelente. A IA cruzou o dado da IT Mídia (55% de diretores são 50+) com o dado do InfoJobs/GPTW (baixa taxa de contratação em vagas de base e relatos de etarismo).
* **Aprendizado:** Prompts restritivos (*"com base estritamente nas fontes fornecidas"*) e que exigem formatos específicos (*"em tópicos citando números"*) funcionam muito melhor no NotebookLM.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado do Assunto

* **O Paradoxo do Mercado:** Enquanto a liderança técnica e o C-Level de grandes corporações são predominantemente ocupados por profissionais experientes (55% dos diretores de TI), as vagas operacionais e de transição de carreira ainda apresentam forte barreira de entrada devido ao etarismo corporativo.
* **A Força dos Dados:** A contratação formal desse público cresceu mais de 50% nos últimos anos, impulsionada pelo apagão de talentos tech. O público sênior se mostra extremamente ativo em plataformas de busca de emprego.
* **Solução de Mercado:** A "Economia Prateada" e a mentoria reversa surgem como ferramentas para que empresas unam a energia dos profissionais mais jovens (Gen Z) à resiliência e maturidade emocional (Soft Skills) do profissional 50+.

### 2. Glossário de Conceitos-Chave

* **Etarismo (Ageism):** Preconceito, estereotipação ou discriminação contra indivíduos ou grupos com base na idade.
* **Economia Prateada (Silver Economy):** O ecossistema de atividades econômicas, produtos e serviços voltados para atender às necessidades de pessoas com mais de 50 anos.
* **C-Level:** Cargos de nível executivo de uma empresa (Chief Executive Officer, Chief Technology Officer, etc.).
* **Soft Skills:** Habilidades comportamentais e inteligência emocional, altamente valorizadas em profissionais seniores para gestão de crises e liderança.

### 3. Prompts Reutilizáveis para Revisões Futuras

Guarde estes prompts para usar quando atualizar o seu caderno com novas fontes:

* *“Crie um resumo executivo focando apenas nas novas estatísticas de contratação de profissionais de TI maduros introduzidas nos últimos documentos.”*
* *“Atuando como um consultor de RH, liste 5 argumentos contidos no texto para convencer uma empresa tech a contratar desenvolvedores seniores acima de 50 anos.”*
* *“Quais são as principais lacunas ou contradições de dados entre as fontes fornecidas sobre o tema?”*

---
🎨 Projeto desenvolvido para o Desafio de Projeto da DIO.
