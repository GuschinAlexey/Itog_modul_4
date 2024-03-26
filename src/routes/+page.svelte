<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<div class="body_films">
        <img src="https://империягрез.рф/wp-content/films/20240229121224_9806.jpg" alt="">
        <div class="title_films">
            <h3>Онегин</h3> 
            <p class="proiz">
                мелодрама 146 минут (2:26) <br>
                <b>Производство:</b> Россия
            </p>
            <p class="description">
                Евгений Онегин живет на широкую ногу: балы, приемы, театральные премьеры и прочие развлечения, которые может предложить молодому человеку столица. Но светская жизнь давно утомила его, потому известие о болезни живущего в деревне дяди, он воспринимает как возможность сбежать от опостылевшего света. Однако, добравшись до имения, Онегин узнает о кончине родственника, что, впрочем, не сильно расстраивает Евгения. Его финансовые дела весьма печальны, а дядя богат и других наследников у него нет. Онегин запирается в имении, сторонится соседей, которые очень скоро начинают называть его между собой чудаком. В бесцельном одиночестве Евгений живет до тех пор, пока в соседнем имении не объявляется вернувшийся из-за границы хозяин – юный, восторженный, еще не пресыщенный жизнью Ленский, который знакомит Евгения с сестрами Татьяной и Ольгой Лариными…
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
            border: 1px solid red;
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