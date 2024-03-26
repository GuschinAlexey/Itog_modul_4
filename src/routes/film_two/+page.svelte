<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="body_films">
        <img src="https://империягрез.рф/wp-content/films/20240111043050_1631.jpg" alt="">
        <div class="title_films">
            <h3>Лёд 3</h3>
            <p class="proiz">
                мелодрама 129 минут (2:09) <br>
                <b>Производство:</b> Россия
            </p>
            <p class="description">
                Надя выросла и стала фигуристкой. Она мечтает о «Кубке Льда», как когда-то мечтала ее мама. Горин возражает против спортивной карьеры дочери — он оберегает ее от любых трудностей, и его можно понять: он потерял слишком много. На тайной тренировке Надя знакомится с молодым и дерзким хоккеистом из Москвы, и между ними вспыхивает первая любовь. Отец не верит в искренность чувств юноши и разлучает пару...
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