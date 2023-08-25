# Git e Github
## Git:
Git é uma ferramenta utilizada por diversas pessoas para salvar projetos de forma mais segura e de forma mais organizada. De forma simples, o projeto salvo no seu computador (repositório local) será rastreado por um site (repositório remoto) para que você consiga salvar alterações chaves em um respositório remoto, deixando o seu projeto organizado e salvo na internet, caso você precise baixar o projeto em outro computador.  
Existem 4 "maneiras" que seu arquivo/projeto pode estar programado.
- Unstaged: O arquivo não está sendo rastreado pelo repositório remoto.
- Staged: O arquivo está sendo rastreado pelo repositório remoto.
- Commited: O arquivo está pronto para ser colocado no repositório remoto.
- No repositório remoto: o arquivo/projeto pode ser baixado em outros computadores pelo repositório remoto.

## GitHub:
GitHub é a ferramenta de repositório remoto utilizado por diversas pessoas. Essa vai ser a ferramenta apresentada nesse tutorial.

## Como começar a utilizar o Git e GitHub (Command Guide):
- Antes de qualquer coisa
    - Você deve baixar o [Git](https://git-scm.com/)  no seu computador.
    - Posteriormente, você deve criar um conta no [GitHub](https://github.com/).
    - Para dar continuidade as atividades, utilize o "CMD" (Prompt de Comando)

### Verificando se o Git está instalado e em qual versão ele está:
- git --version
### Configurando variáveis:
- git config --global user.email you@example.com
- git config --global user.name "Your Name"

## Criando pasta remota e configurando para usá-la no repositório local (Command Guide) 
- Vá para o seu perfil no GitHub e entre em "Your repositories": 
![Repositório](/assets/Screenshot_1.png "Your repositories") 

- Crie uma novo repositório: 
![New](/assets/Screenshot_2.png "New")

- Crie uma pasta com nome, descrição e arquivo README.md
![Pasta](/assets/Screenshot_3.png "Pasta")

- Em um local do seu computador, copie a pasta através do CMD como o comando:
    - git clone < link > 

![Pasta](/assets/Screenshot_4.png "Pasta")

![Pasta](/assets/Screenshot_5.png "Pasta")

![Pasta](/assets/Screenshot_6.png "Pasta")

- Pronto, agora seu repositório local e seu repositório remoto estão conectados!

### Commanda Guide

- Para deixar seu arquivo/pasta pronto para um "commit" use:  
    - "git add ." para todos os arquivos
    - "git add (arquivo)" para apenas um arquivo  
- Para deixar seu arquivo/pasta pronto para enviar ao repositório remoto:
    - "git commit -m (comentário)"
- Para enviar seu arquivo/pasta para o reposiório remoto:
    - git push
- Para trazer arquivos/pastas presentes no repositório remoto para o local
    - git pull