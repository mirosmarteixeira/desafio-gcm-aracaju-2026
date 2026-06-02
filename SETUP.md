# 📖 Guia de Publicação no GitHub

## Passo a Passo para Colocar Online

### 1. Crie uma conta no GitHub
Acesse https://github.com e crie uma conta gratuita (se ainda não tiver).

---

### 2. Crie um novo repositório
1. Clique em **New** (botão verde no topo)
2. Nome sugerido: `desafio-gcm-aracaju-2026`
3. Deixe como **Public** (obrigatório para GitHub Pages gratuito)
4. **NÃO** marque "Add a README file"
5. Clique em **Create repository**

---

### 3. Faça o upload dos arquivos

#### Opção A — Pelo site (mais fácil, sem instalar nada)
1. Na página do repositório criado, clique em **uploading an existing file**
2. Arraste TODOS os arquivos e a pasta `.github` para a área de upload
3. Clique em **Commit changes**

#### Opção B — Pelo terminal (Git instalado)
```bash
# Entre na pasta com os arquivos
cd desafio-gcm-aracaju-2026

# Inicie o repositório local
git init
git add .
git commit -m "🚀 Lançamento inicial — DESAFIO GCM ARACAJU 2026"

# Conecte ao repositório remoto (substitua SEU_USUARIO)
git remote add origin https://github.com/SEU_USUARIO/desafio-gcm-aracaju-2026.git
git branch -M main
git push -u origin main
```

---

### 4. Ative o GitHub Pages
1. No repositório, vá em **Settings** (aba superior)
2. No menu lateral, clique em **Pages**
3. Em **Source**, selecione **GitHub Actions**
4. Aguarde alguns segundos

---

### 5. Acesse o sistema online
Após o deploy (≈ 1 minuto), o sistema estará disponível em:
```
https://SEU_USUARIO.github.io/desafio-gcm-aracaju-2026/
```

Você verá o link exato na aba **Settings → Pages** do repositório.

---

### 6. Compartilhe o link no grupo
Copie o link e envie para o grupo do WhatsApp com os participantes! 🎉

---

## ⚠️ Observações Importantes

- **Os dados ficam no navegador de cada um** (LocalStorage) — não na nuvem
- Para sincronizar, use a função **Exportar/Importar JSON** entre os participantes
- O GitHub Pages é **gratuito** para repositórios públicos
- Qualquer atualização no código: basta fazer novo push que o deploy ocorre automaticamente

---

## 🔗 Links Úteis

- GitHub: https://github.com
- Documentação GitHub Pages: https://pages.github.com
- Git para Windows: https://gitforwindows.org

---

*Desenvolvido por Mirosmar Teixeira — DESAFIO GCM ARACAJU 2026*
