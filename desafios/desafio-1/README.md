# Desafio

# Módulo 1 : Fundamentos

## Objetivos

Exercitar os seguintes conceitos trabalhados no Módulo:

  ✓ Declarar elementos HTML como títulos, input, div, span, ul, li etc.  
  ✓ Estilizar o app com CSS.  
  ✓ Mapear elementos do DOM para serem manipulados com JavaScript.  
  ✓ Formatar valores com JavaScript.  
  ✓ Realizar diversos cálculos com array methods como map, filter e reduce.  
  ✓ Realizar requisições HTTP com o comando fetch.  

## Enunciado

Criar uma aplicação para filtrar usuários e mostrar estatísticas a partir do filtro definido.

## Atividades

Os alunos deverão desempenhar as seguintes atividades:
1. "Subir" o backend de usuários. Basta executar "yarn" ou "npm install" para instalar as dependências e executar "yarn start" ou "npm start" para deixar o backend on-line. Este backend está configurado para "escutar" a porta 3001.
2. Carregar os dados dos usuários em um array.
3. Permitir a filtragem de usuários através de um input com interação do usuário.
4. O usuário poderá filtrar dados quando digitar pelo menos um caractere no input.
5. O usuário poderá filtrar os dados tanto digitando "Enter" quanto clicando no botão
correspondente, conforme imagens mais abaixo.
6. Montar dois painéis.
7. No painel da esquerda, listar os usuários filtrados.
8. No painel da direita, calcular e mostrar algumas estatísticas sobre esses usuários,
conforme imagens abaixo.

**Tela inicial da aplicação:**

<img src="../images/desafio1-1.png" alt="Tela inicial">

**Tela após filtro "santos":**

<img src="../images/desafio1-2.png" alt="Tela após filtro">

## Dicas

1. Após executar a requisição à API, obtenha somente os dados necessários ao app.
Esses são: **name** (first + " " + last), **picture** (imagem), **dob.age** (idade) e **gender**
(sexo).
2. Monitore o input com o evento "keyup".
3. Filtre os dados a partir de qualquer posição no nome, ou seja, o nome "Brenda" (caso
exista na API) deve ser retornado se o filtro for "enda".
4. Para filtrar, considere todo o texto em minúsculas. Assim, o filtro "E" trará tanto
"Elena" quanto "Helena", caso existam na API. Utilize a função Array.includes.
5. **Não faça a “limpeza” do texto, ou seja, devem ser considerados os acentos e
caracteres especiais. Portanto, o texto "Andre" não pode filtrar o nome
“André”.**
6. Dê um console.log() nos dados do evento de digitação e você descobrirá como
"cercar" a tecla "Enter".
7. Foque mais no código JavaScript e menos na interface. O mais importante é que o
filtro e os cálculos estejam corretos.
8. Quebre o seu código em funções bem definidas.
9. Será necessária uma boa dose de manipulação manual do DOM. Isso pode ser feito
tanto com innerHTML + string (recomendo a utilização de template literals) ou com
os comandos document.createElement, appendChild, etc.
10. Se quiser fazer uma interface semelhante a das imagens, utilize o [Materialize](https://materializecss.com).
11. Não deixe de assistir o vídeo desse desafio, onde demonstro a aplicação em
funcionamento e dou mais algumas dicas.

# Como executar o projeto
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/rafa-guimaraes/bootcamp-full-stack.git

# entrar na pasta backend do projeto
cd desafios/desafio-1/backend

# instalar dependências
yarn install ou npm install

# executar o backend
yarn start ou npm start

# executar o frontend
na pasta frontend, abra em index.html no seu navegador
```
# Autor
Rafael Guimarães Nogueira

https://www.linkedin.com/in/rafael-guimaraes-nogueira/
