---
layout: home
---

<style>
  body { 
    line-height: 1.6; 
    color: #333; 
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  }

  /* Top Contact Bar */
  .contact-bar {
    display: flex;
    justify-content: flex-end;
    gap: 15px;
    padding: 10px 0;
    font-size: 0.9rem;
  }
  .btn-contact {
    text-decoration: none;
    color: #555;
    padding: 5px 12px;
    border: 1px solid #ddd;
    border-radius: 20px;
    transition: all 0.3s;
  }
  .btn-contact:hover { background: #f8f9fa; border-color: #007bff; color: #007bff; }

  /* Sticky Nav */
  .nav-bar {
    position: -webkit-sticky; 
    position: sticky; 
    top: 0; 
    background-color: rgba(255, 255, 255, 0.98); 
    backdrop-filter: blur(10px);
    padding: 15px 0; 
    border-bottom: 1px solid #eaeaea; 
    z-index: 1000;
    text-align: center;
    margin-bottom: 40px;
  }
  .nav-bar a { margin: 0 10px; text-decoration: none; color: #007bff; font-weight: 600; font-size: 0.95rem; }

  /* Sections */
  h1[id] { scroll-margin-top: 80px; margin-top: 60px; border-bottom: 2px solid #007bff; display: inline-block; padding-bottom: 5px; }
  
  /* Timeline/Cool List Style */
  .experience-item {
    border-left: 2px solid #e9ecef;
    padding-left: 20px;
    margin-bottom: 25px;
    position: relative;
  }
  .experience-item::before {
    content: "";
    position: absolute;
    left: -7px;
    top: 5px;
    width: 12px;
    height: 12px;
    background: #007bff;
    border-radius: 50%;
  }
  .date-label { font-weight: bold; color: #007bff; display: block; margin-bottom: 2px; }

  .about-container { display: flex; flex-wrap: wrap; gap: 40px; align-items: flex-start; }
  .about-text { flex: 2; min-width: 300px; }
  .about-image { flex: 1; min-width: 250px; text-align: center; }
  .about-image img { border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1); width: 100%; max-width: 300px; }

  .back-to-top { display: block; margin-top: 40px; font-size: 0.8rem; color: #bbb; text-decoration: none; text-align: center; }
</style>

<div class="contact-bar">
  <a href="https://www.linkedin.com/in/YOUR-PROFILE" class="btn-contact">LinkedIn</a>
  <a href="mailto:your.email@uu.nl" class="btn-contact">Email Me</a>
</div>

<div class="nav-bar">
    <a href="#about">About</a>
    <a href="#research">Research</a>
    <a href="#education">Education</a>
    <a href="#teaching">Teaching</a>
    <a href="#community">Community</a>
    <a href="#cv">CV</a>
</div>

Hi! I’m **Annika Brown**, a current Economics Ph.D. student in Utrecht, the Netherlands. I was born in Pennsylvania, grew up in upstate New York, went to college in Connecticut, and now live in the Netherlands. 

---

<h1 id="about">About Me</h1>
<div class="about-container">
  <div class="about-text">
    I’m Annika, a PhD student in Economics at Utrecht University. My doctoral work centers on early childhood education: access, program design, and impacts in contexts where resources or opportunities are uneven. I look at how early conditions shape later outcomes in school and the labor market, with an emphasis on what works, for whom, and why. I also have a strong interest in migration and refugee integration.
    <br><br>
    I became interested in these topics through volunteering and interning during high school and my bachelors in the US. I began working with NGOs and community programs at age 15, doing on-the-ground work with children, families, and marginalized groups such as refugees and homeless individuals. Now I combine that practical experience with research, studying the issues I encountered first-hand and seeking solutions that are developed in collaboration with those in need. I’m interested in the intersection of practice and research, and finding ways to apply real-world experiences.  
    <br><br>
    Outside of work and research, I love being outdoors. I enjoy camping, hiking, kayaking, and cycling. I also love to go on adventure trips, whether that is backpacking in Alaska, or horseback riding in Kyrgyzstan.
  </div>
  <div class="about-image">
    <img src="{{ '/assets/pic.jpg' | relative_url }}" alt="Annika Brown">
    <img src="{{ '/assets/alaska.jpeg' | relative_url }}" alt="Alaska" style="margin-top:15px">
    <img src="{{ '/assets/horse.jpg' | relative_url }}" alt="Kyrgyzstan" style="margin-top:15px">
  </div>
</div>

<h1 id="research">Research</h1>

### Ongoing Work
- **Childcare Subsidies, Pre-Primary School Education, and Academic Outcomes in the Netherlands**, Utrecht University
- **How Psychometric Models Shape Impact and Equity in Early Education RCTs**, Utrecht University  
  Investigating how measurement models influence the assessment of program impact and equity in an early childhood education RCT in Bulgaria.
- **Are Sanctions Discriminatory?** (in collaboration with Prof. Purba Mukerji, Connecticut College)    
  Studying whether economic or legal sanctions disproportionately negatively impact low- and middle-income countries.

### Data Collection
- **Land Use Decisions in Connecticut** (in collaboration with Kiersten Posey)  
  Conducted data collection on over 500 land use decision makers (i.e. zoning board members) to understand patterns and representation in Connecticut. Final report published here: [The Room at the Table Report](https://cho.thehousingcollective.org/impact/participation-local-control-land-use-connecticut).
- **Ukrainian and Afghan Refugees in Denmark, Sweden, and Iceland’s Labor Markets**, Connecticut College, Honors Thesis  
  Conducted a small-scale RCT to examine labor market outcomes and integration policies for refugees across Nordic countries.
- **Empathy in Toddlers: A Cross-Cultural Comparison of Prosocial Actions**, Aarhus University (DK) & Connecticut College (USA), Independent Study  
  Observed and analyzed prosocial behaviors in toddlers across different cultural contexts, with a focus on socioeconomic status of the children.
- **Financial Inclusion of the Underprivileged: Mobile Money** (as a RA with Prof. Purba Mukerji, Connecticut College)  
  Assisted in data collection on mobile money usage and its effects on financial inclusion for low-income communities.

<h1 id="education">Education</h1>
<div class="experience-item">
  <span class="date-label">Expected 2029</span>
  <strong>Ph.D in Economics</strong>, <em>Utrecht University</em>
</div>
<div class="experience-item">
  <span class="date-label">2025</span>
  <strong>Research Master (M.Sc.) in Multidisciplinary Economics</strong>, <em>Utrecht University</em>
</div>
<div class="experience-item">
  <span class="date-label">2023</span>
  <strong>Bachelor of Arts (B.A.) in Quantitative Economics and Econometrics, and Human Development</strong>, <em>Connecticut College</em> (with Certificate in Community Action and Public Policy)
</div>

<h1 id="teaching">Teaching Experience</h1>

### University
<div class="experience-item">
  <span class="date-label">2024–2025</span>
  <strong>Tutorial Instructor</strong>, <em>Macroeconomics</em>, Utrecht University, Netherlands
</div>
<div class="experience-item">
  <span class="date-label">2024</span>
  <strong>Tutorial Instructor</strong>, <em>Microeconomics, Welfare & Institutions</em>, Utrecht University, Netherlands
</div>
<div class="experience-item">
  <span class="date-label">2024</span>
  <strong>Tutorial Instructor</strong>, <em>Intermediate Microeconomics, Games and Behaviour</em>, Utrecht University, Netherlands
</div>
<div class="experience-item">
  <span class="date-label">2023</span>
  <strong>Teaching Assistant</strong>, <em>Financial Literacy for Life</em>, Connecticut College, USA
</div>

### Schools & Community
- **2021** – Head Teacher, *Mathematics (Primary school)*, Unreasonable Kids College, USA
- **2019–2023** – Teaching Assistant, *Toddler Program (Pre-primary school)*, Connecticut College Preschool, USA
- **2019–2020** – Teaching Assistant, *English as a Second Language (Secondary school)*, New London, USA
- **2019** – Teacher, *English as a Second Language (Adult learning)*, Paper Airplanes: Education for Refugees, International
- **2019** – Teaching Assistant, *Mathematics (Primary school)*, Schuylerville Central Schools, USA
- **2016–2018** – Teaching Assistant, *STEM (Primary school)*, Camp Invention, USA

<h1 id="community">Community Engagement</h1>

### Migration and Refugees
- **2023** – Participant, *United States Department of Education: Refugees & Migration Seminar*, Amman, Jordan
- **2022** – Intern, *Icelandic Human Rights Centre*, Reykjavik, Iceland
- **2022** – Volunteer, *Danish Refugee Council*, Copenhagen, Denmark

### Homelessness and Youth Development
- **2023–2024** – Intern, *Centers for Housing Opportunity*, Eastern Connecticut, USA
- **2021** – Intern, *Southeastern Connecticut Community Land Trust*, New London, CT, USA
- **2021** – Intern, *Elks Club Food Pantry*, New London, CT, USA
- **2020** – Intern, *New London Homeless Hospitality Center*, New London, CT, USA
- **2017–2019** – Mentor, *Project LIFT*, Saratoga Springs, NY, USA

### Leadership Roles
- **2023–2025** – Student Assistant, *Center for Global Challenges*, Utrecht, Netherlands
- **2021–2023** – Fellow, *Holleran Center for Community Action*, Connecticut College, USA
- **2022–2023** – Chair, *Economics Student Advisory Board*, Connecticut College, USA
- **2021–2023** – Chair, *Human Development Student Advisory Board*, Connecticut College, USA
- **2022–2023** – Office Assistant, *Human Development Department*, Connecticut College, USA
- **2021** – Fellow, *PPIA Public Service Weekend*, Carnegie Mellon University, PA, USA

<h1 id="cv">Full Curriculum Vitae</h1>
You can download my full CV here: 
<br><br>
<a href="assets/Annika_Brown_CV.pdf" style="background:#007bff; color:white; padding:10px 20px; border-radius:5px; text-decoration:none; font-weight:bold;">Download PDF</a>

<a href="#" class="back-to-top">↑ Back to Top</a>
