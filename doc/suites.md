# Suítes

* Suítes de testes servem para definir o escopo do que está sendo testado.
* Uma aplicação é composta por diversas suítes de testes 
* Exemplos de suítes de testes seriam: Cadastro de clientes, Operações matemáticas...
* No jasmine, a suíte é uma função global javascript chamada de 'describe', que possue 2 parâmetros, que seriam sua descrição e os testes (specs).

```
describe("operação de adição", function() {
  it("deve quarantir que 1 + 1 = 2", function ()=> {
    expect(Calculadora.adicinar(1,1).toBe(2));
  });
});
```