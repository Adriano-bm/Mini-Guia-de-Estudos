# Mini-Guia-de-Estudos# 🛡️ Projeto PIX: Evolução, Tecnologia e Mitigação de Fraudes

Este repositório é um caderno temático digital desenvolvido com o auxílio do **NotebookLM** e técnicas avançadas de **Engenharia de Prompts**. O objetivo é documentar a trajetória do PIX no Brasil, analisando sua infraestrutura técnica e as estratégias de segurança contra crimes cibernéticos.

---

## 🎯 Contexto e Objetivos

O PIX revolucionou o Sistema de Pagamentos Brasileiro (SPB). Este estudo visa:
* **Analisar** a transição histórica dos modelos TED/DOC para o pagamento instantâneo.
* **Explorar** os pilares tecnológicos (ISO 20022, DICT e SPI).
* **Mapear** as principais modalidades de fraudes e os mecanismos de defesa (MED e Bloqueio Cautelar).

---

## 📚 Curadoria de Fontes
As análises e resumos contidos aqui foram consolidados a partir das seguintes fontes oficiais:

1.  **[Relatório de Gestão do Pix - Banco Central](https://www.bcb.gov.br/)**: Dados sobre adoção e volume transacionado.
2.  **[Manual de Segurança do PIX (BCB)](https://www.bcb.gov.br/estabilidadefinanceira/pagamentosinstantaneos)**: Detalhamento técnico de criptografia e mTLS.
3.  **[Cartilha de Segurança para Internet (CERT.br)](https://cartilha.cert.br/)**: Guia sobre ataques de Engenharia Social.
4.  **[Resolução BCB nº 103/2021](https://www.bcb.gov.br/)**: Normativa sobre o Mecanismo Especial de Devolução (MED).

---

## 🧠 Engenharia de Prompts e "Cicatrizes"

O processo de extração de conhecimento da IA passou por refinamentos iterativos para evitar respostas superficiais.

### Estratégia de Prompts
* **Prompt Inicial (Incompleto):** *"Explique como funciona o PIX e seus golpes."*
    * *Resultado:* Resposta generalista, sem profundidade técnica.
* **Prompt Refinado (Final):** *"Atue como um Especialista em Segurança Bancária. Estruture uma análise técnica sobre o padrão ISO 20022 no PIX e correlacione como as falhas de engenharia social burlam essa robustez. Use termos técnicos como mTLS e DICT."*

### 🛠️ Troubleshooting (Desafios)
* **O "Alucinógeno":** Em certos momentos, a IA confundiu falhas de interface de apps bancários com vulnerabilidades do protocolo PIX.
* **Solução:** Foi necessário aplicar a técnica de **Chain-of-Thought** (Cadeia de Pensamento), pedindo para a IA separar a camada de rede da camada de aplicação antes de gerar a resposta final.

---

## 📖 Miniguia de Estudo (Resultado Final)

### Resumo Estruturado
O PIX opera sobre o **SPI (Sistema de Pagamentos Instantâneos)**, com liquidação em tempo real. A segurança não reside apenas na criptografia, mas no monitoramento de contas através do **DICT**.

### 📑 Glossário de Conceitos-Chave
| Termo | Definição |
| :--- | :--- |
| **DICT** | Diretório de Contas Transacionais (base de dados das chaves). |
| **mTLS** | Autenticação mútua que garante que apenas instituições autorizadas acessem o BC. |
| **MED** | Mecanismo Especial de Devolução; fluxo de recuperação de valores em fraudes. |
| **Engenharia Social** | Manipulação psicológica do usuário para realizar transações indevidas. |

### ⚡ Prompts Reutilizáveis para Revisão
* *"Liste as atualizações de segurança do PIX implementadas nos últimos 6 meses."*
* *"Explique o funcionamento do Bloqueio Cautelar para um usuário leigo."*

---

## 📂 Organização do Repositório
* `/fontes`: Arquivos PDF e links utilizados no NotebookLM.
* `/resumos`: Documentos gerados pela IA.
* `/scripts`: Exemplos de automação (se houver).

* ## 🔗 Link do Projeto no NotebookLM
Você pode acessar o caderno temático e interagir com a IA através deste link:
[Acesse o Notebook do PIX aqui](https://notebooklm.google.com/notebook/6387e534-d2f5-4958-858d-9a323d01f51a))

---
*Este projeto foi desenvolvido como parte de um plano de estudos em Análise e Desenvolvimento de Sistemas.*
