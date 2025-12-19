[← Anterior](04-links-e-imagens.md) | [Próximo →](06-linhas-e-divisores.md)

# Código no Markdown

## Objetivo

Aprender a exibir corretamente  
no Markdown usando código inline e blocos de código

## Código inline

Use `console.log()` para mostrar mensagens no console.

A palavra `let` é usada para criar variáveis.

## Bloco de código simples

```
<h1>Título em HTML</h1>
```
<!-- código normal -->

## Bloco de código com linguagem

Isso deixa o código **colorido** (syntax highlight).

```md
### Teste de código markdown

Os códigos ficam estilizados.
```

***

```js
let linguagem = "Javascript";
console.log(linguagem);
``` 

***

```html
<button onclick='funcion()'>Exemplo de código HTML</button>
```

***

```css
.linguagem-css{
    background-color: black;
}
```

*** 

## Quando usar cada um

- Código inline → palavras e comandos curtos
- Bloco simples → exemplo rápido
- Bloco com linguagem → código de estudo ou documentação

## Erros comuns

- Esquecer de fechar as crases
- Misturar texto dentro do bloco
- Usar bloco quando inline resolve

## Resumo

- Código inline usa crase
- Blocos usam três crases
- Linguagem melhora a leitura

---

[← Anterior](04-links-e-imagens.md) | [Próximo →](06-linhas-e-divisores.md)

<!-- Tarefa prática
- Criar código inline próprio
- Criar bloco de código JS
- Criar bloco de código HTML
- Quebre um bloco de propósito e arrume
- Errar e consertar erros ajuda a aprender -->
