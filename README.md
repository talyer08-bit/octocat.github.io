# octocat.github.io
<header>
  <h1>My Website</h1>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>

  <section class="card" id="home">
    <h2>Welcome! 👋</h2>

    <p class="muted">
      Це моя вебсторінка, розміщена на GitHub Pages.
    </p>

    <div class="actions">
      <button class="btn-primary" id="greetBtn">
        Привітатися
      </button>

      <button class="btn-secondary" id="showCode">
        Показати HTML
      </button>
    </div>

    <div id="output"></div>
  </section>

  <section class="card" id="about">
    <h3>About</h3>

    <p class="muted">
      Ця сторінка працює повністю на HTML, CSS та JavaScript.
      Для її роботи не потрібен сервер або база даних.
    </p>
  </section>

  <section class="card" id="contact">
    <h3>Contact</h3>

    <p class="muted">
      Тут можна розмістити свої контактні дані,
      посилання на соціальні мережі або GitHub.
    </p>

    <pre id="codePreview" hidden>&lt;h1&gt;Hello World!&lt;/h1&gt;</pre>
  </section>

</main>

<footer>
  © <span id="year"></span> My Website
</footer>
