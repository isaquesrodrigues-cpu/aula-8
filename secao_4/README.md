Seção 4 — Ordem de implementação

Definam a ordem em que as telas e componentes serão construídos, justificando cada posição com base nas dependências técnicas entre as partes do sistema. Algumas telas dependem de outras para funcionar (ex.: a tela de Detalhes de um Trem só faz sentido depois que a Lista de Trens existe), e os componentes reutilizáveis precisam existir antes das telas que os usam.



# Ordem das telas

## 1 Carregamento

JavaScript é uma linguagem de programação amplamente utilizada no desenvolvimento web, sendo responsável por adicionar interatividade e dinamismo às páginas.

---

## 2 Login ou sing up

O JavaScript é utilizado para tornar as páginas mais interativas, permitindo ações como cliques, animações e atualizações de conteúdo sem a necessidade de recarregar a página.

---

## 3 RELAÇÃO ENTRE JAVASCRIPT, HTML E CSS

O JavaScript atua em conjunto com o HTML e o CSS, manipulando dinamicamente a estrutura (HTML) e o estilo (CSS) das páginas web.

---

## 4 FORMAS DE UTILIZAÇÃO NO HTML

O JavaScript pode ser inserido no HTML de três formas:

* **Externa:** por meio de arquivos `.js` utilizando a tag `<script src="...">`;
* **Interna:** dentro da tag `<script>` no `<head>` ou `<body>`;
* **Inline:** diretamente em atributos HTML, como `onclick`.

---

## 5 DIFERENÇA ENTRE SCRIPT INTERNO E EXTERNO

O script externo precisa ser referenciado no HTML, facilitando a organização e reutilização do código. Já o script interno é inserido diretamente no arquivo HTML, o que pode dificultar a manutenção.

---

## 6 DECLARAÇÃO DE VARIÁVEIS

As variáveis em JavaScript podem ser declaradas com:

* **let:** para valores que podem ser alterados;
* **const:** para valores constantes;
* **var:** forma antiga, não recomendada.

---

## 7 DIFERENÇA ENTRE VAR, LET E CONST

* **var:** possui escopo de função e pode “vazar” para fora de blocos;
* **let:** possui escopo de bloco;
* **const:** possui escopo de bloco e não permite alteração de valor.

---

## 8 ESCOPO DE VARIÁVEL

O escopo de uma variável define a região do código onde ela pode ser acessada e modificada.

---

## 9 OPERADORES DE COMPARAÇÃO

### 9.1 Igualdade

* `==`: compara apenas valores, realizando conversão de tipo;
* `===`: compara valor e tipo, sendo mais seguro.

### 9.2 Diferença

* `!=`: compara apenas valores;
* `!==`: compara valor e tipo, sem conversão.

---

## 10 FUNÇÕES EM JAVASCRIPT

As funções podem ser declaradas de diferentes formas:

* Declaração tradicional: `function nome() {}`
* Expressão de função: `const nome = function() {}`
* Arrow function: `const nome = () => {}`

---

## 11 OPERAÇÕES ARITMÉTICAS E LÓGICAS

### 11.1 Operações aritméticas

* Adição (+)
* Subtração (-)
* Multiplicação (*)
* Divisão (/)
* Resto (%)
* Exponenciação (**)

### 11.2 Operações lógicas

* Igualdade (==, ===)
* Diferença (!=, !==)
* Comparação (<, >)

---

## 12 ESTRUTURAS CONDICIONAIS

As estruturas condicionais permitem executar diferentes ações com base em condições:

```
if (condição) {
   // código
} else {
   // código
}
```

---

## 13 ESTRUTURAS DE REPETIÇÃO

Permitem repetir blocos de código:

```
for (let i = 0; i < 5; i++) {
   // código
}
```

```
while (condição) {
   // código
}
```

---

## 14 INTERAÇÃO COM O DOM

O JavaScript interage com a página por meio do DOM (Document Object Model), permitindo:

* Selecionar elementos (`getElementById`, `querySelector`);
* Alterar conteúdo e estilos;
* Responder a eventos (cliques, formulários, etc.).

Recomenda-se utilizar arquivos JavaScript externos posicionados ao final do HTML para melhor desempenho.

---

## REFERÊNCIAS

WEB.DEV. Global and local scope. Disponível em: https://web.dev/articles/global-and-local-scope?hl=pt-br. Acesso em: 30 mar. 2026.

SUJEITO PROGRAMADOR. Diferença entre == e ===. Disponível em: https://sujeitoprogramador.com/javascript-diferenca-entre-e/. Acesso em: 30 mar. 2026.

STACK OVERFLOW. Diferença entre != e !==. Disponível em: https://pt.stackoverflow.com/questions/3186/qual-a-diferen%C3%A7a-entre-operadores-e-em-javascript. Acesso em: 30 mar. 2026.

MDN WEB DOCS. Funções em JavaScript. Disponível em: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Functions. Acesso em: 30 mar. 2026.