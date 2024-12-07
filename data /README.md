# 📂 data - Dados Utilizados no Projeto

A pasta `data` contém os conjuntos de dados utilizados durante as análises do projeto. A organização foi estruturada para facilitar o acesso e o entendimento do fluxo de dados, desde os arquivos originais até os tratados e prontos para uso.

---

## 📁 Estrutura da Pasta

### 📂 `raw/`
Contém os dados originais, sem nenhum tipo de tratamento ou modificação. Esses arquivos são a fonte principal para o início da análise.

**Conteúdo:**
- Arquivo de exemplo: `dataset_credit_raw.csv`
- Descrição: Arquivo bruto contendo informações dos clientes, transações e limites de crédito.

---

### 📂 `processed/`
Contém os dados tratados e preparados para análises. Aqui, os dados passam por etapas de limpeza, normalização e padronização, tornando-os prontos para uso nas análises e modelos.

**Conteúdo:**
- Arquivo de exemplo: `dataset_credit_processed.csv`
- Descrição: Dados ajustados, incluindo:
  - Remoção de valores ausentes.
  - Padronização de variáveis categóricas.
  - Correção de valores discrepantes (outliers).

---

## 🛠️ Como Adicionar Dados
1. Coloque os arquivos brutos na pasta `raw/`.
2. Execute os scripts ou notebooks de limpeza e processamento para gerar os arquivos tratados na pasta `processed/`.

---

## ⚠️ Avisos Importantes
- Não modifique os arquivos diretamente na pasta `raw/`. Ela deve conter apenas os dados originais.
- Sempre documente quaisquer transformações realizadas nos dados na pasta `processed/`.

---

Com essa estrutura, garantimos a rastreabilidade e a consistência dos dados ao longo do projeto.
