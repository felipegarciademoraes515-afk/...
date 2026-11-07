# GAMEPULSE — O pulso do universo gamer 🎮⚡

Portal editorial moderno e profissional especializado em notícias sobre videogames, hardware, computadores, consoles (PlayStation, Xbox, Nintendo), tecnologia e inteligência artificial.

---

## 🚀 Como Publicar e Gerenciar o Portal Gratuitamente (GitHub + Netlify + Decap CMS)

Este projeto já vem 100% configurado com o **Decap CMS** para que você e sua equipe possam criar, editar e excluir notícias por um painel visual no navegador (em `/admin/`) sem precisar mexer em códigos.

### 1. Criar Repositório no GitHub
1. Acesse [github.com](https://github.com) e crie um novo repositório chamado `gamepulse`.
2. Extraia este pacote `.zip` no seu computador e suba todos os arquivos para a branch `main`:
   ```bash
   git init
   git add .
   git commit -m "Publicação inicial do GamePulse com CMS"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/gamepulse.git
   git push -u origin main
   ```

### 2. Conectar à Netlify (Hospedagem Gratuita)
1. Crie uma conta no [netlify.com](https://www.netlify.com) usando a opção **Sign up with GitHub**.
2. Clique em **Add new site** > **Import an existing project**.
3. Selecione o repositório `gamepulse` que acabou de criar.
4. Mantenha os campos padrão (Publish directory: `.`) e clique em **Deploy site**.
5. Em segundos, seu portal estará ativo na web!

### 3. Ativar o Login Seguro no Painel Editorial
1. No painel do seu site na Netlify, acesse: **Site configuration** > **Identity**.
2. Clique em **Enable Identity**.
3. Role até **Registration preferences** e selecione **Invite only** (para que apenas você convide autores).
4. Role até a seção **Services** > **Git Gateway** e clique em **Enable Git Gateway**.
5. No menu superior da Netlify, clique na aba **Identity** > **Invite users** e insira seu e-mail.
6. Você receberá um e-mail de confirmação para criar sua senha de acesso.

### 4. Acessando o Painel Editorial
- Abra o navegador e acesse: `https://seusite.netlify.app/admin/`
- Faça login com o e-mail e senha cadastrados.
- Pronto! Você terá acesso ao painel para criar novas notícias, enviar fotos e publicar matérias instantaneamente.
