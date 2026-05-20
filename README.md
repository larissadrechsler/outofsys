OutOfSys Studio — Fotografia Esportiva
OutOfSys Studio é uma landing page de alta performance desenvolvida para fotógrafos esportivos. O foco do projeto é oferecer uma experiência de usuário (UX) fluida, com tecnologias modernas de layout, acessibilidade avançada e um sistema de design escalável.

🛠️ Tecnologias e Implementações
Abaixo, descrevo como cada requisito técnico foi resolvido no código:

1. Estrutura Semântica Rigorosa (Módulo 01)
O HTML foi construído utilizando exclusivamente tags semânticas para garantir acessibilidade e SEO.

Utilização de <header>, <main>, <section>, <article> e <footer>.

O conteúdo principal é encapsulado em um <main> com um ID de âncora para o Skip Link.

2. Sistema de Design com Variáveis (Módulo 02)
Implementei tokens de design centralizados no bloco :root. Isso permite o controle global de:

Cores: Paleta Tech-Noir (Azul elétrico e tons de grafite).

Tipografia: Fontes Geist para leitura e Anybody para títulos de impacto.

Espaçamento: Variáveis para garantir consistência em margens e paddings.

3. Layout Híbrido: Flex & Grid (Módulo 03)
Combinei as duas principais ferramentas de posicionamento do CSS:

CSS Grid: Responsável pela albums-grid, permitindo que os cards se organizem automaticamente de acordo com o tamanho da tela.

Flexbox: Utilizado no header, nos botões e na navegação mobile para alinhamentos precisos e distribuição de ícones.

4. Interface Responsiva (Módulo 04)
O site é "Mobile First" e escala até resoluções Desktop 4K sem quebras.

Tipografia Fluida: Uso da função clamp() para que o tamanho das fontes se ajuste proporcionalmente.

Grid Adaptável: Uso de auto-fit e minmax para que o número de colunas mude dinamicamente sem a necessidade de centenas de media queries.

5. Microinterações de Feedback (Módulo 05)
Interface viva e interativa:

Hover: Estados de hover nos botões com transições suaves e efeitos de escala nos cards de álbuns.

Imagens: Transição de preto e branco para colorido com zoom suave ao passar o mouse nas fotos.

6. Curadoria de Código com IA (Módulo 06)
Utilizei Inteligência Artificial para estruturar a lógica do formulário de registro e a seção de FAQ.

Refatoração: Ajustei o código gerado para integrar as variáveis do meu Design System e corrigi seletores para garantir que o layout não ficasse centralizado de forma indesejada no desktop.

7. Dark Mode Nativo (Pesquisa)
Implementei a media query prefers-color-scheme: light. O site detecta a preferência do sistema operacional e:

Inverte as variáveis de cor para um tema claro de alto contraste.

Aplica filtros de inversão na logo para manter a visibilidade em fundos brancos.

8. Sticky Headers e Scroll Snap (Pesquisa)
Pesquisei e apliquei comportamentos avançados de rolagem:

Sticky Header: O menu permanece visível no topo durante a navegação.

Scroll Snap: A página "encaixa" automaticamente no início de cada seção (hero, albums, faq, form), proporcionando uma navegação fluida e focada.

9. Otimização de Performance e Assets (Pesquisa)
WebP: Recomendação de formatos de imagem modernos para carregamento rápido.

Lazy Loading: Implementado em imagens para priorizar a renderização do conteúdo acima da dobra.

Font-Display: Configurado para evitar o efeito de "texto invisível" enquanto as fontes carregam.

10. Acessibilidade Avançada (Pesquisa)
Foco em navegação por teclado e tecnologias assistivas:

Skip Link: Link oculto para pular direto ao conteúdo principal.

Focus Visible: Destaque visual nítido (outline azul) apenas para usuários de teclado.

Aria-Labels: Atributos ARIA aplicados em ícones e botões para compreensão por leitores de tela.
