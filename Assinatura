(function() {
    // 1. Criamos o estilo CSS
    const style = document.createElement('style');
    style.innerHTML = `
        .dmc-btn-exclusivo {
            text-decoration: none !important;
            display: flex !important;
            align-items: center;
            justify-content: center;
            width: 188px;
            height: 40px;
            background-color: #2D2D2D !important;
            border: 1px solid rgba(255,255,255,0.1) !important;
            border-radius: 16px !important;
            overflow: hidden;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            font-family: 'Inter', sans-serif !important;
        }

        .dmc-logo-img {
            height: 20px !important;
            width: auto !important;
            display: block;
            border: none !important;
        }

        .dmc-text-reveal {
            color: #ffffff !important;
            font-size: 12px !important;
            font-weight: 200 !important;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            white-space: nowrap;
            overflow: hidden;
            opacity: 0;
            max-width: 0;
            animation: dmcRevealCycle 10s infinite ease-in-out;
        }

        @keyframes dmcRevealCycle {
            0%, 55%, 100% { max-width: 0; opacity: 0; margin-left: 0; }
            10%, 45% { max-width: 120px; opacity: 1; margin-left: 10px; }
        }

        .dmc-btn-exclusivo:hover {
            background-color: #111111 !important;
            box-shadow: 0 0 20px rgba(255, 255, 255, 0.1);
            transform: translateY(-2px);
        }
    `;
    document.head.appendChild(style);

    // 2. Criamos o HTML do botão
    const htmlBotao = `
        <a href="https://diegomeira.com" target="_blank" class="dmc-btn-exclusivo">
            <div style="display: flex; align-items: center;">
                <img src="https://diegomeira.com/wp-content/uploads/2026/05/Ativo-1.png" alt="DMC Logo" class="dmc-logo-img">
                <span class="dmc-text-reveal">DMC agency</span>
            </div>
        </a>
    `;

    // 3. Insere no local onde o script for chamado
    document.currentScript.insertAdjacentHTML('afterend', htmlBotao);
})();
