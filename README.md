# PetCão

Projeto acadêmico desenvolvido para estudo de desenvolvimento web, com
foco na criação de uma página institucional simples para um negócio
fictício voltado ao segmento pet.

> **Finalidade:** mini projeto exclusivamente educacional, desenvolvido
> para praticar conceitos fundamentais de desenvolvimento front-end.

## Objetivo

O PetCão representa uma empresa fictícia dedicada a produtos e serviços
para animais de estimação. A proposta é praticar a construção de uma
interface web completa, com navegação, apresentação institucional,
galeria e formulário de contato.

## Tecnologias utilizadas

### HTML5

Responsável pela estrutura da página, incluindo cabeçalho, navegação,
seções de conteúdo, títulos, textos, galeria, formulário e rodapé. O
documento utiliza `lang="pt-BR"` e a estrutura básica de um documento
HTML5.

### CSS3

Responsável pela identidade visual, layout e interações. Foram
utilizados variáveis CSS, gradientes, sombras, bordas arredondadas,
efeitos de `hover`, transições, animações, `focus-visible` e
`prefers-reduced-motion`.

## Estrutura da página

### Header

Contém o nome da marca e links para Sobre, Galeria, Mapa e Contato,
utilizando navegação por âncoras internas. fileciteturn6file0L11-L22

### Hero

Área inicial da página, com título de boas-vindas e imagem de destaque
configurada como plano de fundo. O CSS utiliza `background-size: cover`
e altura de `100vh`.

### Sobre

Apresenta uma breve descrição da empresa e sua proposta de atendimento.

### Mapa

Área reservada para informações de localização e futura implementação de
mapa.

### Galeria

Seção visual com imagens de cães, estruturada por meio de elementos
`<img>`.

### Contato

Formulário com campos de nome, e-mail e mensagem, além do botão de
envio. A versão atual não possui backend para processar os dados.
fileciteturn6file0L44-L58

### Rodapé

Apresenta o ano, direitos autorais e identificação de desenvolvimento
como "Nick Code". fileciteturn6file0L60-L60

## Identidade visual

A paleta foi construída principalmente com tons terrosos, creme e oliva.
O CSS também utiliza sombras, gradientes, bordas arredondadas e
transições para criar uma aparência mais elaborada.

Os botões possuem gradiente, bordas arredondadas, sombra e efeitos de
interação.

## Funcionalidades

  Funcionalidade             Status
  -------------------------- ------------------
  Estrutura HTML5            Implementada
  Navegação por âncoras      Implementada
  Seção Hero                 Implementada
  Seção Sobre                Implementada
  Área para mapa             Estruturada
  Galeria de imagens         Estruturada
  Formulário de contato      Estruturado
  Estilização CSS            Implementada
  Efeitos de hover           Implementados
  Transições                 Implementadas
  Focus para navegação       Implementado
  Redução de movimento       Implementada
  Backend                    Não implementado
  Banco de dados             Não implementado
  Envio real do formulário   Não implementado

## Interações

O projeto utiliza efeitos de `hover`, `active`, `focus-visible`,
transições e animações. Há também uma regra para usuários que preferem
reduzir animações e transições.

## Estrutura esperada

``` text
PetCão/
├── index.html
├── css/
│   └── style.css
└── img/
    ├── hero.jpg
    ├── dog1.jpg
    ├── dog2.jpg
    ├── dog3.jpg
    ├── dog4.jpg
    ├── dog5.jpg
    ├── dog6.jpg
    └── dog7.jpg
```

O HTML referencia `css/style.css` e as imagens da galeria dentro de
`img/`.

## Como executar

1.  Manter a estrutura de pastas.
2.  Abrir o arquivo `index.html` em um navegador.
3.  Navegar pelas seções da página.
4.  Para desenvolvimento, pode ser utilizado um servidor local, como
    Live Server.

Não é necessário backend ou banco de dados para visualizar a interface
atual.

## Limitações atuais

Este projeto possui escopo exclusivamente acadêmico. O formulário não
está conectado a um backend, a seção de mapa ainda é apenas estrutural e
não há banco de dados, autenticação, pagamentos ou gerenciamento de
produtos.

Também há pontos técnicos que devem ser corrigidos em versões futuras: o
atributo `viewport` aparece incompleto no HTML e existem tags que podem
ser reorganizadas para melhorar a estrutura semântica.
fileciteturn6file0L3-L10 fileciteturn6file0L11-L31

O HTML também referencia `dog2.jpg` e `dog4.jpg`; esses nomes devem ser
conferidos na pasta de imagens antes da execução final.

## Conhecimentos praticados

-   HTML5 e estrutura de documentos;
-   elementos semânticos;
-   navegação por âncoras;
-   formulários;
-   imagens;
-   CSS3;
-   variáveis CSS;
-   cores e tipografia;
-   gradientes;
-   sombras;
-   pseudo-classes;
-   transições e animações;
-   responsividade;
-   acessibilidade básica;
-   organização de arquivos;
-   construção de interface front-end.

## Possíveis melhorias

1.  Corrigir e padronizar a estrutura semântica do HTML.
2.  Melhorar a responsividade para celulares, tablets e desktops.
3.  Implementar menu mobile.
4.  Adicionar um mapa real.
5.  Conectar o formulário a um backend ou serviço de envio.
6.  Criar páginas individuais para produtos e serviços.
7.  Adicionar JavaScript para interações avançadas.
8.  Criar componentes reutilizáveis.
9.  Ampliar acessibilidade e navegação por teclado.
10. Otimizar imagens e desempenho.
11. Implementar SEO básico.
12. Publicar o projeto em uma plataforma de hospedagem.

## Contexto acadêmico

O PetCão é um **mini projeto de estudo**. A finalidade é aplicar
conhecimentos de desenvolvimento web em uma interface prática,
permitindo evolução posterior com JavaScript, backend, banco de dados e
outras tecnologias.

## Autor

**Nick Code**

Projeto desenvolvido para fins acadêmicos e de aprendizado em
desenvolvimento web.

## Licença

Projeto destinado exclusivamente a estudo e aprendizado. Não representa
uma aplicação comercial ou serviço oficial.
