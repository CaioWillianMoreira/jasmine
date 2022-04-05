# Testes (Specs)

* Specs são os tsetse que validam uma suíte de testes.
* Assim como as suítes, ela é uma função global javascript chamada 'It', que contém dois parâmetros, uma descrição e uma função, respectivamente.
* Dentro do segundo parâmetro, é onde adicionamos as verificações (expectations)

```
it("deve garantir que 1 + 9 = 10", function() {
  expect(Calculadora.adicionar(1,9)).toBe(10);
});
```