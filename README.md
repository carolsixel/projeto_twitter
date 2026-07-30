#  Projeto Final EBAC - Twitter

Esse é um projeto de conclusão do Cusro EBAC - Fulltack Python. Foi desenvolvido um clone do Twitter utilizando o framework Django. A aplicação conta com um sistema completo de interação, suporte a mídias e uma interface que pode ser alterada para Modo Escuro.

## Funcionalidades:

### Sistema de Autenticação:
- **Cadastro e Login:** Sistema de criação e autenticação de usuários.
- **Alteração de Senha:** Funcionalidade para alteração de senha dentro do perfil do usuário.

### Perfil e Customização:
- **Edição de Perfil:** Alteração de nome de usuário, biografia, foto de perfil e imagem de capa.
- **Followers e Following:** Contador em tempo real de seguidores e seguidos.

### Feed:
- **Feed:** Exibe apenas posts do próprio usuário e das pessoas que ele segue.
- **Sistema de Follow:** Possibilita seguir ou deixar de seguir qualquer usuário.
- **Listas de Follow:** Exibe quem o usuário segue e quem são seus seguidores.

### Interações:
- **Likes:** Possibilita curtir e descurtir posts instantaneamente.
- **Retweets:** Sistema de retweetar posts de outros usuários.
- **Comentários:** Sistema que possibilita comentar nos posts.

### Mídia e Notificações:
- **Suporte a Mídia:** Posts com suporte para upload de Imagens e Vídeos.
- **Central de Notificações:** Sistema de alerta para novas curtidas, comentários, retweets e novos seguidores.

---

## Stacks:

- **Back-end:** Python e Django (Arquitetura Monolítica).
- **Banco de Dados:** SQLite.
- **Front-end:** HTML5, Tailwind CSS.

---

## Como rodar localmente:

1. **Clone o repositório:**

   git clone https://github.com/carolsixel/projeto_twitter.git
   cd projeto_twitter

2. **Crie e ative um ambiente virtual (venv):**
python -m venv venv

# Linux / Mac
source venv/bin/activate

# Windows
.\venv\Scripts\activate

3. **Instale as dependências:**
pip install -r requirements.txt

4. **Realize as migrações do Banco de Dados:**
python manage.py migrate

5. **Crie um usuário administrador (Superusuario):**
python manage.py createsuperuser

6. **Inicie o servidor de desenvolvimento:**
python manage.py runserver

7. **Acesse a aplicação em:**
 http://127.0.0.1:8000/

---

## Deploy:

O Site pode ser acessada através do link:

https://projeto-twitter.onrender.com