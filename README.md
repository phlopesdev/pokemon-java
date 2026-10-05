Projeto Pokémon

Projeto desenvolvido em Java para a disciplina de Programação Orientada a Objetos (POO).

O sistema simula um treinador Pokémon, permitindo capturar Pokémon, visualizar o time, batalhar contra Pokémon selvagens, curar e soltar Pokémon. O programa funciona pelo terminal através de um menu de opções.

Pokémon

O projeto possui três tipos:

* Fogo
* Água
* Planta

A classe Pokemon é a classe base, sendo utilizada pelas classes PokemonFogo, PokemonAgua e PokemonPlanta.

Conceitos de POO

* Encapsulamento: atributos privados com getters e setters.
* Herança: os tipos de Pokémon herdam da classe Pokemon.
* Polimorfismo: cada tipo possui sua própria implementação de atacar().
* Abstração: Pokemon é uma classe abstrata.
* Sobrecarga: diferentes construtores e formas de usar receberDano().

Estrutura

App
|
|-- Pokemon
|   |-- PokemonFogo
|   |-- PokemonAgua
|   |-- PokemonPlanta
|
|-- Treinador

A classe Treinador utiliza um ArrayList para armazenar os Pokémon do jogador.

Menu

1. Capturar Pokémon
2. Ver Time
3. Batalha Selvagem
4. Sair
5. Curar/Descansar Time
6. Soltar Pokémon

Durante as batalhas, o dano varia de acordo com o tipo do Pokémon.

Execução

É necessário ter o Java JDK instalado. No VS Code, basta abrir o projeto e executar a classe App.

Objetivo

O objetivo foi aplicar os principais conceitos de Programação Orientada a Objetos na criação de um sistema simples baseado em Pokémon.
