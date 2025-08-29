<div class="navigation">
    <a href="/">home</a>
    <a href="/about">about</a>
    <a href="/contact">contact</a>
    <a href="/projects">projects</a>
</div>

<style>
    .navigation {
        display: flex;
        justify-content: space-around;
    }

    a {
        background-color: var(--secondary);
        color: var(--text);
        /* border-radius: 10px; */
        padding: 10px;
        flex: 1;
        margin: 5px;
        text-align: center;
    }

    a:hover, a:active {
        background-color: var(--accent);
        color: var(--background);
    }
</style>