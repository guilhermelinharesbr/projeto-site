# Projeto Site - Cursos Grátis

Projeto web estático desenvolvido durante os estudos de Git e GitHub, com foco em versionamento e publicação de uma página simples em HTML e CSS.

O site apresenta uma vitrine de cursos gratuitos com duas páginas de conteúdo:
- Curso de HTML5 e CSS3
- Curso de JavaScript

## Objetivo

Este projeto foi criado para praticar:
- Estruturação de páginas com HTML5 semântico
- Estilização com CSS3
- Navegação entre páginas
- Organização de arquivos em um projeto front-end simples
- Fluxo básico de versionamento com Git e GitHub

## Tecnologias Utilizadas

- HTML5
- CSS3
- YouTube Embed (iframes para vídeos)

## Estrutura do Projeto

```text
projeto-site/
├── index.html
├── curso-html.html
├── curso-js.html
├── estilos/
│   └── style.css
├── imagens/
│   ├── btn-back.png
│   ├── curso-em-video-cor.png
│   ├── curso-em-video-pb.png
│   ├── curso-html-css.png
│   └── curso-javascript.png
├── LICENSE
└── README.md
```

## Páginas e Funcionalidades

### 1) Página inicial (`index.html`)

- Exibe o título "Cursos Grátis".
- Mostra a logo do projeto.
- Apresenta dois blocos de curso com:
	- título
	- imagem ilustrativa
	- descrição breve
	- link para a página específica do curso

### 2) Página do curso de HTML (`curso-html.html`)

- Contém descrição introdutória sobre HTML e CSS.
- Exibe um vídeo incorporado do YouTube.
- Possui botão de voltar para a página inicial.

### 3) Página do curso de JavaScript (`curso-js.html`)

- Contém descrição introdutória sobre JavaScript e DOM.
- Exibe um vídeo incorporado do YouTube.
- Possui botão de voltar para a página inicial.

## Estilização (`estilos/style.css`)

O arquivo CSS centraliza o visual do site com:
- Fonte padrão sans-serif
- Largura fixa do conteúdo principal (`560px`)
- Cartão branco com sombra para destacar o conteúdo
- Paleta em tons de azul/roxo
- Efeito de hover nos links
- Imagens laterais flutuando à direita nos cards da página inicial

## Como Executar Localmente

Por ser um projeto estático, não há necessidade de instalar dependências.

1. Clone o repositório:

```bash
git clone <url-do-repositorio>
```

2. Acesse a pasta do projeto:

```bash
cd projeto-site
```

3. Abra o arquivo `index.html` no navegador.

Dica: no VS Code, você pode usar a extensão "Live Server" para visualizar o site com atualização automática.

## Responsividade e Compatibilidade

- O projeto inclui a meta tag `viewport` nas páginas.
- Atualmente, o layout usa largura fixa no container principal, funcionando melhor em telas de desktop.
- Para melhorar em dispositivos móveis, a recomendação é substituir largura fixa por `max-width` e usar regras responsivas com media queries.

## Pontos de Melhoria Sugeridos

- Tornar o layout responsivo para telas menores.
- Melhorar acessibilidade (ex.: links com foco visível e contraste revisado).
- Padronizar e otimizar imagens para performance.
- Adicionar favicon e metadados sociais (Open Graph).
- Criar uma versão com tema claro/escuro.

## Aprendizados Aplicados

Durante o desenvolvimento, este projeto reforça conceitos de:
- HTML semântico (`main`, `header`, `article`, `abbr`, `iframe`)
- Reaproveitamento de estilos com CSS externo
- Navegação entre páginas usando links relativos
- Organização de assets em pastas (`estilos` e `imagens`)

## Licença

Este projeto possui o arquivo [LICENSE](LICENSE). Consulte-o para mais detalhes sobre uso e distribuição.
