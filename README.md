
# 📊 Saldo de Licitações

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pedrossntos/saldo-licitacoes/blob/main/saldo_licitacoes.ipynb)

Automação para criação de planilhas Excel a partir de relatórios do sistema SCP, com foco no controle de contratos da área de Infraestrutura e Manutenção/ALMOX.

---

## ✅ Como Usar

Siga os passos abaixo para utilizar a automação corretamente:

### 1. Extrair o Relatório
- Gere o relatório no sistema SCP/e-Processos no formato **HTML** ou **HTM**.

### 2. Fazer Upload no Colab
- Arraste e solte o arquivo `.htm` diretamente no ambiente do Colab, no menu lateral esquerdo.
- Ou clique no ícone da pasta ➜ botão **"Upload"** ➜ selecione o arquivo no seu computador.

### 3. Atualizar o Nome do Arquivo
- No código, localize a variável `nome_arquivo` e altere para o nome exato do seu arquivo:
```python
nome_arquivo = '10.25.1.htm' # ALTERAR O NOME DO ARQUIVO COM O RELATORIO DO EPROCESSOS AQUI
```

### 4. Executar o Código
- Execute todas as células do notebook ou uma por uma, conforme desejar.

### 5. Baixar a Planilha Gerada
- Após a execução, clique duas vezes sobre o arquivo `.xlsx` gerado no menu lateral esquerdo e selecione **"Download"**.

---

## 📁 Sobre a Planilha

O script extrai automaticamente os seguintes campos:
- **Fornecedor** (em destaque)
- **Produto**
- **Unidade de medida**
- **Valor**
- **Quantidade**

O arquivo Excel será salvo com o mesmo nome do arquivo `.htm` de origem.

---
