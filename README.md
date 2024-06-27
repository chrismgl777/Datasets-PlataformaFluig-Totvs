

![Banner correto](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/7dd2e03b-3880-44d1-b176-99f0eaf8beed)

<H3>  Eclipse   </H3> 
 1.0 - Dentro do Eclipse, é necessário criar um projeto Fluig: <br>
 Clicando com o botão direito, dentro da aba "Project Explorer", localizamos a aba "New", dentro dela, o "Projeto Fluig"<br> 

![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/221ac414-c3e9-42d1-bec6-8709f29c9dc7) <br>

 1.1- Configuração da pasta do Projeto: <br>
 Podemos analisar 3 opções de configurações na criação do projeto: <br>
 ![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/91b77e71-70e3-4dfd-9f12-10573824fbe0)<br>
 1.1.6 Na primeira opção, escolhemos o nome que vamos dar ao projeto, normalmente,inserimos o nome do Dataset ou do projeto Real, para facilitar na localização. <br>
       Na segunda opção, podemos escolher aonde iremos armazenar o projeto criado, eu mantenho por default. <br>
       Na terceira opção, escolhemos se vamos inserir o projeto em um grupo de elementos, utilizamos essa opção para focar o projeto em um grupo que você esteja trabalhando. Por exemplo: <br>
       Estou criando um  Dataset para um projeto em especifico, eu posso inserir dentro desse grupo de elementos, fazendo com que eu possa focar em uma pasta especifica e o projeto não ficar solto. <br>
1.2 - Projeto criado: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/1df883ea-d3e2-4cf7-9011-31042af94078) <br>
1.2 - Criando o ambiente do Dataset <br>
 ![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/d6ebe12f-be17-4f0f-b393-cad4bd0e34e9) <br>
1.3 - Inserindo nome e descrição : <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/c060fae1-648a-48ea-94f8-55d83b3ddff5) <br>
Aqui, inserimos o nome do nosso Dataset, aqui colocamos o mesmo esquema do nome do projeto, porém nesse caso, precisamos inserir um nome para identificar de forma facilitada o nome do dataset. <br>
Na descrição, podemos somente inserir o mesmo nome do Dataset ou colocar uma breve apresentação: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/6d802be5-0a40-4409-b324-2890f7955c54) <br>
Nesse caso, inseri um nome que indicasse oque ele realiza e sua descrição : <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/992782c6-c839-4ed8-bad4-a21a5311035c) <br>
1.4 - Entendendo a estrutura: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/4a22f0b6-6553-4d65-9a71-3d796e76c303) <br>
1.5 - Podemos analisar, que os datasets possuem sua própria pasta. Então todos os datasets do processo que estamos criando, devem ficar agrupados no mesmo local. <br>
1.6 - Function defineStructure () {} <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/1c363bde-50d7-4915-a129-b87e92df3a53) <br>
Utilizado para  definir uma estrutura,utilizado em datasets Jornalizados.  <br>

1.7 - Function onSync(lastSyncDate) {} <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/cfdf8420-7545-4cda-94fb-448a77842e25) <br>
Utilizado para sincronizar dados, como um dataset que sincroniza com um servidor.<br>

1.7 - Function createDataset(fields, constraints, sortFields) {} <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/0bd005f3-ddae-40f7-b8f1-398efaf40dc9) <br>
Utilizado para criar os datasets. <br>

1.8 - Function onMobileSync (user) {} <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/7236034a-cfb4-4f4b-90b6-2e34f13d7bd2) <br>
Utilizado para criar parametros espeficios para aplicativos mobile. <br>
1.9 - Construindo o Dataset <br>
1.10 - Instanciamos um construtor: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/34a6da93-8b45-4505-bd8d-855fe2003e99) <br>
Aqui, eu escolho o nome da variavel, que no caso, vai ser o nome do dataset também. <br>
Chamamos o construtor DatasetBuilder.newDataset() e jogamos o valor dentro da variavel "funcionariosrv". <br>
2.0 -Criando colunas <br>

2.1 - Criando as colunas: <br>

![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/6595be2d-c50d-49e6-8c7a-1f59de1095cc)


Inserimos o nome da coluna, que no caso, funciona como se fosse uma tabela a ser demonstrada. Sendo assim, esse dataset vai possuir alguns pontos de informações, tais como; O nome do usuário, cargo, setor e se esta ativo ou não. <br>
2.2 - Adicioando as linhas da coluna: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/7c29db45-4b6c-4f73-8132-0ce21c1d4df2) <br>
Aqui, adicionamos os valores as colunas, separando por vírgula e aspas duplas, separamos os valores em ordem sequencial das colunas. <br>
O comando addRow passa o comando, instanciamos o array e inserimos os valores. <br>
2.3 - Retornando a função : <br>
 ![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/4bad99de-2692-49c7-b02f-1f2da7ed442c) <br>

2.4 - Exportando o Dataset para o fluig <br>
 Após realizarmos a construção do Dataset e passado seu valor, podemos exportar para o Fluig para realizar a consulta: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/68134ff4-9fbc-4158-9c43-bef14adfa702) <br>

Observação: <br>
Para  consultarmos, não é necessário exportar todo o projeto, somente o Dataset. <br>
Ali, você pode analisar duas opções, exportar e importar, utilizamos o exportar para enviar para o Fluig, isso acontece quando realizamos alteraçóes, correções ou qualquer interferencia no código.<br>
O  importar é realizado para retirarmos do fluig  o desenvolvimento para alterarmos, analisarmos ou qualquer outro fim manual. <br>
2.5 - Aqui inserimos  a opção de "Exportar para o servidor Fluig: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/7bc1f41a-c089-4b71-91b3-45ce67fc2b38) <br>
Aqui escolhemos qual o servidor vão exportar, caso seja um novo Dataset, marcamos a opção.
Na aba Dataset inserimos o nome dele e na descrição, podemos escolher se inserimos uma informação prévia ou repetimos o nome. No meu caso, escolhi não dar descrição pois o nome do Dataset é auto explicativo. Assim confirmamos a exportação <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/abd54c50-96a0-479c-b769-cd8d6bcadda0) <br>

2.6 - Analisando o Dataset dentro do Fluig <br>
Já com o seu fluig aberto, é necessário acessar o menu lateral e localizar o painel de controle, desta forma: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/de74b4c7-6547-4d6c-a831-7848b613dd98) <br>
Dentro do painel de controle, localizamos a tarefa chamada "Datasets", onde utilizamos para analisar sua situação e administrar seus arquivos. <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/5e74381e-d053-463d-8cae-12d50337a6ca) <br>
Dentro da tarefa, podemos localizar o Dataset e visualizar seu andamento, estrutura e muito mais. <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/97196f98-fdcd-4a59-837a-bde3b1930199) <br>
Após localizar o Dataset na aba de pesquisa, podemos identificar algumas informações,tais como: Código, Descrição,Tipo, Sincronização e entre outros. <br>
A coluna chamada "Sincronização", significa que ele é sincronizado internamente, não há possibilidade de interferirmos através do Fluig. Grave isso, pois iremos voltar neste tema daqui a pouco. <br>
Em "Mais opções" <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/18dbdf70-46fc-47aa-9b46-e12a8b5c22d6) <br>
Na opção de consulta, podemos visualizar quais os dados estão presentes no Dataset, desta forma : <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/7308e4ab-aa73-46a9-9c5b-5b79783f696f) <br>
Aqui, podemos analisar os dados inseridos no Dataset, que nesse caso, é apenas uma linha. <br>
Analisando outras opções, possuimos a Editar Dataset e Exibir código. Nelas, podemos editar o Dataset dentro do Fluig, que funciona para correções rapidas e sem risco. Já o exibir código é somente para analise. <br>
O histórico de versões é utilizado para analisarmos quantas vezes ele foi exportado e alterado. <br>
O desativar já fala por si só, não é mesmo ? <br>
<br>
<br>
Observação !! <br>
Lembra quando falamos sobre a sincronização do Dataset ? Utilizamos muito esta opção, nela podemos analisar a programação da tarefa, analisar a hora que o Dataset esta programado para rodar, por exemplo ; Miinutos em minuto, hora em hora, sendo muito utilizado em setores financeiros. <br>
Por exemplo: Criamos um Dataset que prepara pagamentos de una solicitação, ele precisa rodar em determinadas horas, realizando a tarefa automaticamente, podemos através dessa tarefa, analisar o andamento. As vezes, no Datasul ou sistema que estiver integrado, realizou uma nova atualização. Com o dataset programado para rodar em determinada hora, ele vai aceitar essa atualização e integrar. <br>
2.7 - Analisando a parametrização do Dataset: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/0e8e1351-9645-4062-a9c4-720d3fd28456) <br>
Aqui, podemos analisar algumas informações, tais como: <br>
Se possui integração com o servidor. <br>
A ultima sincronização. <br>
A proxima sincronização <br>
Sincronizar agora <br>
Esses dados são muito importantes, pois pode ocorrer uma mudança no sistema, como por exemplo; Um cliente alegar que realizou um ajuste e não apareceu no Fluig. <br>
Analisando os dados do Dataset, podemos descobrir se o Dataset atualizou ou não depois dessa alteraçao, tendo a opção de "Sincronizar agora". Fazendo com que Fluig receba a nova parametrização. <br>
<br>
<br>
<br>
Você notou que no Dataset, possui apenas uma informação, uma linha de usuário, caso tivesse milhares, como filtrariamos para um campo especifico do Fluig ? Vamos descobrir agora! <br>
<br>
Primeiro, vamos inserir mais valores no  Dataset ! <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/dd547479-3eff-4862-a29d-5b88b5729b90) <br>
Pronto, agora com mais informações,vamos exportar novamente para o Fluig ! <br>
Atenção !! Desta vez. não vamos criar um novo Dataset,vamos exportar em cima do que ja estava,então nao marcamos a opção de "Novo Dataset", também precisamos confirmar a atualização do documento após apertar "Finish" <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/00b32193-b3c5-47e1-baa0-7f564093c41b) <br>
2.8  Vamos analisar atualização no Fluig ?? Realizando a busca que foi visto anteriormente, podemos analisar os dados atuais do Dataset: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/326c1b6e-04c2-4029-8643-43e489600dce) <br>
Sendo assim, conseguimos criar um Dataset no Fluig ! Vamos para o proximo passo ? <br>
2.9 - Filtragem de Dados de um Dataset <br>
2.10 - Imagina essa determinada Situação : <br>
Em um processo do Fluig, é necessário apenas da informação do Status do Usuario e seu nome, para realizar inventários,desativações ou por motivos de controle, oque fariamos nesse caso ? Tendo em vista que o Dataset esta entregando conteúdo acima do desejado para determinado fluxo ?? Criamos um dataset de Filtragem. Vamos começar ! <br>
2.11 - Criando um Dataset de Filtragem <br>
Iniciamos criando um novo Dataset: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/c2c01211-a4a8-4c1c-a205-a8b0af4a57c2) <br>
Inserimos o nome e descrição, como falado anteriormente: <br>
Lembrando que é recomendado inserimos um nome de fácil entendimento, que ligue ao dataset. <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/1d552b15-0e04-4bdc-8403-699ff3079650) <br>
Estrutura do novo Dataset: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/52a20c2a-2821-4636-9da5-5966dbfc92e1) <br>
Hora de codar ! <br>
Já com a estrutura aberta, iniciamos o método construtor e colocamos o nome da váriavel que desejamos, nesse caso, a variavel vai se chamar filtro_funcionariosrv. <br
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/b9386d8b-9648-4a86-9ef9-141d455fa763) <br>
Agora inserimos a coluna com o Nome que queremos que apareça, nesse caso, vai ser "Usuarios" e "Sistema". <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/66d5871b-e7c5-4c70-8218-765e2a89cddb) <br>
Já com a coluna e nome informados, precisamos instanciar os dados do Dataset que desejamos, sendo assim precisamos realizar um getDataset.<br>
Como fazemos isso ? De maneira muito simples ! <br>
Dentro do proprio eclipse, existe a possibilidade de visualizarmos um Dataset, desta forma: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/d36f1019-b37c-43d2-abcc-3b4a746290d0) <br>
Aqui, consultamos o dataset e seguimos com a tarefa: <br>
Consultando o Dataset: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/5043516e-d1ea-404a-b3d4-c0c279c44212) <br>
Aqui podemos observar alguns pontos, tais como; <br>
O servidor onde o Dataset esta alocado e queremos consultar. <br>
O filtro, que é utilizado para encontramos o dataset de maneira mais fácil na busca, colocando palavras chaves. <br>
O Dataset que sera consultado. <br>
Consulta realizada, visualizando o Dataset: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/7db09fa1-a2eb-475d-a468-2c0e0979fdad) <br.
Agora, precisamos realizar o Get no código, trazendo esse Dataset para ele, lembra ??? Vamos nesta opção: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/00cf4005-5989-4502-8fe8-c4fe6146ba84) <br>
Aqui, ele vai realizar o código: <br>
Pronto, código gerado. Vamos entender  a estrutura? <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/5bdcc0ba-eb62-4491-9033-49798cff6fba) <br>
Observação: <br>
É necessário retirar a letra maiuscula, pois trabalhamos com a estrutura CaseSensitive. <br>

Primeira linha: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/0d09ad50-2608-4599-a7d4-d6219a993971) <br>
É utilizado para realizar uma limitação no retorno dos Dados. Como vamos utilizar todos, não vamos manter no código,vamos retirar ! <br>
Segunda linha: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/7c6559e6-d0fd-48da-b0cb-861ab3153f0d)<br>
Aqui, vamos retirar o "new Array(constraintFuncionariosrvdigital), pois é uma constraint e trabalha com certas limitações de dados, nesse caso, nao vamos utilizar, inserindo o "Null". <br>
Desta forma: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/bfd2700e-ccf8-40a5-8a10-d0d60dd285df) <br>
Quer entender como funciona esse Get ? Vamos lá ! <br.
O "var datasetFuncionariosrvdigital" é a variavel que recebeu os valores do Dataset que estamos tentando consultar. <br>
O "DatasetFactory.getDataset" é o get que vamos realizar a consulta dos dados que precisamos extrair. <br>
Os três campos "Null", são parametros, em ordem, são o seguinte caso:  Os campos que a gente quer, as constraint, que são restrições como solicitamos acima,poderia ser retornar tal objeto ou limitar a quantidade ou não exibir tal dado dentro do conjunto, o ultimo Null é a ordenação. <br>
Como estamos utilizando o Get para buscar informações,precisamos preparar uma estrutura para receber os dados e organizar, correto ? Vamos criar uma estrutura de repetição. <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/55eb1853-044e-4925-98d1-03f5e682b40d) <br>
Vamos entender a estrutura de repetição ? <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/96032e34-eeca-4962-85a4-02c7be5c7a0e)<br>
Abrimos a estrutura de repetição "FOR",  dentro dela, instanciamos uma váriavel de contador, que nesse caso, foi o "Cont"
O "cont < datasetfuncionariosrvdigital.rowsCount; cont++" siginifica que ele vai iniciar do primeiro valor e enquanto a variavel cont, for menor que o numero de linhas do dataset Funcionariosrvdigital, ele vai printar os valores. Sendo assim, vc declara a variavel que quer retirar essa consulta e utiliza o rowsCount para fazer essa contagem. o Cont++ é utilizado para dizer que enquanto tiver valor, ele precisa ir printando.
Já com a estrutura montada,vamos inserir a variavel do Dataset que irá filtrar os dados,inserindo uma nova linha, utilizando addRow. <br>
Lembra que da ultima vez,inserimos o addRow ja colocando os dados que queriamos que aparecesse ? Desta vez vamos utilizar ele para instanciar os dados do Dataset que criamos anteriormente, desta forma: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/f5f473b4-9691-405c-a2d2-d9d133401530) <br>
Vamos entender o código ? <br>
O datasetfuncionariosrvdigital.getValue(cont, "usuario"), Funciona da seguinte forma: primeiro instanciamos o dataset que queremos retornar um determinado campo, depois, utilizamos o getValue, para buscar esse campo em especifico, dentro do parentese, colocamos o Cont, que é a posição, como realizamos o parametro acima, ele vai fazer a contagem,vai pecorrer buscando e retornando. Depois o campo que queremos que seja retornado, que no caso é o Usuario e sistema.
Depois disso, retornamos a variavel: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/1e9f356a-963f-4d4f-957e-603bce7f7a74) <br>
Agora, vamos exportar o novo Dataset ! <br>
Colocamos como "Novo Dataset" e exportamos : <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/eb98edec-d6a5-431e-9904-121676b24d2c) <br>
Vamos analisar o novo Dataset no Fluig ? <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/8c4062b0-46a6-4a8d-9321-b8efdd89bff2) <br>
Pronto, o novo Dataset esta filtrando o antigo e buscando somente as informações que botamos como parametro: <br>
![image](https://github.com/chrismlg777/Cria-o-de-Dataset-Filtragem-de-dados./assets/94884172/6addd740-cc68-487d-997e-464f91c8aa6a) <br>

<H3>Desta forma, aprendemos a criar um Dataset e realizar a filtragem dele</H3>

























































