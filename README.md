# LaraGram 📸

Clone do Instagram desenvolvido em Laravel com MongoDB.

## 🚀 Tecnologias
- Laravel 10+
- MongoDB Atlas
- Bootstrap 5
- Vite

## ✨ Funcionalidades
✅ Registro/Login de usuários  
✅ Upload de posts com imagens  
✅ Sistema de likes e comentários  
✅ Perfil personalizável  
✅ Controle de acesso por dono

## 📦 Instalação

```bash
# 1. Clone o repositório
git clone [url]
cd laragram

# 2. Instale dependências
composer install
npm install

# 3. Configure ambiente
cp .env.example .env
php artisan key:generate

# 4. Configure MongoDB no .env:
DB_CONNECTION=mongodb
MONGODB_URI=sua_string_de_conexao
MONGODB_DATABASE=laragram

# 5. Build assets
npm run build

# 6. Inicie servidor
php artisan serve
