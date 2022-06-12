<script>
    // Plugins
    import { Link, Route } from 'svelte-routing';

    // Imports Images
    let dark = "assets/img/ldark.png";
    let light = "assets/img/llight.png";
</script>

<header id="topnav" class="defaultscroll sticky">
    <div class="container">
        <Link class="logo" to="/">
            <img src="{dark}" class="l-dark" height="26" alt="logo-dark">
            <img src="{light}" class="l-light" height="26" alt="logo-light">
        </Link>

        <div class="menu-extras">
            <div class="menu-item">
                <Link class="navbar-toggle" id="isToggle">
                    <div class="lines">
                        <span></span>
                        <span></span>
                        <span></span>
                    </div>
                </Link>
            </div>
        </div>

        <ul class="buy-button list-inline mb-0">
            <li class="list-inline-item ps-1 mb-0">
                <Link to="/">
                    <div class="btn btn-primary">Download</div>
                </Link>
            </li>
        </ul>

        <div class="navigation">
            <ul class="navigation-menu nav-light nav-right" id="navmenu-nav">
                <li class="has-submenu">
                    <Link to="/">Home</Link>
                </li>
                <li class="has-submenu">
                    <Link to="/page/feature/">Features</Link>
                </li>
                <li class="has-submenu">
                    <Link to="/page/contact/">Contact</Link>
                </li>
            </ul>
        </div>
    </div>
</header>
