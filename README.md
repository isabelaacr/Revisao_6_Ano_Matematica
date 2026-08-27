📓 Revisão de Matemática — Frações, Porcentagem e Grandezas
Site de estudo interativo, com visual de caderno espiral, feito para revisar frações, porcentagem, razão e proporção, e grandezas (velocidade, densidade demográfica, vazão e escala) — conteúdo de 6º ano. Além do site, o repositório inclui um material de apoio em Word para impressão.
Feito com HTML, CSS e JavaScript puros — sem build step, sem dependências. É só abrir o arquivo no navegador.
📂 Arquivos
Arquivo	Descrição
`revisao-matematica.html`	O site interativo completo (abra direto no navegador).
`material-apoio-fracoes-porcentagem.docx`	Material de apoio para imprimir: definições, exemplos resolvidos e 10 exercícios com gabarito.
🚀 Como usar
Não precisa de servidor nem instalação. Basta abrir `revisao-matematica.html` em qualquer navegador (Chrome, Firefox, Safari, Edge) — em computador ou celular.
```bash
# opcional, só para servir localmente:
python3 -m http.server 8000
# depois acesse http://localhost:8000/revisao-matematica.html
```
🧭 Abas do site
📗 Frações & Porcentagem — conversor de fração para porcentagem, quadriculado de 100 interativo, poltronas de cinema clicáveis, cálculo mental de porcentagem.
🍕 Tipos, Simplificar & Dividir — classificação de frações (própria/imprópria/aparente) com pizzas visuais, simplificador passo a passo com botões de divisão, e divisão de frações pelo método "guarda, troca, inverte".
📝 Resolva sua Lista — seis ferramentas genéricas (operações com frações, fração/porcentagem de um total, razão entre quantidades, velocidade/vazão/densidade/escala com valor faltante, porcentagem em três formatos, conversor fração↔porcentagem↔decimal) para resolver qualquer lista de exercícios parecida, passo a passo.
🧮 Desconto & Acréscimo — calculadora com barra visual proporcional.
⚖️ Razão & Proporção — resolvedor de proporções por multiplicação cruzada, com blocos comparáveis.
🚗 Grandezas — velocidade (carrinho animado), densidade (velocímetro), vazão (tanque enchendo) e escala (régua ilustrativa).
✅ Quiz Final — 6 questões mistas com pontuação e explicação sempre que a resposta estiver errada.
✨ Funcionalidades
100% interativo: sliders, botões e campos que recalculam e desenham (barras, pizzas, quadriculados, animações) em tempo real.
Feedback com explicação: toda resposta errada nos exercícios e no quiz mostra uma dica de "por quê", não só a resposta certa.
Sem dependências externas de runtime — só fontes do Google Fonts (Fredoka, Nunito Sans, JetBrains Mono) via CDN.
Responsivo para celular.
🛠️ Stack
HTML + CSS (custom properties, CSS Grid/Flexbox, `conic-gradient` para as pizzas)
JavaScript vanilla (sem frameworks, sem bundler)
📄 Sobre o material de apoio (.docx)
Gerado a partir do mesmo conteúdo do site, cobrindo: tipos de fração, simplificação, operações (soma, subtração, multiplicação, divisão), porcentagem, desconto/acréscimo, razão e proporção, e as quatro grandezas — com exemplos resolvidos e gabarito ao final. Pode ser impresso ou usado como referência offline.
📝 Licença / uso
Material educacional de uso livre para estudo pessoal.
