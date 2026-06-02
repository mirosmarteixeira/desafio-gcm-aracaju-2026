# 📘 INSTRUÇÕES — DESAFIO GCM ARACAJU 2026
## Como publicar o sistema no GitHub Pages (grátis)

---

## ✅ O QUE VOCÊ VAI PRECISAR

- Conta no GitHub (gratuita) → https://github.com
- Os arquivos desta pasta:
  - `index.html`
  - `README.md`
  - `.gitignore`
  - `.github/workflows/deploy.yml`

---

## 🚀 PASSO A PASSO — MÉTODO MAIS FÁCIL (pelo site do GitHub)

---

### PASSO 1 — Criar uma conta no GitHub (se ainda não tiver)

1. Acesse https://github.com
2. Clique em **Sign up**
3. Crie sua conta gratuitamente

---

### PASSO 2 — Criar o repositório

1. Acesse https://github.com/new
2. Preencha os campos:
   - **Repository name:** `gcm2026`
   - **Description:** `Sistema de estudos GCM Aracaju 2026`
   - **Visibility:** ✅ Public *(obrigatório para GitHub Pages gratuito)*
   - **Add a README file:** ❌ NÃO marque (já temos o nosso)
3. Clique em **Create repository**

---

### PASSO 3 — Fazer upload dos arquivos

Após criar o repositório, você verá uma tela vazia. Siga:

1. Clique em **"uploading an existing file"**
   *(ou no botão "Add file" → "Upload files")*

2. Arraste ou selecione os seguintes arquivos/pastas:
   - `index.html`
   - `README.md`
   - `.gitignore`

3. Para o arquivo do workflow, você precisará criar manualmente:
   - Clique em **"Create new file"**
   - No campo do nome, digite exatamente:
     ```
     .github/workflows/deploy.yml
     ```
     *(o GitHub criará as pastas automaticamente ao digitar a barra)*
   - Cole o conteúdo do arquivo `deploy.yml` desta pasta
   - Clique em **"Commit new file"**

4. De volta à tela principal, clique em **"Commit changes"** para confirmar os uploads

---

### PASSO 4 — Ativar o GitHub Pages com Actions

1. No repositório, clique na aba **Settings** (⚙️)
2. No menu lateral esquerdo, clique em **Pages**
3. Em **"Source"**, selecione: **GitHub Actions**
4. Clique em **Save** (se aparecer)

---

### PASSO 5 — Aguardar o deploy automático

1. Clique na aba **Actions** no topo do repositório
2. Você verá um workflow rodando chamado **"Deploy to GitHub Pages"**
3. Aguarde 1-2 minutos até aparecer um ✅ verde
4. Volte em **Settings → Pages**
5. Você verá o link do seu site:

```
https://SEU-USUARIO.github.io/gcm2026
```

---

## 🔗 COMPARTILHANDO O LINK

Copie o link e envie para o grupo do WhatsApp:

```
Acesse o sistema de estudos:
https://SEU-USUARIO.github.io/gcm2026
```

> Substitua **SEU-USUARIO** pelo seu nome de usuário do GitHub.

---

## 🔄 COMO ATUALIZAR O SISTEMA NO FUTURO

Sempre que quiser atualizar o `index.html`:

1. Acesse seu repositório no GitHub
2. Clique no arquivo `index.html`
3. Clique no ícone de lápis ✏️ (Edit)
4. Faça as alterações
5. Clique em **"Commit changes"**
6. O deploy automático será feito em ~1 minuto

Ou arraste o novo `index.html` via **"Add file → Upload files"**.

---

## 📱 ACESSANDO NO CELULAR

O sistema funciona direto no navegador do celular!

- Abra o Chrome no Android
- Acesse o link do GitHub Pages
- Toque em ⋮ (menu) → **"Adicionar à tela inicial"**
- Pronto! O sistema fica como um app no seu celular

---

## ❓ PROBLEMAS COMUNS

| Problema | Solução |
|----------|---------|
| "Page not found" após o deploy | Aguarde mais 2-3 minutos e atualize a página |
| Workflow com ❌ vermelho | Verifique se o arquivo `.github/workflows/deploy.yml` está na pasta correta |
| Pages não aparece nas Settings | Certifique-se de que o repositório é **Public** |
| Não encontra a opção "GitHub Actions" | Na aba Pages, clique em "Source" e selecione a opção |

---

## 📞 SUPORTE

Em caso de dúvidas, entre em contato com o desenvolvedor:
**Mirosmar Teixeira**

---

*DESAFIO GCM ARACAJU 2026 — Desenvolvido por Mirosmar Teixeira*
