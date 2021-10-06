<h1 align="center">Sailing In Space Website - Testing Details</h1>

[View the main README.md document](README.md)

[View the deployed Sailing In Space Website](https://medusas71.github.io/Sailing-In-Space/)

**Please note: To open any links in this document in a new browser tab, press 'CTRL + Click'.**

<a id="testing"></a>
# Testing 

Testing was conducted manually and through different validator services on each page of the website.

* [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input) was used to ensure that there were no errors in my HTML document and was validated by direct input. Here are the results
* [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) was used to ensure that there were no errors in my CSS document and was validated by direct input. Here are the results 
* [Autoprefixer CSS Online](https://autoprefixer.github.io/) was used to ensure that all vendor prefixes were included in CSS. The results were copied into the style.css file.

**Testing User Stories from the UX section of the README.md**

1.  As a potential fan and an existing fan, I would like to learn about the bands history and the band members:
    * This is achieved by clicking "The Band" navigation link at the top of each page in the fixed header on every page and the "About" navigation link in the fixed footer on every page. 
    <p>&nbsp;</p>

2.  As a potential fan, an existing fan and a record company, I would like to listen to their songs:
    * This is achieved by clicking "The Music" navigation link at the top of each page in the fixed header on every page.  
    <p>&nbsp;</p>  

3.  As a potential fan and an existing fan, I would like the opportunity to book the band for a show:
    * This is achieved by clicking the "Contact Us" page in the fixed header on every page and requesting a booking.
    <p>&nbsp;</p>  

4.  As a potential fan, I would like to follow the band on social media:
    * This is achieved by clicking the social media links that are in the fixed footer on every page.
    <p>&nbsp;</p>

5.  As an existing fan, I would like to see what upcoming gigs the band is playing at:
    * This is achieved by viewing the "Home Page - index.html" and also "The Band" page.
    <p>&nbsp;</p>

6.  As an existing fan, I would like to purchase the bands merchandise:
    * The merchandise can be viewed by clicking "The Band" navigation link at the top of each page in the fixed header. The merchanise can be purchased by using the "Contact Us" form.
    <p>&nbsp;</p>

7.  As a potential and existing fan, I would like to see the site on all devices such as phone, tablet and desktop:
    * This is achieved by making the website responsive for all devices.
    <p>&nbsp;</p>

8.  As a band member of Sailing In Space, I would like to get more gigs:
    * This is achieved by:
        * displaying upcoming gigs on the home page to promote what they are currently doing;
        * displaying upcoming gigs on the Band page to promote what they are currently doing;
        * displaying videos of the band performing on the Band page to promote what they have done previously;
        * having a contact form on the "Contact Us" page.
    <p>&nbsp;</p>

9.  As a band member of Sailing In Space, I would like the opportunity for fans to purchase tickets to upcoming gigs:
    * The upcoming gigs displayed on the "Home" and "The Band" page have links to the event where tickets can be purchased directly from the event.
    <p>&nbsp;</p>

10. As a band member of Sailing In Space, I would like to sell merchandise:
    * This is achieved by viewing all merchandise on "The Band" page and by using the contact form on the "Contact Us" page.
    <p>&nbsp;</p>

11. As a band member of Sailing In Space, I would like to increase our social media following:
    * This is achieved by having all social media links displayed on the fixed footer that is on each page.
    <p>&nbsp;</p>

12. As a band member of Sailing In Space, I would like to receive a record deal:
    * This can potentially be achieved by promoting their music on "The Music" page and their gigs on "The Band" page.
    <p>&nbsp;</p>

13. As a record company, I would like to find out if they already have signed a record deal:
    * The information on "The Band" page advises that the band is looking for a record deal.
    <p>&nbsp;</p>

14. as a record company, I would like to contact the band:
    * This is achieved by having a contact form on the "Contact Us" page.

**Manual testing of all elements and functionality on every page**

**Home Page - index.html** 

1. Logo:
    **Action**                                                              **Expected Behaviour**          **Result**  
    Confirm the logo displays                                                   The logo displays               Pass   
    Confirm that you can click the logo and you are taken to the Home Page      The Home Page displays          Pass  

2. Navigation Bar:
    **Action**                                                                                   
    a.  Confirm the navigation bar displays in blue    
    **Expected Behaviour**                                       
        The navigation bar displays     
     **Result**  
        Pass

    **Action** 
    b.  Confirm there are 3 links in the navigation bar - The Music, The Band and Contact Us  
    **Expected Behaviour**    
        There are 3 links in the navbar
    **Result**   
        Pass


1.  Logo:
    |Action | Expected Behaviour | Result |
    | ----- | ------------------ | ------ |
    |Confirm the logo displays | The logo displays | Pass |
    |Confirm that you can click the logo and you are taken to the Home Page | The Home Page displays | Pass |



2.  Navigation Bar:
    |Action | Expected Behaviour | Result   |
    | ----- | ------------------ | -------- |
    | Confirm that the 3 links in the navigation bar turn yellow when you hover over them | 3 links in navbar turn yellow when hovered over | Pass |



2. Hero image and video:


3. Footer: 



# Bugs/Fixes

**Home Page - index.html**

**1.    Issue**:  
    On the home page, I had issues where the images weren't displaying on top of each other on a mobile view. 
* **Fix**: To rectify this, I made my images responsive and that fixed the issue.  

**2.    Issue**:  
    I initially created the video using the video tag in HTML but found the video was taking over the whole screen and wasn't responsive. I changed the video tag to an iframe and this fixed the problem. However the video was set to autoplay on a desktop, which I didn't want to happen. 
* **Fix**: I reverted back to using the video tag and made it responsive by using height: auto and width: 100%.  

**3.    Issue**:  
    The 2nd event wasn't fully displaying on mobile phones. 
* **Fix**: To rectify this I added some media queries specifically for screens with a max-width of 576px. 

**4.    Issue**:  
    I originally had the background image URL on the music page in the HTML instead of the CSS. I was advised by some of the slack students that it was better if I have the URL in the CSS. I tried to put it in the CSS but I was having lots of issues having the image displayed as I wanted it. I spoke to Tutor Support and they advised that there is nothing wrong with having the URL and a huge negative margin to display the text on top of the image.
* **Fix**: I placed the URL for the background image on the music page back in the HTML and I was able to display the image perfectly.