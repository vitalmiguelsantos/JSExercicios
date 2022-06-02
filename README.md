# JSExercicios
Repositório destinado a armazenar exercicios de lógica de programação e JS


<html>

	<head>
		<title>Basic Project</title>
		<script>

            /* 1- Escreva um programa em Javascript e crie uma variável chamada "nomeDoCarro" e atribua-a um valor "Fusca". */
                var nomeDoCarro;
                nomeDoCarro = "Fusca";

            /* 2- Escreva um programa em Javascript em que o usuário informe o seu nome e exiba a mensagem "Olá, [NomeDoUsuario]".*/
                var nomeDoUsuario = prompt ("Informe seu nome:");
                document.write("Olá,"+nomeDoUsuario.);

            /* 3- Escreva um programa em Javascript em que o usuário informe o seu nome e em seguida o programa perguntará a idade do usuário. Agora o programa deve exibir a mensagem "Olá, [NomeDoUsuario], sua idade é [idade]". */
                var nome = prompt ("Informe seu nome:");
                var idade = prompt ("Informe sua idade:");
                document.write("Olá, "+nome+"sua idade é"+idade);

            /* Retângulo */
                var baseRetangulo = prompt ("Informe a base do retângulo:");
                var alturaRetangulo = prompt ("Informe a altura do retÂngulo:");
                var areaRetangulo = baseRetangulo*alturaRetangulo;
                document.write("A área é igual a"+areaRetangulo);

            /* Quadrado */
                var baseQuadrado = prompt ("Informe a base do quadrado");
                var areaQuadrado = baseQuadrado*baseQuadrado;
                document.write("A área é igual a"+areaQuadrado);

            /* Losango */
                var diagonalMaior = prompt ("Informe o valor da diagonal maior:");
                var diagonalMenor = prompt ("Informe o valor da diagonal menor:");
                var areaLosango = (diagonalMaior*diagonalMenor)/2;
                document.write("A área é igual a"+areaLosango);

            /* Trapézio */
                var baseMaior = prompt ("Informe o valor da base maior:");
                var baseMenor = prompt ("Informe o valor da base menor:");
                var alturaTrapezio = prompt ("Informe o valor da altura:");
                var areaTrapezio = ((baseMaior+baseMenor)*alturaTrapezio)/2;
                document.write("A área é igual a"+areaTrapézio);

            /* Paralelogramo */
                var baseParalelogramo = prompt ("Informe a base do Paralelogramo:");
                var alturaParalelogramo = prompt ("Informe a altura do Paralelogramo:");
                var areaParalelogramo = baseParalelogramo*alturaParalelogramo;
                document.write("A área é igual a"+areaParalelogramo);

            /* Triângulo */
                var baseTriangulo = prompt ("Informe o valor da base do triângulo:");
                var alturaTriangulo = prompt ("Informe o valor da altura do triÂngulo:");
                var areaTriangulo = (baseTriangulo*alturaTriangulo)/2;
                document.write("A área é igual a"+areaTriangulo);

            /* Círculo */
                var raio = prompt ("Informe o valor do raio do círculo:");
                var areaCirculo = 3,14*(raio*raio);
                document.write("A área é igual a"+areaCirculo);


		</script>
	</head>

	<body>
