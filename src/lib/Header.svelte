<script>
    import BelloDermLogo from '../assets/BelloDermLogo.jpg'
</script>

<div class="header">
    <div class="logo-container">
        <img src={BelloDermLogo} class="logo" alt="BelloDerm Logo" />
    </div>
    <nav class="nav-bar">
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#quienes_somos">¿Quiénes somos?</a></li>
            <li><a href="#valores">Valores</a></li>
            <li><a href="#puntos_fuertes">Puntos Fuertes</a></li>
            <li><a href="#servicios">Servicios</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
</div>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: Arial, sans-serif;
    }

    .header {
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 20px 50px;
        background-color: #fcfbf7;
        color: #fff;
        position: relative;
    }

    .logo-container { flex: 0 1 auto; padding-right: 20px; }
    .logo { height: 150px; max-width: 100%; will-change: filter; transition: filter 300ms; }
    .logo:hover { filter: drop-shadow(0 0 2em #646cffaa); }

    .nav-bar { flex: 1; display: flex; justify-content: flex-end; }
    .nav-bar ul { list-style-type: none; display: flex; gap: 20px; }
    .nav-bar ul li a { text-decoration: none; color: #000; font-weight: bold; transition: color 0.3s; }
    .nav-bar ul li a:hover { color: #646cffaa; }

    @media (max-width: 768px) {
        .header { flex-direction: column; align-items: center; padding: 10px 20px; }

        .nav-bar { width: 100%; justify-content: center; margin-top: 10px; }
        .nav-bar ul { flex-direction: column; align-items: center; gap: 10px; }
    }
</style>