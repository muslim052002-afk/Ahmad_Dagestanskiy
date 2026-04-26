# ahmad_dagestanskiy
На этом сайте вы можете знатно поймать хаха
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Приколы 2024 – Сборник угара и кринжа</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Comic Sans MS', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 50%, #ff9a9e 100%);
            min-height: 100vh;
            padding: 20px;
            position: relative;
            overflow-x: hidden;
        }

        /* Декоративные элементы на фоне */
        body::before {
            content: "😂";
            position: fixed;
            font-size: 100px;
            top: 10%;
            left: 5%;
            opacity: 0.1;
            animation: float 6s ease-in-out infinite;
            pointer-events: none;
        }

        body::after {
            content: "🤣";
            position: fixed;
            font-size: 120px;
            bottom: 10%;
            right: 5%;
            opacity: 0.1;
            animation: float 8s ease-in-out infinite reverse;
            pointer-events: none;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-30px) rotate(10deg); }
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            position: relative;
            z-index: 1;
        }

        header {
            text-align: center;
            margin-bottom: 30px;
            background: white;
            border-radius: 30px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            border: 4px dashed #ff6b6b;
        }

        h1 {
            font-size: 3em;
            color: #ff4757;
            text-shadow: 3px 3px 0 #ffa502;
            margin-bottom: 10px;
            animation: shake 0.5s ease-in-out infinite;
        }

        @keyframes shake {
            0%, 100% { transform: rotate(0deg); }
            25% { transform: rotate(-3deg); }
            75% { transform: rotate(3deg); }
        }

        .subtitle {
            font-size: 1.2em;
            color: #2f3542;
            font-style: italic;
        }

        .joke-card {
            background: white;
            border-radius: 20px;
            padding: 25px;
            margin-bottom: 25px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
            border-left: 8px solid #ff6b6b;
            position: relative;
            overflow: hidden;
        }

        .joke-card:hover {
            transform: translateY(-5px) rotate(1deg);
            box-shadow: 0 15px 30px rgba(0,0,0,0.2);
        }

        .joke-card::before {
            content: "🔥";
            position: absolute;
            top: 10px;
            right: 10px;
            font-size: 30px;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .joke-card:hover::before {
            opacity: 1;
            animation: spin 1s linear infinite;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .joke-title {
            font-size: 1.5em;
            color: #ff4757;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .joke-content {
            font-size: 1.1em;
            color: #2f3542;
            line-height: 1.6;
        }

        .joke-category {
            display: inline-block;
            background: #ffa502;
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9em;
            margin-top: 15px;
        }

        .meme-section {
            background: white;
            border-radius: 20px;
            padding: 25px;
            margin-bottom: 25px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            text-align: center;
        }

        .meme-image {
            font-size: 100px;
            margin: 20px 0;
            animation: bounce 2s ease-in-out infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }

        button {
            background: #ff4757;
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 1.2em;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            margin: 10px;
            box-shadow: 0 5px 15px rgba(255,71,87,0.4);
        }

        button:hover {
            background: #ff2e43;
            transform: scale(1.05);
            box-shadow: 0 8px 25px rgba(255,71,87,0.6);
        }

        button:active {
            transform: scale(0.95);
        }

        #randomJoke {
            background: white;
            border-radius: 20px;
            padding: 25px;
            margin: 25px 0;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            font-size: 1.3em;
            min-height: 100px;
            display: flex;
            align-items: center;
            justify-content: center;
            border: 3px solid #ffa502;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            color: #2f3542;
            font-size: 0.9em;
        }

        .dark-joke-warning {
            background: #2f3542;
            color: #ffa502;
            padding: 10px;
            border-radius: 10px;
            text-align: center;
            margin: 20px 0;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>🔥 ПРИКОЛЫ 2024 🔥</h1>
            <p class="subtitle">Сборник угара, кринжа и баянов из интернета</p>
            <p style="margin-top: 15px; color: #ff6b6b;">⚠️ Осторожно: может вызвать смех до слёз, икоту и желание рассказать друзьям!</p>
        </header>

        <div class="joke-card">
            <div class="joke-title">
                <span>🤖</span> Искусственный интеллект
            </div>
            <div class="joke-content">
                — Искусственный интеллект, заменишь меня на работе?<br>
                — Нет, я не умею пить кофе и жаловаться на зарплату.<br>
                <em style="display: block; margin-top: 10px; color: #ff6b6b;">🤦‍♂️ Вот так и живём...</em>
            </div>
            <span class="joke-category">IT-юмор</span>
        </div>

        <div class="joke-card">
            <div class="joke-title">
                <span>🐈</span> Коты в деле
            </div>
            <div class="joke-content">
                Если кот смотрит на вас с презрением — не обижайтесь. Он на всех так смотрит. Даже на себя в зеркало. Просто у него лицо такое.<br>
                <em style="display: block; margin-top: 10px; color: #ff6b6b;">😼 Зато честно!</em>
            </div>
            <span class="joke-category">Жиза</span>
        </div>

        <div class="joke-card">
            <div class="joke-title">
                <span>🍔</span> Дилемма
            </div>
            <div class="joke-content">
                — Вы не поверите, но я заказал пиццу, а привезли здоровый образ жизни!<br>
                — И что теперь?!<br>
                — Пришлось заедать его бургером, чтобы не испортился... 🍕🍔<br>
            </div>
            <span class="joke-category">Еда</span>
        </div>

        <div class="joke-card">
            <div class="joke-title">
                <span>💼</span> Офисные будни
            </div>
            <div class="joke-content">
                — Почему ты опоздал на совещание?<br>
                — Я медитировал.<br>
                — ???<br>
                — На кнопку повтора будильника. 15 раз подряд.<br>
                <em style="display: block; margin-top: 10px; color: #ff6b6b;">🧘‍♂️ Омммм... *храп*</em>
            </div>
            <span class="joke-category">Работа</span>
        </div>

        <div class="dark-joke-warning">
            🌑 ТЁМНАЯ ШУТКА (для тех, кто в теме) 🌑
        </div>

        <div class="joke-card" style="border-left-color: #2f3542; background: #f1f2f6;">
            <div class="joke-title">
                <span>💀</span> Чёрный юмор
            </div>
            <div class="joke-content">
                В детстве мама говорила мне: "Если ты не перестанешь корчить рожицы, ты таким и останешься!"<br>
                Сейчас мне 30 лет, и я работаю клоуном. Мама была права... 🤡<br>
                <em style="display: block; margin-top: 10px; color: #2f3542;">Смех сквозь слёзы...</em>
            </div>
            <span class="joke-category">Чёрный юмор</span>
        </div>

        <div class="meme-section">
            <h2>🎭 Мем недели</h2>
            <div class="meme-image">🐸☕️</div>
            <p style="font-size: 1.3em; color: #2f3542;">
                "Но это не точно"<br>
                <small style="color: #ff6b6b;">— Лягушка Кермит, когда его спрашивают о чём угодно</small>
            </p>
        </div>

        <div style="text-align: center;">
            <button onclick="generateRandomJoke()">🎲 Случайный прикол</button>
            <button onclick="shareJoke()">📱 Поделиться смехом</button>
        </div>

        <div id="randomJoke">
            Нажми на кнопку, чтобы получить случайную шутку! 👆
        </div>

        <footer>
            <p>© 2024 Приколы.бай | Все шутки украдены из интернета</p>
            <p style="margin-top: 10px;">P.S. Если не смешно — попробуй перезагрузить страницу, может поможет 😅</p>
        </footer>
    </div>

    <script>
        const jokes = [
            "Почему программисты путают Хэллоуин и Рождество? Потому что Oct 31 = Dec 25! 🎃🎄",
            "Только лёг в больницу, сразу все вспомнили и позвонили. Друзья познаются в бесплатной раздаче интернета. 📱",
            "Если вы думаете, что никто вам не рад — просто не платите за интернет. Увидите, как вас все полюбят! 💻",
            "Жизнь — как коробка шоколадных конфет: никогда не знаешь, какая попадётся, но точно знаешь, что всё съешь. 🍫",
            "Никогда не спорьте с идиотами. Они опустят вас до своего уровня и задавят опытом. 🤯",
            "Если долго смотреть на холодильник, еда не появится. Проверено. Много раз. 🍕😢",
            "Купил книгу 'Как решить 50% ваших проблем'. Купил две — проблема решена! 📚",
            "Знаете, почему нельзя доверять атомам? Они составляют всё! ⚛️😂",
            "Если кофе не помогает — вы не в том отделе: попробуйте чай, потом какао, потом компот... 💤",
            "Правило бумеранга: если вы сделали доброе дело и забыли — оно обязательно прилетит обратно и ударит по голове. 🤕"
        ];

        function generateRandomJoke() {
            const jokeElement = document.getElementById('randomJoke');
            const randomIndex = Math.floor(Math.random() * jokes.length);
            jokeElement.innerHTML = jokes[randomIndex];
            jokeElement.style.animation = 'none';
            jokeElement.offsetHeight; // reflow
            jokeElement.style.animation = 'shake 0.5s ease-in-out';
        }

        function shareJoke() {
            const jokeText = document.getElementById('randomJoke').innerText;
            if (jokeText.includes('Нажми на кнопку')) {
                alert('Сначала сгенерируй шутку! 😅');
                return;
            }
            
            if (navigator.share) {
                navigator.share({
                    title: 'Прикол дня',
                    text: jokeText,
                }).catch(() => {});
            } else {
                navigator.clipboard.writeText(jokeText).then(() => {
                    alert('Шутка скопирована! Можешь вставить её куда угодно 😉');
                });
            }
        }

        // Запускаем первую шутку сразу
        setTimeout(() => {
            generateRandomJoke();
        }, 500);
    </script>
</body>
</html>
