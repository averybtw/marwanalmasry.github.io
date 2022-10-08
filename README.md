# Marwan Waleed Al Masry
    Goals and Aims
I aim to grow with the company and gain more knowledge and experience to be able to contribute in the company’s success.
     
    *Personal Background*
         
        Date of birth: October 11, 2003
        Place of Birth: United Arab Emirates
        Age: 18
        Sex: Male
        Civil Status: Single
        Religion: Islam
        Weight: 47 kg
        Height: 168 cm
        Nationality: Filipino
        Language Spoken: English, Tagalog

      ##*Academic History*                                                          *Work Experience
      
        Lyceum of the Philippines University Manila                                 Customer Service Representative
        St. John the Baptist Catholic School                                          TaskUs Meycauayan "Fort Excellence (FEX)"
        K-12 Senior Highschool (2019 - 2021)                                            Team-mate
        Corazon Calumpit, Bulacan                                                        December 2021 - September 2022 
        Highschool (2015 - 2019)                                                         Supima Square Bldg. 1, Meycauayan, Bulacan
        Poblacion Calumpit, Bulacan
        De La Salle Montessori
        Elementary (2014 - 2015)
        Malolos, Bulacan
        School of Research Science
        Elementary (2010 - 2014)
        Dubai, United Arab Emirates


       *Skills*                                                                   *Characteristics*
         - Computer Software and Hardware                                           - Willingness to learn
          Knowledge                                                                 - Technology Competent
         - Basic Video Editing using Adobe After                                    - Hard Working
          Effects                                                                   - Highly Motivated
         - Social Media Management                                                  - Team Player
         - Excellent Communication Skills                                           - Patient
         - Creativity                                                               - Empathetic





You are a fantastic developer. Keep your CV on GitHub. Host it on GitHub Pages. Have both HTML and PDF versions automatically generated and consistent.

## What does this project do?

* Helps you to manage your CV as a web app (HTML + CSS + JS).
* Automatically generates and publishes HTML and PDF version on every push to `main`.

Demo: [http://sneas.github.io/cv-template](http://sneas.github.io/cv-template).

Real world example: [http://sneas.github.io/cv](http://sneas.github.io/cv).

## Motivation

GitHub Pages is probably the best place developer could store their CV. Giving a potential employer a link to your CV stored on GitHub shows your intense desire for automation and stands you out.

The idea behind **The Curriculum Vitae Template** is to provide anyone with a quick solution for creating and managing CVs (both HTML and PDF versions) with the help of GitHub.

## Installation

1. Create a new repo out of this template by clicking [this link](https://github.com/sneas/cv-template/generate).
1. Clone the newly created repo.
1. Install project dependencies with `npm install`.
1. Run `npm run deploy` to initialize `gh-pages`. This is a one time action. Further deployments will be initiated by GitHub Actions on every push to `main`.

## Usage

1. Start local development server with `npm start`.
1. Update contents of `src` folder to fit your needs. This item is explained [below](#update-contents).
1. Commit and push your changes.
1. GitHub Actions will automatically build the latest version and deploy it to GitHub Pages.
1. Open `http://your-username.github.io/your-cv-repo`.

### Update contents

The project uses [HandlebarsJS](https://github.com/wycats/handlebars.js/) as a template engine.

The main HTML template is located in [src/templates/index.html](src/templates/index.html). Metadata for the template could be found in [src/metadata/metadata.js](src/metadata/metadata.js).

Don't forget to update [src/assets/favicon.ico](src/assets/favicon.ico). You can generate a new favicon out of your photo with [icoconvert.com](http://icoconvert.com/).
