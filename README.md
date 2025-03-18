# PROJETO - challenge - Amigo Secreto!

O projeto parte de um requisito obrigatório para conclusão dos cursos de formação: iniciante em programação do curso Alura - Oracle Next Education. O desafio foi criar uma aplicação web onde os usuários possam realizar um sorteio a partir de uma lista de "amigos".

O desafio exigia:

Capturar o valor do campo de entrada: Utilize document.getElementById ou document.querySelector para obter o texto pelo usuário;
Confirmar a entrada: Implemente uma validação para garantir que o campo não esteja vazio;
Se o campo estiver vazio, exibir um alerta com a mensagem de erro: "Por favor, insira um nome."
Atualizar o array: Se o valor for válido, adicione-o ao array que armazena os nomes dos amigos usando o método .push().
Limpar o campo de entrada: Após adicionar o nome, redefina o campo de texto para uma string vazia.
Escrever uma função que selecione aleatoriamente um dos nomes armazenados no array amigos.
Use Math.random() e Math.floor() para obter um índice aleatório.
Mostrar o resultado: Atualizar o conteúdo do elemento de resultado usando document.getElementById() e innerHTML para exibir o amigo sorteado.

Funcionalidade:

Adicionar nomes: Os usuários escreverão o nome de um amigo em um campo de texto e o adicionarão a uma lista visível ao clicar em adicionar.
Validar a entrada: Se o campo de texto estiver vazio e o usuário clicar em adicionar,o programa mostrará um alerta solicitando digitar o nome de um amigo.
Impedir a duplicidade de nomes: Se o usuário digitar o nome de um amigo duas vezes, o programa exibirá um alerta avisando que este nome já se encontra na lista de sorteio.
Número mínimo de participantes: A realização do sorteio exige a participação de pelo menos três pessoas, caso contrário um alerta ira destacar a importância de digitar mais nomes.
Visualização dos nomes: Os nomes digitados no campo de texto e adicionados serão descritos logo abaixo em uma lista.
Sorteio aleatório: Ao clicar em sortear amigo, um nome da lista será selecionado aleatóriamente e exibido na tela.
Reiniciar o sorteio: Ao selecionar essa opção todos os campos serão limpos possibilitando um novo sorteio.

Tecnologias usadas:

HTML, CSS, JAVASCRIPT.

Uso da Aplicação:

De forma prática, clique em OK no alerta de reiniciar o sorteio e depois digite cada nome por vez no campo de entrada onde está escrito: "Digite o nome do seu amigo" e clique em "adicionar", a partir de três participantes na lista, já é possivel fazer o sorteio clicando em "sortear amigo". O resultado do amigo secreto aparecerá na tela. Caso clique em "adicionar" amigo sem digitar um nome, receberá um alerta solicitando por favor digite o nome do amigo; se tentar sortear com menos de três nomes na lista, receberá um alerta para adicionar mais nomes. Ao terminar o sorteio é só clicar em "reiniciar o sorteio" e dar continuidade a diversão!
