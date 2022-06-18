# Introdução
Git é um sistema de controle de versão distribuido, foi criado por Linus Torvalds também criador do Linux.
Com ele é possível ter todo o nosso histórico e arquivos que ficam em um repositório.

Dentro do Git temos blobs, tree e commits:
Blobs é uma abreviação para ''binary large object". Quando usamos o comando git add em um arquivo, é criado um ''objet blob'' que contém os conteúdos dos arquivos.

Trees representa um diretório, contendo blobs e trees, ou seja uma listagem de diretório podendo referenciar blobs e outras trees.

commits é a realização de um conjunto de mudanças.

## Comandos basicos do Git Bash
 - Podemos fazer o download do [Git](https://git-scm.com/), após o download instalar o Git e fazer uma conta no Github.
 Configurar usuário: git config --global user.name "NOME DO USUÁRIO"
 Configurar email: git config --global user.email "EMAIL USADO NA CONTA CRIADA NO GITHUB"
 
 - Configuração de credencial SSH (essa credencial deverá ser adicionada em seu computador de confiança)
 No perfil do Github nas configurações você encontrá "SSH and GPG keys" lá você irá inserir a chave SSH.
 
 No Gib Bash você coloque o seguinte comando: "ssh-keygen -t ed25519 -C "your_email@example.com"" ele irá gerar uma chave para você, copie a chave e cole no seu perfil.

 -  Após instalação e configuração segue lista de comandos para navegação e criação de repositório
 
ls- utilizado pata listar itens, assim podemos saber o que tem no repositório.

cd -utilizado para mudar/entrar no repositório.

cd .. - este comando é utilizado para "voltar" ao repositório anterior.

mv - utilizado para mover um repositório para dentro de outro ou ao contrario também.

ls -a - Utilizados para listar todos os arquivos até mesmo os ocultos.

git init - para iniciar o Git.

git remote add "Palavra chave" https://github.com/username/nome_remositorio.git - comando utilizado para configurar git repositório remoto.

Git Push origin main - Quando vamos devolver para o repositório clone

Git Push origin master - quando vamos utilizar nosso Repositório Remoto

git clone https://github.com/username/nome_repositorio.git - comando para clonar um repositório do Github