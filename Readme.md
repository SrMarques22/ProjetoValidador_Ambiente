Olá, esse projeto ensina você a usar o GIT

comandos:
git init  - inicia o git

git add nome_arquivo.extensão - Vai mandar os arquivos para a area de stading (area de envio antes do commit)

porexemplo, esse arquivo Readme.md vamos enviar para esse local, ele serve para deixar o arquivo modificado salvo
no github mas sem aplicar o commit no principal

git status - ele mostra os arquivos que foram enviadas para o standing, e vai mostar os arquivos que mudaram
que serão committados caso vocÊ queira

git commit -m "mensagem a ser passada para idenficar a modificação do commit" - esse comando usa as aspas duplas
para colocar a mensagem que quer mandar com  commit, desta forma o arquivo que estava no standig foi commitado

git branch -M main - renomeia o nome da minha Branch para main, 
por padrão ela inicia como MASTER, esse nome pode ser verificado
ao iniciar o git com o comando git init

crie um repositorio no github
pegue o link que criar assim e o repositorio for criado
ex: https://github.com/SrMarques22/ProjetoValidador_Ambiente.git

git remote add origin link_do_diretorio_conforme_exemplo_acima.git - Com esse comando você irá
transferir o conteúdo do seu diretório windows para o github 
OBS: Nunca esqueça de abrir o git bash no diretório criado

git push -u origin main - comando para enviar o arquivo de fato para o github, caso contrario ele não aparecerá no
repositório do gitub

por fim, aparecerá uma janela para autorizar o upload.


###gerenciamento###

se eu quiser enviar todos os arquivos que tem disponível para a
área de standing, posso usar o comando:

git add .

caso eu queira mandar arquivos com nomes específicos, posso utilizar:

git add nome_arquivo nome_arquivo2 nome_arquivo3....


Caso tenha algum "lixo" que aparece como disponível apra enviar ao Standing
(para ver os arquivos usar o git status), basta dar o comando abaixo, para deletar o arquivo
dos disponíveis para envio:

git rm nome_arquivo

A partir dos segundo envio, não precisa mais utilizar o comando -u para dar o push, ficará:

git push origin main


