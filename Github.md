Comandos: :) 
git --version -> verifica a verção do git instalada e se realmente ela esta no computador;

git init cria um repositorio git dentro de uma pasta especifica;

git add escreve qual o arquivo é mandado para a area de stadin;

git status mostra qual é o status atual do commit;

git commit -m "TITULO" é o que salva as auterações do arquivo;

git branch -M "main" muda o nome da sua branch;

git remote add origin https://github.com/Gaabs007/Projetogit.git.
remote significa a reposição entre o repositorio local e o do github, add pra adicionar e origin significa o nome do repositorio do git hub + o link;

git remote remove origin esse comando serve para caso se tenha adicionado uma origin antes dela ser criada no github;

git checkout -b "TITULO" cria uma branch que é utilizada para a criação de alguma future no seu programa onde o codigo que vc criar ainda não sera necessariamente salvo na versão final do github;

checkout serve para sairmos da nossa branch e ir até alguma outra;

git checkout (nome da branch) esse comando alterna entre as branchs;

git push -u origin main; manda o que esta salvo no git para o github;
commit são as versões do arquivo no git;

git merge (nome da branch secundaria) esse comando vai mandar a branch secundaria para a principal

Exclua um branch com o comando git branch -d <branch> . A opção -d excluirá o branch somente se você já fez o push e o merge com o branch remoto. Use a opção -D em vez disso se quiser forçar a exclusão do branch, mesmo que você ainda não tenha feito o push e o merge com ele;

Você consgue ver o conteúdo do arquivo index com o comando git ls-files.
Para exibir o conteúdo do index para todos os arquivos versionados execute

Quando você executa um comando git que edita o índice, o Git cria um novo arquivo index.lock, grava as alterações e renomeia o arquivo. O arquivo index.lock indica para outros processos do Git que o repositório está bloqueado para edição;

Para clonar um repositorio no github seja ele seu proprio ou de outras pessoas que deixaram o repositorio publico tudo que precisamos fazer e criar uma pasta e abrir o gitbash dela, depois utilizar o comanto 
git clone <link-do-repositorio>;

o comando cd é utilizado para nos movermos para um diretorio especifico dentro do git bash entao digitamos cd <Descktop/exemplo/exemplos/exemplo.git>;

O git pull é utizado para quando fizermos o dowload de um arquivo do github nosso ou de outra pessoa e essa pessoa realizou uma alteração depois do que nos baixarmos. Dessa forma utilizando o git pull na pasta em que nos fizemos o dowload ela tambem sera atualizada de acordo com a ultima alteração;