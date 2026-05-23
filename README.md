## Welcome
--------------------
Work in progress website for displaying blogs, projects, and CV.

https://morganrennie.github.io/

### Current site structure
- `index.html` — dark-themed homepage and portfolio landing page
- `projects.html` — dedicated projects page for analytics and automation work
- `blog.html` — blog listing page for post previews and structure guidance
- `page-template.html` — reusable template for new project/CV/about pages
- `blog-template.html` — reusable template for new blog posts
- `assets/style.css` — shared dark theme CSS for the entire site
- `assets/blogs/blog_readme.md` — blog folder structure instructions
- `mailchimp-project.html` — Mailchimp extraction project page
- `assets/blogs/W0001/blog_id.html` — sample blog post page

##### Prioritisaiton:
  - Website template
  - Charity Blog - scrape data from just giving page, use donations to populate chart. 
  - Write profile
  - Document bike bag. 
  - project hire me
  - blog template -- plus one or two blogs for feel - can copy data over from TIL? 
  - project strava
  - project worldwide
  - project personality

### To Do
--------------------

##### Project Strava
- extract data (python, api connection)
  - activity
  - activity details
- determine storage solution
- dbt core set up for transformations
- automation scehdule (github actions?) - this wont work if using dbt core. Desktop automations instead? is dbt core required?

##### Project Worldwide
- determine tableau alternatives
- put together data set
  - gather photos

##### Project Hire Me
- update cv
- extract text
- certification reel

##### Project Personality
- determine if instagram photos are extractable via code -- add this into blogs? 

##### Blogs: 
- Life: 
  - Travels/adventurous journeys
- Work: 
  - reflective logs (sensitive?)
    - TIL
    - paramount
    - IAG Cargo (part one and two)
    - that power bi one
    - that alteryx one -- invoice matching
  - certifications
    - Tableau 
    - power bi
    - dbt fundamentals
    - dbt analyst
    - dbt architect
    - aws cloud engineer
    - award for ai integration
    - MOS project - Data Award
    - dashboards presented at UN.
  - Troubleshooting
    - TIL Blogs
    - tableau efficiency
  - projects
    - automated tableau refreshes
    - refresh dbt models from gcp
    - automate data extracts from gcp to email/sharepoint?
    - exec dashboard (data creations)
    - oracle - incorta - gcp project (sensitive?)