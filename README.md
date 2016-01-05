# Planning the application
  1. Answer Questions  
      - What am I building?  
      - Who am I building it for?  
      - what features does it need to have?  
  2. User Stories
  3. Model the Data
  4. Think through the pages we need in the app


## Questions


   1. What am I building?  
I am building a personal site. A place where I can blog, share examples of my work, and have people contact me.
   2. Who am I building it for?  
    I am building it for myself, but also the comnunity. Sharing what I am learning by blogging is a great way to learn for myself, by teaching others in the process. And to show potential employers what I am doing.  
   3. What features do I want?
                          
  - Posts
        - Create / Edit / Destroy
        - Markdown
        - Syntax Highlighting
        - Comments (Disqus)
    -  Projects
          - Create / Edit / Destroy
  -  Contact
        - Contact form
        - Sendgrid
  -  A user, for logging into the backend (devise).


## User Stories
          
  As a ______, I want to _____, so that ______.
  
- As a user I want to be able to create posts so that I can   share what I am learning on my blog.
- As a user, I want to be able to edit & delete posts, so I   can manage my blog
- As a user, I want be able to write posts in markdown format so that its easy.
- As a user, I want to be able to highlight the various syntax of code blocks that I share on my blog.
- As a user, I want to be able to show visitors and potential employers examples of my work, or stuff Ive built.
- As a user, I want to be able to have visitors contact me through a form on my site.
- As a user, I want visitors to be able to leave commentson my posts.


## Modeling the Data

  **Post**
    title:string
    content:string

  **Project**
    title:string
    description:text
    link:string

  **User**

## Think through the pages I need in the app

- Home
- Posts#index
- Posts#show
- Projects#index
- Projects#show
- Contact