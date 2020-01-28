<script>
  import { Header, Boton } from "@centroculturadigital-mx/ccd-sistema-diseno";

	let iconoEstadoUno = "menu.svg";
	let iconoEstadoDos = "cerrar.svg";

	let items = [
		{
			ruta: "inicio",
			label: "Inicio"
		},
		{
			ruta: "uno",
			label: "Uno"
		},
		{
			ruta: "dos",
			label: "Dos"
		},
		{
			ruta: "tres",
			label: "Tres"
		},
	]
</script>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>

<Header
  objetosMenu={items}
  logoTexto="Mi Marca"
  altura="3.5rem"
  iconoBotonEstadoUnoUrl={iconoEstadoUno}
  iconoBotonEstadoDosUrl={iconoEstadoDos}
  iconoBotonAltura="2rem"
  color="#FF0000"
  colorFondo="#FFFFFF"
  colorFondoMovil="#FFFFFF"
  sombra
  fixed />
<main>
  <h1>CCD</h1>
  <p>Prueba botón con icono o texto</p>
  <Boton 
   texto="Botón texto"
   color="lime"
   colorBG="black"
   paddingX="2rem"
   radius="0.5rem"
   iconoAltura="2rem"/>
</main>
