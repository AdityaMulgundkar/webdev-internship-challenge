# Web Dev Hiring Challenge

[//]: # (Placeholder for a status badge)

**Note:** This is a hiring test for a web development internship. Basic knowledge of HTML/CSS & experience in some programming language is a prerequisite.

## Idea

There's two approaches to building a website - first is to write everything out in HTML & CSS and stick to modifying that later on. As more tasks, changes & iterations come into play, this might not be the smartest idea. Another approach would be to minimise your time & effort investment at a later point by designing an architecture that is modular, reproducible and easily scalable. A good idea would be to:

- Abstract code that is repeatable. What's the point of having to modify n different files for making a single change in the header? What about changing a theme color - say from red to blue. Find & replace isn't the best solution.
- Automating commands/tasks that are repeatable. Would you want to upload a separate ZIP file to the client's server every time there's a new change (or worse, edit a file on the production server)? Connecting your code repository to a hosting provider such that your code is automatically deployed to the server whenever you make changes to the master branch of your repository is the desired/ideal solution.

### Logical requirements

- Eliminate redundancies
- Retain proper code structure
- Reduce effort for making changes later by building atomic modules
- Create a basic pipeline to generate & deploy your code to a server

### Business requirements

- A basic static website that loads really fast
- Modifyable (from code) header & footer components
- Pages => Landing (home), about, contact us
- Brand color => #38aadd, stick to black (#3d3d3d) and white (#ededed) otherwise
- Header has icons next to title; title is in uppercase
- Footer has social URLs for facebook, twitter, linkedin
- Pick a random brand, say Tesla & add dummy content for their website. (hint: don't go overboard)

### Code requirements

- Sass - Bulma
- Framework - GatsbyJS (React based)
- Server - deploy to Netlify
- Pipeline/Automation - connect your GitHub account to Netlify

## What this test **is**

- Meant to test your ability to learn new skills
- Meant to test your ability to implement something quickly - by looking up examples online, learning on the go, etc.
- Meant to test your will to communicate, ask questions & be open about solving the problem at hand

## What this test **isn't**

- Meant to test your skills/knowledge of GatsbyJS, React or Bulma
- Meant to test your experience with Git, GitHub, Netlify or code pipelines
- Meant to test your degree of correctness, accuracy with minute tasks or attention to detail

## Tasks

- Fork this repository
- In the root directory, create a project with GatsbyJS (that uses Bulma for CSS), a starter template works fine too
- Add a basic gitignore for node_modules, build directory, etc
- Commit & push often, if you're just starting with Git (hint: GitHub has a Desktop client)
- Make necessary changes to the template based on the business requirements
- Hint: remove unneccessary components & their usages; work only on the main sass file & the components/templates directories
- Connect your GitHub repository to a new Project on Netlify
- Configure Netlify to deploy the website whenever there's a new commit to the master branch of your repository
- Add a badge at the top of this Readme file (below the heading text) for the Netlify deployment status
- Make a PR to this repository once your code is pushed to the master branch of your repository and the badge URL to your Netlify deployment works fine too
