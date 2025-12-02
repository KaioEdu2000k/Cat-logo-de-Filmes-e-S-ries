TRABALHO PRÁTICO - POO
## Alunos integrantes da equipe
* Cristhian Dias Braga
* João Pedro Carvalho de Oliveira
* Kaio Eduardo Gomes Oliveira

# Catálogo de Filmes e Séries 
 
Sistema simples para organização de mídias pessoais, permitindo cadastrar filmes e séries, 
criar listas personalizadas, fazer avaliações e filtrar conteúdos. 
 
## Funcionalidades 
 
- Cadastro de filmes e séries 
- Cadastro de usuários 
- Sistema de avaliações (nota + comentário) 
- Listas personalizadas: 
- Quero assistir 
- Assistidos 
- Favoritos 
- Filtros: 
- Por gênero 
- Por ano 
- Por nota média 
 
## Arquitetura 
 
- Programação Orientada a Objetos 
- Herança: `Filme` e `Serie` herdam de `Midia` 
- Composição: `Avaliacao` dentro de `Midia` 
- Extensível para JSON ou APIs públicas 
 
## Como compilar e executar 
 
1. Abra o projeto no **Visual Studio** ou **VS Code** com extensão C#. 
2. Compile o projeto: 
 
dotnet build 

3. Execute: 
 
dotnet run 
 
## Estrutura das Classes 
- Midia (abstrata) 
- Filme 
- Serie 
- Usuario 
- Avaliacao 
- ListaPersonalizada 
 
## Extensões Futuras 
- Exportação/importação para JSON 
- Recomendações inteligentes 
- Integração com APIs (ex.: TMDB) 
 
