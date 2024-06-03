# Criando o par de chaves privada e pública para acesso ao repostiório remoto do GitHub.

## Criando o par de chaves:
$ ssh-keygen -t rsa -b 2048

## Acessando a pasta onde foram criados os arquivos:
$ cd ~/.ssh

## Visualize os arquivos
$ ls
id_rsa  id_rsa.pub

## Visualizer os arquivos com detalhes
$ ll //são 2 L minuscucos
> -rw-r--r-- 1 Pedro Bento 197121 2622 Feb 21 17:43 id_rsa
> -rw-r--r-- 1 Pedro Bento 197121  581 Feb 21 17:43 id_rsa.pub

## Visualizar o caminho relativo dos arquivos criados:
$ pwd
> /c/Users/Pedro Bento/.ssh

# Visualizar e copiar a chave public:
$ cat id_rsa.pub

# Copie a chave publica e adicione na sua conta do GitHub na opção "Settings/SSH and GPG Keys":
> Opção disponível clicando no icone do seu usuário GitHub no canto superior direito de sua tela.

