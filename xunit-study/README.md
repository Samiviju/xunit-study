# xunit-study
Estudos d e xUnit - testes de unidade aplicando o TDD

## Anotações
testes de unidade
padrão AAA

Arrange -> preparação do cenário do teste 
Act -> é a ação do teste
Assert -> resultado esperado

// anotações
[Theory]
conseguimos fazer varios testes com varios objetos.

trabalha junto com a anotação
[InlineData]
Voce ira colocar os objetos que irão ter no teste para serem testados

----
ignorando testes
[Fact(Skip = "")
----
Colocando nomes nos testes
[Fact(DisplayName = "")]
----
Agrupando testes
[Trait]
----------------------

TDD -> 
. Implementar um Teste que falhe 
. Não escrever mais nada além do necessarios para um teste falhar
. Não escrever nada alem do necessario para o teste passar
