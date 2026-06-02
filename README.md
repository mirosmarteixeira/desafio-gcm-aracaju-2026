# 🛡️ DESAFIO GCM ARACAJU 2026

> Sistema de gerenciamento de estudos em grupo para o concurso da **Guarda Municipal de Aracaju — 2026**

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square&logo=github)](https://seuusuario.github.io/desafio-gcm-aracaju-2026)
![HTML](https://img.shields.io/badge/HTML-Single%20File-blue?style=flat-square&logo=html5)
![JS](https://img.shields.io/badge/JavaScript-Vanilla-yellow?style=flat-square&logo=javascript)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

---

## 📋 Sobre o Projeto

Sistema web completo desenvolvido em um único arquivo `index.html`, focado na resolução de questões e acompanhamento de desempenho individual e coletivo para o concurso da Guarda Municipal de Aracaju 2026 (prova: **13/09/2026**).

**Sem backend. Sem instalação. Abre direto no navegador.**

---

## ✨ Funcionalidades

| Módulo | Descrição |
|---|---|
| 🔐 **Login** | 4 usuários fixos com autenticação por senha |
| ⏱ **Contador Regressivo** | Dias/horas/min/seg até a prova com barra de progresso |
| 📚 **Missão do Dia** | Cronograma semanal automático — 70 questões/dia por disciplina |
| ✏️ **Registro de Estudo** | Formulário completo com cálculo automático de erros e aproveitamento |
| 🎯 **Disciplina Extra** | Registro separado para disciplinas fora do cronograma do dia |
| 📊 **Estatísticas** | Individual e coletiva com gráficos interativos (Chart.js) |
| 🏆 **Ranking** | Por questões, aproveitamento, constância e missões batidas |
| 📓 **Caderno de Erros** | Registro, categorização e acompanhamento de status |
| 🎮 **Simulados** | Histórico e gráfico de evolução dos simulados |
| 👥 **Central do Grupo** | Importar/exportar dados JSON entre participantes |
| 📱 **Imagem WhatsApp** | Gera PNG com resumo diário para compartilhar no grupo |
| 💾 **Backup Completo** | Export JSON, CSV e backup total |

---

## 👥 Participantes

| Nome | Senha |
|---|---|
| Amós Barbosa | `AB2026` |
| Walisson Ribeiro | `WR2026` |
| Joalisson Soares | `JS2026` |
| Mirosmar Teixeira | `MT2026` |

---

## 📅 Cronograma Semanal (70 questões/dia)

| Dia | Disciplinas |
|---|---|
| **Segunda** | Português · Dir. Administrativo · Legislação Municipal · Atualidades |
| **Terça** | Dir. Constitucional · Dir. Penal · Raciocínio Lógico · Informática |
| **Quarta** | Português · Dir. Administrativo · Aracaju/SE · Leg. Extravagante |
| **Quinta** | Dir. Penal · Dir. Constitucional · Raciocínio Lógico · Atualidades |
| **Sexta** | Português · Legislação Municipal · Informática · Aracaju/SE |
| **Sábado** | Simulado Parcial · Revisão de Erros · Leg. Extravagante |
| **Domingo** | Simulado Geral · Revisão de Erros · Atualidades |

---

## 🚀 Como Usar

### Opção 1 — GitHub Pages (online)
Acesse diretamente pelo link publicado nas configurações do repositório.

### Opção 2 — Localmente
```bash
git clone https://github.com/SEU_USUARIO/desafio-gcm-aracaju-2026.git
# Abra o arquivo index.html no navegador
```

### Opção 3 — Download direto
Baixe o arquivo `index.html` e abra no navegador. Sem instalação necessária.

---

## 🔄 Compartilhamento entre Participantes

1. Cada participante clica em **GRUPO → Meus Dados JSON** para exportar
2. Envia o `.json` para o grupo do WhatsApp
3. O administrador importa todos os arquivos em **GRUPO → Importar Vários**
4. Ranking e estatísticas coletivas são atualizados automaticamente

---

## 🛠️ Tecnologias

- **HTML5 / CSS3 / JavaScript** (Vanilla — zero dependências locais)
- **[Chart.js 4.4](https://www.chartjs.org/)** via CDN
- **[html2canvas 1.4](https://html2canvas.hertzen.com/)** via CDN
- **LocalStorage** — persistência de dados no navegador
- **Google Fonts** — Orbitron, Rajdhani, Inter

---

## 📁 Estrutura do Repositório

```
desafio-gcm-aracaju-2026/
├── index.html              # Sistema completo (HTML + CSS + JS)
├── README.md               # Este arquivo
├── .gitignore              # Arquivos ignorados pelo Git
└── .github/
    └── workflows/
        └── deploy.yml      # Deploy automático no GitHub Pages
```

---

## 🌐 Deploy no GitHub Pages

O repositório inclui **GitHub Actions** para deploy automático.
A cada `push` na branch `main`, o sistema é publicado em:

```
https://SEU_USUARIO.github.io/desafio-gcm-aracaju-2026/
```

**Para ativar:**
1. Vá em **Settings → Pages**
2. Em *Source*, selecione **GitHub Actions**
3. Faça um push — o deploy ocorre automaticamente

---

## 📄 Licença

MIT License — livre para uso, modificação e distribuição.

---

<div align="center">

Desenvolvido por **Mirosmar Teixeira**

*"70 questões por dia. Uma missão por vez."* ⚔️

</div>
