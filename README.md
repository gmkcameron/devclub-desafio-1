# DevClub - Desafio 1

## Visão geral

- **Objetivo**: praticar HTML e CSS de nível básico recriando uma landing page simples.
- **Base Figma**: layout fornecido em arquivo do Figma, utilizado como referência visual para tipografia, cores e espaçamentos.

## Layout de referência

- O protótipo no Figma foi disponibilizado pelo DevClub junto com o vídeo explicativo do desafio.

## Tecnologias utilizadas

- **HTML5** para a estrutura do conteúdo.
- **CSS3 (nível básico)** para estilização e posicionamento dos elementos.
- **Google Fonts** para aplicar a família `Poppins` indicada no design.
- **Git** para controle de versão e gerenciamento de código-fonte.
- **Figma** como referência visual principal durante o desenvolvimento.

## Execução local

1. Clone o repositório:
   ```bash
   git clone https://github.com/gmkcameron/devclub-desafio-1.git
   ```
2. Acesse a pasta e abra o arquivo `index.html` diretamente no navegador de sua preferência.
3. Ajuste o CSS conforme necessário, comparando com o layout do Figma.

## Estrutura do projeto

- `index.html`: marcação principal da landing page.
- `styles.css`: folha de estilo responsável por cores, tipografia e espaçamento.
- `img/`: contém o ativo gráfico utilizado na página.

## Aprendizados e ajustes

- Aplicação de `margin-top` na `.logo-image` para reproduzir o espaçamento vertical visto no layout do Figma.
- Ajustes tipográficos (`letter-spacing`, família `Poppins` e peso) para igualar o visual ao protótipo.
- Revisão das dimensões do link "Learn more", removendo larguras/alturas fixas e utilizando `display: inline-block` para evitar truncamentos.

## Próximos passos sugeridos

- Adicionar responsividade para tamanhos de tela menores.
- Incluir estados de interação (hover/focus) mais detalhados nos botões e links.
- Documentar o link exato do Figma quando disponível publicamente.
