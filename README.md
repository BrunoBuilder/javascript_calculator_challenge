<p align="center">
  <a href="https://devsuperior.com.br">
    <img src="https://github.com/BrunoBuilder/customer_crud_challenge/assets/84381502/6b8cb2ad-5e4b-450b-a788-cd6c2d43a3c3" alt="DevSuperior Logo">
  </a>
</p>

<h1 align="center">Formação Desenvolvedor Moderno</h1>

<h2 align="center">Módulo: JavaScript</h2>

<h3 align="center">Capítulo: Objetos e Módulos</h3>

### DESAFIO: Calculadora JS

**Forma de entrega:** Link para o projeto no Github

Você deve implementar, conforme mostrado no vídeo explicativo, os controles de tela do problema "calculadora" contido na nossa lista de exercícios: [Lista de Exercícios](https://github.com/devsuperior/fixjs)

Você deve analisar o código HTML para identificar os elementos da tela.

Os comportamentos desejados são (todos devem estar funcionando):

1. O formulário deve iniciar limpo, e a caixa de resultado com o valor 0 (zero).

2. Ao clicar no botão "+", deve aparecer na caixa de resultado a soma dos valores digitados nas caixas de texto. Se houver um ou mais valores nas caixas de texto que não são números válidos, a caixa de texto deve ser marcada de vermelho (classe "input-error"), e a caixa de resultado deve permanecer inalterada.

3. Ao clicar no botão "x", deve aparecer na caixa de resultado a multiplicação dos valores digitados nas caixas de texto. Se houver um ou mais valores nas caixas de texto que não são números válidos, a caixa de texto deve ser marcada de vermelho (classe "input-error"), e a caixa de resultado deve permanecer inalterada.

4. Ao clicar no botão "C", todo o formulário deve ser limpo, e a caixa de resultado deve ter o valor 0 (zero).

**ATENÇÃO:** Para testar se o valor que está na caixa de texto é um número válido, você pode usar a seguinte função:

```javascript
function isNumber(n) {
  return !isNaN(parseFloat(n)) && isFinite(n);
}
```
Basta chamar a função passando o conteúdo da caixa de texto como argumento da função, que a função retornará true se o conteúdo for um número válido. Por exemplo:

```javascript
const n1 = inputNumber1.value;
if (isNumber(n1)) {
  // Seu código aqui
}
```
Item opcional (não precisa fazer se não quiser):
Procure na Internet uma forma de evitar que o usuário digite na caixa de texto um valor que não seja um número válido.
