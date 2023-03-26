Lista de comandos e suas funcionalidades:

Você consgue ver o conteúdo do arquivo index com o comando git ls-files.
Para exibir o conteúdo do index para todos os arquivos versionados execute

Quando você executa um comando git que edita o índice, o Git cria um novo arquivo index.lock, grava as alterações e renomeia o arquivo. O arquivo index.lock indica para outros processos do Git que o repositório está bloqueado para edição.