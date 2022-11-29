# JOAOMARKS.github.io




!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1,0">
  <title>Joao Marcos CV</title>
  <!-- Custom CSS -->
  <link rel="stylesheet" href="style2.css">
</head>
<body>
  <main class="resume-contents">
    <section class="left-section">
      <section class="left-section-content">
        <div class="profile">
          <img class="profile-image" src="\Users\joaom\Downloads\ft.jpg" alt="Profile image">
          <p class="name">Joao Marcos </p>
          <p class="profission">ALUNO</p>
        </div>
        <div class="contact-info">
          <p class="left-title">contato</p>
          <ul>
            <li><i class="fa fa-phone"></i>+55 87 98174-3442</li>
            <li><i class="fa fa-envelope"></i>joao.marcos.2.hotmail@gmail.com</li>
            <li><i class="fa fa-github"></i>JOAOMARCKS</li>
          </ul>
        </div>
        <div class="skills">
          <p class="left-title">skills</p>
          <ul>
            <li><p>python, html.</p></li>
          </ul>
        </div>
      </section>
    </section>
      <section class="right-section">
        <div class="right-section-contents">
          <section class="about gap">
            <div class="right-title">Sobre Mim</div>
            <p class="about-me-contents">
              Olá sou o Joao Marcos.<br>
              estou fazendo COISAS.<br>
            </p>
          </section>
        </div>
        <section class="experience gap">
          <div class="right-title">Experiencia</div>
          <div class="experience-contents">
            <div class="exp-left">
              <p class="exp-company-name">Empresa-01</p>
              <p class="exp-time-period">2021-Present</p>
            </div>
            <div class="exp-right">
              <p class="exp-positiion">GRB</p>
              <p class="exp-desc">
                atividades perito tec em gbr
              </p>
            </div>
          </div>
        </section>
        <section class="education gap">
          <div class="right-title">Formação Academica</div>
          <div class="education-contents">
            <div class="education-left">
            <p class="education-school-name">Estacio</p>
            <p class="education-time-period">2021~2025</p>
          </div>
          <div class="education-rigth">
            <p class="education-subject">Sistema da Imformação</p>
          </div>
        </div>
        </section>
     </section>
  </main>
</body>
</html>
style.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    list-style: none;
    font-family: 'Roboto', sans-serif;
}

.resume-contents {
    min-height: 100vh;
    width: 80%;
    margin: 2rem auto;
    display: grid;
    grid-template-columns: repeat(7, 1fr);
}

.left-section {
    grid-column: span 2;
    height: 100%;
    background-color: #999999;
}

.right-section {
    grid-column: span 5;
    height: 100%;
    background-color: #424a50;
    border-radius: 0px 60px 0px 0px;
}

.left-section-contents{
    padding: 2rem 2rem;
}

.profile {
    width: 100%;
    border-bottom: 2px solid #eeeeee;
}

.profile .profile-image {
    width: 100%;
    border-radius: 100%;
}

.name {
    color: #D6DBDF;
    font-size: 30px;
    letter-spacing: 2px;
    text-transform: uppercase;
}

.profession {
    color: #eeeeee;
    font-size: 20px;
    text-transform: uppercase;
    text-align: center;
}

/* .contact-info { border-bottom: 2px solid #1B2631; } */
.left-title {
    color: #eeeeee;
    font-size: 20px;
}

.contact-info ul {
    padding-top: 1.5rem;
}

.contact-info ul li,
.references ul li {
    padding: .4rem 0;
    color: #eeeeee;
}

.contact-info ul li i,
.references ul li i {
    padding-right: 1rem;
    font-size: 18px;
    color: #eeeeee;
}

.skills ul {
    padding-top: 1.5rem;
}
.skills ul li p {
    padding: .4rem 0;
    color: #eeeeee;
}

.right-section-contents {
    padding: 2rem 2rem;
}

.right-title {
    color: #eeeeee;
}
.education-left {
    color: #eeeeee;
}
.education-rigth {
    color: #eeeeee;
}

.gap {
    padding-bottom: 2rem;
}
.about-me-contents {
    font-size: 18px;
    color: #eeeeee;
}

.experience-contents,
.education-contents,
.awards-contents {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    padding-bottom: 2rem;
    color: #F1F8FD;
}

.exp-company-name,
.education-school-name,
.awards-company-name {
    font-size: 25px;
    font-weight: bold;
}

.exp-time-period,
.educationp-time-period,
.awards-time-period {
    font-size: 18px;
}

.exp-position,
.education-subject,
.awards-name {
    font-size: 25px;
}

.exp-desc,
.education-desc,
.awards-desc {
    font-size: 16px;
    padding-left: 5px;
}
