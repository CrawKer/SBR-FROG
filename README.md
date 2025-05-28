<!DOCTYPE html>

<html lang="pt-BR">

<head>

<meta charset="UTF-8" />

<meta name="viewport" content="width=device-width, initial-scale=1" />

<title>Loja dos CATS 🐱</title>

<style>

/* Reset básico */

* {

box-sizing: border-box;

}

body {

font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;

background: #fff8f0;

margin: 0;

color: #333;

line-height: 1.6;

}

header {

background: #ffb700;

color: #3e1f00;

padding: 1.5rem 2rem;

text-align: center;

box-shadow: 0 3px 6px rgba(0,0,0,0.15);

position: sticky;

top: 0;

z-index: 10;

}

header h1 {

margin: 0 0 .3rem;

font-size: 2.4rem;

}

header p {

margin: 0;

font-size: 1.1rem;

font-weight: 600;

}
nav {

background: #ffc107;

display: flex;

justify-content: center;

flex-wrap: wrap;

gap: 1rem;

padding: 0.8rem 1rem;

box-shadow: 0 2px 5px rgba(0,0,0,0.1);

}

nav a {

text-decoration: none;

color: #3e1f00;

font-weight: 600;

padding: 0.5rem 1rem;

border-radius: 25px;

transition: background-color 0.3s ease;

}

nav a:hover {

background-color: #ffd54f;

color: #000;

}

main {

max-width: 1100px;

margin: 2rem auto 4rem;

padding: 0 1rem;

}

section {

margin-bottom: 3rem;

}

section h2 {

color: #d35400;

border-bottom: 3px solid #d35400;

padding-bottom: 0.3rem;

margin-bottom: 1rem;

font-size: 1.8rem;

}

section h3 {

margin-top: 1rem;

color: #9c6400;

font-weight: 700;

font-size: 1.3rem;

}

ul {

list-style: none;

padding-left: 0;

margin-top: 0.5rem;

max-width: 700px;

}

ul li {

background: #fff3d2;

border-radius: 6px;

margin: 0.3rem 0;

padding: 0.5rem 1rem;

box-shadow: 0 2px 5px rgb(0 0 0 / 0.1);

font-size: 1.05rem;

display: flex;

justify-content: space-between;

align-items: center;

}

ul li span.price {

background: #ffb700;

color: #3e1f00;

font-weight: 700;

padding: 0.2rem 0.7rem;

border-radius: 15px;

font-size: 0.9rem;

white-space: nowrap;

margin-left: 1rem;

}

.disponibilidade {

font-style: italic;

color: #a05200;

font-size: 0.95rem;

margin-left: 10px;

}

/* Responsivo */

@media (max-width: 720px) {

nav {

justify-content: center;

}

ul li {

flex-direction: column;

align-items: flex-start;

}

ul li span.price {

margin-left: 0;

margin-top: 0.3rem;

}

}

</style>

</head>

<body>

<header>

<h1>Loja dos CATS 🐱 🛒</h1>

<p>Sejam bem-vindos! Aqui vocês podem comprar 🛍️ muitas coisas!</p>

</header>
