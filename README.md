# Discover-Tunisia
 
🌍 Discover Tunisia

Click here to explore the live version of my website:
👉 https://dev-by-ahlem.github.io/discover-tunisia/

![Mockup-devices](assets/images/screenshots/mockup.png)
 
 ## 📑Table of Contents

- [Updates](#project-updates)
- [Project Goals](#project-goals)
- [Responsive Design](#responsive-design)
- [Target Audience](#target-audience)
- [User Goals](#user-goals)
- [User Experience (UX)](#user-experience-ux)
- [Website-Flowchart](#flowchart)
- [User Stories & Acceptance Criteria](#user-stories--acceptance-criteria)
  - [User Story 1: User-friendly navigation and responsive design (must-have)](#user-story-1-User-friendly-navigation-and-responsive-design-(must-have))
  - [User Story 2: High-quality images and engaging descriptions (must-have)](#user-story-2-High-quality-images-and-engaging-descriptions-(must-have))
  - [User Story 3: Detailed destination and culture information with interactive gallery (must-have)](#User-Story-3:Detailed-destination-and-culture-information-with-interactive-gallery-(must-have))
  - [User Story 4: Contact form for inquiries (must-have)](#user-story-4-Contact-form-for-inquiries-(must-have))
  - [User Story 5: Subtle animations and micro-interactions (must-have)](#User-Story-5:-Subtle-animations-and-micro-interactions-(should-have))
  - [User Story 6: Social media integration (should-have)](#user-story-6-Social-media-integration-(should-have))
  - [User Story 7: Newsletter sign-up form (could-have)](#User-Story-7:-Newsletter-sign-up-form-(could-have))
  - [User Story 8: Interactive map for destinations (could-have)](#User-Story-8:-Interactive-map-for-destinations-(could-have))
  - [User Story 9: User testimonials (could-have)](#user-story-10-User-testimonials-(could-have))
  - [User Story 10: Location, contact details, and travel information (could-have)](#User-Story-10:-Location,-contact-details,-and-travel-information-(could-have))
  - [User Story 11: Travel quiz or itinerary builder (could-have)](#User-Story-11:-Travel-quiz-or-itinerary-builder-(could-have))
- [Design Justification](#design-justification)
  - [Color Palette](#color-palette)
  - [Imagery & Themes](#imagery-themes)
- [Pages Overview](#page-overview)
  - [Home Page](#home)
  - [Destinations Page](#destinations)
  - [Culture Page](#culture)
     - [Food & Drinks](#[food-drinks)
     - [Traditions](#traditions)
     - [Arts & Crafs](#art-craft)
     - [Traditional Clothing](#traditional-clothing)
  - [Contact Page](#contact)
- [Screenshots](#screenshots)
  - [Home Page](#homepage-screenshots)
  - [Destinations Page](#destinationspage-screenshots)
  - [Culture Page](#culture-page-screenshots)
  - [Contact Page](#contact-page-screenshots)
- [Technologies Used](#technology-used) 
- [Using AI](#using-ai) 
- [Wireframe Home Page](#wireframe)
  - [Desktop](#desktop)
  - [Mobile](#mobie)
- [Bugs & Errors](#bugs-erros)
- [Planned Future Updates](#planned-future-updates)
- [Deployment Procedure](#deployment-procedure)

    ---------------------
    ---------------------
 ## 🔄Updates

### ✔️Mockup generated using Canva

At the top of this README, a **mockup generated using Canva** showcases screenshots of the website displayed on different devices, including desktop, tablet, laptop and mobile. This visual overview highlights the website’s responsive design and ensures a quick, at-a-glance understanding of how the layout adapts across screen sizes.

  ### ✔️Scrolling Gallery Enhancements
  - Implemented a pure CSS scrolling gallery using @keyframes to animate horizontal movement.
  - Used transform: translateX() to shift the entire image track from right to left smoothly.
  - Applied a linear animation to maintain constant scrolling speed across all devices.
  - Ensured the gallery remains fully responsive by using flexible image sizing and overflow control.

  ### ✔️Using CSS Variables

  “This project uses CSS variables defined in the :root selector to create a centralized design system. This approach improves maintainability, ensures visual consistency, and makes it easy to implement theming such as dark mode by updating variables in one place.”

![Css Variable](assets/images/screenshots/root.png)

  ### ✔️Naming Conventions

  - All **HTML, CSS, and image file names** now follow a consistent naming convention:
  - **Lowercase letters**
  - **Hyphens (`-`)** to separate words  
  _Example: `hero-destination.jpg`, `kairaoun.mosque.png`_   
 
 ## 🎯Project Goals
    
- Create an informative and visually engaging website that showcases Tunisia as a travel destination.
- Promote Tunisia’s rich culture, history, and landscapes through high-quality images, interactive sections, and well-structured content.
- Provide visitors with clear and useful travel information, including destinations, cultural insights, and practical tips.
- Inspire users to explore Tunisia by creating an immersive and user-friendly experience that highlights the country’s beauty and diversity.
- Encourage engagement through modern design, smooth interactions, and accessible navigation across all devices.
  
## 📱Responsive Design

- The website was designed with flexibility in mind, allowing it to adapt smoothly to different screen sizes and devices, from large desktop displays to tablets and smartphones.
- This was achieved using Bootstrap’s grid system alongside custom CSS media queries to ensure a consistent and user-friendly experience.

## 🎯Target Audience

- Visitors: The website is designed for visitors who want to explore Tunisia through a modern and visually engaging portfolio-style experience. 
- Travel & Business Interest: It also targets travelers and travel agencies by helping connect people interested in discovering Tunisia’s destinations, culture, and tourism opportunities.  

## 🌟User Goals

- The Discover Tunisia website is designed to support the needs of different types of visitors.
- Below are the main goals users want to achieve when visiting the site:
    - Learn about Tunisia quickly through clear sections, images, and descriptions.
    - Explore destinations and understand what each place offers.
    - Discover Tunisian culture, including food, clothing, and traditions.
    - View high‑quality images to visualize the country before visiting.
    - Use a simple contact form to ask questions or request more information.
    - Navigate easily thanks to a clean layout and responsive design.
    - Enjoy a modern experience with subtle animations and interactive elements.

## 🎨User Experience (UX)

- The Discover Tunisia website is designed to offer a smooth, enjoyable, and intuitive experience for all visitors. The UX focuses on clarity, simplicity, and visual engagement.
- The Discover Tunisia website is designed to support the needs of different types of visitors.
- Below are the main goals users want to achieve when visiting the site:
     - Learn about Tunisia quickly through clear sections, images, and descriptions.
     - Explore destinations and understand what each place offers.
     - Discover Tunisian culture, including food, clothing, and traditions.
     - View high‑quality images to visualize the country before visiting.
     - Find essential travel information, including contact details and location.
     - Use a simple contact form to ask questions or request more information.
     - Navigate easily thanks to a clean layout and responsive design.
     - Stay connected through social media links and optional newsletter sign‑up.
     - Enjoy a modern experience with subtle animations and interactive elements.

 ## 📐Flowchart

  - This flowchart represents the navigation structure of the Discover Tunisia website.
  - All pages — Home, Destinations, Culture, and Contact — are fully accessible from one another through the main navigation bar, ensuring smooth and intuitive browsing. 
  - The arrows in the diagram show the possible navigation paths, highlighting that every section can be reached directly without unnecessary steps.

 🌀The flowchart was created using Miro to visually map out the user journey and overall site architecture.

 ![Flowchart](assets/images/screenshots/flowchart.png)

 ## 👥User Stories & Acceptance Criteria

### 1️⃣User Story 1: User-friendly navigation and responsive design(must-have)

**User story:**  

As a First-Time Visitor, I need easy navigation and a user-friendly design, including a responsive layout for my device, so I can find information quickly and efficiently without frustration.

### Acceptance Criteria

- The website is fully responsive across various devices and screen sizes.
- The site layout and navigation are intuitive, allowing easy access to different sections.

### Tasks

- Apply responsive design principles using Bootstrap to ensure the website is accessible on various devices.
- Arrange the site layout and navigation based on best practices, ensuring all key sections and pages are easily accessible.

---

### 2️⃣User Story 2: High-quality images and engaging descriptions (must-have)

**User story:**  

As a Tourist, I want to see high-quality images and engaging descriptions of Tunisia's destinations and culture, so I can decide if it's the right place for me to visit and explore.

### Acceptance Criteria

- The homepage features a hero section and high-quality scrolling images of Tunisia that rotate automatically and pause when hovered over.
- Engaging descriptions of destinations and cultural aspects are displayed clearly and concisely within the site's content.
- The homepage layout prominently features the images and descriptions in an uncluttered manner.

### Tasks

- Integrate high-quality images of Tunisia into the website using a CSS-based scrolling animation.
- Embed engaging descriptions for destinations and culture within the site's content.
- Design and implement a homepage layout that prominently features the images and descriptions.

---

### 3️⃣User Story 3: Detailed destination and culture information with interactive gallery (must-have)

**User story:**  

As a Traveler, I want to find clear information about destinations, culture, and experiences, along with an interactive gallery of images with hover effects, so I can plan my visit based on my interests and preferences while visualizing the places.

### Acceptance Criteria

- Clear and accurate information about destinations and culture is displayed and easy to find.
- Detailed descriptions are presented on dedicated pages.
- An interactive gallery includes hover effects and image modals.

### Tasks

- Display information about destinations using engaging content.
- Clearly present cultural information with detailed descriptions.
- Create an integrated gallery section with hover effects and image modals.

---

### 4️⃣User Story 4: Contact form for inquiries (must-have)

**User story:**  

As a Visitor, I want to send inquiries using a simple contact form, so I can easily get more information or assistance for my trip.

### Acceptance Criteria

- The contact form is easy to find and simple to use.
- The form includes all necessary fields: Name, Email, Message.
- All fields must be completed before the user can submit the form.
- When the form is completed correctly, the user receives a success message.

### Tasks

- Implement a contact form on the website.
- Apply HTML validation to ensure all required fields are completed.
- Create a success message or page to confirm submission.
  
---

### 5️⃣User Story 5: Subtle animations and micro-interactions (must-have)

**User story:** 

As a User, I want smooth animations and interactions (e.g., fade-ins, hover effects), so the website feels modern and engaging without being distracting.

### Acceptance Criteria

- Elements like buttons, images, and sections include subtle CSS animations.
- Animations enhance user experience without affecting performance.

### Tasks

- Add CSS transitions and animations to interactive elements.
- Test performance on various devices.

### 6️⃣User Story 6: Social media integration (could-have)

**User story:**

As a Visitor, I want links to social media for real-time updates and community engagement, so I can stay connected and see current happenings in Tunisia.

### Acceptance Criteria

- Social media icons in the footer link to relevant accounts.
- Optional embedded feeds or posts if applicable.

### Tasks

- Add social media icons to the footer.
- Link to Tunisia tourism or related accounts.

---

### 7️⃣User Story 7: Newsletter sign-up form (could-have)

**User story:**  

As a Regular Visitor, I want to sign up for newsletters and updates, so I can stay informed about travel tips, new destinations, and cultural events.

### Acceptance Criteria

- The website includes a newsletter sign-up form.
- The form is placed in the footer on every page.

### Tasks

- Integrate the newsletter sign-up form into the website footer.

---

### 8️⃣User Story 8: Interactive map for destinations (could-have)

**User story:**  

As a Traveler, I want an interactive map showing key destinations in Tunisia, so I can visualize locations and plan my itinerary more effectively.

### Acceptance Criteria

- An embedded interactive map (e.g., Google Maps) highlights major destinations.
- The map is easy to navigate and includes markers with brief information.

### Tasks

- Embed an interactive map on the destinations page.
- Add markers and popups for each destination.

---
### 9️⃣User Story 9: User testimonials (could-have)

**User story:**  

As a Prospective Visitor, I want to read testimonials from other travelers, so I can gain insights from real experiences and build confidence in visiting Tunisia.

### Acceptance Criteria

- A testimonials section displays quotes and ratings from visitors.
- Testimonials are presented in an attractive, easy-to-read format.

### Tasks

- Create a testimonials section on the home or culture page.
- Populate it with sample testimonials.

----

### 🔟User Story 10: Location, contact details, and travel information (could-have)

**User story:**  

As a Prospective Traveler, I need to find essential information such as location highlights, contact details, and travel tips clearly and concisely, so I can easily plan my visit or get in touch.

### Acceptance Criteria

- The website contains a dedicated section for contact details and travel information.
- This section is clearly visible and accessible from all parts of the website.

### Tasks

- Design and place a section for contact details and travel information.
- Ensure the contact section is clearly visible and accessible from all parts of the website, adhering to common design standards.

### 1️⃣1️⃣User Story 11: Travel quiz or itinerary builder (could-have)

**User story:**  

As a Tourist, I want a fun quiz or simple tool to help build a personalized itinerary, so I can customize my trip based on my interests.

### Acceptance Criteria

- A quiz or builder asks questions about user preferences (e.g., beaches, history).
- It provides tailored suggestions based on answers.

### Task

- Implement a simple based quiz.
- Display results with recommended destinations.

---

## 🎨Design Justification

The visual design of Discover Tunisia is crafted to reflect the essence of the country: warm, vibrant, cultural, and naturally beautiful. Every color, image, and layout choice supports the goal of presenting Tunisia as a welcoming destination rich in history, landscapes, and traditions.

  ### 🌈Color Palette

  - Warm gold tones are used to represent heritage, tradition, and elegance. Gold reflects Tunisia’s historical richness, from ancient architecture to artisanal crafts, and adds a premium, modern touch to the interface.
  - Soft beige and white backgrounds create clarity, balance, and readability, allowing images and cultural elements to stand out without overwhelming the user.
  - Deep blues and Mediterranean-inspired accents subtly reference Tunisia’s coastline, evoking feelings of calm, travel, and exploration.
  - The palette is intentionally minimal so that the vibrant images of food, clothing, and destinations become the main visual storytellers.Warm gold tones are used to represent heritage, tradition, and elegance. Gold reflects Tunisia’s historical richness, from ancient architecture to artisanal crafts, and adds a premium, modern touch to the interface.

  ![Palette](assets/images/screenshots/palette.png)


  ### ✍️Typography : Google font

  - The website uses Playfair Display for headings to create an elegant, cultural, and traditional feel that reflects Tunisia’s heritage.
  - Lato is used for body text because it is modern, clean, and highly readable on all screen sizes, including mobile devices.
  - The combination of a serif font (Playfair Display) and a sans‑serif font (Lato) creates a balanced visual identity that feels both authentic and contemporary, matching the website’s goal of showcasing Tunisia’s culture in a modern way.
  
  ![Font](assets/images/screenshots/font.png)

## 📄Pages Overview
     
  - All pages contain: Navbar, Hero and Footer

### 🏠Home Page
    
  - The Home page introduces the website with a welcoming hero image, a short introduction, and a visual gallery that highlights Tunisia’s beauty. 
  - It sets the tone for the site and guides users toward exploring destinations, culture, and contact options.


### 📍Destinations Page
      
  - The Destinations page presents a collection of key Tunisian locations through images and short descriptions. 
  - It gives users a quick visual overview of the country’s most iconic regions and encourages them to explore each place.

  ### 🎭Culture Page

  - The Culture page is divided into four interactive sub‑sections — Food & Drink, Traditions, Arts & Crafts, and Traditional Clothing. 
  - Each tab presents a different aspect of Tunisian culture, allowing users to explore the country’s heritage in a structured and engaging way. 
  - All sections are accessible through the tab navigation at the top of the page.
  - The four interactive sub‑sections are:
  
### Section 1: 🍽️Food & Drinks 

  - This section showcases Tunisia’s rich culinary heritage through a grid of realistic food images. 
  - Each card includes a dish photo and a short description, highlighting traditional meals such as couscous, brik, lablabi, and mint tea. 
  - The layout is visual and appetizing, designed to immerse users in the flavors of Tunisia. 

### Section 2:🎉Traditions

  - The Traditions tab presents cultural practices, celebrations, and customs in a clean text‑based layout. 
  - Each item includes an icon, a title, and a short explanation.
  - This section focuses on storytelling — explaining rituals, seasonal events, and daily cultural habits that shape Tunisian life.

### Section 3:🎨Arts & Crafts

  - This section highlights Tunisia’s artistic identity through text cards describing traditional crafts such as pottery, weaving, wood carving, and mosaic art. 
  - The layout is simple and elegant, allowing users to learn about the craftsmanship and creativity behind Tunisian artisanal work.


  ### Section 4:👗Traditional Clothing

  - The Traditional Clothing tab displays a gallery of realistic images featuring iconic Tunisian garments such as the sefsari, jebba, barnous, chechia, and kachabia.
  -  Each card includes an image and a short description, helping users understand the cultural significance and regional variations of these outfits.

## ✉️Contact Page

- The Contact page provides a simple way for users to get in touch. 
- It includes a short checklist, a clean contact form, and a confirmation message after submission, making communication easy and accessible.

## 📸Screenshots

### 🏠Home Page

  🖥️ Desktop Screenshots

![Home-Desktop-Screenshot](assets/images/screenshots/home-ls.png)

  📱 Mobile Screenshots

![Home-Mobile-Screenshot](assets/images/screenshots/home-ss.png)

### 📍Destinations Page
  
  🖥️ Desktop Screenshots

![Destinations-Mobile-Screenshot](assets/images/screenshots/destination-ls.png)

  📱 Mobile Screenshots

![Destinations-Mobile-Screenshot](assets/images/screenshots/destination-ss.png)

### 🎭Culture Page

  ### 🍽️Food & Drinks

  🖥️ Desktop Screenshots

  ![Food-Mobile-Screenshot](assets/images/screenshots/food-ls.png)

  📱 Mobile Screenshots

  ![Food-Mobile-Screenshot](assets/images/screenshots/food-ss.png)

  ### 🎉Traditions

  🖥️ Desktop Screenshots

  ![Tradition-Desktop-Screenshot](assets/images/screenshots/tradition-ls.png)

  📱 Mobile Screenshots

  ![Tradition-Mobile-Screenshot](assets/images/screenshots/tradition-ss.png)

  ### 🎨Arts & Crafts

  🖥️ Desktop Screenshots

  ![Art-Craft](assets/images/screenshots/art-ls.png)

  📱 Mobile Screenshots

  ![Art-Craft](assets/images/screenshots/art-ss.png)

  ### 👗Traditional Clothing

    🖥️ Desktop Screenshots

  ![Traditional-Desktop-Screenshot](assets/images/screenshots/clothing-ls.png)

    📱 Mobile Screenshots

  ![Traditional-Mobile-Screenshot](assets/images/screenshots/clothing-ss.png)

## ✉️Contact Page

    🖥️ Desktop Screenshots

  ![Contact-Mobile-Screenshot](assets/images/screenshots/contact-ls.png)

    📱 Mobile Screenshots

   ![Contact-Mobile-Screenshot](assets/images/screenshots/contact-ss.png)


 ## ⭐Technologies Used 

 - My project was developed using a combination of modern web technologies and professional development tools.

 ![Technologies-Used](assets/images/screenshots/technologies.png)

### ⭐HTML: 

- I used HTML5 to build the structure of my website, organize the content into sections, and create a clean semantic layout.

### ⭐CSS: 

- I used CSS3 to style the entire website, control colors, spacing, fonts, and make the design visually consistent.

### ⭐Bootstrap

- I used Bootstrap to speed up the design process with its responsive grid system and ready‑made components.

### ⭐JavaScript

- I used JavaScript to validate the contact form and control the custom popup that appears after submitting.

### ⭐VS Code

- I used VS Code as my main code editor because it helped me organize my files, preview my project, and work efficiently.

### ⭐GitHub

- I used GitHub to store my project online, track my changes, and keep a clean version history during development.

### ⭐Git

- I used Git for version control to track project changes and manage the development workflow efficiently.

### ⭐Canva (for mockups)

- I used Canva to design the visual mockups of my website, helping me plan the layout, colors, and overall look before starting the coding phase.

### ⭐Miro (for flowchart)

- I used Miro to create the flowchart of my website structure, which helped me visualize the navigation between pages and organize the user journey clearly.

## 🤖Using AI 

- AI tools played an important role in helping me build, improve, and polish this project. 

- I combined multiple AI assistants to benefit from their different strengths and get better results during development.

### 💻GitHub Copilot (inside VS Code)

- I used GitHub Copilot directly inside VS Code as an AI coding assistant. 
- It helped me by reading my project files, understanding the context of my code, suggesting improvements, detecting mistakes, and speeding up my workflow. 
- I also used it to generate code snippets, refactor sections of the project, and even create hero images based on my ideas.

### 🧠Claude & ChatGPT

- I used both Claude and ChatGPT to assist me throughout the development process.
- Since each AI tool has its own strengths and limitations, combining them helped me get clearer explanations, different problem-solving approaches, better design ideas, and more efficient coding support.

### 😄A Funny Personal Experience

- After spending an entire week working closely with AI assistants, the experience became surprisingly funny and human-like. 
- At some point, Copilot even started replying with Arabic expressions, motivating me, checking if I needed a break, and encouraging me during stressful moments.
-  It genuinely felt like having a supportive coding partner during the project journey

![Using-AI](assets/images/screenshots/ai.png) 

## 🧩Wireframe Home Page

### 🖥️Desktop

![Using-AI](assets/images/screenshots/wireframe-home-desktop.png) 

### 📱Mobile

![Using-AI](assets/images/screenshots/wireframe-home-mobile.png) 

## 🐞 Bugs & Errors

- All validation issues and debugging notes are documented in the "validation.md" file.
However, one recurring problem deserves special mention:

###  🐛CSS Update Side‑Effects

- During development, I frequently encountered a situation where updating one part of the CSS caused other sections to break or behave unexpectedly.
This happened because:
  - Styles were shared across multiple components

  - Some selectors were too broad

  - Small changes cascaded into other layouts

  - Media queries overlapped

  - Old rules were still affecting new sections

- This issue required repeated debugging and careful restructuring to ensure that updates in one area did not unintentionally affect others.

- All detailed notes, examples, and fixes are included in the validation.me file.

## 🔮Planned Future Updates

- The following "could‑have" user stories are planned for future development and may be added in later versions of the project:

   - Newsletter Sign‑Up Form — allowing visitors to subscribe for updates.
   - Interactive Destination Map — helping users explore Tunisia visually.
   - User Testimonials — showcasing real visitor experiences.
   - Location & Travel Information Section — providing essential travel details.
   - Travel Quiz / Itinerary Builder — offering personalized trip suggestions.

## 🚀Deployment Procedure

- The website was deployed using GitHub Pages.
- Below is the deployment process followed for this project:
     - The full project folder was pushed to a GitHub repository.
     - In the repository settings, GitHub Pages was enabled.
     - The deployment source was set to the main branch.
     - GitHub automatically generated a live link for the website
     - After each update, changes were committed and pushed, and the deployment refreshed automatically. 

  ### 📝 Commit Documentation Note

- Throughout the project, I made a consistent effort to commit as frequently as possible in order to clearly document every update, fix, and improvement.
-  This ensured full transparency in the development process and made it easier to track changes over time.   