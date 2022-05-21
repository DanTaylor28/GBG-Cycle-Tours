# GBG Cycle Tours
GBG Cycle Tours is a tour website hoping to encourage people to book a guided bicycle tour around the city of Gothenburg, Sweden.
The site is mainly aimed at tourists visiting the city, but also for local people who are interested in learning more about the history of the city. The site also attempts to encourage people to be more active and environmentally friendly by travelling around (or in this case sightseeing) in a sustainable manner while keeping healthy at the same time!

The website will be useful to user's by providing important information on the details of the tour and hopefully encouraging people to visit the city and join them for a bicycle tour. Information on the itinerary and attractive pictures of Gothenburg are included throughout the website to give a glimpse of all the beautiful sights there are to see!
* * * 

## Current Features

 ### Navigation bar 

 - The navigation bar is featured on all three pages and includes interactive links to jump to the other sections of the website. The company logo is in the top left and takes you back to the home page when clicked.
 
 - The links take you to either Home, Tour Information or Book a Tour. This lets you easily switch between pages without the need of using the back button constantly.

![navigation-bar](/assets/images/navigation-bar.png)

 ### The main image 

 - This firt image aims to give the user an immediate idea to what the webite is all about. Its big, bright and eye catching and it shows a cyclist travelling through the streets of Gothenburg.

 - The text overlay is an attention grabbing title along with a call to action button which when clicked, takes you directly to the book a tour page.

 ![main-image](/assets/images/main-image.png)

 ### Welcome section and Table 

 - This paragraph of text gives you a brief introduction of Gothenburg and what can be expected during the tour.

 - The table shows information on the days, times and price of the tour. This information was presented in a table in order to it clear and increase readability for somebody glancing over the homepage.

 - This section would be updated regularly to keep people up to date on any changes in times or dates. It brings value to the user by providing the most important information in the primary part of the home page, so it's unlikely to be missed.

 ![welcome-section](/assets/images/welcome-section.png)

 ### Why take a bike tour section

 - This section is aimed to show people why taking a bike tour is the best way to see a city!
 Here are the unique selling points for doing this cycling tour, while encouraging the user to book.

 - To the right of this, is an appealing image of people riding bicycles to add a graphic element to the section.

 ![why-take-bike-tour-section](/assets/images/why-take-bike-tour.png)

 ### Footer

 - Like the navigation, the footer is located on all three pages. It includes links to all of the relevant social media channels which open in a new tab when clicked. To the left, there is included copyright information.

 - The footer is valuable as it promotes the company on their other social channels and encourages the user to stay connected with us.

 ![footer](/assets/images/footer.png)

 ### Tour Information page 

 - The top of the page once again includes a large attractive image to grab the users attention. This page is valuable to the user as it outlines important information regarding the meetup times, a detailed break-down of what to expect during the tour, and what could be good to bring with you.

 - A map is included at the bottom of the page, with a pin showing exactly where the meetup point in the city is to aid the user as much as possible.

 ![tour-info-page](/assets/images/tour-info-page.png)

 ### Book a Tour page 

 - This page lets the user start the process of booking a tour by inputting their details and receiving further information on our availability.

 - The user is asked to fill in how many people they will be and the preferred date, along with their name, email and telephone number.

 - All of the information in the form is required except for the telephone number. Users will not be able to submit the form until all the required imformation is filled in.

 ![book-tour-page](/assets/images/book-tour-page.png)

 ## Additional Features to implement

 ### A customer review section
 - A seperate page where users can read up on past customer's experiences from our bicycle tour. This would help the user in making a more informed decision about whether this particular tour is for them and an opportunity for past customers to express their personal experiences.
 * * * 

 ## Testing

 - I have tested that the website works on the following browsers : Chrome, Safari & Firefox.
 - I have ensured that the site is responsive and works well on different screen sizes. I have tested this in the development device's tool bar. 
 - I have tested that the form works as expected. Before you can submit, it ensures that all of the required details are filled in. Likewise, a valid email address is required for the email input, a telephone number for the telephone input etc.
 - Once the form is submitted, it takes you to a confirmation page showing that your information has been received. 
* * *

 ## Validator Testing 

- All HTML code passed through the HTML W3C validator with no issues.

- All CSS passed through the CSS Jigsaw validator with no issues.

![lighthouse-score](/assets/images/lighthouse-score.png)

 * * * 

 ## Fixed Bugs

- I noticed that when the home page and form were in landscape on certain mobile devices, some elements were pushed up the screen into the navigation bar. I fixed this by adding extra media queries to account for when devices are in landscape orientation. 

- When I deployed the site, all the images did not show up at first. This was due to me using absolute file paths rather than relative paths, and once changed the site loaded as expected.

 ## Unfixed Bugs

- I encountered some issues with performance when i ran lighthouse tests for mobile rather than desktop. This bought my score down to around 80. I did not have time to work on fixing this unfortunately.

- The way I positioned some elements on the home page early on in development meant that when it came to responsive design, a few of the elements on the main-image section are not consistent on all screen sizes. To avoid this for future reference, I aim to use repetitive methods for positioning such as flexbox. I did not have time to fully research this method before my submission deadline.

 * * *

 ## Deployment

 - I deployed my website by pushing the final changes to Github. From there, I went to the settings and then onto Github pages. Under the source menu, I clicked main and then save. I refreshed the page and my site then became live.

 - You can find my website at this link - 
 https://dantaylor28.github.io/GBG-Cycle-Tours/
 * * * 

 # Credits

## Content 

- Inspiration for the nav bar & the form styling was taken from the Love Running project.

- The icons from the why take a bike tour section and footer were taken from font awesome.

- I researched how to center a div via transform for my home page by reading on hubspot blog.

- General troubleshooting tips for positioning some of the elements were taken from w3schools.com
* * *

## Media 

- All images used on the site were taken from Unsplash.com

- The map was taken directly from the Google Maps website.








 
