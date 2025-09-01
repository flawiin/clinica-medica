# CMLife – Clínica Médica

![Prévia da Home](assets/img/recepcao.png)

![Prévia de Especialidades](assets/img/fisioterapia.png)

Projeto de site estático e responsivo desenvolvido durante o curso "Carreiras Programador: Crie sites e landing pages" da DevMedia. O objetivo é construir uma landing page de clínica médica com navegação entre páginas e foco em tipografia, componentes reutilizáveis e boas práticas de HTML e CSS.

## Visão Geral
- Páginas: `index.html` (Home) e `especialidades.html` (Horários por especialidade)
- Tecnologias: HTML5, CSS3 (flex, grid, variáveis CSS), Google Fonts
- Responsividade: mobile-first, ajustes progressivos em 768px e 1024px
- Acessibilidade: estrutura semântica, textos alternativos em imagens, foco visível em links de navegação

## Estrutura
- `index.html`: Apresentação da clínica, especialidades em destaque, CTA de contato e mapa.
- `especialidades.html`: Descrição das especialidades e tabelas de horários. A partir de 1024px, imagem e tabela ficam lado a lado.
- `assets/css/index.css`: Estilos globais, cabeçalho, navegação, tipografia, seções da Home e rodapé.
- `assets/css/especialidades.css`: Estilos específicos das seções e tabelas de especialidades.
- `assets/img/`: Imagens do site (logo, fotos das especialidades e da clínica).

## Destaques de Implementação
- Navegação entre páginas com âncoras internas (`#sobre`, `#contato`) e link para `especialidades.html`.
- Tabelas acessíveis com `<thead>` e `<tbody>` e zebra-stripes.
- Layout das especialidades com rolagem horizontal em telas estreitas e grid 2 colunas ≥ 1024px.
- Uso de propriedades lógicas como `padding-inline` para melhor suporte a diferentes direções de escrita.

## Como Rodar
1. Clone este repositório ou baixe o ZIP.
2. Abra `index.html` no navegador (duplo clique) ou sirva com um servidor estático.
3. Navegue até "Especialidades" pelo menu para ver a segunda página.

## Customização Rápida
- Cores e fonte: edite variáveis em `assets/css/index.css` no seletor `:root`.
- Itens de navegação: altere os links no cabeçalho de cada página.
- Conteúdo das tabelas: edite os `<tbody>` em `especialidades.html`.

## Créditos
- Curso: DevMedia – "Carreiras Programador: Crie sites e landing pages".
- Autor do projeto: Flávio Pimentel.

## Licença
Projeto para fins educacionais/didáticos. Ajuste a licença conforme sua necessidade.
