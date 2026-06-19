<!doctype html>
<html lang="pt-br">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>TecGym — Treinos para Você — Academia / Casa / Praçinha</title>
  <style>
    :root{
      --bg:#f6f8fb; --card:#ffffff; --accent:#2b7cff; --muted:#6b7280;
      --success:#16a34a;
      font-family: Inter, system-ui, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    body{margin:0;background:var(--bg);color:#0f172a;line-height:1.4}
    header{background:linear-gradient(90deg,#fff 0,#eef6ff);padding:20px 16px;display:flex;align-items:center;justify-content:space-between;box-shadow:0 1px 0 rgba(15,23,42,0.04)}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:44px;height:44px;border-radius:8px;background:var(--accent);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700}
    .container{max-width:1100px;margin:24px auto;padding:0 16px}
    .hero{display:grid;grid-template-columns:1fr 380px;gap:20px;align-items:center}
    .card{background:var(--card);border-radius:12px;padding:18px;box-shadow:0 6px 18px rgba(16,24,40,0.06)}
    h1{margin:0 0 8px;font-size:20px}
    p.lead{margin:0;color:var(--muted)}
    .options{display:flex;gap:10px;margin-top:14px}
    .opt{padding:10px 12px;border-radius:10px;border:1px solid transparent;cursor:pointer;background:#f8fafc}
    .opt.active{border-color:rgba(43,124,255,0.18);box-shadow:0 6px 14px rgba(43,124,255,0.06);background:linear-gradient(180deg,#fff,#f1f8ff)}
    .form-row{display:flex;gap:10px;margin-top:12px}
    .select{flex:1;padding:10px;border-radius:8px;border:1px solid #e6edf7;background:#fff}
    .btn{background:var(--accent);color:#fff;padding:10px 14px;border-radius:8px;border:none;cursor:pointer}
    .note{font-size:13px;color:var(--muted);margin-top:8px}
    .grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:14px;margin-top:18px}
    /* Estilos atualizados para cartões de profissionais */
    .trainer{
      display:flex;
      gap:14px;
      align-items:center;
      background:linear-gradient(180deg,#ffffff,#fbfdff);
      padding:14px;
      border-radius:12px;
      box-shadow:0 8px 20px rgba(16,24,40,0.04);
      transition:transform .18s ease,box-shadow .18s ease;
      border:1px solid rgba(16,24,40,0.03);
    }
    .trainer:hover{
      transform:translateY(-6px);
      box-shadow:0 18px 36px rgba(16,24,40,0.08);
    }
    .avatar{width:64px;height:64px;border-radius:12px;background:linear-gradient(135deg,#eef2ff,#dbe9ff);color:var(--accent);display:flex;align-items:center;justify-content:center;font-weight:700;font-size:20px}
    .meta{flex:1;min-width:0}
    .meta .name{display:flex;align-items:center;gap:8px;justify-content:space-between}
    .meta .name .title{font-weight:700;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
    .price{background:var(--accent);color:#fff;padding:6px 10px;border-radius:999px;font-weight:700;font-size:12px}
    .meta .spec{color:var(--muted);font-size:13px;margin-top:6px}
    .trainer-actions{margin-top:10px;display:flex;gap:8px;align-items:center}
    .btn.small{padding:8px 10px;font-size:13px;border-radius:8px}
    .btn.outline{background:#fff;color:var(--accent);border:1px solid rgba(43,124,255,0.14)}
    .pill{display:inline-block;padding:6px 8px;border-radius:999px;background:#f1f5f9;color:var(--muted);font-size:12px}
    .free-badge{display:inline-block;padding:4px 8px;border-radius:8px;background:#ecfdf5;color:#065f46;font-weight:700;font-size:12px;margin-left:8px}
    footer{margin:36px 0 64px;text-align:center;color:var(--muted)}
    @media (max-width:900px){
      .hero{grid-template-columns:1fr}
      .card{padding:14px}
    }

    /* Modal questionário */
    .overlay{position:fixed;inset:0;background:rgba(5,10,20,0.45);display:none;align-items:center;justify-content:center;padding:20px;z-index:60}
    .modal{background:#fff;border-radius:12px;padding:18px;max-width:640px;width:100%;box-shadow:0 20px 40px rgba(8,15,30,0.25)}
    .modal h3{margin:0 0 8px}
    .form-group{margin-top:10px}
    .radio-row{display:flex;gap:8px;flex-wrap:wrap;margin-top:6px}
    .radio{padding:8px 10px;border-radius:8px;border:1px solid #e6edf7;background:#fafcff;cursor:pointer}
    .modal-actions{display:flex;gap:8px;justify-content:flex-end;margin-top:12px}
  </style>
</head>
<body>
  <header>
    <div class="brand">
      <div class="logo">TG</div>
      <div>
        <div style="font-weight:700">TecGym</div>
        <div style="font-size:12px;color:var(--muted)">Planos para academia, casa ou praçinha</div>
      </div>
    </div>
    <nav aria-label="Navegação">
      <button class="btn" id="exploreBtn">Explorar planos</button>
    </nav>
  </header>

  <main class="container">
    <section class="hero">
      <div class="card">
        <h1>Como você prefere treinar?</h1>
        <p class="lead">Escolha onde você treina e receba planos e profissionais recomendados.</p>

        <div class="options" role="tablist" aria-label="Local de treino">
          <button class="opt active" data-place="academia" role="tab" aria-selected="true">Academia</button>
          <button class="opt" data-place="casa" role="tab" aria-selected="false">Casa</button>
          <button class="opt" data-place="praca" role="tab" aria-selected="false">Praçinha</button>
        </div>

        <div class="form-row" style="margin-top:14px">
          <select id="goal" class="select" aria-label="Objetivo">
            <option value="hipertrofia">Hipertrofia</option>
            <option value="emagrecimento">Emagrecimento</option>
            <option value="resistencia">Resistência / Cardio</option>
            <option value="flexibilidade">Flexibilidade / Mobilidade</option>
          </select>
          <button class="btn" id="findBtn">Encontrar plano</button>
        </div>

        <div id="summary" class="note"></div>
        <div class="note">Profissionais: gratuitos <span class="free-badge" aria-hidden="true">GRÁTIS</span> — Serviço do site é pago</div>
      </div>

      <aside class="card" aria-labelledby="prof-title">
        <h2 id="prof-title" style="margin-top:0">Profissionais recomendados</h2>
        <p style="margin:6px 0 12px;color:var(--muted)">Conecte-se com profissionais especializados no seu contexto.</p>
        <div id="trainersList" class="grid" aria-live="polite"></div>
      </aside>
    </section>

    <section style="margin-top:22px">
      <div class="card">
        <h2 style="margin-top:0">Exemplo de treino personalizado</h2>
        <p class="lead">O plano abaixo é um exemplo gerado a partir das suas escolhas. Personalize com seu profissional.</p>
        <div id="planArea" style="margin-top:12px"></div>
      </div>
    </section>
  </main>

  <!-- Modal Questionário para Hipertrofia -->
  <div id="overlay" class="overlay" role="dialog" aria-modal="true" aria-hidden="true">
    <div class="modal" role="document" aria-labelledby="qTitle">
      <h3 id="qTitle">Questionário rápido — Hipertrofia</h3>
      <p style="color:var(--muted);margin:6px 0 0">Responda perguntas básicas para selecionar exercícios mais adequados.</p>

      <div class="form-group">
        <label class="form-label">Experiência com treino</label>
        <div class="radio-row" id="expRow">
          <div class="radio"><input type="radio" name="exp" value="iniciante" id="exp1" checked /> <label for="exp1">Iniciante</label></div>
          <div class="radio"><input type="radio" name="exp" value="intermediario" id="exp2" /> <label for="exp2">Intermediário</label></div>
          <div class="radio"><input type="radio" name="exp" value="avancado" id="exp3" /> <label for="exp3">Avançado</label></div>
        </div>
      </div>

      <div class="form-group">
        <label class="form-label">Frequência semanal disponível</label>
        <div class="radio-row" id="freqRow">
          <div class="radio"><input type="radio" name="freq" value="2" id="f2" /> <label for="f2">2x</label></div>
          <div class="radio"><input type="radio" name="freq" value="3" id="f3" checked /> <label for="f3">3x</label></div>
          <div class="radio"><input type="radio" name="freq" value="4" id="f4" /> <label for="f4">4x</label></div>
          <div class="radio"><input type="radio" name="freq" value="5" id="f5" /> <label for="f5">5x</label></div>
        </div>
      </div>

      <div class="form-group">
        <label class="form-label">Foco principal</label>
        <div class="radio-row" id="focusRow">
          <div class="radio"><input type="radio" name="focus" value="full" id="full" checked /> <label for="full">Full body</label></div>
          <div class="radio"><input type="radio" name="focus" value="upper" id="upper" /> <label for="upper">Upper</label></div>
          <div class="radio"><input type="radio" name="focus" value="lower" id="lower" /> <label for="lower">Lower</label></div>
          <div class="radio"><input type="radio" name="focus" value="pushpull" id="pp" /> <label for="pp">Push/Pull</label></div>
        </div>
      </div>

      <!-- Novo: pergunta visível apenas quando local = casa -->
      <div class="form-group" id="homeEquipGroup" style="display:none">
        <label class="form-label">Equipamento em casa</label>
        <div class="radio-row">
          <div class="radio"><input type="radio" name="homeEquip" value="nenhum" id="eq_none" checked /> <label for="eq_none">Nenhum (apenas peso corporal)</label></div>
          <div class="radio"><input type="radio" name="homeEquip" value="halteres" id="eq_halters" /> <label for="eq_halters">Halteres / Kettlebell / Anilhas</label></div>
          <div class="radio"><input type="radio" name="homeEquip" value="barra" id="eq_barra" /> <label for="eq_barra">Barra / Estação / Barra fixa</label></div>
        </div>
      </div>

      <div class="form-group">
        <label class="form-label">Alguma lesão ou limitação?</label>
        <input id="injury" type="text" placeholder="Ex: lombar, ombro, nenhuma" style="width:100%;padding:8px;border-radius:8px;border:1px solid #e6edf7;margin-top:6px" />
      </div>

      <div class="modal-actions">
        <button class="btn outline" id="cancelQ">Cancelar</button>
        <button class="btn" id="submitQ">Gerar plano</button>
      </div>
    </div>
  </div>

  <footer>
    <div class="container">
      <small>© 2026 Tecgym — Suporte por email: <a href="mailto:suporte@tecgym.example">suporte@tecgym.example</a></small>
    </div>
  </footer>

  <script>
    // Dados de exemplo (no app real viria do servidor)
    const PROFESSIONALS = [
      { id:1, name:'Mariana Lopes', place:'academia', specialty:'Musculação / Hipertrofia', price:'Gratuito', contact:'mariana@ex.com' },
      { id:2, name:'Rafael Souza', place:'academia', specialty:'Condicionamento', price:'Gratuito', contact:'rafael@ex.com' },
      { id:3, name:'Ana Medeiros', place:'casa', specialty:'Treino sem equipamento / Reabilitação', price:'Gratuito', contact:'ana@ex.com' },
      { id:4, name:'Lucas Pereira', place:'praca', specialty:'Treino funcional ao ar livre', price:'Gratuito', contact:'lucas@ex.com' },
      { id:5, name:'Camila Rocha', place:'casa', specialty:'HIIT / Emagrecimento', price:'Gratuito', contact:'camila@ex.com' }
    ];

    const placeButtons = document.querySelectorAll('.opt');
    const trainersList = document.getElementById('trainersList');
    const findBtn = document.getElementById('findBtn');
    const goalSelect = document.getElementById('goal');
    const summary = document.getElementById('summary');
    const planArea = document.getElementById('planArea');

    // modal elements
    const overlay = document.getElementById('overlay');
    const submitQ = document.getElementById('submitQ');
    const cancelQ = document.getElementById('cancelQ');

    let currentPlace = 'academia';

    function renderProfessionals(place, goal) {
      trainersList.innerHTML = '';
      const filtered = PROFESSIONALS.filter(p => p.place === place);
      if (filtered.length === 0) {
        trainersList.innerHTML = '<div style="color:var(--muted)">Nenhum profissional encontrado para este local.</div>';
        return;
      }
      filtered.forEach(p => {
        const card = document.createElement('div');
        card.className = 'trainer';
        card.innerHTML = `
          <div class="avatar" aria-hidden="true">${p.name.split(' ').map(n=>n[0]).slice(0,2).join('')}</div>
          <div class="meta">
            <div class="name">
              <div class="title">${p.name}</div>
              <div style="display:flex;align-items:center">
                <div class="price">${p.price}</div>
                <div class="free-badge" title="Profissional gratuito">GRÁTIS</div>
              </div>
            </div>
            <div class="spec">${p.specialty}</div>
            <div class="trainer-actions">
              <button class="btn small" data-id="${p.id}" title="Agendar / Contatar">Agendar</button>
              <button class="btn outline small" data-sample="${p.id}" title="Ver plano exemplo">Ver plano</button>
              <button class="pill" style="margin-left:auto" title="Ver contacto">${p.place.toUpperCase()}</button>
            </div>
          </div>
        `;
        trainersList.appendChild(card);
      });
      // attach listeners
      trainersList.querySelectorAll('[data-id]').forEach(b=>{
        b.addEventListener('click',(e)=>{
          const prof = PROFESSIONALS.find(x=>x.id==b.dataset.id);
          window.location.href = `mailto:${prof.contact}?subject=Agendamento%20-%20${encodeURIComponent(prof.name)}`;
        });
      });
      trainersList.querySelectorAll('[data-sample]').forEach(b=>{
        b.addEventListener('click',(e)=>{
          const prof = PROFESSIONALS.find(x=>x.id==b.dataset.sample);
          // abrir questionário se objetivo for hipertrofia, senão gerar plano direto
          if (goalSelect.value === 'hipertrofia') {
            openQuestionnaire(currentPlace, (answers)=> generatePlan(currentPlace, 'hipertrofia', prof, answers));
          } else {
            generatePlan(currentPlace, goalSelect.value, prof);
          }
        });
      });
    }

    // Open modal and optionally accept a callback to run after submit
    let onQuestionSubmit = null;
    // agora aceita place para mostrar pergunta de equipamento apenas para 'casa'
    function openQuestionnaire(place, cb=null) {
      onQuestionSubmit = cb;
      // mostrar campo de equipamento apenas se for casa
      const homeEquipGroup = document.getElementById('homeEquipGroup');
      if (homeEquipGroup) {
        if (place === 'casa') homeEquipGroup.style.display = 'block';
        else homeEquipGroup.style.display = 'none';
      }
      overlay.style.display = 'flex';
      overlay.setAttribute('aria-hidden','false');
    }
    function closeQuestionnaire() {
      overlay.style.display = 'none';
      overlay.setAttribute('aria-hidden','true');
      onQuestionSubmit = null;
    }

    function getQuestionAnswers() {
      const exp = document.querySelector('input[name="exp"]:checked')?.value || 'iniciante';
      const freq = document.querySelector('input[name="freq"]:checked')?.value || '3';
      const focus = document.querySelector('input[name="focus"]:checked')?.value || 'full';
      const injury = document.getElementById('injury').value.trim() || 'nenhuma';
      // equipamento (apenas relevante se modal abriu para 'casa')
      const equipment = document.querySelector('input[name="homeEquip"]:checked')?.value || 'nenhum';
      return { exp, freq: Number(freq), focus, injury, equipment };
    }

    submitQ.addEventListener('click',()=>{
      const answers = getQuestionAnswers();
      closeQuestionnaire();
      // chamar função registrada, se houver
      if (typeof onQuestionSubmit === 'function') {
        onQuestionSubmit(answers);
      } else {
        // padrão: gerar plano hipertrofia com respostas
        generatePlan(currentPlace, 'hipertrofia', null, answers);
      }
    });
    cancelQ.addEventListener('click',()=>{
      closeQuestionnaire();
    });

    function generatePlan(place, goal, prof=null, q=null) {
      // q = questionário (apenas para hipertrofia)
      const title = prof ? `Plano sugerido por ${prof.name}` : 'Plano sugerido';
      const noteQ = q ? `<div style="color:var(--muted);font-size:13px;margin-top:6px">Resumo do questionário: experiência ${q.exp}, ${q.freq}x/semana, foco ${q.focus}, limitação: ${q.injury}${q.equipment ? ', equipamento: ' + q.equipment : ''}</div>` : '';

      const workouts = {
        hipertrofia: {
          academia: {
            iniciante: [
              { section: 'Pernas', items: ['Agachamento guiado / Smith 3x8-10', 'Leg Press 3x10-12', 'Romanian Deadlift leve 3x8-10', 'Cadeira extensora 3x12'] },
              { section: 'Peito', items: ['Supino reto máquina / barra 3x8-10', 'Supino inclinado com halteres 3x8-10', 'Flexão incl. 2x até falha moderada'] },
              { section: 'Costas', items: ['Puxada frontal 3x8-10', 'Remada sentada 3x8-10', 'Pullover / face pull 2-3x12'] },
              { section: 'Ombros/Braços', items: ['Desenvolvimento com halteres 3x8-10', 'Elevação lateral 3x12', 'Rosca bíceps 3x10'] },
              { section: 'Core', items: ['Prancha 3x30-45s', 'Hiperextensão leve 2x12'] }
            ],
            intermediario: [
              { section: 'Pernas (composto)', items: ['Back Squat 4x6-8', 'Romanian Deadlift 3x6-8', 'Leg Press 3x8-10', 'Walking Lunges 3x10/leg'] },
              { section: 'Peito', items: ['Supino reto 4x6-8', 'Supino inclinado 3x8', 'Mergulho (paralelas) assistido 3x8-10'] },
              { section: 'Costas', items: ['Remada curvada 4x6-8', 'Pull-ups / Puxada 3x6-8', 'Remada unilateral 3x8-10'] },
              { section: 'Ombros/Braços', items: ['Press militar 3x6-8', 'Elevação lateral 3x10-12', 'Rosca direta 3x8-10', 'Tríceps pulley 3x10'] },
              { section: 'Core', items: ['Prancha com variação 3x45s', 'Hanging knee raises 3x10-12'] }
            ],
            avancado: [
              { section: 'Pernas', items: ['Back Squat pesado 5x5', 'Deadlift ou Variante pesada 4x4-6', 'Hip Thrust 4x6-8', 'Panturrilha 4x10-15'] },
              { section: 'Peito', items: ['Supino pesado 5x5', 'Supino inclinado com barra/halter 4x6-8', 'Mergulho com lastro 3x6-8'] },
              { section: 'Costas', items: ['Remada pesada 5x5', 'Pull-ups ponderado 4x6', 'Remada T-bar 4x6-8'] },
              { section: 'Ombros/Braços', items: ['Press militar pesado 4x5', 'Elev lat/face pull 3x10', 'Rosca pesada 4x6-8'] },
              { section: 'Core', items: ['Progressão de prancha/anti-extensão 3-4x', 'Weighted carries 2-3x 30-60s'] }
            ]
          },
          casa: {
            iniciante: [
              { section: 'Pernas', items: ['Agachamento goblet com halter 3x8-12', 'Avanço (split) 3x8-10 por perna', 'Ponte de glúteo 3x12', 'Agachamento corporal 3x12'] },
              { section: 'Peito', items: ['Flexões inclinadas 3x8-12', 'Flexões padrão 2x até moderada falha'] },
              { section: 'Costas', items: ['Remada unilateral com halter 3x8-12', 'Australian row (toalha/mesa baixa) 3xMax', 'Pull-up na barra (se tiver) 3xMax'] },
              { section: 'Ombros/Braços', items: ['Press com halteres 3x8-10', 'Elevação lateral 3x12', 'Rosca martelo 3x10', 'Dips em cadeira 3x8-12'] },
              { section: 'Core', items: ['Prancha 3x30-45s', 'Deadbug 3x10/side'] }
            ],
            intermediario: [
              { section: 'Pernas/Força', items: ['Agachamento com halter pesado 4x6-10', 'Stiff unilateral 3x8-10', 'Step-ups com peso 3x8-10', 'Agachamento unilateral corporal/progredido 3x6-10'] },
              { section: 'Peito/Costas', items: ['Flexões com lastro ou progressões 4x6-10', 'Remada com halter pesado 4x6-10', 'Pull-ups / barra 3x6-10'] },
              { section: 'Ombros/Braços', items: ['Press com halteres 3x6-8', 'Elevação lateral 3x10-12', 'Dips 3x8-12'] },
              { section: 'Core', items: ['Prancha com peso/tempo 3x45-60s', 'Elevação de pernas 3x10-15'] }
            ],
            avancado: [
              { section: 'Força/Hypertrophy', items: ['Agachamento com carga (belt/halter) 5x5', 'Romanian deadlift unilateral 4x6-8', 'Flexões com lastro / progressão 4x6-8', 'Remada unilateral pesada 4x6-8'] }
            ]
          },
          praca: {
            iniciante: [
              { section: 'Pernas/Cardio', items: ['Step-ups em banco 3x10-12', 'Agachamento corporal 3x12', 'Corrida leve 8-10min'] },
              { section: 'Peito/Costas', items: ['Flexões em banco 3x8-12', 'Australian rows em barra baixa 3xMax'] },
              { section: 'Core', items: ['Prancha 3x30s', 'Russian twist sem peso 3x15'] }
            ],
            intermediario: [
              { section: 'Pernas/Explosão', items: ['Step-ups pesados 4x8-10', 'Saltos pliométricos em banco 3x6-8', 'Sprints curtos 6x30s'] },
              { section: 'Peito/Costas', items: ['Flexões com elevação de pés 4x6-10', 'Pull-ups / barras 3x6-10'] },
              { section: 'Core', items: ['Hanging knee raises 3x10-15', 'Plank variations 3x45s'] }
            ],
            avancado: [
              { section: 'Força/Explosão', items: ['Pistol assistido/progredido 5x5', 'Pull-ups ponderado 4x6', 'Sprints e pliometria 4-6 sets'] }
            ]
          }
        },
        emagrecimento: [
          'Circuito 20min: polichinelos, agachamentos, mountain climbers',
          'HIIT 15min: 30s esforço / 30s descanso',
          '30-40 min caminhada rápida'
        ],
        resistencia: [
          'Corrida leve 30-40min ou bike',
          'Intervalado: 6x1min forte / 2min leve',
          'Circuito de resistência 3x'
        ],
        flexibilidade: [
          'Sequência de mobilidade 15-20min (yoga flow)',
          'Alongamentos dinâmicos e estáticos 3x por grupo muscular',
          'Treino de core leve 3x12'
        ]
      };

      // Helpers
      function shuffle(arr){ return arr.slice().sort(()=>Math.random()-0.5); }
      function take(arr,n){ return arr.slice(0,n); }

      // Detecta tipo de equipamento requerido por um exercício (heurística)
      function detectEquipTag(name){
        const s = name.toLowerCase();
        if (/(halter|halteres|dumbbell|kettlebell|anilha|anilhas|com carga|com halter|com halteres|lastro|peso)/i.test(s)) return 'dumbbell';
        if (/(barra fixa|barra|pull-ups?|chin-ups?|pullups|chinups|barra\/estação|barra fixa)/i.test(s)) return 'bar';
        // movimentos tipicamente sem equipamento ou que têm versão sem peso
        if (/(flex(ã|a)o|flexoes|flexões|prancha|deadbug|agachamento corporal|corrida|sprint|step-ups?|pistol|saltos|plyo|burpee|bodyweight|russian twist)/i.test(s)) return 'body';
        // remada/unilateral/pull-up podem ser com peso ou corpo; tratar como body para não excluir soluções sem equipamento
        if (/(remada|australian|pull|remada unilateral|australian row)/i.test(s)) {
          // se contém 'com halter' já foi classificado; sem isso, permitir como body
          return 'body';
        }
        // fallback: marcar como 'mixed' (permitir se usuário tem equipamento)
        return 'mixed';
      }

      if (goal === 'hipertrofia' && q) {
        const expKey = q.exp || 'iniciante';
        const placeMap = workouts.hipertrofia[place] || workouts.hipertrofia['academia'];
        const baseBlocks = placeMap[expKey] || placeMap['iniciante'] || placeMap;

        // construir pool com tag de equipamento
        const pool = [];
        baseBlocks.forEach(b=>{
          b.items.forEach(it=>{
            pool.push({ section: b.section, name: it, tag: detectEquipTag(it) });
          });
        });

        // definir equipamentos permitidos para casa conforme resposta
        let allowedTags = ['body','mixed','dumbbell','bar'];
        if (place === 'casa') {
          if (q.equipment === 'nenhum') allowedTags = ['body'];
          else if (q.equipment === 'halteres') allowedTags = ['body','dumbbell','mixed'];
          else if (q.equipment === 'barra') allowedTags = ['body','bar','mixed'];
        }

        function buildSession(focus){
          const n = 5 + Math.floor(Math.random()*3); // 5-7
          let prioritized = [];
          const s = focus.toLowerCase();
          if (s === 'upper') {
            prioritized = pool.filter(e=>/peito|costas|ombros|braços/i.test(e.section));
          } else if (s === 'lower') {
            prioritized = pool.filter(e=>/pernas|glúteo|panturrilha|stiff|agachamento|step/i.test(e.section));
          } else if (s === 'pushpull') {
            prioritized = pool.filter(e=>/peito|ombros|tríceps|press|supino/i.test(e.section))
                           .concat(pool.filter(e=>/costas|bíceps|remada|pull|pulldown/i.test(e.section)));
          } else { // full
            prioritized = pool.slice();
          }
          // aplicar filtro por equipamento permitido
          const filteredByEquip = prioritized.concat(pool).filter(e=> allowedTags.includes(e.tag));
          // remover duplicados mantendo ordem
          const unique = Array.from(new Map(filteredByEquip.map(p=>[p.name,p])).values());
          return take(shuffle(unique).map(u=>u.name), n);
        }

        const sessions = [];
        const freq = Math.max(1, Number(q.freq) || 1);
        if ((q.focus === 'upper' || q.focus === 'lower') && freq >= 2) {
          for (let i=0;i<freq;i++){
            const focus = (i%2===0) ? q.focus : (q.focus==='upper' ? 'lower' : 'upper');
            sessions.push({ section: `${focus.toUpperCase()} - Sessão ${i+1}`, items: buildSession(focus) });
          }
        } else if (q.focus === 'pushpull' && freq>=2) {
          for (let i=0;i<freq;i++){
            const label = (i%2===0) ? 'Push' : 'Pull';
            sessions.push({ section: `Push/Pull - ${label} Sessão ${i+1}`, items: buildSession('pushpull') });
          }
        } else {
          for (let i=0;i<freq;i++){
            sessions.push({ section: `Full Body - Sessão ${i+1}`, items: buildSession('full') });
          }
        }

        // render plano
        planArea.innerHTML = `
          <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
            <div><strong>${title}</strong><div style="color:var(--muted);font-size:13px">${place.toUpperCase()} • ${goal}</div>${noteQ}</div>
            ${prof ? `<div style="text-align:right"><div style="font-size:13px;color:var(--muted)">${prof.specialty}</div><div style="margin-top:6px"><a href="mailto:${prof.contact}" style="color:var(--accent);text-decoration:none">Contactar</a></div></div>` : ''}
          </div>
          <div style="margin-top:12px">
            ${sessions.map(block => `
              <div style="margin-bottom:12px">
                <div style="font-weight:700;margin-bottom:6px">${block.section}</div>
                <ul style="margin:0;padding-left:18px">
                  ${block.items.map(i=>`<li style="margin-bottom:6px">${i}</li>`).join('')}
                </ul>
              </div>
            `).join('')}
          </div>
          <div style="margin-top:10px;display:flex;gap:8px;justify-content:flex-end">
            <button class="btn" id="savePlan">Salvar plano (JSON)</button>
            <button class="btn" id="startNow" style="background:var(--success)">Começar agora</button>
          </div>
        `;

        document.getElementById('savePlan').addEventListener('click',()=>{
          const payload = { place, goal, prof: prof ? {name:prof.name,contact:prof.contact}:null, plan: sessions, questionnaire: q || null };
          const blob = new Blob([JSON.stringify(payload,null,2)], {type:'application/json'});
          const url = URL.createObjectURL(blob);
          const a = document.createElement('a');
          a.href = url; a.download = 'plano-treino.json'; a.click();
          URL.revokeObjectURL(url);
        });
        document.getElementById('startNow').addEventListener('click',()=>{
          alert('Boa sessão! Siga o plano com atenção e consulte um profissional quando necessário.');
        });

        return;
      }

      // Fallback — comportamento anterior
      let chosen;
      if (goal === 'hipertrofia') {
        const expKey = (q && q.exp) ? q.exp : 'iniciante';
        const placeMap = workouts.hipertrofia[place] || workouts.hipertrofia['academia'];
        chosen = placeMap[expKey] || placeMap['iniciante'] || placeMap;
      } else {
        chosen = workouts[goal] || workouts['emagrecimento'];
      }

      if (goal === 'hipertrofia') {
        planArea.innerHTML = `
          <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
            <div><strong>${title}</strong><div style="color:var(--muted);font-size:13px">${place.toUpperCase()} • ${goal}</div>${noteQ}</div>
            ${prof ? `<div style="text-align:right"><div style="font-size:13px;color:var(--muted)">${prof.specialty}</div><div style="margin-top:6px"><a href="mailto:${prof.contact}" style="color:var(--accent);text-decoration:none">Contactar</a></div></div>` : ''}
          </div>
          <div style="margin-top:12px">
            ${chosen.map(block => `
              <div style="margin-bottom:12px">
                <div style="font-weight:700;margin-bottom:6px">${block.section}</div>
                <ul style="margin:0;padding-left:18px">
                  ${block.items.map(i=>`<li style="margin-bottom:6px">${i}</li>`).join('')}
                </ul>
              </div>
            `).join('')}
          </div>
          <div style="margin-top:10px;display:flex;gap:8px;justify-content:flex-end">
            <button class="btn" id="savePlan">Salvar plano (JSON)</button>
            <button class="btn" id="startNow" style="background:var(--success)">Começar agora</button>
          </div>
        `;
      } else {
        planArea.innerHTML = `
          <div style="display:flex;justify-content:space-between;align-items:center">
            <div><strong>${title}</strong><div style="color:var(--muted);font-size:13px">${place.toUpperCase()} • ${goal}</div></div>
            ${prof ? `<div style="text-align:right"><div style="font-size:13px;color:var(--muted)">${prof.specialty}</div><div style="margin-top:6px"><a href="mailto:${prof.contact}" style="color:var(--accent);text-decoration:none">Contactar</a></div></div>` : ''}
          </div>
          <ul style="margin-top:12px;padding-left:18px">
            ${chosen.map(s=>`<li style="margin-bottom:8px">${s}</li>`).join('')}
          </ul>
          <div style="margin-top:10px;display:flex;gap:8px;justify-content:flex-end">
            <button class="btn" id="savePlan">Salvar plano (JSON)</button>
            <button class="btn" id="startNow" style="background:var(--success)">Começar agora</button>
          </div>
        `;
      }

      document.getElementById('savePlan').addEventListener('click',()=>{
        const payload = { place, goal, prof: prof ? {name:prof.name,contact:prof.contact}:null, plan: chosen, questionnaire: q || null };
        const blob = new Blob([JSON.stringify(payload,null,2)], {type:'application/json'});
        const url = URL.createObjectURL(blob);
        const a = document.createElement('a');
        a.href = url; a.download = 'plano-treino.json'; a.click();
        URL.revokeObjectURL(url);
      });
      document.getElementById('startNow').addEventListener('click',()=>{
        alert('Boa sessão! Siga o plano com atenção e consulte um profissional quando necessário.');
      });
    }

    // Interações de UI
    placeButtons.forEach(b=>{
      b.addEventListener('click',()=>{
        placeButtons.forEach(x=>x.classList.remove('active'));
        b.classList.add('active');
        placeButtons.forEach(x=>x.setAttribute('aria-selected','false'));
        b.setAttribute('aria-selected','true');
        currentPlace = b.dataset.place;
        summary.textContent = '';
        renderProfessionals(currentPlace, goalSelect.value);
        planArea.innerHTML = '';
      });
    });

    findBtn.addEventListener('click',()=>{
      const goal = goalSelect.value;
      summary.textContent = `Local: ${currentPlace} • Objetivo: ${goal}`;
      if (goal === 'hipertrofia') {
        // abrir questionário antes de gerar (passa currentPlace para mostrar equipamento quando casa)
        openQuestionnaire(currentPlace, (answers)=> {
          generatePlan(currentPlace, 'hipertrofia', null, answers);
          renderProfessionals(currentPlace, goal);
          setTimeout(()=>document.getElementById('planArea').scrollIntoView({behavior:'smooth',block:'center'}),120);
        });
      } else {
        generatePlan(currentPlace, goal);
        renderProfessionals(currentPlace, goal);
        setTimeout(()=>document.getElementById('planArea').scrollIntoView({behavior:'smooth',block:'center'}),120);
      }
    });

    // inicializa
    renderProfessionals(currentPlace, goalSelect.value);
  </script>
</body>
</html>
