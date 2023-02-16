# Github-for-teams

* Criar um repositório com contribuidores

## Branches

* Pense que o código está guardado em uma caixinha dentro do repositório, podemos criar uma cópia dessa caixinha e colocar outros itens nessa nova caixinha. Pensando em código podemos "ramificar" o nosso projeto, criando linhas de commits com commits separados da linha principal, por exemplo se você vai criar uma feature nova e não quer fazer isso na branch principal que está conectada ao site que está no ar, você criar uma branch trabalhar nessa feature e quando quiser junta resse novo conteúdo na branch principal e consequentemente colocando no ar.

* Para verificar a branch atual, usar o comando git checkout. Para criar uma nova branch o comando é git checkout -b nomedabranch. Depois de adicionado os arquivos na nova branch, com o comando git push origin servicesPages será criado uma nova ramificação no GitHub.

## Merge

* Merge é o comando do git para juntar os commits de uma branch com os commits de outra branch sempre respeitando a ordem cronologica desses commits. Para juntar as branches usa-se o comando git merge servicesPages. Feito isso, fazer um git push origin main para adicionar na branch main.

## Deletando branchs

Para apagar uma branch, usar o comando git branch -D nomedabranch. Inicialmente, a branch só será apagada no repositório local (sua máquina). Para apagar do repositório remoto/github, usar o comando git push origin --delete nomedabranch

## Atualizando as branchs

