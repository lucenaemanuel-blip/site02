<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Raízes Indígenas Bacabalenses</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body{
      background: linear-gradient(to bottom, #1f3b2d, #3f6b4f);
      color:white;
      overflow-x:hidden;
    }

    header{
      height:100vh;
      display:flex;
      flex-direction:column;
      justify-content:center;
      align-items:center;
      text-align:center;
      padding:20px;
      background:
        linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
        url('https://images.unsplash.com/photo-1511497584788-876760111969?auto=format&fit=crop&w=1400&q=80');
      background-size:cover;
      background-position:center;
    }

    header h1{
      font-size:4rem;
      margin-bottom:20px;
      animation: fadeDown 1.5s ease;
    }

    header p{
      font-size:1.4rem;
      max-width:900px;
      line-height:1.6;
      animation: fadeUp 1.5s ease;
    }

    section{
      padding:80px 10%;
    }

    .card{
      background: rgba(255,255,255,0.08);
      border-radius:20px;
      padding:30px;
      margin-bottom:40px;
      backdrop-filter: blur(8px);
      transition:0.4s;
      border:1px solid rgba(255,255,255,0.15);
    }

    .card:hover{
      transform:translateY(-8px);
      box-shadow:0 10px 25px rgba(0,0,0,0.4);
    }

    h2{
      color:#ffd27f;
      margin-bottom:20px;
      font-size:2rem;
    }

    p{
      line-height:1.8;
      font-size:1.1rem;
    }

    .timeline{
      position:relative;
      margin-top:40px;
    }

    .timeline::before{
      content:"";
      position:absolute;
      left:50%;
      width:4px;
      height:100%;
      background:#ffd27f;
      transform:translateX(-50%);
    }

    .timeline-item{
      width:50%;
      padding:20px 40px;
      position:relative;
    }

    .timeline-item:nth-child(odd){
      left:0;
      text-align:right;
    }

    .timeline-item:nth-child(even){
      left:50%;
    }

    .timeline-item::before{
      content:"";
      position:absolute;
      top:25px;
      width:20px;
      height:20px;
      border-radius:50%;
      background:#ffd27f;
    }

    .timeline-item:nth-child(odd)::before{
      right:-10px;
    }

    .timeline-item:nth-child(even)::before{
      left:-10px;
    }

    footer{
      text-align:center;
      padding:30px;
      background:#13241b;
      color:#ccc;
    }

    @keyframes fadeDown{
      from{
        opacity:0;
        transform:translateY(-40px);
      }
      to{
        opacity:1;
        transform:translateY(0);
      }
    }

    @keyframes fadeUp{
      from{
        opacity:0;
        transform:translateY(40px);
      }
      to{
        opacity:1;
        transform:translateY(0);
      }
    }

    @media(max-width:900px){

      header h1{
        font-size:2.5rem;
      }

      .timeline::before{
        left:20px;
      }

      .timeline-item{
        width:100%;
        padding-left:60px;
        padding-right:20px;
        text-align:left !important;
        left:0 !important;
      }

      .timeline-item::before{
        left:10px !important;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>Raízes Indígenas Bacabalenses</h1>
    <p>
      Entre memórias e lembranças, a presença indígena em Bacabal representa
      resistência, cultura, identidade e história. Este projeto busca valorizar
      os povos originários e suas contribuições para a formação cultural da região.
    </p>
  </header>

  <section>

    <div class="card">
      <h2>🌿 A Herança Indígena</h2>
      <p>
        Os povos indígenas fazem parte da construção histórica e cultural do Maranhão.
        Em Bacabal, suas tradições influenciaram costumes, linguagem, alimentação,
        conhecimentos sobre a natureza e formas de convivência social.
      </p>
    </div>

    <div class="card">
      <h2>🔥 Memórias e Tradições</h2>
      <p>
        As memórias indígenas sobrevivem através das histórias contadas pelas famílias,
        das manifestações culturais, do artesanato, das danças e da preservação da natureza.
        Cada lembrança representa a continuidade de uma identidade ancestral.
      </p>
    </div>

    <div class="card">
      <h2>🪶 Cultura e Identidade</h2>
      <p>
        A cultura indígena está presente na culinária, nas palavras do cotidiano,
        na medicina natural e no respeito à terra. Reconhecer essas raízes é valorizar
        a diversidade cultural brasileira.
      </p>
    </div>

    <div class="card">
      <h2>⏳ Linha do Tempo</h2>

      <div class="timeline">

        <div class="timeline-item">
          <h3>Povos Originários</h3>
          <p>
            Presença indígena no território maranhense antes da colonização.
          </p>
        </div>

        <div class="timeline-item">
          <h3>Colonização</h3>
          <p>
            Mudanças culturais e conflitos provocados pela chegada dos europeus.
          </p>
        </div>

        <div class="timeline-item">
          <h3>Resistência Cultural</h3>
          <p>
            Manutenção de costumes, tradições e saberes ancestrais.
          </p>
        </div>

        <div class="timeline-item">
          <h3>Atualidade</h3>
          <p>
            Valorização das raízes indígenas através da educação, cultura e memória.
          </p>
        </div>

      </div>
    </div>

  </section>

  <footer>
    <p>
      Projeto Escolar • Raízes Indígenas Bacabalenses • Entre Memórias e Lembranças
    </p>
  </footer>

</body>
</html>
