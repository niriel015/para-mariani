<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para Mariani</title>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #ff4d6d;
            --white: #ffffff;
            --bg-gradient: radial-gradient(circle at center, #1b1015 0%, #050505 100%);
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            background: var(--bg-gradient);
            color: var(--white);
            font-family: 'Poppins', sans-serif;
            overflow: hidden;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        #starField { position: fixed; top: 0; left: 0; width: 100%; height: 100%; z-index: 1; pointer-events: none; }

        /* BATIMENTO */
        .heart-svg { overflow: visible; filter: drop-shadow(0 0 10px var(--primary)); width: 250px; margin: 20px 0; }
        .svg-line { fill: none; stroke: var(--primary); stroke-width: 2; stroke-dasharray: 1000; stroke-dashoffset: 1000; animation: dash-anim 4s linear infinite; }
        .svg-heart { fill: var(--primary); transform-origin: center; animation: blink-anim 4s linear infinite; }

        @keyframes dash-anim { 0% { stroke-dashoffset: 1000; } 80%, 100% { stroke-dashoffset: 0; } }
        @keyframes blink-anim { 0%, 65% { opacity: 0; transform: scale(0); } 75%, 85% { opacity: 1; transform: scale(1.2); } 80% { transform: scale(1.0); } 95%, 100% { opacity: 0; } }

        /* PÁGINAS */
        .page { 
            position: absolute; width: 100%; padding: 20px; 
            text-align: center; transition: 0.5s; 
            display: flex; flex-direction: column; align-items: center;
            opacity: 0; pointer-events: none; z-index: 5;
        }
        .page.active { opacity: 1; pointer-events: all; z-index: 10; }

        h1 { font-family: 'Dancing Script', cursive; font-size: 2.5rem; text-shadow: 0 0 15px var(--primary); margin-bottom: 10px; }
        .phrase { font-size: 1.1rem; line-height: 1.5; font-style: italic; max-width: 85%; margin-bottom: 20px; }

        /* GALERIA */
        .photo-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; width: 100%; max-width: 320px; margin: 15px 0; }
        .photo-item { 
            width: 100%; aspect-ratio: 1/1; object-fit: cover; 
            border: 3px solid white; box-shadow: 0 5px 15px rgba(0,0,0,0.5); 
            transition: 0.4s; cursor: pointer; 
        }
        .photo-item:nth-child(odd) { transform: rotate(-3deg); }
        .photo-item:nth-child(even) { transform: rotate(3deg); }
        .photo-item.zoom { transform: scale(1.8) rotate(0deg) !important; z-index: 100; box-shadow: 0 20px 40px rgba(0,0,0,0.8); }

        /* ENVELOPE E SELO */
        .envelope-wrapper { position: relative; width: 280px; height: 160px; margin-top: 40px; cursor: pointer; }
        .envelope { position: absolute; width: 100%; height: 100%; background: #d1d1d1; border-radius: 0 0 8px 8px; z-index: 10; transition: 0.5s; }
        .flap { position: absolute; top: 0; border-left: 140px solid transparent; border-right: 140px solid transparent; border-top: 100px solid #e5e5e5; transition: 0.5s; z-index: 15; transform-origin: top; }
        
        .seal { 
            position: absolute; top: 70px; left: 50%; transform: translateX(-50%);
            width: 70px; height: 70px; background: var(--primary); 
            clip-path: path('M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z');
            z-index: 20; transition: 0.4s; filter: drop-shadow(0 4px 6px rgba(0,0,0,0.4));
        }

        .letter { 
            position: absolute; bottom: 5px; left: 5%; width: 90%; height: 120px; 
            background: #fff; border-radius: 5px; padding: 30px 20px; color: #333; 
            text-align: left; transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1); z-index: 5; opacity: 0; pointer-events: none;
        }
        
        .is-open .envelope, .is-open .flap, .is-open .seal { opacity: 0; transform: translateY(50px) scale(0.5); pointer-events: none; }
        .is-open .letter { 
            opacity: 1; pointer-events: all; position: fixed; top: 50%; left: 50%;
            transform: translate(-50%, -50%); width: 90vw; height: 75vh; max-width: 400px;
            z-index: 1000; box-shadow: 0 0 50px rgba(0,0,0,0.8);
        }

        .btn { background: rgba(255, 255, 255, 0.1); border: 1px solid white; padding: 10px 20px; border-radius: 30px; color: white; font-weight: 600; cursor: pointer; margin-top: 10px; transition: 0.3s; }
        .btn:hover { background: white; color: var(--primary); }
    </style>
</head>
<body>

    <div id="starField"></div>

    <section class="page active" id="p1">
        <h1>Para Mariani</h1>
        <svg class="heart-svg" viewBox="0 0 502.98 108.61">
            <path class="svg-heart" d="M213.35 29.43c19.41-15.19 33.68 10.86 37.73 18.82-.28-13.61 11.64-40.98 25.94-34.01 32.3 15.74-15.88 83.8-26.4 81.76-13.24-9-51.35-53.3-37.27-66.57Z" />
            <path class="svg-line" d="M5.32 78.13c.96-.01 5-8.5 5.54-8.54.58-.05 6.1 8.51 7.1 8.51 3.66 0 9.29.06 10.71.05 2.53-.01 4.82-72.88 4.82-72.88l4.76 97.28 3.97-24.45 20.45-.22C64 77.86 77.1 63.66 78.36 63.8c1.31.15 6.68 14.08 7.94 14.07 2.3-.03 33.32.04 35.76.02.96 0 5-8.5 5.53-8.53.59-.05 6.1 8.51 7.1 8.5 3.66 0 9.3.07 10.72.06 2.53-.02 4.81-72.89 4.81-72.89l4.77 97.28 3.97-24.44s83.34-3.33 74.69 7.67c-8.65 11-45.3-42.94-31.65-53.58 25.6-19.96 49.96 36.94 40.26 36.5-12.2-.53 1.8-62.32 23.41-51.7 32.24 15.86-17.56 84.92-26.4 81.77-5.73-2.05-.68-21.68 31.4-26.58 26.65-6.42 29.5 2.35 52.62 7.11 2.53-.02 4.82-72.89 4.82-72.89l4.76 97.28 3.97-24.44 20.45-.22c1.31-.02 14.41-14.22 15.68-14.07 1.32.15 6.7 14.08 7.95 14.07 2.29-.03 33.32.04 35.76.02.95 0 5-8.5 5.53-8.54.58-.04 6.1 8.52 7.1 8.52 3.66 0 9.3.06 10.72.05 2.53-.02 4.81-72.89 4.81-72.89l4.77 97.28 3.97-24.44 20.45-.23c1.31-.01 14.4-14.22 15.68-14.07 1.32.16 6.69 14.09 7.94 14.07" />
        </svg>
        <p>4 meses iluminando minha vida.</p>
        <button class="btn" onclick="goTo(2)">Começar</button>
    </section>

    <section class="page" id="p2"><p class="phrase">"Desde que você chegou, cada dia ganhou uma cor diferente e um brilho especial."</p><button class="btn" onclick="goTo(3)">Próximo</button></section>
    <section class="page" id="p3"><p class="phrase">"4 meses podem parecer pouco para o mundo, mas para mim foram uma vida inteira de felicidade."</p><button class="btn" onclick="goTo(4)">Continuar</button></section>
    <section class="page" id="p4"><p class="phrase">"Obrigado por ser meu porto seguro e por transformar meus sorrisos em algo mais verdadeiro."</p><button class="btn" onclick="goTo(5)">Seguir</button></section>
    <section class="page" id="p5"><p class="phrase">"Você é o meu pensamento favorito em todos os momentos do dia."</p><button class="btn" onclick="goTo(6)">Mais um pouco</button></section>
    <section class="page" id="p6"><p class="phrase">"Eu amo a nossa história e o jeito que a gente se encaixa perfeitamente."</p><button class="btn" onclick="goTo(7)">Quase lá...</button></section>
    
    <section class="page" id="p7"><p class="phrase">"Que o nosso amor continue crescendo e transbordando luz por onde a gente passar."</p><button class="btn" onclick="goTo(8)">Eu te amo</button></section>

    <section class="page" id="p8">
        <h1>Eu amo essa garota💕</h1>
        <div class="photo-grid">
            <img src="https://lh3.googleusercontent.com/d/1lbVBgwrEyhmkRu8Adk8MhnI5pUbPxvsD" class="photo-item" onclick="toggleZoom(this)">
            <img src="https://lh3.googleusercontent.com/d/1TDtOdDa0W614L7COAzKDKEx0pPN95hGp" class="photo-item" onclick="toggleZoom(this)">
            <img src="https://lh3.googleusercontent.com/d/1Uxw92e_t7D3owmjABj-l3Wx4kBoi4Pi1" class="photo-item" onclick="toggleZoom(this)">
            <img src="https://lh3.googleusercontent.com/d/1lbVBgwrEyhmkRu8Adk8MhnI5pUbPxvsD" class="photo-item" onclick="toggleZoom(this)">
        </div>
        <p style="font-size: 0.7rem; opacity: 0.5;">(Toque para ampliar)</p>
        <button class="btn" onclick="goTo(9)">Ler minha carta</button>
    </section>

    <section class="page" id="p9">
        <div class="envelope-wrapper" onclick="this.classList.toggle('is-open')">
            <div class="flap"></div>
            <div class="seal"></div>
            <div class="envelope"></div>
            <div class="letter">
                <div class="letter-content">
                    <h2 style="font-family:'Dancing Script'; color:var(--primary); margin-bottom:15px; font-size: 2.2rem;">Minha Mariani,</h2>
                    <p style="font-size:1.05rem; line-height:1.7; color: #333;">
                        Completar 4 meses com você é ter a certeza de que a vida reservou o melhor para mim. <br><br>
                        Obrigado por cada conversa, cada abraço e por ser essa pessoa incrível que você é. <br><br>
                        Você é a minha paz, o meu amor e a dona do meu coração.<br><br>
                        <b>Te amo hoje e para sempre! ❤️</b>
                    </p>
                </div>
            </div>
        </div>
        <p style="margin-top: 40px; font-size: 0.8rem; opacity: 0.6;">Toque no coração para abrir</p>
    </section>

    <script>
        function toggleZoom(el) {
            const isZoomed = el.classList.contains('zoom');
            document.querySelectorAll('.photo-item').forEach(img => img.classList.remove('zoom'));
            if (!isZoomed) el.classList.add('zoom');
        }

        function goTo(num) {
            document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
            setTimeout(() => { document.getElementById(`p${num}`).classList.add('active'); }, 100);
        }

        const starField = document.getElementById('starField');
        for (let i = 0; i < 80; i++) {
            const star = document.createElement('div');
            star.style.cssText = `position:absolute; background:#fff; border-radius:50%; width:${Math.random()*2}px; height:${Math.random()*2}px; left:${Math.random()*100}%; top:${Math.random()*100}%; opacity:${Math.random()};`;
            starField.appendChild(star);
        }
    </script>
</body>
</html>
