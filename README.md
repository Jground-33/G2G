# Got 2 Go
![](https://img.shields.io/badge/Deployed-✓-brightgreen) ![](https://img.shields.io/badge/Version-0.1-fab1a0)

[Deployed Link](https://g2g-gottago.herokuapp.com/welcome)

![alt text](/public/G2G.png)

**GottaGo: an app designed for anyone who’s gotta go.**

Got 2 Go is a bathroom-finding app that features:

* Locating a restroom within close proximity to your current location

* Filtering based on wheelchair accessibility, gender-neutral bathrooms, changing stations, safety, cleanliness, and single-occupancy

* Leaving a review of restrooms so that clean restrooms are easier to find and the user can choose a restroom knowledgeably

* Bookmarking restrooms with notes for later use.

## Design

![alt text](/public/color-styles.png)
![alt text](/public/bathroom-listing-page.png)

[Trello Board](https://trello.com/b/mncwglez/project-devutantes)

We designed the app to be as clean as we would like all of our restrooms to be; soft pinks and minimal icons bring levity and playfulness to the serious issue of finding a suitable public restroom.

Minimal design allows the user to quickly find and add bathrooms from a map, identify the location and the type of restroom used and leave a review of that restroom.

## Technology

Because we wanted to provide fast geo-location and retrieval of bathrooms for mobile devices we had to be a little creative with our tech stack. Rather than opting for MERN stack, we used JAM stack.

Our application is decoupled with the backend API hosted independently on Heroku. The backend was made with GraphQL, GraphQL-yoga, Prisma, MongoDB, and JavaScript. We used GraphQL to create the schema calls to our frontend and used Prisma as our "ORM" for GraphQL so that it created resolver functions for us.

We connected our backend to a React frontend using Apollo to manipulate our backend. All components and pages were styled through CSS modules and a little bit of materialize.

To render maps onto our application we used the Google Maps API and styled the map to create a warm color pallette for the user. Custom markers were made to display information about the bathrooms and the markers themselves are clickable to direct users to a detail page about the specific bathroom.


## Future Features

* Upvote Downvote implementaion

* User Profile page

* Booksmarks

* Mailchimp API

* Stripe API

## The Team


[Jack](https://github.com/Jground-33): API/Admin Portal Lead

[Elise](https://eliseentzenberger.com ): UX Designer/Research Lead

[Joe](https://github.com/SleepyJosus): Front End Lead

[David](https://github.com/baeddavid): Back End Lead

[Alice](https://aliceccheung.com): UX Designer/Design Lead

[Rachel](https://rachelakerley.com): UX Designer
