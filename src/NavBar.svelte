<script>
    let hide = true;
    window.onscroll = () => {
        hide = false;
    }
</script>
<nav class:hide>
    <span id="greeting"><i class="fas fa-smile-beam"></i> Welcome</span>
    <a href="#banner"><i class="fas fa-flag"></i> Banner</a>
    <a href="#about"><i class="fas fa-address-card"></i> About</a>
    <a href="#projects"><i class="fas fa-tasks"></i> Projects</a>
    <a href="#contact"><i class="fas fa-link"></i> Contact</a>
</nav>

<style>

    .hide {
        height: 0;
        overflow: hidden;
    }

    nav {
        position: fixed;
        top: 0;
        height: 3rem;
        width: 100vw;
        display: flex;
        justify-content: flex-end;
        align-items: center;

        background-color: rgba(24, 24, 24, 0.9);
        z-index: 1;

        transition: 0.6s height;
    }

    nav a {
        padding-right: 3rem;
        color: rgb(223, 223, 223);
        text-decoration: none;
    }

    nav a:hover {
        transform: translateY(-1px);
    }

    #greeting {
        padding-left: 1rem;
        color: rgb(223, 223, 223);
        flex: 2;
    }

    @media screen and (max-width: 600px) {
        #greeting {
            display: none;
        }

        nav {
            justify-content: space-evenly;
        }

        nav a {
            padding: 0;
        }
    }
</style>