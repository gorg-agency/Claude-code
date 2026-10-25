# Guia de estilo: posts de referência

Biblioteca dos posts que você mandou como referência. Cada post tem uma ficha com formato, cores (medidas na imagem), fontes, layout, componentes, efeitos e texto. As imagens originais estão em `imagens/`.

**Para criar um post novo:** escolha uma família (seção 2), abra a ficha do post mais parecido (seção 3), use os componentes da seção 4 e confira a lista da seção 5.

**As cores dos posts novos são sempre as da GORG (seção 0).** Das referências vêm só o layout, os componentes, os efeitos e a estrutura do texto. As cores que aparecem nas fichas são as originais de cada referência e ficam só como registro.

As fontes das fichas são palpites visuais com equivalente gratuito no Google Fonts. As cores das fichas foram medidas nas imagens (podem variar ±5% por causa da compressão JPG).

---

## 0. Cores da GORG (use sempre)

Tiradas do site da GORG Presets (repositório `gorg-agency/gorgpresets.site`): `src/index.css`, `src/members/members.css` e as cores mais usadas nos componentes. Amostra em `../marca/paleta-gorg.png`.

| Papel | Cor | Hex | Uso |
|---|---|---|---|
| **Destaque principal** | Vermelho GORG | `#D82828` | Palavra-chave do título, ícones, botões, CTA, formas sólidas. É a cor da marca (usada 335 vezes no site). |
| Destaque com brilho | Vermelho brilho | `#FF4B4B` | Glow, neon, luz atrás do herói e **texto vermelho pequeno sobre fundo escuro**. |
| Destaque escuro\* | Vermelho escuro | `#8E1616` | Meio de degradês, sombras vermelhas, faixas. |
| Fundo vermelho\* | Vinho noite | `#3A0909` | Fundo escuro puxado para o vermelho, vinheta, base de degradê. |
| **Fundo** | Preto | `#000000` | Fundo padrão (é o fundo do tema “cinema” da área de membros). |
| Fundo 2 / cards | Grafite | `#1D1D1F` | Cards, pílulas, faixas. Também é o texto em fundo claro. |
| Bordas e divisores | Chumbo | `#424245` | Linhas, bordas de cards sólidos. |
| Texto apagado | Cinza escuro | `#6E6E73` | Microtexto, legendas. |
| **Texto secundário** | Cinza | `#86868B` | Subtítulos e textos de apoio no escuro. |
| Texto terciário | Cinza claro | `#A1A1A6` | Rodapé, informações de contato. |
| **Texto principal** | Off-white | `#F5F5F7` | Títulos e texto em fundo escuro. No claro, é o fundo. |
| Branco | Branco | `#FFFFFF` | Fundo da loja (versão clara) e reflexos de vidro. |

\* Derivados do vermelho GORG para degradês. Não aparecem no site.

**Regras:**
- Uma cor só de destaque: o vermelho. Nada de azul, verde, roxo ou laranja das referências.
- Vermelho `#D82828` sobre preto tem contraste 3,2:1. Serve para título grande, ícone e forma, mas **não para texto pequeno**. Texto vermelho pequeno no escuro vai em `#FF4B4B` (6,4:1).
- No fundo claro, o vermelho `#D82828` serve para qualquer tamanho de texto (6,6:1 sobre branco).
- Vidro sobre o preto: branco 6–12% com borda branca 15–25%. Com brilho na marca: borda `#D82828` 70% + glow `#FF4B4B` 40%.

**Fonte:** Inter (é a fonte do site), em Black e Bold nos títulos e SemiBold e Regular no resto. A área de membros usa títulos em **caixa alta com espaçamento apertado**, pílulas e vidro fosco. Mantenha isso nos posts.

**Logo:** em `../marca/`.
- `logo-gorg-preto.png`: para fundo claro.
- `logo-gorg-branco.png`: para fundo escuro (o “gorg” fica off-white e “PRESETS” continua vermelho).
- `icone-gorg.png`: o “g” grafite e vermelho, para avatar e marca d'água.

---

## 1. O que todos têm em comum

Isto se repete em quase todos os 16 posts. É o que define o estilo.

| Padrão | Como aparece |
|---|---|
| **Fundo escuro + uma cor forte** | 14 de 16 têm fundo quase preto puxado para a cor da marca (preto-azulado, preto-esverdeado, vinho). Só uma cor de destaque saturada por post. |
| **Vidro (glassmorphism)** | Cards e pílulas com fundo branco 4–12%, desfoque de fundo, borda de 1px branca 15–40% e às vezes brilho interno na cor da marca. |
| **Título enorme e curto** | 2 a 4 linhas, peso Bold/Black, espaçamento entre letras negativo (−2% a −4%), entrelinha apertada (0,95–1,1). Ocupa 50–80% da largura. |
| **Palavra-chave na cor da marca** | Uma linha ou expressão do título em cor (“Real Growth.”, “New Month!”, “Choose”, “CRM confiável”, “in 4 steps.”). |
| **Pílula com ícone em círculo** | Formato recorrente: círculo (ícone ou seta →) + divisor opcional + texto de 1–2 linhas. Serve de CTA, lista de benefícios, chips de categoria e notificações. |
| **Brilho e luz** | Glow na cor da marca atrás do objeto principal, feixes de luz, vinheta colorida nas bordas, anéis de luz no “chão”. |
| **Objeto 3D ou foto como herói** | Rei de xadrez de vidro, interrogação neon, joinha cromado, anel 3D, mão em cards flutuantes, retrato com luz colorida. |
| **Logo no topo, contato no rodapé** | Logo centralizado no topo (ou topo esquerdo). Rodapé com site, @, telefone ou ícones sociais. |
| **CTA de engajamento** | Pedem uma ação no Instagram: “Comente VIP”, “DM PROCESS”, “Salve este checklist”, “Marque sua avaliação”. |
| **Margem de segurança** | 6–9% da largura em todos os lados. Nada importante encosta na borda (exceto objetos que saem do quadro de propósito). |
| **Formato** | Domina o 4:5 (1080×1350). Também 1:1 (1080×1080) e 9:16 (1080×1920, story). |

---

## 2. Famílias de estilo

| Família | Posts | Clima | Bom para |
|---|---|---|---|
| **A. Cinema vermelho + azul com vidro canelado** | 01 | Dramático, sério, premium | Advocacia, segurança, consultoria |
| **B. Laranja editorial** | 02, 03 | Direto, forte, comercial | Ofertas, construção, serviços com preço |
| **C. Azul vidro premium** | 04, 05, 06, 07, 09 | Confiável, tecnológico | SaaS, depoimentos, promoções, agências |
| **D. Roxo de processo** | 08 | Tech, organizado | Passo a passo, metodologia |
| **E. Verde neon no escuro** | 10, 11, 12, 13, 14 | Tecnológico, energia, crescimento | Marketing, CRM, listas de serviços |
| **F. Vermelho líquido** | 15, 16 | Autoral, moderno, artístico | Marca pessoal, música, portfólio |

### Cada família nas cores da GORG

Use esta tabela ao criar. A cor original de cada referência fica na coluna da direita só para comparar.

| Família | Fundo | Fundo 2 / cards | Destaque | Brilho | Texto | Como adaptar | Original da referência |
|---|---|---|---|---|---|---|---|
| A | `#000000` | `#3A0909` → `#1D1D1F` | `#D82828` | `#FF4B4B` | `#F5F5F7` / `#86868B` | A luz azul vira luz branca fria (`#F5F5F7`). Fica a luz dividida vermelho + branco, com o vidro canelado. | vermelho `#E30102` + azul `#031642` / `#335B94` |
| B claro | `#FFFFFF` → `#F5F5F7` | `#1D1D1F` | `#D82828` | — | `#1D1D1F` / `#6E6E73` | O laranja vira vermelho. É o visual da loja da GORG (fundo branco, preço vermelho, pílula grafite). | laranja `#EA572B` em branco |
| B escuro | `#000000` | `#3A0909` | `#D82828` | `#FF4B4B` | `#F5F5F7` | O balão laranja vira balão vermelho e o duotone laranja vira duotone vermelho e cinza. | laranja `#E46117` / `#EE4A1B` |
| C | `#000000` | `#1D1D1F` | `#D82828` | `#FF4B4B` | `#F5F5F7` / `#86868B` | O azul vira vermelho: holofote, bordas com brilho, ícones em círculo. O lima do post 04 também vira vermelho. | azul `#1D54D9` / `#0761F8` |
| D | `#000000` | `#1D1D1F` | degradê `#D82828` → `#FF4B4B` | `#FF4B4B` | `#F5F5F7` / `#86868B` | Os números e o “in 4 steps.” passam do degradê roxo para o vermelho. | roxo `#8755F7` |
| E | `#000000` | `#1D1D1F` | `#D82828` | `#FF4B4B` | `#F5F5F7` | O neon verde vira neon `#FF4B4B`. O card “ativo” sólido fica `#D82828`. | verde `#06FF65` / `#24CD6D` |
| F | `#000000` / `#3A0909` | `#8E1616` | `#D82828` | `#FF4B4B` | `#F5F5F7` | Já é vermelho: troque os vermelhos da referência pelos da GORG. | vermelho `#C90118` / vinho `#931128` |

---

## 3. Fichas dos posts

> As paletas abaixo são as **originais** de cada referência, guardadas como registro. Ao criar, troque pelas cores da GORG usando a tabela “Cada família nas cores da GORG” (seção 2).

### 01. Jurídico, carrossel vermelho e azul
`imagens/01-juridico-carrossel-vermelho-azul.jpg` · Família A

- **Formato:** carrossel de 9 peças em 4:5. Seis slides soltos + um panorama contínuo de 3 slides (última linha do grid), com o fundo emendando de um slide para o outro.
- **Paleta:** preto-azulado `#01010B`, marinho `#031642` e `#01062B`, vermelho `#E30102` / `#BA1C04`, vermelho escuro `#8A0504` e `#400708`, azul de luz `#335B94`, texto branco e cinza `#7A7C88`.
- **Fontes:** título em grotesca Bold com espaçamento negativo (Inter Tight Bold, Archivo SemiBold ou Helvetica Now Display Bold). Textos de apoio na mesma família em Regular.
- **Luz da foto:** iluminação dividida, gel azul de um lado e vermelho do outro, fundo bem escuro (low key). Rostos de perfil ou 3/4.
- **Efeito-assinatura: vidro canelado.** Um retângulo de faixas verticais finas que refratam e esticam a foto (como vidro de box canelado), cobrindo metade do rosto ou do objeto. Aparece em todos os slides.
- **Elementos fixos em todos os slides:**
  - Topo esquerdo: círculo pequeno (≈4% da largura) com seta fina ↘, borda branca 30%.
  - Topo direito: pílula de vidro “Assistência jurídica” (texto de ~11px, fundo branco 12%, borda branca 25%).
  - Borda lateral: texto vertical “SEU DIREITO, NOSSA MISSÃO” com letras espaçadas, girado 90°, opacidade baixa, tom sobre tom.
  - Rodapé esquerdo: pílula com ícone ↻ + “www.advogados.com.br”.
  - Rodapé direito, alinhado à direita: “Compromisso com a sua justiça” (branco, semibold) / “Equipe Jurídica 2025” (cinza).
- **CTA:** card de vidro arredondado (raio ≈12px) com círculo e seta → + 2 linhas de texto, com a última palavra em negrito (“Agende sua consulta gratuita **agora.**”).
- **Slides:**
  1. Retrato de perfil, título à direita no terço inferior: “Defesa jurídica com excelência e confiança” + CTA “Agende sua consulta gratuita agora.”
  2. Aperto de mãos ao fundo + card de vidro grande (borda branca, seta ↘ no canto) com “Seus direitos em boas mãos” / “Atendimento ágil, transparente e focado em resultados.” / CTA “Fale com um advogado especialista hoje.”
  3. “Encontre o seu advogado certo aqui” + dois cards de foto inclinados (homem e mulher, luz vermelha/azul) com ícone ⇄ entre eles + “Temos especialistas em diversas áreas, prontos para ajudar.” + microtexto em caixa alta “ESCOLHA QUEM VAI DEFENDER SUA CAUSA”.
  4. Martelo e balança: “Justiça com confiança” / “Atuação ética e comprometida em todas as áreas do direito.” + pílula “Marque sua avaliação” + “Saiba mais ↓”.
  5. Escritório desfocado + card de vidro de enquete: avatar + “Marcos Gomes / Advogado Trabalhista”, “**Nos conte:** como se sentiu sendo atendido pelos nossos advogados?” e 3 emojis (o do meio, feliz, maior e em círculo branco).
  6. Equipe de 6 advogados em frente ao prédio + chips de vidro com seta: Direito Civil, Trabalhista, Penal, de Família, Empresarial, do Consumidor. Título centralizado “Especialistas em direito ao seu lado” / “Assessoria jurídica que garante segurança e tranquilidade” + seta ↓.
  7. a 9. (panorama) Retrato de óculos + “Como escolher o advogado certo para o seu caso?” → três cards de vidro inclinados com seta (“Verifique a especialidade”, “Avalie a experiência”, “Sinta segurança”, cada um com uma linha de explicação) e a estátua da Justiça ao fundo → “Conte com nosso time para escolher o advogado ideal para o seu caso.” + card “Atendimento personalizado, por área e com especialistas experientes.”
- **Copy:** promessa curta (4–6 palavras) + uma linha de benefício + CTA com verbo no imperativo.

### 02. Soltadigital, oferta de site (story)
`imagens/02-soltadigital-oferta-site-story.jpg` · Família B (versão clara)

- **Formato:** story 9:16 (1080×1920). É um print do Instagram: a figurinha “Ver detalhes” e a barra de baixo são do app, não da arte. Deixe essa área livre.
- **Paleta:** fundo branco com degradê radial (`#FEFEFC` no centro, `#E8E7E5` nas bordas), preto `#0E1014`, laranja `#EA572B`.
- **Fontes:** título em grotesca Black com espaçamento bem negativo (Inter Black, Satoshi Black ou Archivo Black). Pílula e textos em sans humanista SemiBold (Nunito Sans ou Gilroy).
- **Layout (de cima para baixo, tudo centralizado):**
  1. Logo “soltadigital.” preto bold + quadrado laranja arredondado com seta branca ↗.
  2. “O teu novo / site.” preto, enorme, 2 linhas.
  3. “150€” laranja gigante (o maior elemento da peça) + “+ IVA” laranja menor.
  4. Pílula preta “Só pagas se gostares” com texto branco.
  5. Dois blocos separados por linha vertical fina: “Criado em **WordPress**” | “Primeira versão em **72 horas**” (72 horas em laranja) + nota “Após receção dos materiais e confirmação do projeto.”
  6. Mockup de notebook + celular com sites de exemplo (LUXMOTORS, carro preto; BELLA Beauty Studio).
  7. Rodapé: “Domínio e alojamento não incluídos.” à esquerda e “soltadigital.com” em negrito à direita.
- **Copy:** oferta com preço em destaque, redução de risco (“Só pagas se gostares”), prova de prazo (72h), letra miúda honesta. Português de Portugal (“teu”, “receção”, “alojamento”).

### 03. Canlar İnşaat, construtora em laranja (grid de 9)
`imagens/03-canlar-construcao-laranja-grid.jpg` · Família B (versão escura e clara alternadas)

- **Formato:** 9 posts 4:5 pensados para o grid do perfil, alternando fundo claro e escuro como um tabuleiro.
- **Paleta:** laranja `#E46117` / `#EE4A1B`, brilho âmbar `#F7A83B`, preto `#030101`, marrom `#381F19`, cobre `#90543D`, cinza claro `#DDDBD8` e `#F4F4F4`.
- **Fontes:** títulos em geométrica Bold (Poppins Bold ou Gilroy ExtraBold). Topo e caixa alta espaçada em Montserrat. Logo com letras largas.
- **Elementos fixos:**
  - Topo central: “C A N L A R  İ N Ş A A T” com espaçamento enorme (~+600), pequeno, cinza ou laranja apagado.
  - Rodapé central: logo (ícone de telhado em camadas cor de cobre + “CANLAR” + “İNŞAAT & YAPI”).
  - Seta ↗ ou ↘ laranja como ícone da marca.
- **Componentes:**
  - **Balão laranja:** retângulo de cantos bem arredondados (≈40px) com traço branco curto em cima, título bold, texto pequeno e um **selo giratório** (texto em círculo + seta → em círculo preto).
  - **Recorte saindo do quadro:** foto recortada (mão com capacete, operário, corrente) passando por cima do balão para dar profundidade.
  - **Foto em duotone:** fotos dessaturadas puxadas para laranja/cobre.
  - **Dupla exposição:** perfil de homem com capacete com prédio e guindaste dentro da silhueta.
  - **Tipografia gigante de fundo:** “CANLAR İNŞAAT” escura no fundo preto, ou “canlar” enorme e cortada atrás do prédio.
- **Posts (títulos):** “Gücümüz, Detaylarda Saklı.” (capacete na mão) · “ZAMAN KAYBETTIRMEYIZ” (seta laranja enorme brilhando atrás de dois homens apertando as mãos, cidade à noite) · “İnşa Etmek, Geleceğe İmza Atmaktır.” (operário + corrente + capacete amarelo) · “Sağlam Temeller Güçlü Yarınlar” (dupla exposição, faixa laranja diagonal) · “Sağlamlığın Şekil Bulmuş Hali” (bloco de concreto flutuando entre rochas) · “CANLAR ↗ İNŞAAT / Yaşama Değer Katan Yapılar.” (guindastes, brilho laranja vertical) · “Yüksek Hedefler, Güçlü Yapılar.” (prédios vistos de baixo) · “Her proje, emeğin, güvenin ve ustalığın birleştiği bir eserdir.” (silhueta + semicírculo laranja na base) · “Geleceği Kat Kat İnşa Ediyoruz” (obra + “canlar” gigante).

### 04. Creative Tech, depoimento em card de vidro
`imagens/04-creative-tech-depoimento-glass-azul.jpg` · Família C

- **Formato:** 4:5.
- **Paleta:** marinho `#0A142F` no topo descendo para azul elétrico `#1060D0` / `#1297FA` embaixo, verde-limão `#D0E44B` (coração e estrelas), branco.
- **Fontes:** Poppins (Regular no depoimento, SemiBold no nome).
- **Fundo:** grade de linhas finas (≈100px) com pontinhos nos cruzamentos, faixas de luz branca difusas nas laterais de baixo.
- **Card principal:** vidro grande (borda branca 25%, fundo transparente descendo para azul) com **recorte no topo direito** onde encaixa um círculo com coração verde-limão, e **recortes laterais em meia-lua** (estilo ingresso) separando a parte de baixo.
- **Conteúdo:** ícone de cursor clicando no topo central · avatar genérico azul + “John” + “☆ 5 reviews” · depoimento justificado em 2 parágrafos · pílula com 5 estrelas verde-limão · 3 botões redondos de vidro (curtir, comentar, enviar, imitando o Instagram) · QR code branco à direita.
- **Rodapé em 3 colunas:** telefone, site e endereço, cada um com ícone azul.

### 05. The Zubix, depoimento de cliente
`imagens/05-zubix-depoimento-cliente.jpg` · Família C

- **Formato:** 4:5.
- **Paleta:** preto `#010106`, azul profundo `#0D185D` / `#1328A8`, estrelas `#302AE1`, linhas `#4C578B` claras.
- **Fontes:** título em geométrica (Outfit ou Questrial SemiBold), texto e nome em Poppins.
- **Layout:** logo no topo · card quadrado de cantos arredondados (≈40px) com borda azul fina e fundo um pouco mais claro · uma **linha curva fina de órbita** com estrela de 4 pontas cruza o card de um canto ao outro · **joinhas 3D cromados/iridescentes** saem do card nos cantos opostos (topo direito e base esquerda).
- **Conteúdo centralizado:** “Client Testimonial” grande + barra azul curta embaixo · depoimento em 4 linhas · nome em negrito · 5 estrelas azuis · site no rodapé.

### 06. Orbitaxia, xadrez e estratégia
`imagens/06-orbitaxia-xadrez-estrategia.jpg` · Família C

- **Formato:** 1:1.
- **Paleta:** azul-preto `#010516` / `#040F2F`, azul `#1D54D9` (texto destacado `#2F6BFF`), azul claro `#69B7FC` nos brilhos.
- **Fontes:** Inter ou SF Pro Display SemiBold no título; Regular no resto.
- **Layout:** logo “orbit axia.” com asterisco em círculo (topo esquerdo) · tagline no topo direito “Strategy today. / Stronger tomorrow.” (2ª linha azul) · título centralizado “Strategic Moves.” branco / “Real Growth.” azul · divisor linha–ponto–linha · subtítulo com trecho em azul.
- **Herói:** rei de xadrez de vidro azul 3D sobre um painel de vidro, com **anéis de luz concêntricos** no chão.
- **Diagrama:** 4 cards em pílula de vidro (ícone azul em círculo + título + linha curta) ligados ao rei por linhas finas com pontinhos: Focused Strategy, Measurable Results, Stronger Brand, Sustainable Growth.
- **Rodapé:** barra larga em pílula de vidro com Telegram @ | e-mail, separados por divisor vertical.

### 07. Advbox, bônus em pílula de vidro
`imagens/07-advbox-bonus-pill-glass.jpg` · Família C

- **Formato:** 4:5.
- **Paleta:** azul `#0341B1` / `#07308D`, marinho `#000B1F`, azul do botão `#015DFD`.
- **Fontes:** Lato (Light no texto principal, Regular e Bold nas palavras de destaque).
- **Layout:** muito espaço vazio · **feixe de luz vertical azul** no centro (holofote) · anel 3D desfocado e cortado na borda esquerda · logo ADVBOX branco no topo.
- **Pílula principal:** vidro grande com borda azul brilhando (glow), ícone % em círculo azul sólido, texto em 4 linhas: “Envie mensagem agora e **libere até R$1000 de bônus** na sua contratação!”.
- **CTA:** pílula azul sólida com brilho: “Comente "VIP" e receba o link no seu direct”.
- **Copy:** uma só oferta, sem distração. Gatilho de comentário para automação de DM.

### 08. Aimsols, processo em 4 passos
`imagens/08-aimsols-processo-4-passos.jpg` · Família D

- **Formato:** 1:1.
- **Paleta:** roxo escuro `#151127` / `#1D1831`, roxo `#8755F7`, lilás `#B06CF1`, texto cinza-lilás `#8274A2`.
- **Fontes:** Poppins Bold (título e números), Poppins Regular (textos).
- **Layout:**
  - Pontinhos roxos com borda branca nos 4 cantos; grade sutil e brilhos roxos no fundo.
  - Tag em pílula “• OUR PROCESS” em caixa alta espaçada (topo esquerdo); logo no topo direito.
  - Título: “From idea to launch” branco / “in 4 steps.” em degradê roxo (`#8B5CF6` → `#C084FC`).
  - Subtítulo cinza de 2 linhas.
  - Grade 2×2 de cards (fundo branco 3–4%, borda branca 8%, raio ≈16px, brilho roxo no canto de cima à direita): número grande roxo “01–04”, título branco (Discover, Design, Develop, Deliver), texto cinza de 2–3 linhas.
  - Rodapé: “Want this for your project?” + botão roxo em pílula “DM "PROCESS" →”.

### 09. Advbox, Black November
`imagens/09-advbox-black-november.jpg` · Família C

- **Formato:** 4:5.
- **Paleta:** marinho quase preto `#000B1F` (mais da metade da peça), azul `#0761F8`, azul claro `#AACDF1` / `#339BFB`.
- **Fontes:** Lato (Regular e Bold); selo “BLACK NOVEMBER” em geométrica fina com “20/25” empilhado em negrito.
- **Layout:** selo no topo · título centralizado “Entre no ecossistema / **ADVBOX** até **30/11** e garanta:” · grade 2×2 de **pílulas grandes** (raio total, fundo marinho, borda azul com brilho interno, ícone em círculo azul sólido + texto de 2–3 linhas): Usuários ilimitados, OAB Nacional liberada, 500 processos adicionais totalmente inclusos, Todos os sistemas eletrônicos inclusos · print do painel do produto (interface escura) na metade de baixo · botão redondo azul com seta → sobre o print · logo no rodapé · anel 3D de vidro azul cortado na borda direita.

### 10. Davia, checklist de CRM
`imagens/10-davia-crm-checklist.jpg` · Família E

- **Formato:** 4:5.
- **Paleta:** preto-esverdeado `#020607` / `#020D0D`, verde neon `#1CE018`, verde escuro `#11221C`, branco.
- **Fontes:** Poppins Regular (título e subtítulo), logo “DAVIA” em fonte pixelada/tech.
- **Layout:** logo no topo · título centralizado em 3 linhas: “Um **CRM confiável** começa pelo que sua equipe registra.” (destaque em verde) · subtítulo com palavras em verde (“**Cinco campos** transformam cadastro em **inteligência.**”).
- **Herói:** foto de mão tocando um de 5 cards de vidro flutuando sobre um tablet. Ícones de linha: pessoa, documento, envelope, telefone, prédio. O card tocado brilha verde.
- **CTA:** pílula com contorno verde e ícone de marcador: “Salve este checklist”.
- **Rodapé:** “www.davia.com.br” com letras espaçadas entre duas linhas verdes.

### 11. FOMO Boost, órbita de notificações
`imagens/11-fomo-boost-orbita-notificacoes.jpg` · Família E

- **Formato:** 4:5.
- **Paleta:** preto `#010101`, vinheta verde nas bordas `#062A19`, verde `#28DD89` (brilho `#03FF8C`).
- **Fontes:** Inter ou Helvetica Medium (título), Regular (resto).
- **Layout:** dois círculos concêntricos finos verdes · logo no centro (ícone play verde + “FOMO BOOST”) · título “Turn / Silence / Into Sales” branco, 3 linhas centralizadas · subtítulo “Use **Proof**, **Urgency** & **Trust** Together” (palavras em verde).
- **6 notificações em pílula de vidro na órbita**, como as horas de um relógio: ícone verde em círculo + 2 linhas de texto. “Jhon Just Purchased / 2 min ago”, “Sarah left a 5-star review”, “20% OFF Sitewide / Today only!”, “Only 3 left in stock / Hurry up!”, “Deal ends in 02:45:30” (com barra de progresso), “248 Visitors online”.

### 12. Velovis, carrossel verde de produto
`imagens/12-velovis-carrossel-verde.jpg` · Família E

- **Formato:** apresentação em grade, com um quadro grande 2×2 e quadros pequenos 4:5.
- **Paleta:** preto-esverdeado `#030C0C` / `#020506`, verde-garrafa `#193A33` / `#0C2823`, verde-água `#31B183`, verde neon `#44F096`, com **granulação** (ruído) por cima.
- **Fontes:** Outfit ou Urbanist (Light e Medium), centralizada.
- **Elementos fixos:** rodapé com logo “velovis” à esquerda e “velovistech.co” à direita; títulos centralizados de 2 linhas com subtítulo de 2 linhas.
- **Componentes:** cards de vidro escuro com borda verde fina e ícones de linha · barra deslizante com pílula verde brilhante · pílulas verdes com ícone (palmeira, paquímetro), onde a ativa tem brilho mais forte · arco de luz verde com cometa e logo com ondas concêntricas no centro · grade bento de fotos com tinta verde · chips com contorno, sendo um preenchido em verde neon (“Satışları Hızlandırın”) · card com recorte no topo direito + foto de homem de terno com tablet · “PLUS+ TECHNOLOGY” no canto.
- **Títulos:** “Projenizi Tüm Detaylarıyla Gösterin”, “Konum Avantajınızı Satışa Dönüştürün”, “Peyzajdan teknik detaylara projenizi eksiksiz sunun”, “Velovis Ayrıcalıkları”, “Satış Ofisinizde Geleceği İnşa Edin”, “Gayrimenkulde Geleceğin Standartı”.

### 13. Sprucegraphix, feliz mês novo
`imagens/13-sprucegraphix-novo-mes.jpg` · Família E

- **Formato:** 4:5.
- **Paleta:** preto `#020307`, verde `#24CD6D`, verde escuro `#062C1A`.
- **Fontes:** Poppins Bold/ExtraBold (título), SemiBold (cards); logo “spruce” leve + “graphix” bold + ponto verde.
- **Fundo:** linhas onduladas sutis + grade de pontinhos nos cantos.
- **Layout:** logo no topo · “Happy” branco / “New Month!” verde, enorme · divisor linha–estrela de 4 pontas–linha verde.
- **Cards em cascata:** 4 cards levemente girados (±3°), em zigue-zague, indo do escuro ao verde sólido (o último é todo verde). Cada um: ícone de linha em círculo + divisor vertical + texto (Exciting Opportunities, Positive Connections, Great Health, Abundant Success). Um **fio neon verde** passa por trás dos cards.
- **Rodapé:** 5 ícones sociais em quadrados arredondados com contorno verde.

### 14. Fewlix Studio, por que nos escolher
`imagens/14-fewlix-por-que-escolher.jpg` · Família E

- **Formato:** 4:5.
- **Paleta:** preto `#000000`, verde neon `#06FF65`, verde escuro `#0A3C1C` / `#062411`, verde médio `#4C8962`.
- **Fontes:** Inter ou Helvetica Now Display Bold (título), Medium (resto).
- **Layout:** brilho verde nos cantos de cima à esquerda e de baixo à direita, grade sutil · logo no topo central · **coluna esquerda:** “Why” branco / “Choose” verde neon, gigante / “Fewlix Studio?” branco + texto em 3 linhas com a última em verde · **interrogação 3D** com borda neon verde · **coluna direita:** 6 cards empilhados (degradê verde escuro → preto, borda 1px, raio ≈16px) com ícone de linha + divisor verde + serviço em negrito de 2 linhas.
- **Rodapé:** números (“700+ Projects Completed” | “Trusted by Businesses Worldwide”) com ícones verdes · ícones de ação (salvar, curtir, enviar, comentar) à direita · linha divisória verde · site com ícone de globo · ícones sociais em círculos com contorno.

### 15. Elgar Design, card de vidro vermelho
`imagens/15-elgar-card-vidro-vermelho.jpg` · Família F

- **Formato:** retrato ≈3:4 (1080×1400).
- **Paleta:** vinho `#3C0E16` → `#5B0F1D` → `#8D0E1F`, vermelho dos círculos `#AA0911`, texto branco.
- **Fontes:** Montserrat Bold com espaçamento bem negativo (título); Montserrat Light/Regular (resto).
- **Fundo:** degradê vinho com **círculos enormes desfocados** em vermelho em cima e embaixo.
- **Card:** vidro fosco ocupando ~85% da peça, raio ≈80px, borda branca 1px a 50%, reflexo mais claro nos cantos.
- **Conteúdo do card:** topo “**Elgar** | Design Studio” à esquerda e “Let's Design!” à direita · título gigante alinhado à esquerda: “Hello, / I'm a / Designer.” · rodapé “@elgardesign”.
- **Copy:** minimalista, apresentação pessoal. Tipografia é a imagem.

### 16. Temporal Sound, interface vermelha
`imagens/16-temporal-sound-ui-vermelho.jpg` · Família F

- **Formato:** 1:1.
- **Paleta:** preto puro `#000000`, vermelho `#C90118` / `#DB0119`, vermelho escuro `#610109`.
- **Fontes:** Outfit ou Lexend (SemiBold em caixa alta nos títulos, Regular nos dados).
- **Layout bento com 3 painéis**, todos com **degradê líquido** vermelho ↔ preto, borda vermelha de 1px e raio ≈40px:
  1. Painel grande: tabela ARTIST / TRACK / TIME com #1–#4 (Temporal Echo · Waves of Eternity · 3:48; Silent Horizon · Island Beyond Time · 4:26; Ancient Tides · Echoes of Centuries · 4:11; Midnight Currents · Endless Flow · 4:35), separados por linhas brancas finas.
  2. Painel pequeno: “Eternal Island Atmosphere” + parágrafo pequeno + “VIEW PLAYING” em caixa alta.
  3. Painel médio: “TEMPORAL SOUND VOL. 02” + menu ☰ + “Kronos Atmosphere Collection” + “2026”.
- **Ideia:** post com cara de interface de app. Funciona para lista, ranking, cardápio ou agenda.

---

## 4. Componentes para recriar em HTML/CSS

Valores base para uma tela de 1080px de largura, já com as cores da GORG.

```css
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;900&display=swap");

:root {
  /* Cores da GORG (seção 0) */
  --fundo: #000000;
  --fundo-2: #1D1D1F;
  --vinho: #3A0909;
  --acento: #D82828;           /* vermelho GORG */
  --acento-brilho: #FF4B4B;    /* glow e texto vermelho pequeno no escuro */
  --acento-escuro: #8E1616;
  --texto: #F5F5F7;
  --texto-2: #86868B;
  --texto-3: #A1A1A6;
  --borda: #424245;
  --margem: 80px;              /* ~7,5% de 1080 */
  font-family: "Inter", system-ui, sans-serif;
}

/* Título grande com palavra-chave colorida */
.titulo { font: 900 120px/0.98 "Inter", sans-serif; letter-spacing: -0.035em; color: var(--texto); }
.titulo.caixa-alta { text-transform: uppercase; letter-spacing: -0.02em; } /* jeito da área de membros GORG */
.titulo em { font-style: normal; color: var(--acento); }

/* Card de vidro */
.vidro {
  background: linear-gradient(160deg, rgba(255,255,255,.12), rgba(255,255,255,.03));
  border: 1px solid rgba(255,255,255,.22);
  border-radius: 28px;
  backdrop-filter: blur(24px) saturate(140%);
  box-shadow: inset 0 1px 0 rgba(255,255,255,.18), 0 30px 80px rgba(0,0,0,.45);
}

/* Pílula com ícone em círculo (CTA, benefício, chip, notificação) */
.pilula { display: flex; align-items: center; gap: 20px; padding: 14px 32px 14px 14px; border-radius: 999px; }
.pilula .icone { width: 64px; height: 64px; border-radius: 50%; background: var(--acento); display: grid; place-items: center; }

/* Borda com brilho na cor da marca (Advbox, Fewlix) */
.brilho { border: 1.5px solid color-mix(in srgb, var(--acento) 70%, transparent);
          box-shadow: 0 0 24px color-mix(in srgb, var(--acento-brilho) 45%, transparent),
                      inset 0 0 18px color-mix(in srgb, var(--acento-brilho) 25%, transparent); }

/* Vidro canelado (post 01): faixas verticais por cima da foto */
.canelado {
  background: repeating-linear-gradient(90deg,
    rgba(255,255,255,.10) 0 2px, rgba(255,255,255,0) 2px 14px, rgba(0,0,0,.18) 14px 18px);
  backdrop-filter: blur(3px);
  mix-blend-mode: screen;
}
/* Para uma refração real, use filtro SVG: feTurbulence (baseFrequency="0.08 0") + feDisplacementMap na foto. */

/* Feixe/holofote (Advbox) e vinheta colorida (FOMO, Fewlix) */
.holofote { background: radial-gradient(40% 70% at 50% 20%, color-mix(in srgb, var(--acento) 55%, transparent), transparent 70%); }
.vinheta  { background: radial-gradient(75% 75% at 50% 50%, transparent 55%, color-mix(in srgb, var(--vinho) 90%, transparent)); }

/* Degradê líquido vermelho (família F) */
.liquido { background:
  radial-gradient(60% 80% at 80% 70%, var(--acento) 0%, transparent 60%),
  radial-gradient(50% 60% at 20% 20%, var(--acento-escuro) 0%, transparent 65%),
  var(--fundo); }

/* Granulação (Velovis) */
.grao { background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='200' height='200'><filter id='n'><feTurbulence baseFrequency='.9'/></filter><rect width='100%' height='100%' filter='url(%23n)' opacity='.08'/></svg>"); }

/* Texto vertical na borda (post 01) */
.vertical { writing-mode: vertical-rl; transform: rotate(180deg); letter-spacing: .4em; font-size: 14px; text-transform: uppercase; opacity: .35; }

/* Topo com letras espaçadas (Canlar) */
.sobrescrito { letter-spacing: .6em; font-size: 16px; text-transform: uppercase; opacity: .5; }
```

### Fotos e objetos 3D com IA

Modelos de prompt para gerar as imagens heroicas, já nas cores da GORG (vermelho #D82828, preto e luz branca fria):

- **Família A:** “retrato cinematográfico de perfil, pessoa de roupa escura, luz dividida com gel vermelho (#D82828) de um lado e luz branca fria do outro, fundo preto, pouca luz, alto contraste, fotografia 85mm”.
- **Família B:** “objeto do produto seguro por uma mão, recortado em fundo branco, duotone vermelho e cinza, fotografia de produto”.
- **Família C:** “peça de xadrez rei de vidro vermelho translúcido, iluminada por baixo, anéis de luz vermelha concêntricos no chão, fundo preto, render 3D”.
- **Família E:** “mão tocando ícones holográficos de vidro sobre um celular, brilho vermelho neon, fundo preto, fotografia de estúdio”.
- **Família F:** “degradê líquido abstrato vermelho (#D82828) e preto, textura suave de mesh gradient, sem objetos”.

---

## 5. Lista para conferir um post novo

- [ ] Formato certo (4:5 feed, 1:1, 9:16 story) e margem de 6–9% em todos os lados.
- [ ] Só cores da GORG (seção 0): fundo preto `#000000` (ou branco na família B clara) e vermelho `#D82828` como único destaque.
- [ ] Vermelho em 1 palavra ou linha do título, ícones e CTA. Texto vermelho pequeno no escuro em `#FF4B4B`.
- [ ] Fonte Inter e logo GORG certo para o fundo (`logo-gorg-branco.png` no escuro, `logo-gorg-preto.png` no claro).
- [ ] Título com no máximo 4 linhas, peso Bold/Black, espaçamento negativo.
- [ ] Hierarquia de no máximo 3 níveis: título, apoio, detalhe.
- [ ] Um herói visual (foto com luz colorida, objeto 3D ou tipografia gigante).
- [ ] Pelo menos um componente de vidro ou pílula com ícone em círculo.
- [ ] Brilho ou luz atrás do herói.
- [ ] Logo no topo e contato ou site no rodapé.
- [ ] CTA de engajamento claro (comente, salve, chame no direct, agende).
- [ ] Em carrossel: elementos fixos repetidos em todos os slides (cantos, rodapé, texto lateral).
- [ ] Em story: deixar livres os ~250px de cima e os ~340px de baixo (interface do Instagram).

---

## Como adicionar novas referências

1. Salve a imagem em `imagens/` com o próximo número: `17-marca-assunto.jpg`.
2. Crie a ficha na seção 3 seguindo o mesmo modelo (formato, paleta, fontes, layout, componentes, copy).
3. Coloque o post na família certa (seção 2) ou crie uma família nova.
4. Atualize a seção 1 se aparecer um padrão novo que se repete.
