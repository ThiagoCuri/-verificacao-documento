# 🇧🇷 Landing Page - Verificação de Documento

Landing Page profissional para verificação de autenticidade de documentos, inspirada no padrão GOV.BR.

## 🚀 Deploy Rápido no Vercel

### Passo 1: Criar Repositório no GitHub

1. Acesse: https://github.com/new
2. Nome do repositório: `verificacao-documento` (ou o nome que preferir)
3. Deixe como **Public** ou **Private** (sua escolha)
4. **NÃO** marque "Add a README file"
5. Clique em "Create repository"

### Passo 2: Fazer Upload dos Arquivos

No seu terminal/prompt de comando, navegue até a pasta do projeto e execute:

```bash
# Configure seu nome e email (apenas na primeira vez)
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"

# Adicione os arquivos
git add .

# Faça o commit
git commit -m "Initial commit - Landing Page de Verificação"

# Conecte ao seu repositório GitHub (substitua SEU-USUARIO e NOME-DO-REPO)
git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPO.git

# Renomeie a branch para main (padrão do GitHub)
git branch -M main

# Envie para o GitHub
git push -u origin main
```

**Dica:** O GitHub vai pedir suas credenciais. Se for a primeira vez, pode precisar criar um **Personal Access Token** em: https://github.com/settings/tokens

### Passo 3: Deploy no Vercel

1. Acesse: https://vercel.com
2. Clique em "Add New" → "Project"
3. Clique em "Import Git Repository"
4. Selecione seu repositório `verificacao-documento`
5. Clique em "Import"
6. **NÃO PRECISA MUDAR NENHUMA CONFIGURAÇÃO**
7. Clique em "Deploy"
8. Aguarde ~30 segundos
9. 🎉 **PRONTO!** Link público gerado!

### Passo 4: Pegar o Link Público

Após o deploy, o Vercel vai gerar um link tipo:
```
https://verificacao-documento-abc123.vercel.app
```

Você pode também configurar um domínio personalizado nas configurações do projeto no Vercel.

---

## 📋 O que está incluído

- ✅ HTML completo e responsivo
- ✅ Design profissional padrão GOV.BR
- ✅ Todas as informações do documento
- ✅ Layout mobile-friendly
- ✅ Configuração do Vercel pronta

## 🔄 Atualizações Futuras

Para atualizar a Landing Page:

```bash
# Faça suas alterações no index.html

# Adicione as mudanças
git add .

# Faça o commit
git commit -m "Descrição das alterações"

# Envie para o GitHub
git push
```

O Vercel vai fazer o deploy automático das alterações!

---

## 📞 Suporte

Se tiver dúvidas sobre:
- **GitHub:** https://docs.github.com
- **Vercel:** https://vercel.com/docs

---

Desenvolvido com 💙 para verificação de documentos oficiais brasileiros.
