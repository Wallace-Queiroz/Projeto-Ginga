# Projeto Ginga

Site institucional do Projeto Ginga, coletivo que promove o desenvolvimento de crianças e jovens por meio de atividades de esporte, arte e tecnologia. A proposta do projeto é incentivar resiliência, autonomia e autoconfiança em um ambiente acolhedor.

## Páginas

- **Início (`index.html`)** — apresenta o projeto, seu propósito, sua forma de atuação e os três pilares.
- **Projetos (`projetos.html`)** — detalha as atividades de patinação, música e dança, e desenvolvimento tecnológico. Cada atividade oferece caminhos para os formulários de doador e voluntário.
- **Cadastro de doador (`cadastroDoador.html`)** — formulário de contato com nome, e-mail, telefone, projeto de interesse e mensagem.
- **Cadastro de voluntário (`cadastroVoluntario.html`)** — formulário com dados pessoais e de endereço, projeto de interesse e apresentação do candidato.

As páginas compartilham a navegação e o rodapé com informações de contato e links para participação.

## Tecnologias

- HTML5 para a estrutura e o conteúdo.
- CSS3 para estilos, layouts e adaptação a telas menores.
- Google Fonts para as famílias Inter, Montserrat e Oswald.

O projeto não possui JavaScript, backend, gerenciador de pacotes ou etapa de build configurada. Os estilos responsivos incluem ajustes para telas com largura de até 760 px.

## Como executar

Não é necessário instalar dependências:

1. Baixe ou clone o projeto.
2. Abra `index.html` diretamente em um navegador; ou sirva a pasta com uma extensão de servidor local, como o Live Server do VS Code.
3. Use o menu superior para navegar pelas páginas.

As fontes do Google Fonts dependem de conexão com a internet. Sem conexão, o navegador usará as fontes alternativas definidas nos estilos.

## Estrutura

```text
.
├── index.html
├── projetos.html
├── cadastroDoador.html
├── cadastroVoluntario.html
├── css/
│   ├── index.css
│   ├── projetos.css
│   ├── cadastroDoador.css
│   ├── cadastroVoluntario.css
│   └── tipografia.css
└── img/
    ├── comoatuamos1.jpg
    ├── danca1.webp
    ├── esporte1.jpg
    ├── nossoproposito1.png
    ├── quemsomos1.jpg
    └── tecnologia1.jpg
```

- `css/tipografia.css` define as famílias tipográficas usadas nos títulos, textos, links e rótulos.
- Os demais arquivos em `css/` estilizam suas respectivas páginas.
- `img/` contém as imagens utilizadas nas páginas inicial e de projetos.

## Observações

- Os formulários ainda não estão conectados a um serviço de envio ou armazenamento: ambos usam `action="#"` e `method="POST"`. Para receber cadastros, será necessário configurar um endpoint ou integrar um backend.
- Os dados de contato exibidos no rodapé — como o telefone com zeros — parecem ser valores demonstrativos e devem ser substituídos pelos canais oficiais antes da publicação.
- Não há testes automatizados ou instruções de deploy configurados no projeto.
