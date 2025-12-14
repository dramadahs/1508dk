# Description of 1508dk
This project was created for educational purposes only. It references real brands and certifications, but it is not affiliated with, endorsed by, or connected to any of them. All information found on the website is false.

# Authors
Signe Storgaard (https://github.com/sist0002)

Kia Vinther (https://github.com/kivi0001)

Kamilla Christiansen (https://github.com/kach0006)

Ida Petersen (https://github.com/idax3451)

# Development

### General
You can edit the project in any editor with Astro installed. When the project repository is cloned, you can install Astro by running the command "npm install" in the editor terminal. 

### API endpoints
The site is fetching data from a free Supabase database: 

### CSS 
All pages should have the main.css file imported to ensure style consistency across all pages. Individual page and component styling should be set between the style tags of those specific pages and components. 

### Javascript
Javascript is added directly in the Frontmatter block when possible, otherwise at the bottom of a page or component.

### Images and icons
Images and icons must be added to the public folder.

### SVGs
SVG files must be added in the src/assets folder.

### Fonts
Fonts must be added in the src/assets/fonts folder. 

# Naming structure
### Language
Although the majority of the website content is in Danish, English is our technical working language, and all classes and IDs should have English names.

### Spaces
Spaces between words in file names should be filled with a hyphen.

### Pages
With the exception of index.html, all pages should be named the same as the intended landing page title. Example: min-side.html

### Components
Components must have names that clearly describe their contents. Example: Header.astro

### Javascript
Use camel case. Example: productContainer

# Workflow

### General
Features that are used across multiple pages, such as header and footer, must be created as separate components, so that their contents can easily be copied into other documents.

### Git branches
The name of the Git branches published should reflect the feature or specific document worked on by the developer.

### Merges
When a push is made, the developer must leave a short description of the changes made if this is not made obvious by the branch name. All team members must sync to the most recent copy of main before changes are made to shared across several documents, such as main.css.

