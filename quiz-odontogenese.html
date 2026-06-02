<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Quiz Odontogênese 🦷</title>
<link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Nunito:wght@400;600;700;800&display=swap" rel="stylesheet">
<style>
  :root {
    --pink: #FF6B9D;
    --blue: #4ECDC4;
    --yellow: #FFE66D;
    --purple: #A78BFA;
    --green: #6BCB77;
    --red: #FF6B6B;
    --dark: #1a1a2e;
    --card: #ffffff;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'Nunito', sans-serif;
    background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%);
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
    color: white;
  }

  h1 {
    font-family: 'Fredoka One', cursive;
    font-size: clamp(1.8rem, 5vw, 3rem);
    text-align: center;
    margin-bottom: 8px;
    background: linear-gradient(90deg, var(--pink), var(--blue), var(--yellow));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    filter: drop-shadow(0 0 20px rgba(255,107,157,0.4));
  }

  .subtitle {
    font-size: 1rem;
    opacity: 0.7;
    margin-bottom: 24px;
    text-align: center;
  }

  /* ---- MENU ---- */
  #menu {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 14px;
    width: 100%;
    max-width: 480px;
  }

  .topic-btn {
    width: 100%;
    padding: 18px 24px;
    border: none;
    border-radius: 18px;
    font-family: 'Fredoka One', cursive;
    font-size: 1.2rem;
    cursor: pointer;
    display: flex;
    align-items: center;
    gap: 14px;
    transition: transform 0.15s, box-shadow 0.15s;
    box-shadow: 0 6px 20px rgba(0,0,0,0.3);
    color: #1a1a2e;
  }
  .topic-btn:hover { transform: translateY(-3px) scale(1.02); box-shadow: 0 12px 30px rgba(0,0,0,0.4); }
  .topic-btn .emoji { font-size: 1.8rem; }

  .btn-all { background: linear-gradient(135deg, var(--pink), var(--purple)); color: white; }
  .btn-odonto { background: linear-gradient(135deg, var(--yellow), #FFA552); }
  .btn-hist { background: linear-gradient(135deg, var(--blue), #45B7D1); }
  .btn-glands { background: linear-gradient(135deg, var(--green), #4CAF50); }
  .btn-teeth { background: linear-gradient(135deg, var(--purple), var(--pink)); color: white; }

  /* ---- GAME SCREEN ---- */
  #game { display: none; width: 100%; max-width: 560px; }

  .top-bar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 16px;
  }

  .score-box {
    background: rgba(255,255,255,0.1);
    border-radius: 12px;
    padding: 8px 16px;
    font-weight: 800;
    font-size: 1.1rem;
  }

  .progress-wrap {
    flex: 1; margin: 0 12px;
    background: rgba(255,255,255,0.15);
    border-radius: 99px;
    height: 10px;
    overflow: hidden;
  }
  .progress-bar {
    height: 100%;
    background: linear-gradient(90deg, var(--pink), var(--blue));
    border-radius: 99px;
    transition: width 0.4s ease;
  }

  .q-counter { font-size: 0.9rem; opacity: 0.7; white-space: nowrap; }

  .question-card {
    background: white;
    color: #1a1a2e;
    border-radius: 24px;
    padding: 28px 24px 24px;
    margin-bottom: 16px;
    box-shadow: 0 10px 40px rgba(0,0,0,0.3);
    animation: popIn 0.3s cubic-bezier(0.175,0.885,0.32,1.275);
  }

  @keyframes popIn {
    from { transform: scale(0.9); opacity: 0; }
    to { transform: scale(1); opacity: 1; }
  }

  .q-tag {
    display: inline-block;
    font-size: 0.72rem;
    font-weight: 800;
    text-transform: uppercase;
    letter-spacing: 0.08em;
    padding: 4px 10px;
    border-radius: 99px;
    margin-bottom: 14px;
  }

  .q-text {
    font-size: 1.1rem;
    font-weight: 700;
    line-height: 1.5;
    margin-bottom: 4px;
  }

  .hint {
    font-size: 0.85rem;
    color: #888;
    margin-top: 6px;
    font-style: italic;
  }

  .options {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 10px;
    margin-top: 10px;
  }

  .opt-btn {
    padding: 14px 12px;
    border: 2.5px solid #e0e0e0;
    border-radius: 14px;
    background: #f9f9f9;
    font-family: 'Nunito', sans-serif;
    font-size: 0.92rem;
    font-weight: 700;
    cursor: pointer;
    transition: all 0.15s;
    text-align: center;
    color: #1a1a2e;
    line-height: 1.3;
  }
  .opt-btn:hover:not(:disabled) { border-color: var(--blue); background: #e8fafa; transform: scale(1.03); }
  .opt-btn.correct { background: #d4f5e9; border-color: var(--green); color: #155724; }
  .opt-btn.wrong { background: #fde8e8; border-color: var(--red); color: #721c24; }
  .opt-btn:disabled { cursor: default; }

  .feedback-box {
    background: #f0fff8;
    border-left: 4px solid var(--green);
    border-radius: 12px;
    padding: 14px 16px;
    margin-top: 12px;
    font-size: 0.95rem;
    display: none;
    animation: fadeIn 0.3s;
    color: #1a1a2e;
  }
  .feedback-box.wrong-fb { background: #fff0f0; border-color: var(--red); }
  .feedback-box .fb-title { font-weight: 800; margin-bottom: 4px; }

  @keyframes fadeIn { from { opacity:0; transform: translateY(5px); } to { opacity:1; transform:none; } }

  .next-btn {
    width: 100%;
    padding: 16px;
    border: none;
    border-radius: 16px;
    background: linear-gradient(135deg, var(--pink), var(--purple));
    color: white;
    font-family: 'Fredoka One', cursive;
    font-size: 1.2rem;
    cursor: pointer;
    margin-top: 12px;
    display: none;
    transition: transform 0.15s, box-shadow 0.15s;
    box-shadow: 0 6px 20px rgba(167,139,250,0.4);
  }
  .next-btn:hover { transform: translateY(-2px); box-shadow: 0 10px 28px rgba(167,139,250,0.5); }

  /* ---- RESULT ---- */
  #result {
    display: none;
    text-align: center;
    max-width: 480px;
    width: 100%;
  }

  .result-card {
    background: white;
    color: #1a1a2e;
    border-radius: 28px;
    padding: 36px 28px;
    box-shadow: 0 12px 50px rgba(0,0,0,0.35);
    animation: popIn 0.4s cubic-bezier(0.175,0.885,0.32,1.275);
  }

  .result-emoji { font-size: 5rem; display: block; margin-bottom: 12px; }
  .result-title { font-family: 'Fredoka One', cursive; font-size: 2rem; margin-bottom: 6px; }
  .result-score { font-size: 3rem; font-weight: 800; color: var(--pink); margin: 10px 0; }
  .result-msg { font-size: 1rem; color: #555; margin-bottom: 20px; line-height: 1.6; }

  .result-btns { display: flex; gap: 10px; flex-wrap: wrap; justify-content: center; }
  .result-btn {
    padding: 14px 22px;
    border: none; border-radius: 14px;
    font-family: 'Fredoka One', cursive;
    font-size: 1.05rem;
    cursor: pointer;
    transition: transform 0.15s;
    color: white;
  }
  .result-btn:hover { transform: scale(1.05); }
  .btn-retry { background: linear-gradient(135deg, var(--blue), #45B7D1); }
  .btn-menu2 { background: linear-gradient(135deg, var(--pink), var(--purple)); }

  .back-btn {
    background: rgba(255,255,255,0.1);
    border: none;
    color: white;
    font-family: 'Nunito', sans-serif;
    font-weight: 700;
    font-size: 0.95rem;
    padding: 10px 18px;
    border-radius: 12px;
    cursor: pointer;
    margin-bottom: 16px;
    display: none;
    transition: background 0.15s;
    align-self: flex-start;
  }
  .back-btn:hover { background: rgba(255,255,255,0.2); }
  #game .back-btn { display: block; }

  .streak { font-size: 0.95rem; font-weight: 700; }
  .streak span { color: var(--yellow); }

  .divider { height: 1px; background: #eee; margin: 14px 0; }

  .missed-list { text-align: left; margin-top: 16px; }
  .missed-list h3 { font-size: 0.95rem; font-weight: 800; margin-bottom: 8px; color: var(--red); }
  .missed-item { font-size: 0.85rem; background: #fff0f0; border-radius: 8px; padding: 8px 12px; margin-bottom: 6px; line-height: 1.5; }
  .missed-item strong { display: block; color: #333; }
  .missed-item em { color: var(--green); font-style: normal; font-weight: 700; }
</style>
</head>
<body>

<h1>🦷 Quiz Odontogênese</h1>
<p class="subtitle">Sua prova é amanhã — bora arrasar! 💪</p>

<!-- MENU -->
<div id="menu">
  <button class="topic-btn btn-all" onclick="startQuiz('all')">
    <span class="emoji">⚡</span>
    <span>TUDO MISTURADO<br><small style="font-family:Nunito;font-size:0.75rem;font-weight:600">Todas as questões</small></span>
  </button>
  <button class="topic-btn btn-odonto" onclick="startQuiz('odonto')">
    <span class="emoji">🌱</span>
    <span>Fases da Odontogênese<br><small style="font-family:Nunito;font-size:0.75rem;font-weight:600">Lâmina → Botão → Capuz → Campânula</small></span>
  </button>
  <button class="topic-btn btn-hist" onclick="startQuiz('hist')">
    <span class="emoji">💋</span>
    <span>Histologia Oral<br><small style="font-family:Nunito;font-size:0.75rem;font-weight:600">Lábio, bochecha, gengiva</small></span>
  </button>
  <button class="topic-btn btn-glands" onclick="startQuiz('glands')">
    <span class="emoji">💧</span>
    <span>Glândulas Salivares<br><small style="font-family:Nunito;font-size:0.75rem;font-weight:600">Parótida, Submandibular, Sublingual</small></span>
  </button>
  <button class="topic-btn btn-teeth" onclick="startQuiz('teeth')">
    <span class="emoji">🦷</span>
    <span>Estruturas do Dente<br><small style="font-family:Nunito;font-size:0.75rem;font-weight:600">Dentes, gengiva, periodonto</small></span>
  </button>
</div>

<!-- GAME -->
<div id="game">
  <button class="back-btn" onclick="goMenu()">← Voltar ao menu</button>
  <div class="top-bar">
    <div class="score-box">⭐ <span id="score">0</span></div>
    <div class="progress-wrap"><div class="progress-bar" id="progress"></div></div>
    <div class="q-counter"><span id="qnum">1</span>/<span id="qtotal">10</span></div>
  </div>
  <div class="question-card" id="qcard">
    <div class="q-tag" id="qtag">Odontogênese</div>
    <div class="q-text" id="qtext"></div>
    <div class="hint" id="qhint"></div>
    <div class="options" id="opts"></div>
    <div class="feedback-box" id="feedback">
      <div class="fb-title" id="fb-title"></div>
      <div id="fb-text"></div>
    </div>
  </div>
  <button class="next-btn" id="nextBtn" onclick="nextQuestion()">Próxima →</button>
</div>

<!-- RESULT -->
<div id="result">
  <div class="result-card">
    <span class="result-emoji" id="res-emoji">🎉</span>
    <div class="result-title" id="res-title">Mandou bem!</div>
    <div class="result-score" id="res-score">8/10</div>
    <div class="result-msg" id="res-msg"></div>
    <div class="missed-list" id="missed-list"></div>
    <div class="divider"></div>
    <div class="result-btns">
      <button class="result-btn btn-retry" onclick="retryQuiz()">🔄 Tentar de novo</button>
      <button class="result-btn btn-menu2" onclick="goMenu()">📚 Outro tema</button>
    </div>
  </div>
</div>

<script>
const ALL_QUESTIONS = [
  // ============ ODONTOGÊNESE ============
  {
    cat: 'odonto', tag: '🌱 Odontogênese',
    q: 'Qual é a PRIMEIRA estrutura que aparece no começo da formação do dente?',
    hint: 'Pensa numa "lâmina" que vai dar início a tudo...',
    opts: ['Folículo dentário', 'Lâmina dental', 'Papila dentária', 'Botão dental'],
    ans: 1,
    explain: 'A lâmina dental é o pontapé inicial! É uma proliferação do epitélio oral que mergulha no ectomesênquima e vai originar todas as fases seguintes.'
  },
  {
    cat: 'odonto', tag: '🌱 Odontogênese',
    q: 'Na fase de BOTÃO, o que se vê proliferando abaixo do epitélio?',
    hint: 'Vem do mesênquima e é derivado de células da crista neural...',
    opts: ['Retículo estrelado', 'Ectomesênquima', 'Folículo piloso', 'Tecido conjuntivo frouxo'],
    ans: 1,
    explain: 'Na fase de botão, o ectomesênquima se condensa e prolifera abaixo do botão epitelial. Essa conversa entre o epitélio e o ectomesênquima é fundamental para o dente crescer!'
  },
  {
    cat: 'odonto', tag: '🌱 Odontogênese',
    q: 'A ordem correta das fases da odontogênese é:',
    hint: 'De simples para complexo — como a planta que cresce!',
    opts: [
      'Botão → Capuz → Lâmina → Campânula',
      'Lâmina → Capuz → Botão → Campânula',
      'Lâmina → Botão → Capuz → Campânula',
      'Campânula → Capuz → Botão → Lâmina'
    ],
    ans: 2,
    explain: 'Lâmina dental → Botão → Capuz → Campânula. Uma dica: LC BC (Lâmina, Capuz, Botão, Campânula — não, espera... LBCC: Lâmina → Botão → Capuz → Campânula! 😄)'
  },
  {
    cat: 'odonto', tag: '🌱 Odontogênese',
    q: 'Na fase de CAPUZ, qual estrutura fica entre o epitélio interno e externo do órgão do esmalte?',
    hint: 'O nome lembra uma rede de estrelas...',
    opts: ['Papila dentária', 'Folículo dentário', 'Retículo estrelado', 'Alça cervical'],
    ans: 2,
    explain: 'O retículo estrelado! Ele fica no meio do órgão do esmalte, como uma esponja cheia de líquido. Nas lâminas aparece mais claro, com células com formato de estrela.'
  },
  {
    cat: 'odonto', tag: '🌱 Odontogênese',
    q: 'Na fase de CAPUZ, qual estrutura vai originar a polpa dental?',
    hint: 'Fica embaixo do órgão do esmalte, é de ectomesênquima...',
    opts: ['Folículo dentário', 'Epitélio interno do esmalte', 'Papila dentária', 'Retículo estrelado'],
    ans: 2,
    explain: 'A papila dentária! É ela que vai originar a polpa e a dentina. Na lâmina, fica como um "caroço" de ectomesênquima dentro do capuz epitelial.'
  },
  {
    cat: 'odonto', tag: '🌱 Odontogênese',
    q: 'O folículo dentário (na fase de capuz) vai originar qual estrutura do dente adulto?',
    hint: 'São 3 coisas: cemento, ligamento e osso alveolar...',
    opts: [
      'Esmalte e polpa',
      'Cemento, ligamento periodontal e osso alveolar',
      'Dentina e cemento',
      'Gengiva e epitélio oral'
    ],
    ans: 1,
    explain: 'O folículo dentário é o "envelope" que envolve tudo. Ele vai originar o periodonto: cemento (reveste a raiz), ligamento periodontal e o osso alveolar.'
  },
  {
    cat: 'odonto', tag: '🌱 Odontogênese',
    q: 'Na fase de CAMPÂNULA, a alça cervical é formada por:',
    hint: 'É onde o epitélio interno encontra o externo...',
    opts: [
      'Papila dentária e retículo estrelado',
      'Epitélio interno + epitélio externo do órgão do esmalte',
      'Folículo dentário e ectomesênquima',
      'Apenas o epitélio interno do esmalte'
    ],
    ans: 1,
    explain: 'A alça cervical é a dobra onde o epitélio interno e externo do órgão do esmalte se encontram na parte inferior. Ela é importante pois vai originar a Bainha de Hertwig, que induz a formação da raiz!'
  },
  {
    cat: 'odonto', tag: '🌱 Odontogênese',
    q: 'O órgão do esmalte é formado por quantas camadas (na fase de campânula)?',
    hint: 'Pensa: externo, retículo, estrato intermediário e interno...',
    opts: ['2 camadas', '3 camadas', '4 camadas', '5 camadas'],
    ans: 2,
    explain: '4 camadas: epitélio externo, retículo estrelado, estrato intermediário e epitélio interno (ameloblastos). São os ameloblastos (do epitélio interno) que vão produzir o esmalte!'
  },

  // ============ HISTOLOGIA ORAL ============
  {
    cat: 'hist', tag: '💋 Histologia Oral',
    q: 'Qual é o tipo de epitélio da área INTERNA do lábio?',
    hint: 'É mucosa, não precisa resistir a muito atrito...',
    opts: [
      'Estratificado queratinizado',
      'Simples colunar',
      'Estratificado pavimentoso NÃO queratinizado',
      'Pseudoestratificado'
    ],
    ans: 2,
    explain: 'A área interna do lábio (mucosa) é revestida por epitélio estratificado pavimentoso NÃO queratinizado. Não precisa de queratina pois é protegida pela saliva e não sofre tanto atrito!'
  },
  {
    cat: 'hist', tag: '💋 Histologia Oral',
    q: 'Qual é o tipo de epitélio da parte EXTERNA do lábio (pele)?',
    hint: 'Fica exposta ao sol, resseca... precisa de proteção extra!',
    opts: [
      'Estratificado pavimentoso não queratinizado',
      'Estratificado pavimentoso queratinizado',
      'Simples pavimentoso',
      'Pseudoestratificado ciliado'
    ],
    ans: 1,
    explain: 'A pele externa tem epitélio estratificado queratinizado — a queratina protege contra desidratação e atrito! Também encontramos folículo piloso e glândula sebácea no tecido abaixo.'
  },
  {
    cat: 'hist', tag: '💋 Histologia Oral',
    q: 'O que você encontra na parte EXTERNA do lábio que NÃO existe na parte interna?',
    hint: 'Pense em pelo e gordura protetora...',
    opts: [
      'Tecido conjuntivo denso',
      'Epitélio estratificado',
      'Folículo piloso e glândula sebácea',
      'Retículo estrelado'
    ],
    ans: 2,
    explain: 'Na parte externa (pele) existem folículo piloso (raiz do pelo), glândula sebácea (produz sebo/gordura) e glândula sudorípara. Na parte interna (mucosa) nada disso existe!'
  },
  {
    cat: 'hist', tag: '💋 Histologia Oral',
    q: 'A bochecha INTERNA tem qual tipo de epitélio?',
    hint: 'Mesma lógica da parte interna do lábio!',
    opts: [
      'Estratificado queratinizado',
      'Estratificado pavimentoso não queratinizado',
      'Simples colunar',
      'Estratificado colunar'
    ],
    ans: 1,
    explain: 'A bochecha interna (mucosa oral) também tem epitélio estratificado pavimentoso NÃO queratinizado. Regra geral: mucosa oral = não queratinizado!'
  },
  {
    cat: 'hist', tag: '💋 Histologia Oral',
    q: 'A gengiva é formada por epitélio + tecido conjuntivo. Juntos, formam o quê?',
    hint: 'É escrito na imagem da lâmina...',
    opts: ['Periodonto', 'Mucosa oral', 'Lâmina própria', 'Submucosa'],
    ans: 1,
    explain: 'Epitélio + tecido conjuntivo = mucosa oral! A gengiva é um exemplo de mucosa mastigatória (sofre bastante pressão ao mastigar).'
  },
  {
    cat: 'hist', tag: '💋 Histologia Oral',
    q: 'A superfície DORSAL da língua tem qual classificação de epitélio?',
    hint: 'É queratinizado por causa da função... mecânica!',
    opts: [
      'Estratificado pavimentoso não queratinizado',
      'Simples colunar ciliado',
      'Estratificado pavimentoso queratinizado',
      'Pseudoestratificado'
    ],
    ans: 2,
    explain: 'A superfície dorsal da língua é estratificado pavimentoso queratinizado, pois sofre muito atrito durante a mastigação. As papilas filiformes também são bem queratinizadas!'
  },

  // ============ GLÂNDULAS SALIVARES ============
  {
    cat: 'glands', tag: '💧 Glândulas Salivares',
    q: 'Qual glândula salivar tem SOMENTE ácinos serosos?',
    hint: 'É a maior das 3, fica perto da orelha...',
    opts: ['Sublingual', 'Submandibular', 'Parótida', 'Todas as três'],
    ans: 2,
    explain: 'A PARÓTIDA tem somente ácinos serosos! Dica para lembrar: Parótida = Pura serosa. Ela produz saliva aquosa e rica em enzimas (como a amilase).'
  },
  {
    cat: 'glands', tag: '💧 Glândulas Salivares',
    q: 'Qual glândula é predominantemente MUCOSA (mais ácinos mucosos)?',
    hint: 'Fica embaixo da língua...',
    opts: ['Parótida', 'Submandibular', 'Sublingual', 'Todas iguais'],
    ans: 2,
    explain: 'A SUBLINGUAL tem predominância de ácinos MUCOSOS! Dica: Sub-LINGUAL → mucosa (saliva mais espessa, lubrifica a língua). Fica embaixo da língua.'
  },
  {
    cat: 'glands', tag: '💧 Glândulas Salivares',
    q: 'Qual glândula tem predominância de ácinos SEROSOS (mas não é exclusivamente serosa)?',
    hint: 'Fica abaixo da mandíbula, do lado...',
    opts: ['Parótida', 'Submandibular', 'Sublingual', 'Nenhuma das anteriores'],
    ans: 1,
    explain: 'A SUBMANDIBULAR tem mais ácinos serosos (mas também tem mucosos — é mista com predominância serosa). Dica: Sub-MANDIBULAR → Mista, majoritariamente Serosa.'
  },
  {
    cat: 'glands', tag: '💧 Glândulas Salivares',
    q: 'Nas lâminas histológicas, os ácinos MUCOSOS aparecem de que forma?',
    hint: 'Compara com ácino seroso que é mais rosa e escuro...',
    opts: [
      'Mais rosados e densos, com núcleo central',
      'Mais claros/esbranquiçados, com núcleo achatado na base',
      'Com cílios visíveis na borda',
      'Com grânulos escuros no citoplasma'
    ],
    ans: 1,
    explain: 'Os ácinos mucosos são mais CLAROS (o muco não cora muito com HE), com núcleo achatado na base da célula. Já os serosos são mais rosados/escuros com núcleo redondo central!'
  },
  {
    cat: 'glands', tag: '💧 Glândulas Salivares',
    q: 'Complete: Parótida = _____ / Submandibular = _____ / Sublingual = _____',
    hint: 'Pensa: Pura, Mista-serosa, Mista-mucosa',
    opts: [
      'Mucosa / Serosa / Mista',
      'Serosa pura / Mista serosa / Mista mucosa',
      'Mista / Serosa / Mucosa',
      'Mucosa / Mista / Serosa'
    ],
    ans: 1,
    explain: 'Parótida = serosa PURA. Submandibular = mista com predomínio SEROSO. Sublingual = mista com predomínio MUCOSO. Esse é um favorito de prova!'
  },

  // ============ DENTES / PERIODONTO ============
  {
    cat: 'teeth', tag: '🦷 Dentes & Periodonto',
    q: 'Quais são os 4 tecidos do periodonto (suporte do dente)?',
    hint: 'São as estruturas ao redor e de suporte do dente...',
    opts: [
      'Esmalte, dentina, cemento e polpa',
      'Osso alveolar, ligamento periodontal, cemento e gengiva',
      'Polpa, dentina, esmalte e gengiva',
      'Folículo, papila, retículo e ameloblastos'
    ],
    ans: 1,
    explain: 'O periodonto = estruturas de suporte do dente: osso alveolar (suporte ósseo), ligamento periodontal (fibras que prendem o dente), cemento (recobre a raiz) e gengiva (tecido mole).'
  },
  {
    cat: 'teeth', tag: '🦷 Dentes & Periodonto',
    q: 'Qual tecido reveste a RAIZ do dente (por fora da dentina)?',
    hint: 'Não é esmalte — o esmalte fica só na coroa...',
    opts: ['Esmalte', 'Polpa', 'Cemento', 'Gengiva'],
    ans: 2,
    explain: 'O CEMENTO reveste a raiz! Enquanto o esmalte cobre a coroa, o cemento cobre a raiz. Ele permite a ancoragem do ligamento periodontal no dente.'
  },
  {
    cat: 'teeth', tag: '🦷 Dentes & Periodonto',
    q: 'A polpa dental é histologicamente classificada como que tipo de tecido?',
    hint: 'Na lâmina aparece frouxo, com vasos e nervos...',
    opts: [
      'Tecido conjuntivo denso',
      'Tecido conjuntivo frouxo',
      'Tecido epitelial',
      'Tecido muscular liso'
    ],
    ans: 1,
    explain: 'A polpa é tecido conjuntivo FROUXO, rico em células (odontoblastos, fibroblastos), fibras colágenas, vasos sanguíneos e nervos. É por isso que dói quando tem cárie profunda!'
  },
  {
    cat: 'teeth', tag: '🦷 Dentes & Periodonto',
    q: 'O ligamento periodontal conecta qual estrutura a qual estrutura?',
    hint: 'É como uma corda prendendo o dente no osso...',
    opts: [
      'Esmalte ao cemento',
      'Cemento ao osso alveolar',
      'Dentina à gengiva',
      'Polpa ao folículo dentário'
    ],
    ans: 1,
    explain: 'O ligamento periodontal conecta o CEMENTO (raiz do dente) ao OSSO ALVEOLAR. São fibras de colágeno que funcionam como "molas" absorvendo o impacto da mastigação!'
  },
  {
    cat: 'teeth', tag: '🦷 Dentes & Periodonto',
    q: 'As PAPILAS FILIFORMES da língua têm qual característica principal?',
    hint: 'Todas apontam para o mesmo lado — têm função mecânica!',
    opts: [
      'Muitos botões gustativos na superfície',
      'Base estreita e topo alargado',
      'Muito queratinizadas, apontam na mesma direção, função mecânica',
      'Localizam-se no sulco circunvalado'
    ],
    ans: 2,
    explain: 'As papilas FILIFORMES são muito queratinizadas e todas apontam para uma mesma direção (posterior), pois têm função MECÂNICA — ajudam a movimentar o alimento. Poucas ou nenhum botão gustativo!'
  },
  {
    cat: 'teeth', tag: '🦷 Dentes & Periodonto',
    q: 'Como identificar uma papila FUNGIFORME na lâmina histológica?',
    hint: 'O nome "fungo" já ajuda a imaginar o formato...',
    opts: [
      'Base larga e topo estreito, muito queratinizada',
      'Base ESTREITA e superfície alargada (formato de cogumelo), poucos botões na superfície',
      'Localiza-se somente no sulco da língua com botões laterais',
      'Igual à filiforme, mas maior'
    ],
    ans: 1,
    explain: 'Fungiforme = formato de FUNGO/cogumelo: base mais estreita e superfície (topo) alargada. Tem poucos botões gustativos, sempre na superfície (não nas laterais). Fica entre as filiformes!'
  },
];

let currentQuestions = [];
let currentIdx = 0;
let score = 0;
let wrongAnswers = [];
let currentTopic = 'all';
let answered = false;

function shuffle(arr) {
  const a = [...arr];
  for (let i = a.length - 1; i > 0; i--) {
    const j = Math.floor(Math.random() * (i + 1));
    [a[i], a[j]] = [a[j], a[i]];
  }
  return a;
}

function startQuiz(topic) {
  currentTopic = topic;
  let pool = topic === 'all' ? ALL_QUESTIONS : ALL_QUESTIONS.filter(q => q.cat === topic);
  currentQuestions = shuffle(pool);
  currentIdx = 0;
  score = 0;
  wrongAnswers = [];
  answered = false;

  document.getElementById('menu').style.display = 'none';
  document.getElementById('result').style.display = 'none';
  document.getElementById('game').style.display = 'block';
  document.getElementById('qtotal').textContent = currentQuestions.length;

  showQuestion();
}

function showQuestion() {
  answered = false;
  const q = currentQuestions[currentIdx];
  document.getElementById('qnum').textContent = currentIdx + 1;
  document.getElementById('qtag').textContent = q.tag;
  document.getElementById('qtag').style.background = tagColor(q.cat);
  document.getElementById('qtag').style.color = '#1a1a2e';
  document.getElementById('qtext').textContent = q.q;
  document.getElementById('qhint').textContent = q.hint ? '💡 ' + q.hint : '';
  document.getElementById('feedback').style.display = 'none';
  document.getElementById('nextBtn').style.display = 'none';

  const prog = ((currentIdx) / currentQuestions.length) * 100;
  document.getElementById('progress').style.width = prog + '%';

  // Shuffle options maintaining correct answer tracking
  const optIndices = [0,1,2,3];
  const shuffledOpts = shuffle(optIndices.map(i => ({ text: q.opts[i], orig: i })));

  const opts = document.getElementById('opts');
  opts.innerHTML = '';
  shuffledOpts.forEach(opt => {
    const btn = document.createElement('button');
    btn.className = 'opt-btn';
    btn.textContent = opt.text;
    btn.dataset.orig = opt.orig;
    btn.onclick = () => selectAnswer(btn, q, shuffledOpts);
    opts.appendChild(btn);
  });

  // Re-animate card
  const card = document.getElementById('qcard');
  card.style.animation = 'none';
  card.offsetHeight;
  card.style.animation = 'popIn 0.3s cubic-bezier(0.175,0.885,0.32,1.275)';
}

function tagColor(cat) {
  const colors = { odonto: '#FFE66D', hist: '#4ECDC4', glands: '#6BCB77', teeth: '#A78BFA' };
  return colors[cat] || '#FF6B9D';
}

function selectAnswer(btn, q, shuffledOpts) {
  if (answered) return;
  answered = true;

  const allBtns = document.querySelectorAll('.opt-btn');
  allBtns.forEach(b => b.disabled = true);

  const origIdx = parseInt(btn.dataset.orig);
  const correct = origIdx === q.ans;

  allBtns.forEach(b => {
    if (parseInt(b.dataset.orig) === q.ans) b.classList.add('correct');
  });

  if (!correct) {
    btn.classList.add('wrong');
    wrongAnswers.push(q);
  } else {
    score++;
  }

  document.getElementById('score').textContent = score;

  const fb = document.getElementById('feedback');
  const fbTitle = document.getElementById('fb-title');
  const fbText = document.getElementById('fb-text');

  if (correct) {
    fb.className = 'feedback-box';
    fbTitle.textContent = '✅ Correto! Ótimo!';
  } else {
    fb.className = 'feedback-box wrong-fb';
    fbTitle.textContent = '❌ Não era essa... mas agora você sabe!';
  }
  fbText.textContent = q.explain;
  fb.style.display = 'block';

  const nextBtn = document.getElementById('nextBtn');
  nextBtn.style.display = 'block';
  if (currentIdx === currentQuestions.length - 1) {
    nextBtn.textContent = 'Ver resultado 🎯';
  } else {
    nextBtn.textContent = 'Próxima →';
  }
}

function nextQuestion() {
  currentIdx++;
  if (currentIdx >= currentQuestions.length) {
    showResult();
  } else {
    showQuestion();
  }
}

function showResult() {
  document.getElementById('game').style.display = 'none';
  document.getElementById('result').style.display = 'block';

  const total = currentQuestions.length;
  const pct = Math.round((score / total) * 100);

  document.getElementById('res-score').textContent = score + '/' + total;

  let emoji, title, msg;
  if (pct === 100) {
    emoji = '🏆'; title = 'PERFEITO!';
    msg = 'Incrível! Você acertou tudo! Tá pronta pra prova! Vai com tudo amanhã! 🎉';
  } else if (pct >= 80) {
    emoji = '🌟'; title = 'Mandou muito bem!';
    msg = 'Você domina o conteúdo! Revise rapidinho os que errou e vai estar ótima pra prova! 💪';
  } else if (pct >= 60) {
    emoji = '😊'; title = 'Tá indo bem!';
    msg = 'Mais da metade certa! Foca nos temas que errou e vai melhorar bastante. Você consegue!';
  } else if (pct >= 40) {
    emoji = '📚'; title = 'Quase lá!';
    msg = 'Ainda tem espaço pra crescer! Releia os erros abaixo com calma — eles vão fixar na memória!';
  } else {
    emoji = '💪'; title = 'Não desiste!';
    msg = 'Todo mundo começa de algum lugar! Leia as explicações dos erros — elas ensinam muito. Vai de novo!';
  }

  document.getElementById('res-emoji').textContent = emoji;
  document.getElementById('res-title').textContent = title;
  document.getElementById('res-msg').textContent = msg;

  const missedDiv = document.getElementById('missed-list');
  if (wrongAnswers.length > 0) {
    let html = '<h3>📝 Revise estes pontos:</h3>';
    wrongAnswers.forEach(q => {
      html += `<div class="missed-item"><strong>${q.q}</strong><em>✔ ${q.opts[q.ans]}</em><br><span style="color:#555;font-size:0.82rem">${q.explain}</span></div>`;
    });
    missedDiv.innerHTML = html;
  } else {
    missedDiv.innerHTML = '';
  }
}

function retryQuiz() {
  document.getElementById('result').style.display = 'none';
  startQuiz(currentTopic);
}

function goMenu() {
  document.getElementById('game').style.display = 'none';
  document.getElementById('result').style.display = 'none';
  document.getElementById('menu').style.display = 'flex';
}
</script>
</body>
</html>
