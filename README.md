# BARBEARIA-ALURA

<img src="img/logo-branco.png" width="150px" style="position: relative; right: 10px" />

Construção de site (prototipo) com a finalidade de trabalhar conceitos de   <img align="center" alt="Bruno-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg"> e
<img align="center" alt="Bruno-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg"> do Projeto ONE + Alura.
<hr/>

## Primeiros passos da criação do projeto:


1. Primeiramente, foi feito o download de todos os componentes necessários para contrução da página.
2. Com o editor de código aberto, foi criado 03(três) arquivos `html` sendo as seguintes:<br/> 
  ->`index.html`<br/> 
  ->`produtos.html`<br/> 
  ->`contato.html`<br/> 
3. Depois foi criado o arquivo `css` onde foi feito toda parte de estilização da página.<br/> 
  ->`style.css`<br/> 
4. Além disso, foi feito também toda parte de responsividade usando `media query`.

## Processo de contrução:
<hr/>

Para a parte de html foi utilizado toda estrutura base com uso de tags `<>`, classes `class` e identificadores `id`.
<br/>

```html
 <label for="name-lastName">Nome e Sobrenome</label>
        <input
          type="text"
          id="name-lastName"
          placeholder="Digite seu nome completo"
          class="input-pattern" required
        />
```

<br/>

Foi passado todos os conceitos de usuabilidade de toda estrutura e boas práticas iniciais para construção.

<hr/>

Já com o uso do `css` foi empregado conceitos de estilização para modelagem visual da página.

![image](https://user-images.githubusercontent.com/104768950/182266006-44d84abc-91b0-49aa-9846-945982c8affd.png)

<br/>

```css
/* Variables Universal */
*,
p,
li {
  font-family: "Montserrat", sans-serif;
}

/* header  */
.header-main {
  background: #bbbbbb;
}

.container {
  width: 940px;
  position: relative;
  margin: 0 auto;
}

nav {
  position: absolute;
  top: 110px;
  right: 0;
}

nav ul li {
  display: inline;
  list-style: none;
  margin: 0 0 0 15px;
  cursor: pointer;
}
```
<br/>

Foi feito também a parte de responsividade das páginas utilizando media query.

```css
@media (min-width: 425px) and (max-width: 767px) {
 
 }
@media (min-width: 768px) and (max-width: 991px) { 
 
}

```
<br/>

![image](https://user-images.githubusercontent.com/104768950/182268228-321b3a62-aa2b-4d63-929c-89ee26c46aa1.png)






