# 🛡️ Relatório de Cibersegurança – CineViewExperience

## 📋 Descrição

Este repositório contém o relatório técnico de análise de segurança da aplicação web **CineViewExperience**, desenvolvido como parte da disciplina de Cibersegurança.

A análise focou em identificar vulnerabilidades comuns em aplicações web, simulando ataques e avaliando o impacto de falhas exploráveis, sempre respeitando o escopo proposto pela atividade.

---

## 🧪 Metodologia

A metodologia utilizada baseou-se em:

- Preparação e configuração do ambiente com **Docker**
- Navegação e testes manuais em endpoints de front-end e back-end
- Interceptação e modificação de requisições com **Burp Suite**
- Testes exploratórios baseados no comportamento da aplicação
- Simulação de ataques (brute force, tampering, session fixation, etc.)

---

## ✅ Estrutura do Relatório

O relatório PDF contém:

- **Capa**
- **Resumo do Projeto**  
  Total de vulnerabilidades, datas de início e término, principais impactos
- **Seção de Vulnerabilidades**  
  Cada vulnerabilidade reportada inclui:
  - Nome da vulnerabilidade
  - Ponto afetado (URL, funcionalidade ou comportamento sistêmico)
  - Descrição técnica e evidências (print ou explicação)
  - Passos para reprodução
  - Impacto à aplicação
  - Procedimento de correção recomendado

---

## 🐞 Vulnerabilidades Identificadas

1. **Enumeração de Usuários**
2. **Falha de Autenticação (Sessão)**
3. **Session Fixation**
4. **IDOR (Insecure Direct Object Reference)**
5. **Ataque de Força-Bruta**
6. **Falta de Monitoramento e Logging**
7. **Manipulação de Preço (Tampering)**

---

## 🛠 Ferramentas Utilizadas

- 🐳 Docker / Docker Compose  
- 🌐 Navegador (modo anônimo e autenticado)  
- 🔍 Burp Suite (Community Edition)  
- 🧾 Editor de texto / terminal  
- 🧠 ChatGPT (para suporte e validação de técnicas)

---

## 👤 Autoria

**Aluna:** Maria Júlia Pessoa Cunha  
**Professor:** Henrique Arcoverde  
**Curso:** *Ciência da Computação*  
**Período:** *Sexto período*  
**Data de início:** 16/04/2025  
**Data de término:** 25/04/2025

---

## 📁 Arquivos

- `Relatorio_Reorganizado_Ciberseguranca.pdf` – Versão final do relatório
- `README.md` – Este arquivo de instruções

---

## 🔐 Observações Finais

Este relatório é um exercício acadêmico com propósito educativo. Nenhuma vulnerabilidade foi explorada fora do ambiente controlado e nenhuma aplicação real foi afetada.

