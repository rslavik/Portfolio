https://www.youtube.com/watch?v=3HNyXCPDQ7Q
https://www.sanity.io/javascriptmastery

1. SET UP SANITY
- Create "backend_sanity" folder
- Open terminal > cd backend_sanity > run code below from sanity site above
    npm create sanity@latest -- --coupon javascriptmastery2022
- Press enter > Login using Google (cis email)
- Return to terminal and name project: portfolio_rs
- Press Y then 'enter' to use the default data set configuration
- Press 'enter' to choose the default  configuration path
    - Sanity offers a lot of predefined templates so that you can quickly start your project
    - We are going to use a clear project with no predefined schemas
    - Everything from scratch!
    - Scroll down menu and select last option "clean schema"
- Q: Do you want to use TypeScript? 
    - The video did not cover this 
    - Compared the tsconfig.json from the git repository for this project to a sanity blog. 
    - Navigating to: project_professional_portfolio/backend_sanity_portfolio/tsconfig.json
    - Blog: https://www.sanity.io/docs/using-typescript-in-sanity-studio 
    - Git: (https://github.com/adrianhajdin/project_professional_portfolio/blob/master/backend_sanity_portfolio/tsconfig.json)
    - Answered: N - *IN THIS VERSION I SAID YES* to try to get this project to work
- Q: Package manager to use for installing dependencies?
    - The video did not cover this
    - Chose 'npm'
<!-- - Terminal: npm install --> didn't do because selected npm above
- Terminal: cd portfoliors
- Terminal: npm run dev - to open up your sanity studio
- Go to Local Host page
- Login with Google again
- Shows that we have an empty schema
- Terminal: ctrl + c to stop running

2. SCHEMAS
- Create testimonials.js in schemas folder
- Video uses old version of sanity.  
    - Solution found on: https://www.sanity.io/docs/create-a-schema-and-configure-sanity-studio

<!-- actually do testimonials.ts (typescript - help with debugging javascript - https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
- Rename index.js to schema.js -->

SANITY START: npm run dev
