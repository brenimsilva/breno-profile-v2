<main>
    <section id="profile-section">
        <h1>Breno Almeida</h1>
        <h2>Desenvolvedor Pleno em Nuria</h2>
        <p>Construo soluções web com elegância e performance</p>
        <div>
            <ul>
                <li class="selected"><div class="menu-line"></div><a href="/">Sobre mim</a></li>
                <li><div class="menu-line"></div><a href="/">Experiência Profissional</a></li>
                <li><div class="menu-line"></div><a href="/">Projetos</a></li>
            </ul>
        </div>
    </section>
    <aside>
        <section>
            <div>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto neque, voluptates perspiciatis quos officia voluptatem commodi unde! Harum ad eligendi, error blanditiis laudantium at. Perspiciatis amet delectus eos eligendi suscipit.</p>
            </div>
        </section>
    </aside>
</main>

<style scoped>
    main {
        display: flex;
    }
    aside > section {
        padding: 80px;
        max-height: 90vh;
        overflow: auto;
    }

    #profile-section {
        padding: 80px;
        min-width: 450px;
        max-width: 450px;
    }
    /* ===== Scrollbar CSS ===== */
    /* Firefox */
    * {
        scrollbar-width: auto;
        scrollbar-color: #ffffff #adadad;
    }

    /* Chrome, Edge, and Safari */
    *::-webkit-scrollbar {
        width: 6px;
    }

    /*  *::-webkit-scrollbar-track {
}*/

    *::-webkit-scrollbar-thumb {
        background-color: #ffffff;
        border-radius: 24px;
    }
    a {
        text-transform: uppercase;
        font-size: 14px;
        color: var(--stroke);
        text-decoration: none;
    }

    li {
        display: flex;
        align-items: center;
        gap: 15px;
    }

    .menu-line {
        height: 2px;
        border-radius: 15%;
        background-color: white;
        min-width: 40px;
        max-width: 40px;
    }

    .selected > div {
        min-width: 80px;
        max-width: 80px;
        color: var(--light-stroke);
    }

    .selected > a {
        color: var(--light-stroke);
    }


    h1 {
        font-size: 56px;
        margin: 0;
        color: var(--light-stroke);
    }

    h2 {
        font-size: 24px;
        margin: 10px 0px 20px 0px;
        color: var(--light-stroke);
    }

    p {
        margin: 0 0px 50px 0px;
        font-size: 16px;
        color: var(--stroke);
    }
</style>
