<template>
  <!--awesome inc work -->

  <div>
    <div class="ppnp-container">
      <nuxt-link to="bikeshikes-ecommerce">
        <previous />
      </nuxt-link>

      <nuxt-link to="wonder-wares">
        <next />
      </nuxt-link>

      <div class="ppnp-number-container">
        <p class="black ppnp-p-number">
          <span style="color:#FF4F00;">02</span>
          <span>/</span>
          <span>22</span>
        </p>
      </div>
    </div>
    <projecthero
      pDate="May 2021"
      pWebsite="Artiso"
      pCategory="App Design"
      pHeading="Bringing Art Closer: Designing an Immersive Art Gallery App Experience"
      pHeadingcolor="color:#FF4F00;"
      pSubheading="Artiso App Case Study: A Digital Space for Artists and Art Lovers"
    />
    <div class="p-hero_image">
      <div class="reveal-holder" data-aos="fade-up">
        <div class="reveal-block right theme_artiso" data-aos="reveal-right"></div>

        <picture>
          <source
            media="(max-width: 600px)"
            srcset="~assets/projects/artiso/art-gallery-app-home-mockup-mobile.jpg"
          />
          <img
            src="~assets/projects/artiso/art-gallery-app-home-mockup.jpg"
            alt="a person in art museum holding a phone and browsing an art app"
          />
        </picture>
      </div>
    </div>

    <Preface
      timeframe="May 2021- <br> July 2021"
      tools="  Adobe Creative Suite, Marvel, Invision 
            <br>Pen, paper"
      role="UX Researcher, UI/UX Designer

            <br>Designed the art gallery app from concept to delivery"
      team=" Me, Friends, and
            <br>a lot of shared creativity"
    />
    <!-- Preface -->
    <pcase
      heading="Preface"
      para="Art is more than just visuals; it’s an experience. The idea behind this app was to create a digital space
      where artists could showcase their work, and art lovers could explore, appreciate, and even purchase artwork without barriers.
  <br>
  <br>
Traditional art galleries have limitations—physical space, accessibility,
and engagement. This app aimed to break those barriers by offering an immersive,
user-friendly experience that brings the gallery to everyone, anywhere, anytime."

      
      theme="theme_artiso"
    />

    <!-- Challenge -->
    <pcase
      heading="The problem"
      para="Visiting art galleries isn’t always convenient. Limited exhibitions, geographical constraints,
      and a lack of accessibility to diverse art collections make it challenging for both artists and audiences.
      Many online platforms that do exist feel cluttered, transactional, and lack the emotional engagement that a physical gallery provides.
<br>
<br>
We wanted to design an app that provides an immersive digital gallery
experience while keeping it simple and intuitive."
      theme="theme_artiso"
    />
  <!-- Goal -->
    <pcase
      heading="The Goal"
      para="The aim was to design an app that seamlessly bridges the gap between artists and art enthusiasts. It needed to feel like a real gallery—organized,
      aesthetic, and easy to navigate. Key priorities included:
      <ul>
        <li>A clean and elegant UI that complements, not overshadows, the artwork. </li>
        <li>An intuitive browsing experience with categorized collections and artist profiles.</li>
        <li>PFeatures that allow users to interact with art, learn about pieces, and make purchases without feeling overwhelmed.</li>
      </ul>"
      theme="theme_artiso"
    />

  <div class="p-quote contain red">
      <blockquote>
        The aim was to design an app that seamlessly bridges
        the gap between artists and art enthusiasts.
      </blockquote>
    </div>

    <br></br>
    
    <!-- Challenge -->
    <pcase
      heading="Understanding the user"
      para="
      To create an experience that feels natural, I conducted user research through interviews
      with artists and casual art lovers. My goal was to deeply understand their needs and behaviors before shaping the design. To achieve this, I followed a structured design process that involved:.
      <ul>
        <li>User Research </li>
        <li>Personas</li>
        <li>Problem Statements</li>
        <li>User Journey Maps</li>
        <li>User Flow</li>
      </ul>
      "

      theme="theme_artiso"
    />
    <pcase
      heading="User research: Summary"
      para="
      I conducted interviews with 5 participants and created empathy maps to understand the users I’m 
      designing for and their needs. The primary user group identified through research 
      was people aged between 18 to 65, people who are rts lovers and people who want to learn and explore arts.
      <br> <br>
      This user group confirmed initial assumptions about art galley app customers, but research 
      also revealed that users wanted an interactive experience through storytelling and ability to search and sort thought different kind of artworks. 
      Other user problems included obligations, busy schedule, that make it 
      difficult to use app and explore their interest.
      "

      theme="theme_artiso"
    />

    <div class="contain">
      <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/ux-interview-plan-phase-1-mobile.jpg"
            />
            <img src="~assets/projects/artiso/ux-interview-plan-phase-1.jpg" />
          </picture>
          <p class="ps black70">UX Interview Plan Document</p>
        </div>
      </div>
    </div>

    <div class="p-image-100-duo">
      <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
        <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>

        <picture>
          <source
            media="(max-width: 600px)"
            srcset="~assets/projects/artiso/usability-study-painpoints-mobile.jpg"
          />
          <img src="~assets/projects/artiso/usability-study-painpoints.jpg" />
        </picture>
        <p class="ps black70">Usability Study Painpoints</p>
      </div>
    </div>

<pcase
      heading="Personas"
      para="Problem statement: <br>
            Mudita is a busy working adult who needs easy and interactive app to explore arts so that she can
              explore arts and fulfills her creative curiosity and apply her ideas, inspiration from these to her daily works.

        "
      theme="theme_artiso"
    />


  <div class="contain">
    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <!-- <source
              media="(max-width: 600px)"
              srcset="~assets/projects/salesfactory/salesfactoryl-colors-typo-mobile.jpg"
            /> -->
            <img src="~assets/projects/artiso/art-gallery-persona-mudita.jpg" />
          </picture>
          <p class="ps black70 b-t-space">Persona [Mudita]</p>
        </div>
      </div>
  </div>

  <pcase
      para="Problem statement: <br>
            Govind is an art enthusiast who needs a platform where he can learn and explore all kind of arts because he
            can't find much information about arts in art galleries he visits or any other source.
        "
      theme="theme_artiso"
    />

 <div class="contain">
    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <!-- <source
              media="(max-width: 600px)"
              srcset="~assets/projects/salesfactory/salesfactoryl-colors-typo-mobile.jpg"
            /> -->
            <img src="~assets/projects/artiso/art-gallery-persona-govind.jpg" />
          </picture>
          <p class="ps black70 b-t-space">Persona [Govind]</p>
        </div>
      </div>
  </div>
    
      <!-- <p class="contain just-para black90">
      Saharsh is a busy sales student manager who needs Jargon free website, and
      required search filters because he want online shopping to be fast and stress-free.
    </p> -->

    <div class="p-quote contain red">
      <blockquote>
       I want to have unique experience that surprises me on every turn.
      </blockquote>
    </div>
     <!-- Preface -->
    <pcase
      heading="User journey map"
      para=" 
       Mapping Mudita’s journey revealed that an interactive art gallery
       app would greatly enhance her experience.. 
      "
      theme="theme_artiso"
    />

 <div class="contain">
    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <!-- <source
              media="(max-width: 600px)"
              srcset="~assets/projects/salesfactory/salesfactoryl-colors-typo-mobile.jpg"
            /> -->
            <img src="~assets/projects/artiso/art-gallery-user-journey-map.jpg" />
          </picture>
          <p class="ps black70">User Journey Map</p>
        </div>
      </div>
  </div>

  <br></br>
   <br></br>

   <pcase
      heading="User Flow"
      para=" 
       User flow helped me to decide to flow of possible screens, 
       from entry point to the final step that is required for a successful outcome.
       <br>
       User Task Flow:
       <ol>
        <li>Open the app </li>
        <li>Complete onboarding</li>
        <li>Browse favorite artworks</li>
        <li>Learn about their details and backstories</li>
        <li>Contact sellers and make a purchase</li>
      </ol>
      "
      theme="theme_artiso"
    />

 <div class="contain">
    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <!-- <source
              media="(max-width: 600px)"
              srcset="~assets/projects/salesfactory/salesfactoryl-colors-typo-mobile.jpg"
            /> -->
            <img src="~assets/projects/artiso/art-gallery-user-flow.jpg" />
          </picture>
          <p class="ps black70">User Journey Map</p>
        </div>
      </div>
  </div>

   <pcase
      heading="Starting the Design Process"
      para="
      Difficulty with website navigation was a primary pain point
      for users, so I used that knowledge to create a sitemap.
      <br>
      <br>

      My goal here was to make strategic information architecture decisions
      that would improve overall website navigation. The structure I chose was
      designed to make things simple and easy. <br>

      <ul>
        <li>Paper Wireframes</li>
        <li>Digital Wireframes</li>
        <li>Low-fidelity Prototype</li>
        <li>Usability Studies</li>
      </ul>"

      theme="theme_artiso"
    />


    <pcase
      heading="Paper wireframes"
      para="I used Crazy Eight technique to quickly generate multiple wireframe ideas for the app.
      This method involves an intense 8-minute brainstorming session where I sketched out as many screen variations
      as possible. The goal was to explore a wide range of design possibilities,
      ensuring a creative and diverse approach to the app.
        "
      theme="theme_artiso"
    />

    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <!-- <source
              media="(max-width: 600px)"
              srcset="~assets/projects/bikeshikes-ecommerce/bikeshikes-digital-wireframe-all-mobile.jpg"
            /> -->
            <img src="~assets/projects/artiso/crazy-8-activity-sketch.jpg" />
          </picture>
          <!-- <p class="ps black70">Homepage Digital Wireframe</p> -->
        </div>
      </div>

      
      <pcase
      para="Taking the time to draft iterations of each screen of the app on paper ensured
      that the elements that made it to digital wireframes would be well-suited to address
      user pain points. For the home screen, I prioritized a quick and easy exploring of arts
      with easy bottom navigation.
        "
      theme="theme_artiso"
    />

    <client-side>
      <agile>
        <div class="slide">
          <img
            class="slide-img"
            src="~assets/projects/artiso/paper-wireframe-all-pages.jpg"
            alt="Paper Wireframes for app"
          />
        </div>

        <div class="slide">
          <img
            class="slide-img"
            src="~assets/projects/artiso/paper-wireframe-sketch-1.jpg"
            alt="Paper Wireframes for app"
          />
        </div>
        <div class="slide">
          <img
            class="slide-img"
            src="~assets/projects/artiso/paper-wireframe-sketch-2.jpg"
            alt="Paper Wireframes for app"
          />
        </div>
        <div class="slide">
          <img
            class="slide-img"
            src="~assets/projects/artiso/paper-wireframe-sketch-3.jpg"
            alt="Paper Wireframes for app"
          />
        </div>
        
      </agile>
    </client-side>

    <div class="p-quote contain red">
      <blockquote>
        Paper wireframes and Crazy 8 activities served multiple purpose here, it helped me to connect the
        app's information architecture to its visual design by showing
        paths between screens. Genrate many Layout and go with the one that serves the purpose or combine from one to another. 
      </blockquote>
    </div>
 
    <br>

    <!-- Digital Wireframe -->

      <pcase
      heading="Digital wireframes"
      para="Moving from paper to digital wireframes made it easy
      to understand how the redesign could help address user pain
      points and improve the user experience. Prioritizing useful button
      locations and visual element placement on the home page was a key part
      of my strategy.

    <br>
    <br>
    Easy navigation was a key user need to address in the designs
    in addition to equipping the app to work with assistive technologies.

      "
      theme="theme_artiso"
    />
  
    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/digital-wireframe-mobile-app-features-1.jpg"
            />
            <img src="~assets/projects/artiso/digital-wireframe-mobile-app-features.jpg" />
          </picture>
          <!-- <p class="ps black70">Homepage Digital Wireframe</p> -->
        </div>
      </div>

<br></br>
  
<div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/digital-wireframe-all-pages-mobile.jpg"
            />
            <img src="~assets/projects/artiso/digital-wireframe-all-pages.jpg" />
          </picture>
          <!-- <p class="ps black70">Homepage Digital Wireframe</p> -->
        </div>
      </div>

<br></br>
<br></br>




      <pcase
      heading="Low-fidelity prototype"
      para="Using the completed set of digital wireframes, I created a low-fidelity prototype. The primary user flow I
      connected was Exploring Arts, Details and Contacting Seller.

View the Art Gallery App 
low-fidelity prototype.
 https://xd.adobe.com/view/0ddc5f3d-f89c-49fa-8ec5-d435564d5083-588f/?fullscreen     

      "
      theme="theme_artiso"
    />
  

   <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <!-- <source
              media="(max-width: 600px)"
              srcset="~assets/projects/salesfactory/salesfactoryl-colors-typo-mobile.jpg"
            /> -->
            <img src="~assets/projects/artiso/Low-fidelity-prototype.jpg" />
          </picture>
          <p class="ps black70">Low-fidelity prototype (Adobe XD)</p>
        </div>
      </div>

    <pcase
      heading="Usability study"
      para="Using the completed set of digital wireframes, I created a low-fidelity prototype.
      The primary user flow I connected was Exploring Arts, Details and Contacting Seller.. 
      "
      theme="theme_artiso"
    />

 <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/usability-study-parameters-mobile.jpg"
            />
            <img src="~assets/projects/artiso/usability-study-parameters.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>

 <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/ux-research-study-plan-mobile.jpg"
            />
            <img src="~assets/projects/artiso/ux-research-study-plan.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>

    <pcase
      heading="Usability study: findings"
      para="I conducted two rounds of usability studies. Findings from the first study
      helped guide the designs from wireframes to mockups. The second study used a high-fidelity
      prototype and revealed what aspects of the mockups needed refining. 
      "
      theme="theme_artiso"
    />

     <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/usability-study-findings-1-mobile.jpg"
            />
            <img src="~assets/projects/artiso/usability-study-findings-1.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>


    <pcase
      heading="Refining the Design"
      para="Early designs allowed for some customization, 
      but after the usability studies, I added additional options to choose pizza crust and sauce.
      I also revised the design so users see all the customization options when they first land on the screen."
      theme="theme_artiso"
    />

    
    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/mokups-usability-studt-before-and-after-1-mobile.jpg"
            />
            <img src="~assets/projects/artiso/mokups-usability-studt-before-and-after-1.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>


 <p class="contain just-para black90">
  The second usability study revealed confusion with some user as Microcopy was inconsistent across screen
  like same login and sign in were used for same purpose.
  To Make it more consistent I used login Microscopy across all screen and for other such inconsistencies.
    </p> 

        
    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/mokups-usability-studt-before-and-after-1-mobile.jpg"
            />
            <img src="~assets/projects/artiso/mokups-usability-studt-before-and-after-2.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>

<!-- Low fi fidelity prototype -->
<!-- 
<client-side>
      <agile>
        <div class="slide">
          <img
            class="slide-img"
            src="~assets/projects/bikeshikes-ecommerce/mockups-before-and-after-usability-study-1.jpg"
            alt="feeding trends ideation"
          />
        </div>
        <div class="slide">
          <img
            class="slide-img"
            src="~assets/projects/bikeshikes-ecommerce/mockups-before-and-after-usability-study-2.jpg"
            alt="feeding trends ideation"
          />
        </div>
        <div class="slide">
          <img
            class="slide-img"
            src="~assets/projects/bikeshikes-ecommerce/mockups-before-and-after-usability-study-3.jpg"
            alt="feeding trends ideation"
          />
        </div>
        
        
      </agile>
    </client-side> -->

    <pcase
      heading="High Fidelity Mockups"
      para="I started by combining research, user personas, and wireframes. Then, I focused on
      designing the home screen, establishing a visual theme for the art app. Once I was satisfied with
      its look and feel, I applied the same approach to other screens, ensuring a consistent and intuitive user experience. 


        <br><br>
        My goal was to provide clear navigation so users could explore the app naturally.
        The best design feels effortless, allowing artists to focus on their creativity without distractions..
      "
      theme="theme_artiso"
    />

    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <!-- <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/Multidevice-mockup-3-mobile.jpg"
            /> -->
            <img src="~assets/projects/artiso/initial-hifi-mockups-all-page.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>


    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <!-- <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/Multidevice-mockup-3-mobile.jpg"
            /> -->
            <img src="~assets/projects/artiso/hifi-mockup-screen-1.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>


    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <!-- <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/Multidevice-mockup-3-mobile.jpg"
            /> -->
            <img src="~assets/projects/artiso/hifi-mockup-screen-2.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>


    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <!-- <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/Multidevice-mockup-3-mobile.jpg"
            /> -->
            <img src="~assets/projects/artiso/hifi-mockup-screen-3.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>


    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <!-- <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/Multidevice-mockup-3-mobile.jpg"
            /> -->
            <img src="~assets/projects/artiso/hifi-mockup-screen-4.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>

    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/hifi-mockup-screen-5-mobile.jpg"
            />
            <img src="~assets/projects/artiso/hifi-mockup-screen-5.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>


    <pcase
      heading="High-fidelity prototype"
      para="
        I used Mrvel and Adobe XD to create prototype to used for further user testing final high-fidelity prototype presented cleaner user flows for exploring
        artworks with cool interactions, animations and transition. It also met user
        needs for exploring different kinds of arts and simple layout form for contacting seller.  
      <br>
      <br>
     View the Art Gallery App high-fidelity prototype

            
            "
      theme="theme_artiso"
    />


    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <!-- <source
              media="(max-width: 600px)"
              srcset="~assets/projects/salesfactory/salesfactoryl-colors-typo-mobile.jpg"
            /> -->
            <img src="~assets/projects/artiso/High-fidelity-prototype-xd-screenshot.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>

    <pcase
      heading="Usability Testing"
      para="
        There were few scenarios which i prepared for user testing on the mockups. Below are what users responded. My Focus we mainly on:  

    <ul>
        <li>If User able to complete the flow and perform required task in the prototype</li>
        <li>Readability</li>
        <li>Bottom Navigation of App (tested with Three different scenarios)</li>
        <li>App Overall Experience</li>
        <li>Feedback and Further Improvements</li>
      </ul>

            
            "
      theme="theme_artiso"
    />


    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/usability-study-bts-1-mobile.jpg"
            />
            <img src="~assets/projects/artiso/usability-study-bts-1.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>

    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/usability-study-bts-2-mobile.jpg"
            />
            <img src="~assets/projects/artiso/usability-study-bts-2.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>

    <pcase
      heading="Accessibility Considerations"
      para="
        While designing I have kept an eye on the accessibility
        consideration like color contrast, Hierarchy and Layout,
        typography and all those design principles.  It's always
        easier to fix things that you uncover in the design process,
        so it's best to consider accessibility upfront in the design process.
            "
      theme="theme_artiso"
    />


    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <source
              media="(max-width: 600px)"
              srcset="~assets/projects/artiso/accessibility-considerations.jpg"
            />
            <img src="~assets/projects/artiso/accessibility-considerations.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>


    <pcase
      heading="Takeaways"
      para="
       Impact: <br>
The app makes users feel engaged with lots of content to explore with modern and simple design.

One quote from peer feedback:
“The app made it so easy and fun to explore arts. I love how interactive the app is.
I would definitely use this app as go-to for keeping with my desire to explore all kinds of arts”
 
      <br>
      <br>
      What I learned:<br>
While designing the Art Gallery app, I learned that the first ideas for the app are only the
beginning of the process. How much it is important to follow the design process. Usability studies
and peer feedback influenced each iteration of the app’s designs. 

   "
      theme="theme_artiso"
    />

    

    <pcase
      heading="Going forward"
      para="
        Usability Stry in Different part of the process helped me to really understand the user and design for intended user taking their feedbacks and improving on it on each step. 
      <br>
      <br>
      Prioritizing useful button locations and visual element placement on the
      home page was a key part of my strategy.
   "
      theme="theme_artiso"
    />

    <pcase
      heading="Next Step"
      para="
        Usability Study in Different part of the process helped me to really understand the user
        and design for intended user taking their feedbacks and improving on it on each step. 
   "
      theme="theme_artiso"
    />

    
    <div class="p-image-100-duo">
        <div class="reveal-holder" data-aos="fade-up" data-aos-once="true">
          <div class="reveal-block right" data-aos="reveal-right" data-aos-once="true"></div>
  
          <picture>
            <!-- <source
              media="(max-width: 600px)"
              srcset="~assets/projects/salesfactory/salesfactoryl-colors-typo-mobile.jpg"
            /> -->
            <img src="~assets/projects/artiso/next-step.jpg" />
          </picture>
          <!-- <p class="ps black70">Low-fidelity prototype Page connection in Adobe XD</p> -->
        </div>
      </div>


    <!-- key Focus Area -->

    <div class="keyfocus">
      <div class="content">
        <div class="contain">
          <h2 class="p-para black50">Stuff I did</h2>

          <div class="pm black70">
            <div class="kf-layout">
              <span>✔ Research</span>
              <span>✔ Ideation</span>
              <span>✔ Planning indepth for UX Research</span>
              <span>✔ Conducting User Interviews</span>
              <span>✔ User personas</span>
              <span>✔ Drank Lots of Coffee</span>
              <span>✔ Explored Different Kind of Arts</span>
              <span>✔ Made Wireframe</span>
              <span>✔ Structured User Journey</span>
              <span>✔ Worked in nights</span>
              <span>✔ Branding</span>
              <span>✔ UI Design</span>
              <span>✔ Leanrned New Tools</span>
              <span>✔ Pop and un-pop things</span>
            </div>
          </div>
        </div>
      </div>
    </div>


    <div class="p-quote contain red">
      <blockquote>
        Its tough to not enter yourself in the design process but staying true to user is itslef a challenge. 
      </blockquote>
    </div>

    <!-- End Line  -->

    <div class="section-divider">
      <hr class="section-divider" />
    </div>

  

    <!-- Appreciate section -->

    <Appreciate
      heading="Lets make art together."
      subHeading="Don't forget to appreciate."
    />

    <!-- Project Footer Navigation -->

    <div class="project-footer">
      <div class="projects-footer-container">
        <allprojectsnav />
        <div class="p-f-p-container">
          <nuxt-link to="/projects/bikeshikes-ecommerce">
            <pfooterp
              projectName="BikeShikes"
              projectCategories="Casestudy, eCommerce"
              thumbnail="/bikeshikes-web-mockup-thumbnail-3.jpg"
            />
          </nuxt-link>
        </div>

        <div class="p-f-n-container">
          <nuxt-link to="/projects/wonder-wares">
            <pfootern
              projectName="WonderWares"
              projectCategories="App | eCommerce"
              thumbnail="/wonder-wares-app-thumbnail-2.jpg"
            />
          </nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Projecthero from '~/components/projects/projecthero'
import Preface from '~/components/projects/preface'
import Projectfooter from '~/components/projects/projectfooter'
import Pcase from '~/components/projects/pcase'
import Appreciate from '~/components/projects/appreciate'
import Next from '~/components/projects/next'
import Previous from '~/components/projects/previous'
import Pfootern from '~/components/projects/pfootern'
import Pfooterp from '~/components/projects/pfooterp'
import Allprojectsnav from '~/components/projects/allprojectsnav'
export default {
  layout: 'projects',
  components: {
    Projectfooter,
    Preface,
    Appreciate,
    Pcase,
    Projecthero,
    Next,
    Previous,
    Pfooterp,
    Pfootern,
    Allprojectsnav
  }
}
</script>

<style>
.project-footer {
  bottom: 0%;
}
.b-t-space{
  bottom: 3% !important;
}
</style>
