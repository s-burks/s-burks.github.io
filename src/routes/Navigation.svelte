<div class="navigation">
    <a href="/"><h2>home</h2></a>
    <a href="/about"><h2>about</h2></a>
    <a href="/contact"><h2>contact</h2></a>
    <a href="/projects"><h2>projects</h2></a>
</div>

<style>
    .navigation {
        display: flex;
        justify-content: space-around;
    }

    a {
        background-color: var(--secondary);
        color: var(--text);
        border-radius: 10px;
        flex: 1;
        margin: 5px;
        text-align: center;
    }

    a:hover, a:active {
        background-color: var(--accent);
        color: var(--background);
    }
</style>