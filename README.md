<h1>Desafio 15 - Contador de Lista</h1>

<p>
Bem-vindo ao projeto de Manipulação de Listas em Python! Este projeto visa explorar operações básicas em listas, uma das estruturas de dados fundamentais em Python. Utilizando um exemplo prático, vamos analisar como verificar a presença de um elemento específico em uma lista e imprimir o resultado. Este projeto é uma introdução valiosa para iniciantes que desejam compreender a manipulação de listas em Python.
</p>

<h2>Código Interativo:</h2>
Terminal:

    # Lista - Frutas
    frutas = ['maça', 'morango', 'laranja', 'maça', 'figo', 'maça']

    # Verificar quantas vezes "maça" está presente em "frutas".
    verificando = frutas.count('maça')

    # Imprimir resultado.
    print(f'Maça está presente {verificando} vezes na lista "frutas".')


<h2>Explicação do Código:</h2>

<ol>

<h3><li>Definição da Lista:</li></h3>
<ul>
<li>frutas = ['maça', 'morango', 'laranja', 'maça', 'figo', 'maça']: Cria uma lista chamada "frutas" com seis elementos.</li>
</ul>

<h3><li>Contagem de "Maça":</li></h3>
<ul>
<li>verificando = frutas.count('maça'): Utiliza o método count() para contar quantas vezes a string 'maça' aparece na lista "frutas" e armazena o resultado na variável verificando.</li>
</ul>


<h3><li>Impressão do Resultado:</li></h3>
<ul>
<li>print(f'Maça está presente {verificando} vezes na lista "frutas".'): Imprime o resultado indicando quantas vezes a palavra 'maça' aparece na lista "frutas".</li>
</ul>

</ol>

<h2>Saída Esperada:</h2>

<p>Ao executar o código, a saída será:</p>
Terminal:

    Maça está presente 3 vezes na lista "frutas".