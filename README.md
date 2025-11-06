# 🚀 GeekStation — Guia de Publicação na Vercel

Bem-vindo ao **GeekStation**, seu portal geek com estilo cyberpunk e sistema de recomendações afiliadas! 💻⚡

---

## 🌐 Como colocar o site online (Vercel)

### 1️⃣ Criar conta na Vercel
1. Vá para [https://vercel.com](https://vercel.com)
2. Clique em **Sign Up**
3. Entre com sua conta **GitHub**

---

### 2️⃣ Enviar o código para o GitHub
1. Crie um novo repositório em [https://github.com/new](https://github.com/new)
2. No seu computador, descompacte o arquivo `geekstation.zip`
3. No terminal:
   ```bash
   git init
   git add .
   git commit -m "Versão inicial do GeekStation"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/geekstation.git
   git push -u origin main
   ```

---

### 3️⃣ Publicar na Vercel
1. Vá até [https://vercel.com/dashboard](https://vercel.com/dashboard)
2. Clique em **Add New Project → Import Git Repository**
3. Selecione o repositório **geekstation**
4. Vercel detecta automaticamente o framework **React + Vite**
5. Clique em **Deploy** 🎉

➡️ Seu site ficará disponível em:
```
https://geekstation.vercel.app
```

---

### 4️⃣ Domínio personalizado (opcional)
Na Vercel, vá em **Settings → Domains**
- Pode usar o domínio gratuito `geekstation.vercel.app`
- Ou conectar um domínio próprio (ex: `geekstation.com.br`)

---

### 5️⃣ Atualizações futuras
Sempre que atualizar algo no código:
```bash
git add .
git commit -m "Atualização GeekStation"
git push
```
A Vercel atualizará o site automaticamente! ⚡

---

Feito com por Davi
