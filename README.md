
<!DOCTYPE html>
<html lang="en">
   <head>
      <meta charset="UTF-8" />
      <meta name="viewport" content="width=device-width, initial-scale=1" />
      <title>George Lorentzos - Portfolio</title>
      <link rel="icon" href="images/website_icon.svg">
      <meta name="author" content="George Lorentzos">
      <style>
         :root {
         --blue: #4daafc;
         --foreground: #9ba3b4;
         --background: #0D1117;
         --header-foreground: #c3d0e5;
         --codebox: #181f29;
         }
         @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap');
         html, body {
         height: 100%;
         min-height: 100vh;
         margin: 0;
         background: var(--background);
         color: var(--foreground);
         display: grid;
         place-items: center;
         font-family: 'Montserrat', sans-serif;
         line-height: 1.6;
         box-sizing: border-box;
         }
         html::-webkit-scrollbar {
         display: none;
         }
         body {
         padding: 0 15px;
         }
         .container {
         max-width: 600px;
         width: 100%;
         padding: 0 15px;
         border-radius: 8px;
         text-align: left;
         }
         h1 {
         margin-bottom: 0.5em;
         color: var(--header-foreground);
         font-weight: 600;
         }
         .section-title {
         font-weight: 600;
         margin-top: 1.5em;
         margin-bottom: 0.4em;
         color: var(--header-foreground);
         }
         p {
         margin-top: 0.4em;
         margin-bottom: 0.8em;
         }
         a {
         color: var(--blue);
         text-decoration: none;
         }
         .skills {
         font-size: 0.9rem;
         margin: 1rem 0;
         }
      </style>
   </head>
   <body>
      <div class="container">
         <h1>George Lorentzos</h1>
         <p>
            I am a backend developer specializing in Python and Flask, with coding experience since the age of 12. 
            I am committed to building reliable, efficient, and scalable web applications. Currently, I am 
            <span id="age"></span> years old.
         </p>
         <div class="section-title">Technical Skills</div>
         <div class="skills">
            <p><strong>Backend Frameworks:</strong> Flask, Flask-SQLAlchemy, Flask-Login, Flask-WTF, Flask-Bcrypt, Flask-Mail, Flask-SocketIO</p>
            <p><strong>Python Libraries:</strong> Stripe, Werkzeug, Pydantic, Requests, Pytest, Dotenv, Json, Datetime, Os, Pathlib, Random, Threading, Shutil</p>
            <p><strong>Servers & Deployment:</strong> Gunicorn, Uvicorn, Nginx, Ngrok, Cloudflare Tunnel</p>
            <p><strong>Databases & ORM:</strong> PostgreSQL, MySQL, SQLite, ORM (Flask-SQLAlchemy)</p>
            <p><strong>Frontend Basics:</strong> HTML, CSS, JavaScript, Bootstrap</p>
            <p><strong>Tools & Platforms:</strong> Git, Docker, AWS, Microsoft Teams</p>
         </div>
         <span>
   </body>
</html>
