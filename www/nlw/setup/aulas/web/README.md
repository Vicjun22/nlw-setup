## WEB

Instalar as dependências
* npm install


Instalando bibliotecas de estilização:
* npm install -D tailwindcss postcss autoprefixer

tailwindcss -> é um plugin do postcss
postcss -> automatiza tarefas dentro do css
autoprefixer -> é uma ferramenta que adicina prefixos de browser

Criando a configuração do postcss.config.cjs, do contrário o Vite não interpreta o tailwindcss
* npx tailwindcss init -p