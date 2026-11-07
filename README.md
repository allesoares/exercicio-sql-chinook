# Exercício SQL — Chinook

Objetivo do exercício: Neste exercício, você irá praticar consultas SQL utilizando o banco de dados de exemplo disponível no DBeaver, baseado em um sistema de músicas.

O objetivo é reforçar o uso de comandos SQL básicos e intermediários, explorando tabelas relacionadas, filtros, ordenações e junções.

## Arquivos

- `consultas.sql`: perguntas e respectivas respostas em SQL.
- `banco/Chinook.sqlite`: banco de exemplo pronto para abrir.
- `banco/LICENSE-Chinook.md`: licença do banco original.



## O que as consultas respondem

1. Todos os artistas em ordem alfabética.
2. Músicas com duração superior a cinco minutos.
3. Músicas do gênero Rock.
4. Álbuns e seus respectivos artistas.
5. Músicas do álbum “Let There Be Rock”.
6. Clientes que moram no Brasil.
7. Total de músicas por gênero, em ordem decrescente.
8. Músicas com “Love” em qualquer parte do nome.

## Banco utilizado

O banco incluído é o **Chinook v1.4.5**, obtido da
[distribuição oficial](https://github.com/lerocha/chinook-database/releases/tag/v1.4.5).


## Validação

As oito consultas foram executadas no banco incluído, usando SQLite em um
contêiner temporário Docker com a imagem `python:3.14-alpine`.


