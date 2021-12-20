# PostgreSQLPython

Prática do tutorial https://www.postgresqltutorial.com/postgresql-python/

Esta seção PostgreSQL Python mostra como trabalhar com o banco de dados PostgreSQL usando a linguagem de programação Python .

Python possui vários drivers de banco de dados para PostgreSQL. Atualmente, o psycopg é o adaptador de banco de dados PostgreSQL mais popular para a linguagem Python. O psycopg implementa totalmente a especificação Python DB-API 2.0.

A versão atual do psycopg é 2 ou psycopg2. O adaptador de banco de dados psycopg2 implementado em C como um wrapper libpq, resultando em rapidez e segurança. O psycopg2 fornece muitos recursos úteis, como cursores do lado do cliente e do lado do servidor , notificação e comunicação assíncronas, suporte ao comando COPY, etc.

Além disso, o driver psycopg2 suporta muitos tipos Python prontos para uso. O psycopg2 combina objetos Python com os tipos de dados PostgreSQL , por exemplo, lista para o  array , tuplas para registros e dicionário para hstore . Se você deseja personalizar e estender a adaptação de tipo, pode usar um sistema de adaptação de objeto flexível.
