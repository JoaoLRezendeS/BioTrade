# 🛒 Biotrade 5.0

O **Biotrade 5.0** é um sistema web de gestão comercial desenvolvido em **PHP, MySQL e JavaScript**, com interface moderna em HTML e CSS.  
Ele foi projetado para auxiliar no controle de **vendas, notas fiscais, pagamentos, mercadorias e fornecedores**, proporcionando uma experiência intuitiva e integrada.  

---

## ✨ Funcionalidades Principais

- 📦 **Gestão de Mercadorias** – cadastro e acompanhamento de produtos  
- 🧾 **Controle de Notas Fiscais** – emissão e organização simplificada  
- 💳 **Sistema de Pagamentos** – suporte a múltiplas formas, incluindo **PIX**  
- 📊 **Relatórios** – geração de relatórios de vendas e desempenho  
- 👤 **Gestão de Usuários/Fornecedores** – cadastro e gerenciamento  

---

## 🛠️ Tecnologias Utilizadas

- **Backend:** PHP 7+  
- **Frontend:** HTML5, CSS3, JavaScript  
- **Banco de Dados:** MySQL (dump incluído em `BioTrade.sql`)  
- **Gerenciador de Dependências:** Composer  

---

## 📂 Estrutura de Pastas

Biotrade_5.0/
├── Biotrade/
│ ├── index.php
│ ├── database.php
│ ├── Registro.php
│ ├── pix.php
│ ├── relatorio_vendas.php
│ ├── pag_princ.html / .css / .js
│ ├── pag_merca.html / .css / .js
│ ├── Pag_relatorio.html / .css / .js
│ ├── Pag_TelaForn.html / .css / .js
│ └── [outros módulos do sistema]
├── BioTrade.sql # Dump do banco de dados
├── composer.json # Dependências PHP
├── composer.lock
└── .vscode/ # Configurações de ambiente

yaml
Copiar
Editar

---

## 🚀 Como Executar Localmente

### 1. Pré-requisitos
- PHP 7.4+  
- MySQL 5.7+  
- Composer instalado  
- Servidor Apache (ex: XAMPP ou WAMP)  

### 2. Configuração
1. Clone este repositório:
   ```bash
   
