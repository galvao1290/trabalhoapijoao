# Trabalho para Conclusão da Disciplina Criação de API Rest Básica com PHP


# Aqui está uma forma alternativa de expressar a criação de uma API REST básica utilizando PHP e um banco de dados MySQL:

Implementar uma API REST simples utilizando PHP e um banco de dados MySQL.

Recuperar todas as tarefas disponíveis/GET.

Obter detalhes de uma tarefa específica/GET.

Adicionar uma nova tarefa/POST.

Atualizar informações de uma tarefa existente/PUT.

# Aqui estão as instruções para configurar o sistema de API:

Abra o Git Bash e execute o comando "git clone" seguido pela URL do repositório do projeto-laravel do Professor João. Em seguida, digite "cd projeto-laravel/" para entrar na pasta do projeto.

Utilize o comando "code ." para abrir o Visual Studio Code (VSCode) com todos os arquivos do projeto.

Navegue pelos seguintes arquivos e faça as alterações necessárias:

app/Http/Controllers/TaskController.php
database/migrations/2023_06_27_221132_create_tasks_table.php
routes/api.php
routes/web.php
Copie o arquivo ".env.example" novamente e renomeie-o para ".env". Abra o terminal no VSCode pressionando "CTRL+' " e execute o comando "composer install" para baixar as dependências do projeto.

Inicie o XAMPP e inicie os serviços do Apache e MySQL.

No terminal, execute os comandos "php artisan migrate" e "php artisan serve" para iniciar o servidor.

Abra o Postman e crie uma nova collection. Adicione as requests necessárias para criar as funções da API. Para obter mais detalhes sobre como usar o Postman, consulte o vídeo abaixo.

Certifique-se de seguir as instruções e os passos demonstrados no vídeo mencionado para usar o Postman corretamente e interagir com a API.


link do video: https://youtu.be/HiQycu9LVFQ
