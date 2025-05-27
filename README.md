# Aula de Testes automatizados com Pytest - Create

Nesta aula introdutória sobre testes automatizados, vamos aprender como construir testes unitários com Python usando o framework PyTest. 
O PyTest é uma ferramenta que nos ajuda a garantir a qualidade dos nossos programas por meio de testes automatizados. 
Vamos começar entendendo como funciona o PyTest com um exemplo simples, onde criamos uma função "inc" que incrementa um valor em 1. 
Em seguida, escrevemos um teste automatizado para essa função, verificando se o resultado é igual ao esperado. 
Se o teste falhar, significa que algo mudou no comportamento da função e nosso programa pode não funcionar corretamente.
No contexto do nosso projeto, vamos criar um arquivo chamado "testes.py" e importar as bibliotecas PyTest e Requests. Em seguida, definiremos algumas variáveis, como a URL do servidor que vamos testar e uma lista para armazenar as tarefas criadas. 
Vamos começar testando o endpoint de criação de tarefas (createTask), onde faremos uma requisição POST para enviar os dados da nova tarefa. Usando o PyTest, verificaremos se a resposta da requisição é um código 200, indicando que a tarefa foi criada com sucesso.
É importante ter o hábito de construir testes, pois isso garante a qualidade do código. Na próxima aula, continuaremos criando os testes para os outros endpoints da nossa API.