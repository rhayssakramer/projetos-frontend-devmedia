# Projetos Frontend - Potência Tech Ifood + DevMedia

## 3ª Missão - Site de Informações de Livro

Esse é o projeto final da `3ª missão` do curso de `Formação Frontend`. O objetivo desse projeto é ajudar a montar a primeira página web.

A proposta desse projeto é criar uma página web utilizando as tecnologias `HTML` e `CSS`. Assim, teremos apenas uma única página que conterá informações sobre um determinado produto. 

No projeto teremos um arquivo HTML que conterá a estrutura da página de informações de livro e um arquivo CSS que conterá os estilos para mudar a aparência da página.

Ao criar esse projeto, coloca-se em prática os seguintes conceitos:
- Utilizar tags HTML (básicas);
- Estilizar uma página com CSS.  

>[!NOTE]
>
>Não abordaremos a parte responsiva do CSS (adaptação para telas de celular) para facilitar o processo de aprendizado/prática.

Não haverá navegação entre páginas do projeto, pois o intuito é exibir as informações de um produto, e para isso utilizaremos uma única página. Isso foi feito por uma questão didática para facilitar a construção do primeiro projeto. 

## Modelo do Projeto:
![](https://github.com/rhayssakramer/projetos-frontend-devmedia/blob/main/HTML-CSS-Projetos/terceira-miss%C3%A3o/assets/requisitos/layout_completo.jpg)

## Resultado do Projeto:
![](https://github.com/rhayssakramer/projetos-frontend-devmedia/blob/main/HTML-CSS-Projetos/terceira-miss%C3%A3o/assets/resultado.gif)

## Tecnologias Utilizadas:

| Linguagens de Programação | Ferramentas e Tecnologias |
| :-----------------: | :-----------------------: |
| <img height="40" src="https://github.com/rhayssakramer/rhayssakramer/blob/main/assets/icon/HTML.svg"> <img height="40" src="https://github.com/rhayssakramer/rhayssakramer/blob/main/assets/icon/CSS.svg"> | <img height="40" src="https://github.com/rhayssakramer/rhayssakramer/blob/main/assets/icon/VSCode-Dark.svg">

## Requisitos do Projeto:

#### Desenvolva um projeto HTML/CSS:
O projeto é uma `página web` que contém `informações sobre um livro`. Ele deve estar dividido em `4 seções`. Cada seção reúne um tipo de informação sobre o livro:
- **Seção 1:** informações principais do livro.
- **Seção 2:** descrição da história do livro.
- **Seção 3:** informações do autor.
- **Seção 4:** marketing do livro.

A página do projeto é `autocontida`, ou seja, todas as informações estão reunidas dentro dela. Sendo assim, não precisamos criar mais páginas nesse projeto. Ao invés de separar as informações em páginas diferentes, reunimos todas elas em blocos que chamamos de seções dentro de uma única página.

O projeto do livro está separado em 4 seções, cada uma elas representada por um container (tag div) e seus elementos. Sempre que precisar agrupar informações em uma página web, é importante utilizar containers para essa finalidade.

A construção de um projeto web funciona de forma semelhante à construção de qualquer outro projeto (ex.: uma casa). Esse processo de construção é feito em camadas. As camadas representam etapas da construção de um projeto:

`1ª etapa - Fundação da casa`  
`2ª etapa - Estrutura da casa`  
`3ª etapa - Acabamento da casa`

>[!NOTE]
>
>No projeto web a fundação é a construção das pastas e arquivos, a estrutura é o arquivo HTML e CSS é o acabamento.

O projeto de site de informações de livro deve ter uma estrutura de pastas para que possa ficar bem organizado.
- **Pasta raiz** do projeto, é a pasta da estrutura, que vai conter outra pasta e todos os arquivos do projeto.
- A pasta contida na pasta raiz, pode conter qualquer nome, mas normalmente é chamada de **img** e vai conter todas as imagens que serão exibidas na página do projeto.
- O arquivo HTML chamado index.html, é usado para conter a estrutura da página do projeto.
- O arquivo CSS chamado style.css, é usado para conter toda a estilização da página do projeto.

>[!NOTE]
>
>A folha de estilo só deve ser criada, após a estrutura HTML, para aplicar os estilos precisamos que os elementos estejam visíveis na tela. Sem ter os elementos na tela, é impossível criar os estilos.

#### Especificações das seções:
**Seção 1:**  
`container com textos (títulos, subtítulos e parágrafos), imagem e um link. O  link em destaque aponta para uma página externa, no caso o site da Amazon (para comprar o livro);`  

**Seção 2:**  
`container com span, subtítulo e parágrafo.`  

**Seção 3:**  
`container com subtítulo, imagem e parágrafo.`

**Seção 4:**  
`container com span, parágrafo e link. O link em destaque aponta para uma página externa, no caso o site da Amazon (para comprar o livro).`  

#### Especificações do Projeto: 
A **PÁGINA** precisa conter:  
`1. Título da página;`  
`2. Meta charset;`  
`3. Meta description;`  
`4. Link do arquivo de estilo ao arquivo HTML`   
`5. Agrupe todos os elementos de cada seção;`   
`6. A página deve conter os seguinte elementos: 'títulos', 'subtítulos', 'imagens', 'parágrafos', 'spans', 'links';`  
`7. Os links devem ser estilizados; `  
`8. A fonte da página deve ser 'Tahoma';`  
`9. Remova da margem do corpo da página, para evitar os espaços ao redor da página;`  
`10. As imagens tem largura de '190px';`  
`11. Os spans tem estilo em 'negrito';`  
`12. O h3 tem a fonte em '20px';`  
`13. O h2 tem a fonte em '24px';`  
`14. Os containers tem a cor de fundo '#f5f5f5' e um espaçamento interno de '50px';`  
`15. O parágrafo tem alinhamento de texto 'centralizado', altura da linha com '28px' e largura de '930px'. Para deixar o parágrafo no centro da tela, foram usados valores 'automáticos' nas margens laterais;`  
`16. O link tem cor de fundo '#49b970' e está situado na parte inferior, tamanho de fonte de '14px' e em 'negrito', está 'sem sublinhado', tem a cor da fonte '#ffffff', tem espaçamento interno para todos os lados e bordas arredondadas;`  
`17. Todas as seções terão uma borda superior para separar de cor '#d5d5d5'.`

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
Este projeto foi desenvolvido como finalização da `3ª missão` do curso de **Formação Frontend** do Potência Tech Ifood + DevMEdia, para avaliar abordado na missão, sobre os fundamentos básicos aplicado no HTML e CSS.

>[!NOTE]
>
>Este projeto é apenas para fins educacionais e não possui nenhuma afiliação oficial com a franquia DevMedia ou suas empresas associadas.

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
