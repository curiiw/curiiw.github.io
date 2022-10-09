# curiiw.github.io

<html>	
	<head>
		<title>Cats</title>
		<script>
			
			var login;
			var password;
			login = prompt("Введите логин");
			if (login == null){
				alert ("Вход отменён");
				
			}
			if (login == "Админ"){
				password = prompt("введите пароль");
				if (password == "Черный Властелин"){
					alert ("Добро пожаловать!")
				}
				else{
					alert ("Пароль не верен");
					
				}
			if (password== null){
				alert ("Вход отменён");
				}
			
			}
			else{
				alert("Я вас не знаю");
			}
			
			
		</script>
		
		
		<style>
		
		
			*{
				padding: 0;
				margin: 0;
			}
			
			
			.header{
				color: white;
				background: #151c39eB;
				padding: 20px;
				display: flex;
				justify-content: space-between;
				align-items: center;
				padding: 0 50px;
			}
			
			.header-logo
			{
				display: flex;
				align-items: center;
			}
			
			.menu
			{
				display: flex;
				
			}
			
			.menu-item{
				list-style: none;
				padding: 0 10px;
			}
			
			.menu-link{
				text-decoration: none;
				color: white;
			}
			
			.banner-section{
				background: url(banner-bg.jpg);
				padding: 100px 0;
				background-size: cover;
			}
			
			.banner-title{
				font-size: 40px;
			}
			
			.banner-text{
				color: white;
				text-align: center;
			}
			
			
			.cards-section{
				padding: 50px 0;
			}
			
			.carda-title, .cards-description{
				color: #151c39;
				text-align: center;
			}
			
			.card
			{
				padding: 25px;
				margin-top: 25px;
				width: 25%;
				background: white;
				box-shadow: 0px 2px 7px #9e90ff;
				text-align: center;
			}
			
			.card:hover
			{ 
				box-shadow: 0px 10px 30px #9e90ff; 
			}

			.card-link
			{
				text-decoration: none;
				color: white;
			}

			.card-button
			{
				text-align: center;
				background: #151c39;
				padding: 10px 70px;
				border-radius: 10px;
			}

			.card-title, .card-text
			{
				margin-bottom: 10px;
			}
			
			.cards{
				display: flex;
				justify-content: space-around;
				flex-wrap: wrap;
			}
			
			.footer
			{
				background: url(footer-bg.jpg);
				background-size: cover;
				padding: 100px 0px;
			}
			
			.copyright
			{
				color: white;
			}
			
			.container
			{
				padding: 0 15px;
				margin: 0 auto;
			}
			

			
			.footer
			{
				background: url(footer-bg.jpg); /*необходимо прокомментировать каждое свойство!*/
				background-size: cover;
				padding: 100px 0px;
			}

			.copyright
			{
				color: white;
			}

			.footer-row{
				display: flex;
				flex-direction: row;
				justify-content: space-between;
			}

			.social-networks{
				display: flex;
				justify-content: flex-end;
			}

			.footer-logo{
				margin: 10px;
				width: 60px;
				height: 60px;
			}

			.footer-search{
				display: flex;
				justify-content: space-between;
				margin-top:30px;
				align-items: center;
			}

			.footer-search-input{
				height: 40px;
				flex-grow: 3;
				margin-right: 20px;
				border-radius: 10px;
				border: none;
			}

			.footer-search-button{
				height: 40px;
				flex-grow: 2;
				border-radius: 10px;
				text-transform: uppercase;
				font-weight: bold;
			}
			
			
			
			
		</style>
		
	</head>
	<body>
	
		<header class="header">

			<div class="header-logo">
				<img class="logo-img" src="cat.png">
				<h1 class="logo-title">CATS</h1>
			</div>
			
			<div class="header-menu">
				<ul class="menu">
					<li class="menu-item">
						<a href="#" class="menu-link">Home</a>
					</li>
					<li class="menu-item">
						<a href="#" class="menu-link">About</a>
					</li>
					<li class="menu-item">
						<a  href="#" class="menu-link">Animals</a>
					</li>
				</ul>
			</div>

		</header>
		
		<main class="main">
		
			<section class="banner-section">
				<div class="banner-text">
					<h1 class="banner-title">Зоомагазин</h1>
					<div class="banner-description">Заведи питомца!</div>
				</div>
			</section>
			
			<section class="cards-section">
				<div class="container">
					<div class="cards-text">
						<h1 class="cards-title">Рекомендуемы животные!</h1>
						<div class="cards-description">Специально для вас</div>
					</div>
					
					<div class="cards">
						<div class="card">
							<img class="card-img" src="Vasiliy.jpg">
							<div class="card-body">
								<h3 class="card-title">Кот Василий</h3>
								<div class="card-text">Ищет добрых хозяев!</div>
								<div class="card-button">
									<a class="card-link" href="#">Узнать подробности</a>
								</div>
							</div>
						</div>
						
						<div class="card">
							<img class="card-img" src="Vasiliy.jpg">
							<div class="card-body">
								<h3 class="card-title">Кот Василий</h3>
								<div class="card-text">Ищет добрых хозяев!</div>
								<div class="card-button">
									<a class="card-link" href="#">Узнать подробности</a>
								</div>
							</div>
						</div>
						
						<div class="card">
							<img class="card-img" src="Vasiliy.jpg">
							<div class="card-body">
								<h3 class="card-title">Кот Василий</h3>
								<div class="card-text">Ищет добрых хозяев!</div>
								<div class="card-button">
									<a class="card-link" href="#">Узнать подробности</a>
								</div>
							</div>
						</div>
						
						<div class="card">
							<img class="card-img" src="Vasiliy.jpg">
							<div class="card-body">
								<h3 class="card-title">Кот Василий</h3>
								<div class="card-text">Ищет добрых хозяев!</div>
								<div class="card-button">
									<a class="card-link" href="#">Узнать подробности</a>
								</div>
							</div>
						</div>
						
						<div class="card">
							<img class="card-img" src="Vasiliy.jpg">
							<div class="card-body">
								<h3 class="card-title">Кот Василий</h3>
								<div class="card-text">Ищет добрых хозяев!</div>
								<div class="card-button">
									<a class="card-link" href="#">Узнать подробности</a>
								</div>
							</div>
						</div>
						
						<div class="card">
							<img class="card-img" src="Vasiliy.jpg">
							<div class="card-body">
								<h3 class="card-title">Кот Василий</h3>
								<div class="card-text">Ищет добрых хозяев!</div>
								<div class="card-button">
									<a class="card-link" href="#">Узнать подробности</a>
								</div>
							</div>
						</div>
						
					</div>
				</div>
			</section>
			
		</main>
		
		<footer class = 'footer'>
        <div class = 'container'>
            <div class = 'footer-row'>
                <div class = 'search'>
                    <div class = 'copyright'>Копирайт 2022. Все права защищены Maximum</div>
                    <div class="footer-search">
                        <input type="text" class="footer-search-input">
                        <button class="footer-search-button">Subscribe</button>
                    </div>
                </div>
                <div class = 'social-networks'>
                    <a href="#"><img class = 'footer-logo' src='img/vk.png'></a>
                    <a href="#"><img class = 'footer-logo' src='img/instagram.png'></a>
                    <a href="#"><img class = 'footer-logo' src='img/youtube.png'></a>
                    <a href="#"><img class = 'footer-logo' src='img/facebook.png'></a>
                </div>
            </div>
        </div>
    </footer>
	
				
	
	</body>
</html>