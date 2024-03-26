<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="body_films">
        <img src="https://империягрез.рф/wp-content/films/20240111011044_6294.jpg" alt="">
        <div class="title_films">
            <h3>Мастер и Маргарита</h3> 
            <p class="proiz">
                драма, фэнтези 157 минут (2:37) <br>
                <b>Производство:</b> Россия
            </p>
            <p class="description">
                Москва, 1930-е годы. Известный писатель на взлёте своей карьеры внезапно оказывается в центре литературного скандала. Спектакль по его пьесе снимают с репертуара, коллеги демонстративно избегают встречи, в считанные дни он превращается в изгоя. Вскоре после этого, он знакомится с Маргаритой, которая становится его возлюбленной и музой. Воодушевлённый ее любовью и поддержкой, писатель берется за новый роман, в котором персонажи — это люди из его окружения, а главный герой — загадочный Воланд, прообразом которого становится недавний знакомый иностранец. Писатель уходит с головой в мир своего романа и постепенно перестает замечать, как вымысел и реальность сплетаются в одно целое.
            </p>
            <button>Купить билет</button>
        </div>
    </div>
    <style>
        .body_films {
            display: flex;
            justify-content: center;
            gap: 50px;
            width: 100%;
        }
        p {
            font-size: 20px;
        }
        button {
            font-size: 20px;
            background-color: orange;
            border: none;
            color: white;
            width: 180px;
            height: 30px;
        }
		img {
			width: 40%;
		}
        button:hover {
            border: 1px solid orange;
            width: 178px;
            height: 28px;
            background-color: white;
             color: black;
        }
        h3 {
            color: orange;
            font-size: 30px;
        }
 </style>