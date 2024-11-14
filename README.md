# Personal Profile Website

This is a personal profile website designed and developed using HTML and styled with CSS. It showcases key sections such as Home, About, Services, Portfolio, and Contact.

## Project Overview

The website consists of several sections:

1. **Home**: Displays a profile picture and introduction.
2. **About**: Provides a brief introduction of me, detailing interests in software engineering, design, and technology.
3. **Services**: Lists services such as Web Design, Graphics Designing, and Copyright services.
4. **Portfolio**: Displays a showcase of projects related to design and development.
5. **Contact**: Contains contact information and a contact form for inquiries.
6. **Footer**: Contains copyright information.



## Table of Contents

1. [Home](#home)
2. [About](#about)
3. [Services](#services)
4. [Portfolio](#portfolio)
5. [Contact](#contact)
6. [Footer](#footer)





## Code Breakdown

### 1. **Home Section**
```html
<section id="home" class="hero">
    <div class="hero-content">
        <img src="02240365.JPG" alt="Profile Picture" class="profile-pic">
        <h1>I am Sonam Zangmo</h1><br>
        <p class="subtitle">I am a Software Engineering Student</p>
    </div>
</section>
```

The home section introduces the user with a profile image and a subtitle.

### 2. About Section
```html
<section id="about" class="about">
    <h2>About Me</h2><br>
    <div class="about-content">
        <div class="about-text">
            <p>Hello There, I am <b>Sonam Zangmo</b></p><br>
            <p>A passionate Software Engineering student with a keen interest in both back-end and front-end development. I love exploring the intersection of design and technology, and I enjoy bringing ideas to life through intuitive and user-friendly interfaces. 

            <br><br>Proficient in Figma, I use my design skills to craft engaging digital experiences while continuously learning and evolving my technical expertise. When I'm not coding or designing, you can find me exploring the latest trends in technology and UI/UX.</p>
        </div>
    </div>
</section>
```
The About section highlights the user's skills, interests, and tools (such as Figma) used for design.

### 3. Services Section
```html
<section id="services" class="services">
    <h2>Services</h2><br>
    <p>As a first-year software engineering student with a passion for design, I utilize Figma to create intuitive 
        and visually engaging user interfaces. My focus is on merging technical skills with creative design 
        solutions to build functional and user-centered digital experiences.</p><br>
    <div class="services-grid">
        <div class="service">
            <i class="icon">❤️</i><br><br>
            <h3>Web Design</h3><br>
            <p>Offering web design services for personal profiles, specializing in clean, responsive designs using Figma. Tailored for first-year software engineering students.</p>
        </div>
        <div class="service">
            <i class="icon">📄</i><br><br>
            <h3>Copyright</h3><br>
            <p>You can protect personal profile designs in Figma by registering copyrights or using licenses through creative services like Creative Commons.</p>
        </div>
        <div class="service">
            <i class="icon">✨</i><br><br>
            <h3>Graphics Designing</h3><br>
            <p>I offer graphic design services for personal profiles using Figma, tailored for first-year software engineering students seeking unique visual identity.</p>
        </div>
    </div>
</section>
```
The Services section explains the user's offerings, including web design, copyright, and graphic design services.

### 4. Portfolio Section
```html
<section id="portfolio" class="portfolio">
    <h2>Portfolio</h2><br>
    <p>My portfolio showcases my journey in design and development. Using Figma, I create intuitive user interfaces and engaging layouts. My projects emphasize problem-solving and creativity, reflecting my commitment to learning and growth in both software engineering and design principles</p><br>
    <div class="portfolio-filter">
        <button>All</button>
        <button>Web Design</button>
        <button>UI/UX</button>
        <button>Development</button>
    </div>
    <div class="portfolio-grid">
        <div class="portfolio-item"><img src="coding.jpg" alt="Project 1"></div>
        <div class="portfolio-item"><img src="code2.jpg" alt="Project 2"></div>
        <div class="portfolio-item"><img src="code3.jpg" alt="Project 3"></div>
        <div class="portfolio-item"><img src="code 4.jpg" alt="Project 4"></div>
        <div class="portfolio-item"><img src="code5.jpg" alt="Project 5"></div>
    </div>
</section>
```
The Portfolio section features a filterable gallery to display the user's work in design and development.

### 5. Contact Section
```html
<section id="contact" class="contact">
    <h2>Get In Touch</h2><br>
    <p>I’m excited to design my personal profile in Figma. I aim to showcase my skills, projects, and experiences creatively and engagingly. I’m eager to learn and explore design principles to make my profile stand out and reflect my passion for technology and innovation.</p><br>
    <div class="contact-info">
        <div class="contact-item">
            <i class="icon">📞</i><br><br>
            <p>Call Me</p><br>
            <p>+975 17948142</p>
        </div>
        <div class="contact-item">
            <i class="icon">📍</i><br><br>
            <p>Address</p><br>
            <p>CST, Bhutan</p>
        </div>
        <div class="contact-item">
            <i class="icon">✉️</i><br><br>
            <p>Email</p><br>
            <p>02240365.cst@rub.edu.bt</p>
        </div>
    </div>
    <form class="contact-form" action="contact_form.php" method="POST">
        <input type="text" name="name" placeholder="Name" required>
        <input type="email" name="email" placeholder="Email" required>
        <textarea name="message" placeholder="Message" required></textarea>
        <button type="submit">Send Message</button>
    </form>        
</section>
```
The Contact section provides the user’s contact details and a form for visitors to send messages.

### 6. Footer Section
```html
<footer>
    <p>&copy; 2024 Sonam Zangmo. All rights reserved.</p>
</footer>
```
The Footer section includes a copyright notice.

