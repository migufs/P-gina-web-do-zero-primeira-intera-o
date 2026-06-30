# P-gina-web-do-zero-primeira-intera-o
Estruture páginas web utilizando HTML semântico. Estilize elementos e layouts com CSS, incluindo Flexbox. Implemente interatividade em páginas web usando JavaScript para manipular o DOM. Desenvolva funcionalidades dinâmicas como contadores de interação e lógica condicional.
Torres Verdes – Equilíbrio & Produção
Projeto desenvolvido para o Concurso Agrinho 2026 – Categoria Programação, na Subcategoria 3: Programação Front-End – HTML, CSS e JavaScript.
🌱 Tema do Concurso: O equilíbrio entre sustentabilidade e produção.
📌 Sobre o Projeto
O projeto apresenta, de forma visual, interativa e educativa, o conceito revolucionário das Colunas de Plantação (Prédios de Fertilidade Natural). A proposta mostra como o cultivo vertical e a arquitetura agrícola controlada podem eliminar completamente o uso de agrotóxicos no campo, provando que é possível alcançar altíssima produtividade, segurança alimentar e regeneração ambiental ao mesmo tempo. Por meio de textos, infográficos dinâmicos, um acordeão interativo, quiz e um jogo, o site busca aproximar o visitante da realidade da agroecologia de precisão e destacar como o uso inteligente do espaço pode salvar nossos ecossistemas.
🎯 Objetivo
Conscientizar os visitantes sobre os impactos negativos dos defensivos químicos convencionais e apresentar a solução das "colunas de plantação". O projeto demonstra que o desenvolvimento econômico e produtivo pode caminhar junto com a eliminação de agrotóxicos, a economia de água e a recuperação da fertilidade natural do solo.
🧭 Páginas e Funcionalidades
O projeto é composto por cinco páginas HTML:
🏠 Início (index.html)
Hero animado com partículas de folhas e gotas de água.
Painel de estatísticas dinâmico (renderizado via JS) mostrando a economia de água e espaço.
Seção "O que são Prédios de Fertilidade?" com texto e imagem ilustrativa.
Abas interativas com os pilares do Cultivo Vertical (Zero Agrotóxicos, Água, Espaço, Nutrição).
Carrossel de imagens com exemplos de fazendas verticais.
Cards de impacto ambiental (renderizados via JS).
📜 O Método das Colunas (metodo.html) (Substitui a página História)
Seção sobre o problema dos agrotóxicos no modelo tradicional.
Bloco completo explicando a engenharia e biologia por trás das colunas de plantação.
Seção sobre controle biológico e como a estrutura isolada dispensa venenos.
Ciclo de nutrientes naturais e compostagem integrada.
Linha do tempo da evolução agrícola: do arado à fazenda vertical (renderizada via JS).
Acordeão interativo respondendo mitos e verdades sobre agricultura sem agrotóxicos (renderizado via JS).
🌿 Meio Ambiente (meio-ambiente.html)
Seção sobre como tirar a pressão de desmatamento das florestas nativas.
Dados sobre a não contaminação de lençóis freáticos e rios (Graças à ausência de químicos).
Gráficos sobre a economia de até 90% de água em sistemas fechados de irrigação.
Reflexão sobre o futuro da alimentação nas grandes cidades e no campo.
🎮 MiniJogo (minijogo.html)
Seletor de abas para alternar entre os dois jogos.
Quiz Agroecológico com 7 perguntas sobre defensivos naturais, economia de água e cultivo vertical, com feedback explicativo.
Torre de Nutrientes (MiniJogo Runner/Stacker) — O jogador controla um carrinho coletor no subsolo de um "prédio de plantação". Deve usar as teclas ⬆️⬇️ / W / S ou toque na tela para coletar nutrientes naturais (composto orgânico, água limpa) e desviar de elementos tóxicos ou pragas que tentam invadir a base. Velocidade aumenta progressivamente.
📋 Sobre o Projeto (projeto.html)
Apresentação do projeto, motivação e base na ODS 2 (Fome Zero e Agricultura Sustentável).
Cards de tecnologias utilizadas.
Referências bibliográficas no formato ABNT.
♿ Acessibilidade
Botão para aumentar/diminuir o tamanho da fonte.
Modo de alto contraste.
Textos alternativos em todas as imagens.
Uso de elementos semânticos do HTML (header, main, footer, nav, section, figure, figcaption).
Atributos aria-label, aria-current, aria-expanded e role nos elementos interativos.
Navegação organizada por seções e menu responsivo (hambúrguer).
💻 Tecnologias Utilizadas
Desenvolvido utilizando apenas tecnologias básicas de front-end, conforme as regras:
HTML5
CSS3
JavaScript (Vanilla)
✅ Não foram utilizados frameworks ou bibliotecas externas (como Tailwind, Bootstrap ou jQuery). ✅ Os arquivos de estilo e script estão separados (style.css e script.js).
🌿 Sustentabilidade (Foco Principal)
O conteúdo do site aborda práticas inovadoras relacionadas ao equilíbrio entre produção e meio ambiente:
🚫 Fim dos Agrotóxicos: Como ambientes semicontrolados evitam pragas naturalmente.
🏗️ Otimização de Espaço: Produzir o equivalente a hectares de terra em poucos metros quadrados de colunas empilhadas.
💧 Economia Hídrica: Sistema de irrigação em circuito fechado, reaproveitando a água que não foi absorvida pelas plantas.
🐛 Fertilidade Natural: Uso de biofertilizantes e compostagem orgânica na base das colunas em vez de fertilizantes sintéticos.
🧠 Conceitos de Programação Aplicados
Estruturação semântica com HTML5 e uso intensivo de CSS Grid/Flexbox.
Manipulação do DOM com JavaScript para renderização dinâmica (timeline, cards, tabs, carrossel).
Eventos de clique, teclado e toque (touch).
requestAnimationFrame para o loop do jogo interativo.
Variáveis CSS para temas dinâmicos (claro/escuro/alto contraste).
🤖 Prompts Genéricos de IA Utilizados (Exemplo Adaptado)
🌾 Modelo base para o site:
Contexto: Atue como um Desenvolvedor Full-Stack focado em UX e Acessibilidade. Crie um modelo de um site MPA (Multi page Website) sobre "Agricultura Vertical: Equilíbrio e o fim dos agrotóxicos". Arquitetura de Arquivos: Entregue o código dividido em três arquivos: index.html, style.css e script.js. No HTML, use tags semânticas (header, main, section) e atributos ARIA. Design System (CSS): Use Variáveis CSS para paleta de cores (tons de verde limpo e terra) e layout Mobile-First. Adicione modo de Alto Contraste. JS: Não escreva conteúdo repetitivo direto no HTML, crie arrays no JavaScript para renderizar dinamicamente as seções de "Vantagens das Colunas de Plantação".
🌱 Protótipo do jogo interativo:
Crie um jogo HTML5/Canvas do zero com as seguintes características: O personagem principal é um "Drone Agrícola Orgânico" 🚁. Os obstáculos são "Nuvens de Agrotóxicos" ☠️ e os coletáveis são "Gotas de Água Pura" 💧. O fundo deve ser um grande prédio de fazenda vertical (colunas verdes). O cenário se move continuamente para criar sensação de subida na torre. O jogador controla o drone utilizando as teclas S/W ou setas, desviando das nuvens tóxicas e coletando água. A velocidade e a dificuldade aumentam com o tempo. Inclua pontuação, tela de Game Over e botão de reiniciar.
👨‍🎓 Autoria 
Miguel Fonseca de Souza
Guarapuava – Paraná
📄 Licença Projeto desenvolvido exclusivamente para fins educacionais e para participação no Concurso Agrinho 2026.
