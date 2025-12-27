# 🚀 COMO SUBIR NO GITHUB - GUIA PASSO A PASSO

## Pré-requisitos

1. Ter uma conta no GitHub (crie em: https://github.com)
2. Ter Git instalado no computador (baixe em: https://git-scm.com)

---

## 📋 PASSO 1: Criar Repositório no GitHub

1. Acesse: https://github.com/new
2. Nome do repositório: `whatsapp-10k`
3. Descrição: "Landing page para curso WhatsApp 10K"
4. Público ou Privado (você escolhe)
5. **NÃO** marque "Add README" (já temos um)
6. Clique em **Create repository**

---

## 💻 PASSO 2: Subir os Arquivos

### Opção A - Pelo Site (Mais Fácil)

1. No repositório criado, clique em **uploading an existing file**
2. Arraste TODOS os arquivos da pasta `whatsapp-10k-github`:
   - `index.html`
   - `README.md`
   - `.gitignore`
   - Pasta `assets/` completa
3. Escreva mensagem: "Initial commit"
4. Clique em **Commit changes**

### Opção B - Por Linha de Comando

Abra o terminal/cmd na pasta do projeto e execute:

```bash
# Inicializar Git
git init

# Adicionar todos os arquivos
git add .

# Fazer primeiro commit
git commit -m "Initial commit - WhatsApp 10K Landing Page"

# Conectar ao repositório remoto (substitua USERNAME pelo seu usuário)
git remote add origin https://github.com/USERNAME/whatsapp-10k.git

# Enviar para o GitHub
git branch -M main
git push -u origin main
```

---

## 🌐 PASSO 3: Ativar GitHub Pages (Hospedar Grátis)

1. No seu repositório, vá em **Settings**
2. No menu lateral, clique em **Pages**
3. Em **Source**, selecione: `main` branch
4. Clique em **Save**
5. Aguarde 1-2 minutos
6. Seu site estará em: `https://USERNAME.github.io/whatsapp-10k`

---

## 📸 PASSO 4: Adicionar as Imagens

### Pelo GitHub Web:

1. Acesse seu repositório
2. Navegue até: `assets/images/`
3. Clique em **Add file** → **Upload files**
4. Arraste as 7 imagens que você criou
5. Commit: "Add images"

### Por Linha de Comando:

```bash
# Cole as imagens na pasta assets/images/
# Depois execute:

git add assets/images/*
git commit -m "Add images"
git push
```

---

## ✅ PASSO 5: Testar o Site

1. Acesse: `https://USERNAME.github.io/whatsapp-10k`
2. Teste tudo:
   - [ ] Imagens aparecem
   - [ ] Botões funcionam
   - [ ] WhatsApp abre
   - [ ] Design está bonito
   - [ ] Funciona no celular

---

## 🔧 Como Fazer Alterações Depois

### Pelo GitHub Web:
1. Clique no arquivo que quer editar
2. Clique no ícone de lápis (editar)
3. Faça as alterações
4. Commit changes

### Por Linha de Comando:
```bash
# Edite o arquivo localmente
# Depois:

git add .
git commit -m "Descrição da mudança"
git push
```

---

## 🔗 Usar Domínio Próprio (Opcional)

Se você comprar um domínio (ex: whatsapp10k.com.br):

1. No GitHub Pages settings
2. Em **Custom domain**, coloque: `whatsapp10k.com.br`
3. No seu provedor de domínio, adicione registro CNAME:
   - Nome: `@` ou deixe vazio
   - Valor: `USERNAME.github.io`

---

## 🆘 Problemas Comuns

### "Imagens não aparecem"
- Verifique se estão na pasta `assets/images/`
- Nomes devem ser EXATAMENTE como no HTML
- `logo-whatsapp-10k.png` ≠ `Logo-WhatsApp-10k.png`

### "Site não atualiza"
- Aguarde 1-2 minutos após o commit
- Limpe o cache do navegador (Ctrl + Shift + R)
- Aguarde o GitHub Pages processar

### "404 Not Found"
- Verifique se o repositório é público
- Verifique se GitHub Pages está ativado
- Aguarde alguns minutos

---

## 📱 Próximos Passos

Depois de subir no GitHub:

1. ✅ Teste tudo completamente
2. ✅ Configure o link de checkout da Kiwify
3. ✅ Configure seu WhatsApp
4. ✅ Adicione CNPJ/CPF
5. ✅ Divulgue o link!

---

## 🎉 Pronto!

Seu site está no ar, grátis, com:
- ✅ Hospedagem profissional
- ✅ HTTPS automático
- ✅ Backup versionado
- ✅ Fácil de atualizar

**Qualquer dúvida, consulte: https://docs.github.com/pt/pages**

---

**Boa sorte com as vendas! 💰🚀**
