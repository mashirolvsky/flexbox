# Git

- git status
    //Retorna qual é o estado de como estão os status das diferentes "áreas" do git;
    ex.: Fiz alterações, quero commit-á-las MAS não dei "git add .";

- git init
    //Inicializa um repositório .git na sua pasta local;

- git clone
    //Inicializa um repositório .git, porém, clonando um repositório já existente para a sua pasta local;
    ex.: git clone "https://github.coom/algum-repositorio.git

- git remote add origin [link para o repositório remoto]
    Pede para o git atribuir um repositório remoto à uma variável específica.
    Por convensão, nós damos a essa variável o nome "origin".
    ex.: git remote add origin "https://github.coom/algum-repositorio.git

- git add .
    //Rastrear todas as alterações, adições e remoções feitas nos arquivos da pasta que contém o .git
     
- git commit -m "Alguma coisa"
    //Cria uma referência para as alterções feitas no último git add .

- git checkout
    //Permite acessar um commit ou branch específico.
    Ex.: git checkout 'EFD00AZF342K'


- git push [variavel que representa o seu repositório remoto] [nome da branch]
    //Utilizado para enviar as modificações de uma branch local a uma branch do repositório remoto

- git push --set-upstream

- git pull
    //Utilizado para trazer as modificações de uma branch remota para a sua branch local

- git branch -a
    //lista todas as branches criadas no projeto .git

- git branch [Nome da branch]
    //Cria uma nova branch com o nome passado no terminal git

- git branch -d
    //Deleta uma branch com o nome passado no terminal git
    obs.: Para deletar  uma branch você precisa dar um checkout para uma outra branch

- git checkout -b [Nome da branch]
    //Cria uma nova branch (assim como o git branch) com o nome especificado, e em seguida faz o checkout para ela

-git checkout
    //Permite o desenvolvedor navegar entre branches ou commits
    Ex.: git checkout master
    Ex.: git checkout estilizacoes
    Ex.: git checkout '1EDD3A59O'

- git merge [nome da branch que você deseja trazer as alterações]
    //O merge é utilizado para "mesclar" alterações entre duas branches
    Ex.: Estou na branch "master" e quero trazer todas as modificações feitas na branch SideB. Posso utilizar: git merge SideB, e resolver os conflitos pendentes