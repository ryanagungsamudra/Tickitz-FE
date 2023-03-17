## Tickitz-Frontend

This is a frontend part for [api project](https://github.com/ryanagungsamudra/Tickitz-BE).

## Getting started

To get the Next.js app running locally:

* Clone this repo with `git clone https://github.com/stringifyy/Tickitz-FE.git`
* `cd Tickitz-FE`
* `npm install` to install all required dependencies
* Create a `.env.local` file and reference the `dotenv.example` file
* `npm start` to start the local server

## Folder Structure


    src
     ┣ app
     ┃ ┣ account-information
     ┃ ┃ ┗ page.js
     ┃ ┣ admin
     ┃ ┃ ┗ page.js
     ┃ ┣ login
     ┃ ┃ ┗ page.js
     ┃ ┣ movie-details
     ┃ ┃ ┣ [id]
     ┃ ┃ ┃ ┗ page.js
     ┃ ┃ ┗ page.js
     ┃ ┣ order
     ┃ ┃ ┣ data.json
     ┃ ┃ ┗ page.js
     ┃ ┣ order-history
     ┃ ┃ ┗ page.js
     ┃ ┣ payment
     ┃ ┃ ┗ page.js
     ┃ ┣ signup
     ┃ ┃ ┗ page.js
     ┃ ┣ ticket-result
     ┃ ┃ ┗ page.js
     ┃ ┣ globals.css
     ┃ ┣ head.js
     ┃ ┣ layout.js
     ┃ ┣ page.js
     ┃ ┗ page.module.css
     ┣ assets
     ┃ ┣ images
     ┃ ┃ ┣ png
     ┃ ┃ ┗ svg
     ┣ component
     ┃ ┣ AuthBanner
     ┃ ┃ ┗ index.js
     ┃ ┣ AuthForm
     ┃ ┃ ┗ index.js
     ┃ ┣ CardAdmin
     ┃ ┃ ┗ index.js
     ┃ ┣ CardMovieDetails
     ┃ ┃ ┗ index.js
     ┃ ┣ Footer
     ┃ ┃ ┗ index.js
     ┃ ┣ Navbar
     ┃ ┃ ┣ afterLogin.js
     ┃ ┃ ┗ index.js
     ┃ ┣ nowShowing
     ┃ ┃ ┗ index.js
     ┃ ┣ SelectSeat
     ┃ ┃ ┗ index.js
     ┃ ┣ TicketMobile
     ┃ ┃ ┗ index.js
     ┃ ┗ upComing
     ┃ ┃ ┗ index.js
     ┗ pages
     ┃ ┗ api
     ┃ ┃ ┗ hello.js
    
## Screenshot

![Landing Page](https://user-images.githubusercontent.com/114414904/220416734-bcca7143-0238-4d8a-8c4b-13b2776dd873.png)
![Auth Page](https://user-images.githubusercontent.com/114414904/220417219-f53950b2-05b3-4f07-96c6-ad8f9faf8356.png)
![Movie Detail](https://user-images.githubusercontent.com/114414904/220420773-16b438d8-d514-4014-9374-2fcdc08ce939.png)
