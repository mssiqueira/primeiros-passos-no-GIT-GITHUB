# Introdução ao GIT/GITHUB

## índice
* O que é Git?
* O que é CLI?
* O que é GitHub?
* Criando sua conta no GitHub
* O que é Markdown?
* Instalação do Git
* Configurando o Git
* Criando um repositório
---

# O que é Git?
O Git é um sistema de versionamento de código. Ok! Mas caso você não seja um programador experiente deve estar se perguntando o que é versionamento de código?! Versionamento é o processo de atribuir um nome único ou uma numeração única pra indicar o estado de desenvolvimento de um programa ( início e todas as atualizações subsequentes.) classificação adotada pelos programadores com o intuito de controlar e acompanhar o histórico de alterações de um software, sem perder o arquivo original.

# O que é CLI?
O GIT usa a interface CLI (command-line interface)  Ele é um programa que permite que os usuários digitem comandos de texto dando instruções a um computador para fazer funções específicas.
Vista pela primeira vez esta interface pode assustar um pouco, porém é necessário que você se familiarize, pois através dela você consegue entender conceitos chaves por baixo do GIT  e firmar e estabelecer o conhecimento na sua cabeça.

# O que é GitHub?
GitHub é um repositório local, é uma das maiores plataformas online de trabalho colaborativo do mundo. Aqui você pode compartilhar seus projetos e pessoas de qualquer lugar do mundo podem trabalhar paralelamente neles. 

# Criando sua conta no GitHub 
Tudo que precisamos para começar a usar o GitHub é uma conta na ferramenta e isso pode ser feito em seu [site o ficial](https://github.com/).
Se tudo deu certo, você receberá um E-mail para confirmar sua conta. Não esqueça de realizar este processo de ativação, ele é importante para iniciar sua conta.

Dica: _use um e-mail e nome de usuário profissional, pois muitas empresas e recrutadores olham os perfis do github, então é interessante voce deixar o seu perfil atrativo_

# O que é Markdown?
Markdown é um sistema de formatação aberto que torna a escrita e a leitura mais simples. Com uma codificação mínima, além de fácil, ele é visualmente mais "limpo" e pode ser convertido facilmente para HTML. Você encontra vários editores de Markdown disponíveis para download, escolha um de sua preferência e instale em sua máquina, pois iremos utiliza-lo daqui para a frente

# Instalação do Git
Agora vamos instalar o Git, vá até a [pagina oficial]( https://git-scm.com/) do GIT e faça o download do instalador, ele possui versões para Windows e Mac.

# Configurando o GIT
Para começar vamos criar uma pasta, dentro da pasta criada você ira clicar com o botão direito do mouse e clicar em ‘’Git Bash Here’’
Após isso será aberto o terminal do Git Bash e com o terminal aberto vamos configurar seu e-mail e seu username, digite os seguintes comandos

__git config --global user.name "seu nome"__

__git config --global user.email "seu e-mail"__

dica: _use o mesmo e-mail e username usados no GitHub_

# Criando repositorio 
Dentro da pasta que criamos, vamos criar um novo arquivo chamado de README.md
_Os arquivos ".md" são no formato MarkDown_

Abra o arquivo README.md e escreva ‘’Ola mundo’’ 
_(isso é apenas um exemplo, futuramente você ira escrever seus códigos)_

Depois de ter escrito, salve e volte para o Git bash, la vamos digitar dois comandos:

 __git add *__  com este comando você esta basicamente dizendo ‘’quero que todos os arquivos dentro dessa pasta seja gerenciado pelo GIT’’

__git commit –m__  com este comando você esta basicamente dizendo ‘’Git, salve todas as modificações e prepare-se para enviar tudo ao GitHub’’

Feito isso vá até o site do GitHub e clique em ‘’novo repositório’’ preencha com o nome desejado e clique em ‘’criar repositório’’

Após isto você irá copiar a URL da página do seu repositório e ira voltar para o Git bash e vai digitar o seguinte comando 

__git remote add origin URL DO SEU REPOSITORIO__
com este comando você está basicamente dizendo ‘’quero que a url do meu repositório se chame origin’’

em seguida você ira digitar o seguinte comando

__git push origin__ e com este comando você acaba de enviar seus arquivos para o GitHub 

Pronto, estes foram seus primeiros passos com Git e GitHub! 



                        Este repositório faz parte do primeiro exercício do Bootcamp Santander 2022 em parceria com a DIO
