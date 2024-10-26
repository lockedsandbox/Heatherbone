---
title: Teaching
summary: My courses
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

# sections:
#   - block: collection
#     id: teaching
#     content:
#       title: <h3>Teaching</h3>
#       filters:
#         folders:
#           - teaching
#     design:
#       view: article-grid
#       columns: 2
#   - block: markdown  
#     content: 
#       text: |- 
#         <a class="get-research" href="teaching-overview/">Get to know my research</a> 

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: hero
    content:
      title: Teaching
      subtitle: <h3>Teaching Experience</h3>
      text: "Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem"
    design:
      columns: '1'
      css_class: "exmaple-class"
      background:
        image: 
          filename: "hero-teaching-experience.jpg"
          filters:
            brightness: 0.5
          parallax: false
          position: center
          size: cover
          text_color_light: false
      spacing:
        padding: ['60px', '0', '60px', '0']
      css_class: fullscreen overview-page
      no_padding: true  
  - block: markdown
    id: section-1
    content:
      title: Teaching Experience
      text: |
        
        **ECO200: Intermediate Microeconomics (Spring 2023)**
        Description of course goes here. Also add links to syllabus and course review**
        
        **ECO225: Big Data Tools for Economists (Guest Instructor, Spring 2024)**
        Include picture of me teaching, as well as some quotes from the reviews that students left

        **Lead Writing TA, Department of Economics (Beginning Date - End Date)**
        Describe the WIT program, what I did as part of it, and link to any relevant materials

        **Teaching Assistantships**
        Create a list of all the courses I have TAed below
  - block: markdown
    id: section-2
    content:
      # title: Teaching Certification
      text: |- 
              <a class="get-research" href="conference-paper.pdf" download="conference-paper.pdf">download my teaching dossier</a> 
---

# hhhh