# Projetos Frontend - Potência Tech Ifood + DevMedia

## 2ª Missão - Página de Informação de Parque

Esse é o projeto final da `2ª missão` do curso de `Formação Frontend`. O objetivo desse projeto é ajudar a montar a `primeira página HTML`, é criar o arquivo HTML do site e a estrutura básica do documento.

O foco é criar a pasta e o arquivo HTML, que deve ser feito nessa ordem, porque sem a pasta do projeto e o arquivo HTML não é possível inserir o conteúdo da página do site.

A proposta desse projeto é criar uma página web utilizando apenas `HTML`, onde teremos apenas uma única página que conterá informações sobre um parque. Assim, teremos um arquivo HTML que conterá a estrutura da página de informações do parque.

Antes de implementar a parte visual da página, precisamos criar a pasta do projeto e o arquivo HTML. A criação de um site deve ser sempre iniciada pela sua estrutura. 

A `estrutura do projeto` é composta por uma pasta e um arquivo HTML. A pasta serve para organizar o projeto e o arquivo HTML server para conter a estrutura da página. A pasta é usada para guardar os arquivos usados no site. 

O `arquivo HTML` é usado para conter os elementos da página, contém o código HTML que representa a estrutura da página, o que será exibido na página.

Ao criar esse projeto, coloca-se em prática os seguintes conceitos:
- Utilizar tags HTML (básicas)

>[!NOTE]
>
>Nesta missão nosso foco é posicionar e exibir elementos HTML, por isso não vamos nos preocupar com a estética, ou seja, em criar estilos CSS.

## Modelo do Projeto:
![](https://github.com/rhayssakramer/projetos-frontend-devmedia/blob/main/HTML-CSS-Projetos/segunda-miss%C3%A3o/assets/requisitos/layout-finalizado.jpeg)

## Resultado do Projeto:
![](https://github.com/rhayssakramer/projetos-frontend-devmedia/blob/main/HTML-CSS-Projetos/segunda-miss%C3%A3o/assets/resultado.gif)

## Tecnologias Utilizadas:

| Linguagens de Programação | Ferramentas e Tecnologias |
| :-----------------: | :-----------------------: |
| <img height="40" src="https://github.com/rhayssakramer/rhayssakramer/blob/main/assets/icon/HTML.svg"> | <img height="40" src="https://github.com/rhayssakramer/rhayssakramer/blob/main/assets/icon/VSCode-Dark.svg">

## Requisitos do Projeto:

#### Desenvolva um projeto HTML:
O projeto é um site que contém informações sobre um parque. Esse site tem apenas um arquivo que contém diversas tags básicas do HTML. Na estrutura do projeto deve-se criar uma pasta diretório e dentro dela, um arquivo index.html. Após isso, deve-se criar a estrutura padrão do HTML, e por fim, criar os elementos visuais da página, como títulos, subtítulos, parágrafos, imagens e links. 

A página está dividia em 4 pequenas seções que deve ser incluída com uma tag que agrupa elementos. Ao final da página, deve conter um link que direciona para telefone.

Cada seção reúne um tipo de informação sobre o parque:
- **Seção 1:** informações principais do parque.
- **Seção 2:** descrição do parque.
- **Seção 3:** descrição do parque.
- **Seção 4:** informações de ingresso.

A página do projeto é autocontida, ou seja, todas as informações estão reunidas dentro dela. Sendo assim, não precisamos criar mais páginas nesse projeto.

O projeto do parque está separado em 4 seções, cada uma elas representada por um container (tag div) e seus elementos. Sempre que precisar agrupar informações em uma página web, é importante utilizar containers para essa finalidade.

O projeto de site de informações de parque deve ter uma estrutura de pastas para que possa ficar bem organizado.
- **Pasta raiz** do projeto, é a pasta da estrutura, que vai conter outra pasta e todos os arquivos do projeto.
- A pasta contida na pasta raiz, pode conter qualquer nome, mas normalmente é chamada de **img** e vai conter todas as imagens que serão exibidas na página do projeto.
- O arquivo HTML chamado index.html, é usado para conter a estrutura da página do projeto.


#### Especificações do Projeto: 
A **PÁGINA** precisa conter:  
`1. Pasta do projeto: criar uma pasta com o nome do site para guardar os arquivos do site. Com ela é possível organizar o projeto e agrupar os arquivos do site em um único lugar;`   
`2. Arquivo index.html: dentro da pasta crie o arquivo index.html para conter a estrutura da página, nesse arquivo é que fica todo o código HTML;`   
`3. Título da página;`  
`4. Meta charset;`  
`5. Meta description;`  
`6. Dentro do arquivo index.html deve-se colocar o código base que será o código que representa a estrutura básica do HTML: `  

~~~HTML
<!DOCTYPE html>
<html>
	<head>
		<title>Nome do Parque</title>
	</head>
	<body>
	</body>
</html>
~~~

`7. O conteúdo fica dentro da tag '<body>' e '</body>';`  
`8. Deve conter os seguintes elementos: título, imagem, subtítulos (maiores e menores), parágrafos e link; `  
`9. O link deve ter o nome 'clique aqui' e deve ser usado como meio de contato. Esse elemento cria um link para um telefone. Ao ser clicado ele faz uma chamada para o número.'.`  

#### Especificações das seções:
**Seção 1:**  
`container título, subtítulo, imagem e parágrafos.`  

**Seção 2:**  
`container com subtítulo e parágrafo.`  

**Seção 3:**  
`container com subtítulo e parágrafo.`

**Seção 4:**  
`container com subtítulo, parágrafo e link. O link 'clique aqui' deve ser usado como meio de contato.`  

#### Especificações técnicas:
- **HTTP-Server:** para executar o projeto, será necessário um servidor HTTP local. Utilize o http-server para isso.

## Instruções de Uso
1. Clone ou baixe este repositório para a sua máquina local.

2. Certifique-se de ter o Node.js instalado em sua máquina.

3. Abra o terminal e navegue até o diretório raiz do projeto.

4. Instale o http-server globalmente, se ainda não estiver instalado, usando o seguinte comando:
```
npm install -g http-server
```

5. Inicie o servidor HTTP local utilizando o comando:
```
http-server
```
6. Após iniciar o servidor, você receberá uma mensagem informando o endereço local onde a aplicação está sendo executada. 

7. Abra este URL em seu navegador.

## Créditos
Este projeto foi desenvolvido como finalização da missão 2ª do curso de **Formação Frontend** do Potência Tech Ifood + DevMEdia, para avaliar abordado na missão, sobre os fundamentos básicos aplicado no HTML.

>[!NOTE]
>
>*Este projeto é apenas para fins educacionais e não possui nenhuma afiliação oficial com a franquia DevMedia ou suas empresas associadas.*

## Autora:
<table>
  <tr>
    <td>
      <img width="80px" align="center" src="https://github.com/rhayssakramer/rhayssakramer/blob/main/assets/images/logo.png"/>
    </td>
    <td align="left">
      <a href="https://github.com/rhayssakramer">
        <span><b>Rhayssa Kramer</b></span>
      </a>
      <br>
      <span>Desenvolvedora Full Stack</span>
    </td>
  </tr>
</table>

##
<div align="center">Feito por <a href="https://github.com/rhayssakramer">@devrhakramer</a>.</div>
