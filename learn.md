- Modificador Defer

Sem o defer, o navegador pausa o carregamento do HTML.

DOM (Document Object Model) -> Ele precisa de componentes para poder funcionar.

nome. -> cria uma div com uma classe nome
nome# -> cria uma div com um id nome

-----

getElementById() -> sempre vai retornar um id único ou null se não encontrar

    - console.log(document.getElementById("meuTitulo"));

innerText -> Irá pegar o texto que está entre as tags 

    - console.log(document.getElementById("meuTitulo").innerText);

-------------------

querySelector() -> seletor. vai pegar o primeiro elemento que bate com um seletor CSS(id, tag, class..) e retorna apenas o 1º elemento que encontrar

    - console.log(document.querySelector("p").innerText);
    - console.log(document.querySelector(".destaque").innerText);

getElementsByClassName -> Seleciona todos os elementos que possui aquela classe

    - const itens = document.getElementsByClassName("produto);
    -