## Apredizado 02/12/2024
* Configuração do meu usuario local git 
 git config --global user.name "seu nome aqui"
git config --global user.email "seu email aqui"

* Geração do meu arquivo de ssh 
ssh-keygen -t rsa -b 4096 -C "mesmo e-mail do git"

* OBS VOU VOLOCAR SEMPRE PARA FICAR NA PASTA ATUAL OU SEJA UTILIZANDO UM UNICO PONTO ./NOME_DO_ARQUIVO

* Iniciar o ssh no meu computador 
eval "$(ssh-agent -s)"

* Adicionar uma chave ao agente para uso neste aquivo
ssh-add ./nome_do_meu_aquivo_ssh

* OBS o cat ele serve para ler arquivos por isso estou utilizando 
Ler o arquivo do ssh 
cat ./arquivo_ssh.pub

* abrir meu repositorio.
clicar no meu icone no canto direito
settings/configurações
ssh and gpg
new ssh
nome do ssh e cole a chave copiada no cat

* Git comandos...
git add . adiciona todos os arquivos modificados 
git add nome do arquivo adiciona somente esse arquivo desejado

git commit -m "mensagem" 
commita o a mensagem  para com a descrição da modificação gerada

git push origin nome da branch no seu caso (master) manda para o repositorio