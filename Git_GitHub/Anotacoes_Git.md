# Anotações

#### :link: Link para download do  Git:

[Git - Download](https://git-scm.com/downloads)



### :control_knobs: Comandos para uso no terminal

| Comando                                                      | Ação                                             |
| ------------------------------------------------------------ | ------------------------------------------------ |
| "dir" ou "ls"                                                | lista as pastas/arquivos existentes no diretório |
| "cd \\(nome diretório)"                                      | abre o diretório                                 |
| "ls -a"                                                      | lista pasta/arquivos ocultos dentro do diretório |
| "cls" ou "ctrl L"                                            | limpa a tela do terminal                         |
| "mkdir (nome diretório)"                                     | cria diretório                                   |
| "rmdir (nome diretório) /S /Q"                               | remove o diretório                               |
| "mv (nome diretório)./(nome diretório pra onde quer mover)/" | mover diretórios                                 |
| "pwd"                                                        | mostra o caminho até uma pasta                   |



### :key: Gerar uma chave SSH

***Passos e comandos***:

1. No GitHub: Usuário > Settings > SSH e GPG Key > New SSh Key.
2. No Git Bash: comando "ssh-keygen -t ed25519 -C (e-mail)" > definir local para salvar a chave > cadastrar uma passphrase > Verficar se foi criado um par de chaves  (publica/privada) > comando "cat id_ed25519.pub" para mostrar a chave pública > copiar chave pública.
3. No GitHub: adicionar título p/ chave e a chave pública no GitHub > Ass SSH.
4. No Git Bash: comando "eval $(ssh-agent -s)" > vai gerar um agent pid > entragar a chave privada ao agent  passando o caminho onde ela está "ssh-add id_ed25519".
5. No GitHub: para clonar, copiar a chave SSH.

### :pen: Gerar um Token

***Passos e comandos***:

1. No GitHub: Usuário > Settings > Developer Settings > Personal Access tokens > Generate new token > definir um nome > definir data de expiração > em Select scopes marcar "repo" > Generate token > copiar o token e salvar em local seguro.
2. No GitHub: para clonar, copiar a URL da página (https...).

### 👬🏿 Clonar repositório no GIT

***Passos e comandos***:

1. No GitHub: copiar URL (se usar token) ou SSH (se estiver usando a chave)

2. No Git Bash: comando "git clone (colar URL ou SSH a ser clonado)"

   🚨 ***Obs importante***: Não copiar a URL se tiver criado uma chave SSH.

### :muscle: Criar repositório no GIT



### :wrench: Conflitos - Merge





