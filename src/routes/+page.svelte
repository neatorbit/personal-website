<section id="profile">
    <div class="section-align">
        <h1>A. Dominik</h1>
        <h2>
            software developer (engines/games & tools),
            <br />
            reinventer of wheels & lifelong learner.
        </h2>

        <ul>
            <li>Based in <span>Lisbon</span>, <span>PT</span>.</li>
            <li>
                Building reliable & lightweight applications like it's the 90s.
            </li>
            <li>
                I mostly code in C but I also use Odin, Lua & Python depending
                on the project.
            </li>
        </ul>

        <h2>
            Here are my <a
                href="https://github.com/aubs-dev/dotfiles"
                target="_blank"><span>Dotfiles</span></a
            >.
        </h2>

        <div class="button-container">
            <a href="https://github.com/aubs-dev" target="_blank"
                ><button>Github</button></a
            >
            <a href="mailto:hello@aubs.dev" target="_blank"
                ><button class="inverse-button">Contact Me</button></a
            >
        </div>
    </div>
</section>

<style>
    @import url("https://fonts.googleapis.com/css2?family=Lato:wght@400;700&display=swap");
    @import url("https://fonts.googleapis.com/css2?family=Karla:ital,wght@0,200..800;1,200..800&display=swap");
    @import url("https://fonts.googleapis.com/css2?family=Montserrat+Alternates:wght@300;400&display=swap");

    * {
        margin: 0;
        padding: 0;
        list-style: none;
        text-decoration: none;
    }

    a > span:hover {
        text-decoration: underline;
    }

    span {
        color: #ff004d;
        font-weight: 400;
    }

    section {
        width: 100vw;
        height: 100vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    .section-align {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        justify-content: left;
    }

    h1 {
        margin-bottom: 0.25em;
        font-family: "Lato", sans-serif;
        font-size: 2.5em;
        font-weight: 700;
        color: #ff004d;
    }

    h2 {
        margin-bottom: 0.5em;
        font-family: "Karla", sans-serif;
        font-size: 1.25em;
        font-weight: 400;
        color: #05010c;
    }

    ul {
        padding-left: 0.5em;
    }

    li {
        padding-bottom: 0.65em;
        font-family: "Montserrat Alternates", sans-serif;
        font-size: 0.875rem;
        font-weight: 300;
        line-height: 1.25rem;
        list-style-type: ">";
        padding-inline-start: 0.5em;
    }

    li::marker {
        color: #333333;
        font-size: 0.8rem;
    }

    button {
        width: 8rem;
        height: 2.5rem;
        margin-right: 1.25rem;
        font-family: "Lato", sans-serif;
        font-size: 0.875rem;
        font-weight: 400;
        color: #f7f1e8;
        background-color: #ff004d;
        border-style: solid;
        border-color: #ff004d;
        border-width: 2px;
        transition: all;
        transition-duration: 150ms;
        cursor: pointer;
    }

    button:hover {
        box-shadow: -4px 4px 0px 0px black;
        transform: scale(1.1, 1.1);
    }

    .button-container {
        width: 100%;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center;
    }

    .inverse-button {
        color: #ff004d;
        background-color: transparent;
    }
</style>
