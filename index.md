---
layout: home
---

<style>
  /* Modern Styling - Doesn't change your words, just the "frame" */
  /* 1. Center the whole page content */
body {
  margin: 0 auto;
  max-width: 900px; /* Limits width so it's readable */
  padding: 0 40px;  /* Adds 'breathing room' on the sides */
  background-color: #fdfdfd; /* Very subtle off-white for less eye strain */
}

/* 2. Fix the Navigation Bar to span the whole screen but center the text */
.nav-bar {
  position: sticky;
  top: 0;
  width: 100vw;       /* Spans full browser width */
  margin-left: calc(-50vw + 50%); /* Centers the full-width bar on a narrow body */
  background-color: rgba(255, 255, 255, 0.98);
  display: flex;
  justify-content: center;
  gap: 60px;          /* More space between Nav items */
  padding: 25px 0;
  border-bottom: 1px solid #eee;
  z-index: 1000;
}

/* 3. Add more space between major sections */
hr {
  margin: 80px 0;    /* Massive spacing between "About", "Research", and "CV" */
  border: 0;
  border-top: 1px solid #eee;
}

/* 4. Improve text readability */
.about-text {
  line-height: 0.8;   /* More space between lines of text */
  font-size: 1.1rem;
  text-align: justify; /* Optional: makes the edges look clean like a book */
}
  
  body { 
    line-height: 1.6; 
    color: #333; 
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  }
  
  
/* Sticky Navigation Bar - Improved */
  .nav-bar {
    position: sticky;
    top: 0;
    background-color: #ffffff; /* Solid white so text doesn't bleed through */
    padding: 20px 0;
    border-bottom: 2px solid #f0f0f0;
    z-index: 1000;
    display: flex;
    justify-content: center; /* Centers the links horizontally */
    gap: 40px; /* Even spacing between links */
    box-shadow: 0 2px 10px rgba(0,0,0,0.05); /* Soft shadow for depth */
  }

  .nav-bar a {
    text-decoration: none;
    color: #444; /* Dark grey for a professional look */
    font-weight: 600;
    font-size: 1.1rem;
    transition: color 0.3s ease; /* Smooth hover effect */
  }

  .nav-bar a:hover {
    color: #007bff; /* Colors change when you hover */
    border-bottom: 2px solid #007bff;
    padding-bottom: 5px;
  }

  /* Section Spacing */
  h1[id] { scroll-margin-top: 80px; margin-top: 60px; border-bottom: 2px solid #f0f0f0; padding-bottom: 10px; }
  h2 { margin-top: 40px; color: #444; }

  /* Updated Layout for About Section */
  .about-container {
    display: flex;
    flex-wrap: wrap;
    gap: 40px;
    align-items: flex-start; /* Keeps images at the top */
  }

  .about-text { 
    flex: 2; 
    min-width: 300px; 
  }

  .about-image { 
    flex: 1; 
    min-width: 250px; 
    display: flex;
    flex-direction: column; /* Stacks images vertically */
    gap: 20px; /* Modern way to add spacing between stacked items */
  }

  .about-image img { 
    width: 100%; /* Makes images responsive to the column width */
    height: auto;
    border-radius: 20px; /* Increased rounding for a modern look */
    box-shadow: 0 8px 20px rgba(0,0,0,0.1); 
    display: block;
  }

  /* Back to Top Link */
  .back-to-top {
    display: inline-block;
    margin-top: 20px;
    font-size: 0.9rem;
    color: #888;
    text-decoration: none;
  }
</style>

 <div class="nav-bar">

    <a href="#about">About Me</a>

    <a href="#research">Research</a>

    <a href="#cv">Education & Experience</a>

</div> 


Hi! I’m **Annika**, a current first year Economics Ph.D. student at Utrecht University. 

You can download my CV [here.](assets/Annika_Brown_CV.pdf)

---

<a name="about"></a>
<h1 id="about">About Me</h1>

<div class="about-container">
  <div class="about-text">
    My doctoral work centers on early childhood education: access, program design, and impacts in contexts where resources or opportunities are uneven. I look at how early conditions shape later outcomes in school and the labor market, with an emphasis on what works, for whom, and why. I also have an interest in migration and refugee integration.
    <br><br>
    I became interested in these topics through volunteering and interning during high school and my bachelors in the US. I began working with NGOs and community programs at age 15, doing on-the-ground work with children, families, and marginalized groups such as refugees and homeless individuals. Now I combine that practical experience with research, studying the issues I encountered first-hand and seeking solutions that are developed in collaboration with those in need. I’m interested in the intersection of practice and research, and finding ways to apply real-world experiences.  
    <br><br>
    Outside of work and research, I love being outdoors. I enjoy camping, hiking, kayaking, and cycling. I also love to go on adventure trips, whether that is backpacking in Alaska, or horseback riding in Kyrgyzstan.
</div>
  <div class="about-image">
    <img src="{{ '/assets/pic.jpg' | relative_url }}" alt="Annika Brown">
    <img src="{{ '/assets/alaska.jpeg' | relative_url }}" alt="Backpacking in Alaska">
    <img src="{{ '/assets/horse.jpg' | relative_url }}" alt="Horseback riding in Kyrgyzstan">
  </div>
</div>

<a href="#" class="back-to-top">↑ Back to Top</a>

---

<a name="research"></a>
<h1 id="research">Research</h1>

## Ongoing Work

- **Childcare Subsidies, Pre-Primary School Education, and Academic Outcomes in the Netherlands**, Utrecht University

- **How Psychometric Models Shape Impact and Equity in Early Education RCTs**, Utrecht University
  Investigating how measurement models influence the assessment of program impact and equity in an early childhood education RCT in Bulgaria.

- **Are Sanctions Discriminatory?** (in collaboration with Prof. Purba Mukerji, Connecticut College)  
  Studying whether economic or legal sanctions disproportionately negatively impact low- and middle-income countries.

## Data Collection

- **Land Use Decisions in Connecticut** (in collaboration with Kiersten Posey)
  
  Conducted data collection on over 500 land use decision makers (i.e. zoning board members) to understand patterns and representation in Connecticut. Final report published here: [The Room at the Table Report](https://cho.thehousingcollective.org/impact/participation-local-control-land-use-connecticut).

- **Ukrainian and Afghan Refugees in Denmark, Sweden, and Iceland’s Labor Markets**, Connecticut College, Honors Thesis

  Conducted a small-scale RCT to examine labor market outcomes and integration policies for refugees across Nordic countries.

- **Empathy in Toddlers: A Cross-Cultural Comparison of Prosocial Actions**, Aarhus University (DK) & Connecticut College (USA), Independent Study
  
  Observed and analyzed prosocial behaviors in toddlers across different cultural contexts, with a focus on socioeconomic status of the children.

- **Financial Inclusion of the Underprivileged: Mobile Money** (as a RA with Prof. Purba Mukerji, Connecticut College)
  
  Assisted in data collection on mobile money usage and its effects on financial inclusion for low-income communities.

<a href="#" class="back-to-top">↑ Back to Top</a>

---

<a name="cv"></a>
<h1 id="cv">Education & Experience</h1>

## Education

- **Ph.D in Economics**, *Utrecht University*, expected 2029
- **Research Master (M.Sc.) in Multidisciplinary Economics**, *Utrecht University*, 2025  
- **Bachelor of Arts (B.A.) in Quantitative Economics and Econometrics, and Human Development**, *Connecticut College* (with Certificate in Community Action and Public Policy), 2023

---

## Teaching Experience
### University

- **2024** – Tutorial Instructor, *Microeconomics, Welfare & Institutions*, Utrecht University, Netherlands  
- **2024** – Tutorial Instructor, *Intermediate Microeconomics, Games and Behaviour*, Utrecht University, Netherlands  
- **2024–2025** – Tutorial Instructor, *Macroeconomics*, Utrecht University, Netherlands  
- **2023** – Teaching Assistant, *Financial Literacy for Life*, Connecticut College, USA

### Schools & Community
- **2021** – Head Teacher, *Mathematics (Primary school)*, Unreasonable Kids College, USA  
- **2019–2023** – Teaching Assistant, *Toddler Program (Pre-primary school)*, Connecticut College Preschool, USA  
- **2019–2020** – Teaching Assistant, *English as a Second Language (Secondary school)*, New London, USA  
- **2019** – Teacher, *English as a Second Language (Adult learning)*, Paper Airplanes: Education for Refugees, International  
- **2019** – Teaching Assistant, *Mathematics (Primary school)*, Schuylerville Central Schools, USA  
- **2016–2018** – Teaching Assistant, *STEM (Primary school)*, Camp Invention, USA

---

## Community Engagement Experience

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

### Community Leadership Roles
- **2023–2025** – Student Assistant, *Center for Global Challenges*, Utrecht, Netherlands
- **2021–2023** – Fellow, *Holleran Center for Community Action*, Connecticut College, USA  
 
### Academic Leadership Roles
- **2022–2023** – Chair, *Economics Student Advisory Board*, Connecticut College, USA
- **2021–2023** – Chair, *Human Development Student Advisory Board*, Connecticut College, USA
- **2022–2023** – Office Assistant, *Human Development Department*, Connecticut College, USA
- **2021** – Fellow, *PPIA Public Service Weekend*, Carnegie Mellon University, PA, USA  

<a href="#" class="back-to-top">↑ Back to Top</a>
