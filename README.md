# 📄 NF·highlight

Ferramenta web para destacar automaticamente informações importantes em Notas Fiscais em PDF.

**100% local — nenhum dado sai do seu computador.**

## ✨ O que é destacado

| Categoria | Cor | Exemplos |
|-----------|-----|---------|
| CNPJ / CPF | 🟡 Amarelo | `12.345.678/0001-99` |
| Valores (R$) | 🟢 Verde | `R$ 1.500,00` |
| Datas | 🔵 Azul | `01/01/2024` |
| Chave de Acesso | 🩷 Rosa | `0000 0000 0000 ...` |
| Nº Nota / Série | 🟠 Laranja | `NF 000123`, `Série 1` |

## 🚀 Como usar

### Opção 1 — GitHub Pages (recomendado para a empresa)

1. Faça um fork deste repositório
2. Vá em **Settings → Pages → Branch: main → / (root)**
3. Acesse o link gerado (ex: `https://suaempresa.github.io/nf-highlight`)
4. Pronto! Compartilhe o link com o time.

### Opção 2 — Rodar localmente

Basta abrir o arquivo `index.html` direto no navegador. Não precisa de servidor.

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/nf-highlight.git

# Abra o arquivo
open index.html   # macOS
start index.html  # Windows
```

## 🔒 Privacidade

- Nenhuma biblioteca externa de analytics
- O PDF nunca é enviado para nenhum servidor
- Todo o processamento ocorre no navegador do usuário
- Pode ser usado sem conexão à internet (após carregado)

## 🛠️ Tecnologias

- [PDF.js](https://mozilla.github.io/pdf.js/) — leitura do PDF no navegador
- HTML + CSS + JavaScript puro — sem frameworks

## 📁 Estrutura

```
nf-highlight/
└── index.html   # tudo em um único arquivo
```
