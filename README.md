# Pylab Seletive
Esse projeto foi desenvolvido durante o evento Pylab realizado pelo Caio Sampaio, idealizador do Pythonando.
<br>
O Seletive é um site responsável por gerenciar empresas e vagas de emprego que você possui interesse. Você adiciona as empresas e as vagas de trabalho correspondentes a elas.
<br>
<br>
O projeto utiliza Python, Django e Bootstrap. É ensinado a estrutura Cliente Servidor e os fluxos de dados no Django que envolvem Requisição e Resposta. O Template que apresenta o Website realiza a requisação Http para o roteamento de URLs, URLs faz a requisição para Views e Middlewares e Views faz Requisição para os Modelos que tem conexão com o banco de dados. As respostas de Modelos são enviadas para Views que possuem conexão com HTML, CSS, JS e formulários. Em seguida, Views manda a resposta HTTP para o Template Website.
<br>
<br>
Eu complementei o projeto realizando alguns desafios propostos como possibilitar a troca de status de progresso dentro de uma vaga e a troca de tecnologias dominadas e a estudar dentro de uma vaga. Também implementei a lista de vagas com as informações e a possibilidade de excluir as vagas.
<br>
<br>
O protótipo no Figma do projeto original pode ser encontrado no link: https://www.figma.com/file/rPWCJABt3WnDdSaRQvzMCM/PYLAB-2022?node-id=0%3A1

*Tela de Cadastro de Nova Empresa*
![Pylab](https://user-images.githubusercontent.com/66453382/204203385-559d52b8-dc86-48ae-bdd1-b59931ad6eab.png)
O cadastro de Nova Empresa possui tratamento para que todos campos sejam preechidos e o tamanho do logo seja adequado.

<br>

*Tela da Lista de Empresas Cadastradas*
![Pylab (1)](https://user-images.githubusercontent.com/66453382/204205445-01039d6a-043a-4d11-a803-31d27a855637.png)
A lista de empresas contém algumas informações sobre cada empresa cadastrada e exibe a quantidade de vagas cadastradas em cada empresa. Além disso, também é possível excluir uma empresa e localizar uma empresa específica por intermédio do filtro de nome e tecnologias. Nessa tela também é possivel ser redirecionado para cadastrar nova empresa.

<br>

*Tela exibida ao Selecionar uma Empresa*
![Pylab (2)](https://user-images.githubusercontent.com/66453382/204372598-651febb3-b2b0-451e-95ce-8500d1140772.png)
Aqui são exibidas algumas informações da empresa selecionada. É possível visualizar as vagas que estão cadastradas na empresa, acessar cada vaga e criar nova vaga.

<br>

*Tela de Cadastro de Nova Vaga*
![Pylab (3)](https://user-images.githubusercontent.com/66453382/204374299-f0b3b6ef-d265-433f-9d33-19b92beb22ef.png)
Essa tela é um modal utilizando Bootstrap que permite a criação de uma nova vaga para a empresa selecionada.

<br>

*Tela da Lista de Vagas*
![Pylab (5)](https://user-images.githubusercontent.com/66453382/204377068-45a10692-52d2-4491-abef-01508a42a471.png)
A lista de vagas contém algumas informações sobre cada vaga cadastrada, sendo possivel acessar a vaga e excluir determinada vaga.

<br>

*Tela exibida ao Selecionar uma Vaga*
![Pylab (6)](https://user-images.githubusercontent.com/66453382/204378612-e7fe37ff-038b-4ef2-b4e9-d111f7868bf8.png)
É exibido o progresso da vaga, sendo possivel alterar o status do progresso. Também é possível criar tarefas e visualizá-las.
![Pylab (7)](https://user-images.githubusercontent.com/66453382/204383595-fea4a2c0-9c22-4e5e-80dd-bf9fe5a8753a.png)
É possível enviar E-mail e verificar o histórico de e-mails enviados. É exibido as tecnologias que domina e as tecnologias que é necessário estudar, sendo possivel mover essas tecnologias entre essas áreas.

<br>

*Criando e Exibindo Tarefas*
![Pylab (8)](https://user-images.githubusercontent.com/66453382/204384628-761f5400-65a8-45b6-b8e9-e9e57781e60f.png)


