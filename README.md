<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tevin Munene - Product Designer</title>

    <!-- Fonts + Icons -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet" />
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet" />

    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }
      body {
        font-family: 'Inter', sans-serif;
        background: #f8fafc;
        color: #2d3748;
        line-height: 1.6;
      }
      .resume-container {
        max-width: 900px;
        margin: 40px auto;
        background: #fff;
        border-radius: 10px;
        overflow: hidden;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08);
      }
      .header {
        background: linear-gradient(135deg, #667eea, #764ba2);
        color: #fff;
        text-align: center;
        padding: 40px 20px;
      }
      .profile-section {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 10px;
      }
      .profile-image {
        width: 120px;
        height: 120px;
        border-radius: 50%;
        background: rgba(255, 255, 255, 0.15);
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 40px;
        font-weight: 600;
      }
      .full-name {
        font-size: 2rem;
        font-weight: 700;
      }
      .job-title {
        font-size: 1.1rem;
        opacity: 0.9;
      }
      .contact-info {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 15px;
        margin-top: 15px;
      }
      .contact-item {
        display: flex;
        align-items: center;
        gap: 8px;
        font-size: 0.95rem;
        opacity: 0.95;
      }
      .contact-item i {
        font-size: 14px;
      }
      .contact-item a {
        color: #fff;
        text-decoration: none;
      }
      .main-content {
        padding: 30px;
        display: grid;
        gap: 40px;
      }
      .section-title {
        font-size: 1.4rem;
        font-weight: 600;
        color: #2d3748;
        margin-bottom: 15px;
        border-bottom: 2px solid #e2e8f0;
        padding-bottom: 5px;
      }
      .summary-text {
        color: #4a5568;
        text-align: justify;
      }
      .job {
        border-bottom: 1px solid #e2e8f0;
        padding-bottom: 15px;
        margin-bottom: 20px;
      }
      .job-header {
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
        gap: 5px;
      }
      .job-title {
        font-weight: 600;
        color: #2d3748;
      }
      .company-name {
        color: #667eea;
      }
      .job-duration {
        font-size: 0.9rem;
        color: #718096;
      }
      .job-responsibilities {
        margin-top: 10px;
        list-style: none;
      }
      .job-responsibilities li::before {
        content: "▸ ";
        color: #667eea;
        font-weight: bold;
      }
      .education-item {
        margin-bottom: 15px;
      }
      .degree {
        font-weight: 600;
      }
      .institution {
        color: #667eea;
      }
      .skill-tags {
        display: flex;
        flex-wrap: wrap;
        gap: 8px;
      }
      .skill-tag {
        background: linear-gradient(135deg, #667eea, #764ba2);
        color: #fff;
        padding: 6px 12px;
        border-radius: 20px;
        font-size: 0.85rem;
      }
      .project {
        background: #f7fafc;
        border-left: 4px solid #667eea;
        padding: 15px;
        border-radius: 6px;
        margin-bottom: 15px;
      }
      .project h4 {
        font-weight: 600;
        color: #2d3748;
      }
      .project p {
        color: #4a5568;
        font-size: 0.9rem;
        margin-top: 5px;
      }
      .project a {
        display: inline-block;
        margin-top: 8px;
        font-size: 0.85rem;
        color: #667eea;
        text-decoration: none;
      }
      .project a:hover {
        text-decoration: underline;
      }
      @media (max-width: 768px) {
        .full-name { font-size: 1.8rem; }
        .job-header { flex-direction: column; }
      }
      @media (max-width: 480px) {
        .header { padding: 30px 15px; }
        .main-content { padding: 20px; }
        .contact-info { flex-direction: column; gap: 10px; }
        .profile-image { width: 100px; height: 100px; font-size: 32px; }
      }
    </style>
  </head>

  <body>
    <div class="resume-container">
      <header class="header">
        <div class="profile-section">
          <div class="profile-image">TM</div>
          <h1 class="full-name">Tevin Munene</h1>
          <h2 class="job-title">Product Designer</h2>
        </div>
        <div class="contact-info">
          <div class="contact-item"><i class="fas fa-envelope"></i> tevin.munene@email.com</div>
          <div class="contact-item"><i class="fas fa-phone"></i> +254 700 000 000</div>
          <div class="contact-item"><i class="fas fa-map-marker-alt"></i> Nairobi, Kenya</div>
          <div class="contact-item"><i class="fab fa-linkedin"></i> <a href="#">linkedin.com/in/tevinmunene</a></div>
          <div class="contact-item"><i class="fab fa-behance"></i> <a href="#">behance.net/tevinmunene</a></div>
        </div>
      </header>

      <main class="main-content">
        <section>
          <h3 class="section-title">Professional Summary</h3>
          <p class="summary-text">
            Creative and detail-oriented Product Designer with experience in user-centered design. Skilled in research, wireframing, prototyping, and creating intuitive interfaces that improve user experience and business outcomes.
          </p>
        </section>

        <section>
          <h3 class="section-title">Experience</h3>
          <div class="job">
            <div class="job-header">
              <div>
                <div class="job-title">Product Design Student</div>
                <div class="company-name">Moringa School</div>
              </div>
              <div class="job-duration">2023 - 2024</div>
            </div>
            <ul class="job-responsibilities">
              <li>Completed comprehensive product design bootcamp covering UX and UI design.</li>
              <li>Conducted user research, interviews, and usability testing.</li>
              <li>Created wireframes, prototypes, and high-fidelity designs in Figma.</li>
              <li>Collaborated in team projects using design thinking to solve problems.</li>
            </ul>
          </div>
        </section>

        <section>
          <h3 class="section-title">Education</h3>
          <div class="education-item">
            <div class="degree">Product Design Certificate</div>
            <div class="institution">Moringa School (2023 - 2024)</div>
          </div>
        </section>

        <section>
          <h3 class="section-title">Skills</h3>
          <div class="skill-tags">
            <span class="skill-tag">Figma</span>
            <span class="skill-tag">Adobe XD</span>
            <span class="skill-tag">User Research</span>
            <span class="skill-tag">Wireframing</span>
            <span class="skill-tag">Prototyping</span>
            <span class="skill-tag">HTML</span>
            <span class="skill-tag">CSS</span>
            <span class="skill-tag">JavaScript</span>
          </div>
        </section>

        <section>
          <h3 class="section-title">Key Projects</h3>
          <div class="project">
            <h4>Wedding Planner App</h4>
            <p>Designed a wedding planner application to simplify event coordination and vendor communication, focusing on intuitive UX and elegant UI flow.</p>
            <a href="https://www.figma.com/board/Y7us5C4zoG0oSNJMjnJHZc/wedding-planner-app?node-id=0-1&t=VHjcFh4XN0ohNV8q-1" target="_blank">View Project ↗</a>
          </div>
          <div class="project">
            <h4>Grocery List App</h4>
            <p>Created a mobile grocery list app prototype with task management and reminders to improve user convenience and productivity.</p>
            <a href="https://www.figma.com/proto/k5K6dl6NaI16y7m8GCr45m/Grocery-List-App?node-id=19-1829&starting-point-node-id=7%3A2&t=JSbvoHfA1ZeARcRT-1" target="_blank">View Project ↗</a>
          </div>
        </section>
      </main>
    </div>
  </body>
</html>
