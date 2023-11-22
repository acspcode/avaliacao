<h1>Teste para candidatos à vaga de desenvolvedor Fullstack</h1>
<h2>Instruções</h2>
<hr></hr>
<p>Você deverá criar um repositório público para o projeto no Github. Use o README principal do seu repositório para nos contar como você desenvolveu o seu teste e nele você deverá contar as suas decisões tomadas, o porque de cada tecnologia escolhida por você e como organizou e separou o seu código. As instruções de como rodar seu projeto também devem estar presentes no README.</p>
<p>Não existe uma resposta correta para o teste. Você pode alcançar o objetivo de várias maneiras possíveis e será avaliado a maneira, métodos e tecnologias que você escolheu para finalizar o desafio.</p>
<p>Não há um tempo definido para a conclusão do teste. Ao concluir o teste você deve enviar o link do repositório nos seguintes emails: mspereira@acsp.com.br, aschartz@acsp.comb.r, para que possamos dar uma conferida.</p>

<h2>Desafio</h2>
<p>Você será responsável por integrar a próxima landing page de um de nossos clientes e criar uma pequena API para o armazenamento dos leads convertidos nessa landing page. Para isso você deve seguir os seguintes pontos:</p>
<ul>
    <li>1. Criar um banco de dados para que armazene leads, guardando informações como o horário do lead gerado, o produto que está sendo ofertado, possíveis origens e o que mais que você ache que pode ser relevante para guardar sobre um lead.</li>
    <li>2. Criar uma API que permita realizar pelo menos 4 ações básicas, GET, POST, PUT, DELETE, manipulando os dados do banco criado previamente, realizando as seguintes ações:<br>
        2.1. Fornecer listagem dos leads via método GET;<br>
        2.2. Cadastrar novos leads via método POST;<br>
        2.3. Visualizar um lead via método GET;<br>
        2.4. Atualizar um lead via método PUT;<br>
        2.5. Deletar um lead via método DELETE.</li>
    <li>3. Na landing possui um formulário na página. Você deve implementar a integração desse formulário com a API criada no passo 2 e os dados devem ser persistidos no banco do passo 1.</li>
</ul>

<h2>O que nós esperamos do seu teste</h2>
<hr></hr>
<ul>
    <li>Utilizar PHP 7.4 disponivel na maquina fornecida</li>
    <li>Banco de dados Mysql</li>    
    <li>Utilize a tecnologia ou framework da melhor forma possível (metodologia/estrutura).</li>
    <li>Utilização de dependency managers (composer, npm, yarn) para instalação de bibliotecas utilizadas no projeto.</li>
    <li>O formulário deve possuir como campos obrigatórios Nome(name), E-mail(email), Telefone(phone) e caso queira adicionar novos campos, esses campos podem ser considerados como opcional.</li>
    <li>Desenvolver método para submissão do formulário, este deverá ser uma requisção do tipo POST, além dos dados visíveis no formulário é necessário que seja enviado um parâmetro code que não será visivel para o usuário da página mas que será enviado na requisição para identificação do lead.</li>

</ul>

<h2>Informações adicionais</h2>
<p>Usuario e senha linux: usuario: fcamara, senha: fcamara</p>
<p>Dados banco de dados. host:localhost, user:root, senha: 12345678</p>
<p>Aplicativo para acesso banco de dados: localhost/phpmyadmin</p>

