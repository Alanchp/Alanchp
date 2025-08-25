<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alan</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bangers&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <style>
      :root {
        --heading-font: "Bangers", system-ui;
        --paragraph-font: "Poppins", sans-serif;
        --p1: 1rem;
        --p2: .5rem;
      }

      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        list-style: none;
      }

      body {
        font-family: var(--paragraph-font);
        padding: var(--p1);
      }

      h1, h2 {
        font-family: var(--heading-font);
        color: #37a0c0;
      }

      h2 {
        font-size: 1.6rem;
        margin-bottom: var(--p2);
      }

      h1 {
        font-size: 3rem;
        font-weight: bold;
      }

      span {
        color: #37a0c0;
        font-weight: bold;
        font-style: italic;
      }

      p {
        font-size: 1.25rem;
      }

      .main {
        display: flex;
        flex-direction: column;
        gap: var(--p1);
      }

      ul {
        display: flex;
        flex-direction: column;
        gap: var(--p2);
      }
    </style>
  </head>
  <body>
    <main class="main">
      <section>
        <h1>Hi, there 👋!</h1>
        <p>My name is <span>Alan Chala</span>. I'm a systems engineering student focused on learning full-stack development. I'm passionate about learning new things and enjoying every moment of my life to the fullest.</p>
      </section>
      <section>
        <h2>My stack</h2>
        <ul>
          <li>
            <img src="https://skillicons.dev/icons?i=html,css,js,ts,react&theme=dark" alt="Programming icons">
          </li>
          <li>
            <img src="https://skillicons.dev/icons?i=nodejs,mongodb,mysql,express,nextjs&theme=light" alt="Programming icons">
          </li>
          <li>
            <img src="https://skillicons.dev/icons?i=py,tailwind,java,github,git&theme=light" alt="Programming icons">
          </li>
        </ul>
      </section>
      <footer>
        <p>Thanks for watching my profile. You can also see my work!</p>
      </footer>
    </main>
  </body>
</html>
