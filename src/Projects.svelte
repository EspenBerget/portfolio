<script>
    import Project from './Project.svelte';

    let projects = [
	{name:"Todo",href:"https://basic-todo-reminder.netlify.app/",src:"/images/todo",alt:"A Todo reminder site", extref:"https://github.com/EspenBerget/todo"},
        {name:"Snake",href:"https://canvassnake.netlify.app",src:"/images/snake",alt:"A snake game webpage", extref:"https://github.com/EspenBerget/snake"},
	{name:"Reader",href:"https://noeyemovement-reader.netlify.app/", src:"/images/reader", alt:"A no eye movement reader", extref:"https://github.com/EspenBerget/reader"},
	{name:"Quiz",href:"https://inspiring-haibt-e07661.netlify.app/",src:"/images/quiz",alt:"A quiz written with react",extref:"https://github.com/EspenBerget/quiz"},
        {name:"Game of Life",href:"https://life-react.netlify.app/",src:"/images/gol",alt:"A game of life celluar automata",extref:"https://github.com/EspenBerget/gameoflife"},
        {name:"Guessjs",href:"https://guessjs.netlify.app/",src:"/images/guess",alt:"Find two equal cells", extref:"https://github.com/EspenBerget/guessjs"},
        {name:"Star Wars",href:"https://anewhopeintro.netlify.app/",src:"/images/starwars",alt:"star wars text scrolling on the screen", extref:"https://github.com/EspenBerget/starwars"},
        {name:"Calculator",href:"https://codepen.io/espenberget/full/yLadLGg",src:"/images/calc",alt:"a calculator"},
        {name:"Drum machine",href:"https://codepen.io/espenberget/full/bGwydXP",src:"/images/drums",alt:"a drum machine"},
        {name:"25+5 Clock",href:"https://codepen.io/espenberget/full/jOMgmaK",src:"/images/clock",alt:"a 25+5 clock"},
        {name:"Quotes",href:"https://codepen.io/espenberget/full/YzGgpgd",src:"/images/quotes",alt:"random quotes"}
    ];

</script>
<articel id="projects">
    <div>
        {#each projects as project}
        <Project href={project.href} src={project.src} alt={project.alt} name={project.name} extref={project.extref} />
        {/each}
    </div>
</articel>
<style>
    #projects {
        min-height: 100vh;
        width: 100vw;
        background-color: rgb(213, 213, 213);

        display: flex;
        justify-content: center;
    }
    div {
        display: flex;
        justify-content: space-evenly;
        align-items: center;

        flex-wrap: wrap;

        max-width: 1500px;
    }


</style>
