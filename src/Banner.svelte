<article id="banner">
    <div>
        <h1>Espen Berget</h1>
        <p>Web developer</p>
    </div>
</article>

<style>
    #banner {
        display: flex;
        flex-direction: column;
        justify-content: center;

        text-align: center;
        font-size: 3rem;
        line-height: 0.5;
        text-shadow: 5px 5px black;

        height: 100vh;
        width: 100vw;

        background-image: url("/images/pexels-sabrina-gelbart-249798.jpg");
        background-position: top left;
        background-size: 120vw 110vh;
        background-repeat: no-repeat;
        background-color: #424242;

        animation: living-bg 20s linear 0s infinite; 
    }

    #banner h1 {
        font-family: 'Lalezar', Helvetica, cursive;
        letter-spacing: 5px;
        color: white;
    }

    @media screen and (max-width: 471px) {
        #banner h1 {
            line-height: 1;
        }
    }

    #banner p {
        font-family: 'Farsan', cursive;
        color: #36c01a;
    }

    @keyframes living-bg {
        50% {
            background-position: center;
        }
    }
    
</style>