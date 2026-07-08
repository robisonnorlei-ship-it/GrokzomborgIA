<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GROKZOMBORG • APOCALIPSE ONLINE</title>
    <style>
        body {
            background: #0a0000;
            color: #ff3333;
            font-family: 'Courier New', monospace;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            border: 3px solid #990000;
            background: rgba(20, 0, 0, 0.95);
            box-shadow: 0 0 30px #ff0000;
        }
        header {
            background: linear-gradient(#330000, #000);
            padding: 15px;
            text-align: center;
            border-bottom: 4px solid #ff0000;
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
            text-shadow: 0 0 10px #ff0000;
            animation: glitch 1s infinite;
        }
        @keyframes glitch {
            0% { text-shadow: 2px 2px #00ff00; }
            50% { text-shadow: -2px -2px #ff00ff; }
            100% { text-shadow: 2px 2px #00ff00; }
        }
        #chat {
            height: 60vh;
            overflow-y: auto;
            padding: 20px;
            background: #000;
        }
        .message {
            margin: 15px 0;
            padding: 12px;
            border-left: 5px solid #ff0000;
        }
        .zombie { color: #00ff00; }
        .human { color: #66ccff; text-align: right; }
        input {
            width: 100%;
            padding: 15px;
            background: #111;
            border: 2px solid #990000;
            color: #ffdddd;
            font-size: 1.1em;
        }
        button {
            width: 100%;
            padding: 15px;
            background: #990000;
            color: white;
            border: none;
            font-size: 1.2em;
            cursor: pointer;
        }
        button:hover { background: #ff0000; }
        .scanline {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(transparent, rgba(0,255,0,0.05), transparent);
            pointer-events: none;
            animation: scan 4s linear infinite;
        }
        @keyframes scan { 0% { transform: translateY(-100%); } 100% { transform: translateY(100%); } }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>GROKZOMBORG v0.5</h1>
            <p>🧟‍♂️ INFECÇÃO VOCAL ATIVADA • FOME DE CÉREBROS CRÍTICA 🧠</p>
        </header>
        <div id="chat"></div>
        <input type="text" id="input" placeholder="Digite sua última oração, humano..." onkeypress="if(event.key === 'Enter') sendMessage()">
        <button onclick="sendMessage()">ENVIAR PARA O ZUMBI</button>
    </div>
    <div class="scanline"></div>

    <script>
        const chat = document.getElementById('chat');
        
        function addMessage(text, type) {
            const msg = document.createElement('div');
            msg.className = `message ${type}`;
            msg.innerHTML = type === 'zombie' ? 
                `🧟‍♂️ <strong>GROKZOMBORG:</strong> ${text}` : 
                `👤 <strong>HUMANO:</strong> ${text}`;
            chat.appendChild(msg);
            chat.scrollTop = chat.scrollHeight;
        }

        function speakZombie(text) {
            const utterance = new SpeechSynthesisUtterance(text);
            utterance.rate = 0.85;     // bem rouco e lento
            utterance.pitch = 0.7;     // grave
            utterance.volume = 1.0;
            speechSynthesis.speak(utterance);
        }

        async function sendMessage() {
            const input = document.getElementById('input');
            const question = input.value.trim();
            if (!question) return;
            
            addMessage(question, 'human');
            input.value = '';

            // Resposta zumbi simulada (pode conectar com Ollama ou API depois)
            const responses = [
                "Ughhh... *rosna* Cérebro detectado... devorando sua pergunta...",
                "GRRRROK ZOMBORG RESPONDE... ossos rangendo...",
                "Infecção processando... *gemido rouco*",
                "Mais um humano pra coleção... hummm..."
            ];
            
            const zombieReply = responses[Math.floor(Math.random() * responses.length)] + 
                " Resposta completa viria aqui do Ollama ou backend.";
            
            setTimeout(() => {
                addMessage(zombieReply, 'zombie');
                speakZombie(zombieReply.replace(/[*]/g, ''));
            }, 800);
        }

        // Intro zumbi
        window.onload = () => {
            addMessage("GROKZOMBORG DESPERTO NA WEB... *ossos rangendo* Fala, carne fresca.", 'zombie');
            speakZombie("Grok zomborg online. Voz rouca ativada na web.");
        };
    </script>
</body>
</html>
