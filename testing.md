Testing
=======

**As a User, I would like a Navigation Bar, so I can easily navigate the Website.**
-----------------------------------------------------------------------------------

- At the top of the website the user will see that the navigation bar is fixed to the top of the page. User can scroll down the page 
with the navigation bar still there for them to click on if they want to go to another page. 

- Its layout is simple, using only black and white colouring. If the user hovers over a link it changes to green and underlines the heading. 
- Each link takes you to its page; Things To Do, City Info & History. When on these pages its highlighted in green and underlined in the navigation bar.
- The Visit Gotham logo takes you back to the home page.

Steps taken -

>1. Go to the Visit Gotham website.
>2. Click on Things To Do link to verify it takes you to the Things To Do page.
>3. Verify the link on this page in navigation bar is highlighted in green with underlining. 
>4. Click on City Info link to verify it takes you to the City Info page.
>5. Verify the link on this page in navigation bar is highlighted in green with underlining. 
>6. Click on History link to verify it takes you to the History page.
>7. Verify the link on this page in navigation bar is highlighted in green with underlining. 
>8. Click on Visit Gotham logo to verify it takes you to the Home page.
>9. Repeat process for every page. 

![image](README_files/images/navbar.png)
![image](README_files/images/nb-hl.png)

**As a User, I would like the Home Page to have links to each section within the Things To Do page.**
----------------------------------------------------------------------------------------------------

- User scrolls down the home page, to the Things To Do section. All categories are displayed in a grid layout.
- The User can click on each category and will take them to that section on the Things To Do page. 

Steps taken -

>1. Click on the Gotham City Zoo link to verify it takes you to the Gotham City Zoo section on the Things To Do page.
>2. Click on the Museums & Galleries link to verify it takes you to the Museums & Galleries section on the Things To Do page.
>3. Click on the Educational Tours link to verify it takes you to the Educational Tours section on the Things To Do page.
>4. Click on the Activities link to verify it takes you to the Activities section on the Things To Do page.
>5. Click on the Sightseeing link to verify it takes you to the Sightseeing section on the Things To Do page.
>6. Click on the Parks & Recreation link to verify it takes you to the Parks & Recreation section on the Things To Do page.
>7. Click on the Nightlife link to verify it takes you to the Nightlife section on the Things To Do page.
>8. Click on the Bars & Restaurants link to verify it takes you to the Bars & Restaurants section on the Things To Do page.
>9. Click on the Batman Memorial link to verify it takes you to the Batman Memorial section on the Things To Do page.

![image](README_files/images/ttd-sec.png)

**As a User, I would like the Home Page to have links to each section within the City Info page.**
--------------------------------------------------------------------------------------------------

- User scrolls down the home page, to the City Info section. All categories are displayed in a grid layout.
- The User can click on each category and will take them to that section on the City Info page.

Steps taken - 

>1. Click on the Basic Information link to verify it takes you to the Basic Information section on the City Info page.
>2. Click on the Geography/Weather/Climate link to verify it takes you to the Geography/Weather/Climate section on the City Info page.
>3. Click on the Tours & Visitors Pass link to verify it takes you to the Tours & Visitors Pass section on the City Info page.
>4. Click on the Transportation link to verify it takes you to the Transportation section on the City Info page.
>5. Click on the Local Laws & Currency link to verify it takes you to the Local Laws & Currency section on the City Info page.

![image](README_files/images/ci-sec.png)

**As a User, I would like to be able to preview and download a map of Gotham City.**
-------------------------------------------------------------------------------------

- User scrolls down the home page to the City Info section where they can find a link to the Gotham City Map. The User can click on the 
link and it will tak them to a preview of the Gotham City Map.
- The preview is clearly titled, with a link to return to the home page and also a link to download the map.
- The User also has a link on to download the map on the City Info page.

Steps taken - 

>1. Go to the Gotham City Map link on the Home page.
>2. Click on the Gotham City Map link to verify it shows a preview of the Gotham City map.
>3. Click on the Return link to verify it returns you to the homepage. 
>4. Click on the Download link to verify it will download to the device.
>5. Go to the City Info page.
>6. Go to the Geography section. 
>7. Click on the Click here to download a Map of Gotham City link to verify it downloads the map to the device.

![image](README_files/images/gm-pre.png)
![image](README_files/images/ci-gm.png)

**Bugs and Problems**

I went back and forth between its current html preview page and using a Bootstrap framework to create a Modal. Unfortunately, 
even though I was successful in implementing this. I couldn't get the Modal to pass through a Validator without errors from the 
Bootstrap framework, if I had more time I would have tried to solve the issue. 

**As a User, I would like contact information from the website, so I can speak to them directly.**
--------------------------------------------------------------------------------------------------

- User can scroll down to the bottom of any page in the footer and find the contact information of the website. 
- User can also click on the email address or phone number directly rather than enter the details manually.

Steps taken - 

>1. Go to the Contact Information section.
>2. Specifically for smart phones. Click on phone number link to verify it will open the phone app on the device.
>3. Click on the email address to verify it will open the email app on the device. 
>4. Repeat process for every page.

**As a User, I would like to be able to see which social media platforms the website is on.**
---------------------------------------------------------------------------------------------

- User can scroll down to the bottom of any page in the footer and find the social media links for the website. Each icon will 
take the user to its corresponding platform. 

Steps taken - 

>1. Go to the Social Media section. 
>2. Click on the Facebook Icon to verify it takes you to Facebook.
>3. Click on the Twitter Icon to verify it takes you to Twitter.
>2. Click on the Instagram Icon to verify it takes you to Instagram.

**As a User, I would like a list of the business partners associated with Gotham City.**
----------------------------------------------------------------------------------------

- User can scroll down to the bottom of any page in the footer and find links to Gotham's business partners as the companies logo. 
Each logo will take the user to its corresponding social platform.

Steps taken - 

>1. Go to the Business Partners section. 
>2. Click on the Business logo to verify it goes to the relevant site.
>3. Repeat for each business partner.
>4. Repeat process for every page.

**As a User, I would like to be able to enter my email address, so I can subscribe to the website's newsletter.**
-----------------------------------------------------------------------------------------------------------------

- User can scroll down to the bottom of any page in the footer and find Newsletter sign up section with an input field. 
- User can enter a valid email address and click 'Sign Me Up!' to register for the newsletter.

Steps taken -

>1. Go to the Newsletter Sign Up section.
>2. Try to submit the empty form and verify that an error message about the required fields appears.
>3. Try to submit the form with an invalid email address and verify that the relevant error message appears.
>4. Try to submit the form with a valid email address to verify that as successful message appears. 

![image](README_files/images/be-frm.png)
![image](README_files/images/em-cfrm.png)

**As a User, I would like a scroll up feature at the bottom of each page, so I am able to go back to the top of the page.**

- User can scroll down to the bottom of any page and in the footer find an up arrow icon that they can click, which will take them 
back to the top of that page. 

Steps taken - 

>1. Go to Scroll Up feature at the bottom of the page.
>2. Click on the icon to verify it takes you back to the top of the page you are on. 
>3. Repeat process for every page.

**Bugs and Problems**
Initially when I implemented this feature I made it scroll up to the top of the page by linking it to the Navigation bar, however a
 problem occurred when I decided to make the navigation bar fixed, the scroll up bar visually didn't appear to work. I fixed this by 
 changing the link from the navigation bar to the hero image at the top of the page. 

**As a User, on the City Info page I would like information and links to contact numbers and addresses, that are useful for when I'm visiting the city.**
-------------------------------------------------------------------------------------------------------------------------------------------------------

- The User can go to the City Info page and find useful and important information they would need as well as contact numbers and 
addresses they could utilise when visiting the city. 
- User can click on website links to take them to relevant pages.
- User can click on phone numbers directly rather than enter the details manually.

Steps taken - 

>1. Go to the City Info page.
>2. Go to the Tours & Visitors Pass section.
>3. Click on the **Visit our Tours page** link to verify it works. 
>4. Repeat process for **visit our calendar** link in the Seasonal Events & Attractions section.
>5. Repeat process for **911**, **611**, **818-GOTHAM 468-426** and **411** links in the Useful Phone Numbers section.
>6. Repeat process for **275-157-9586** and **146-432-7929** links in the Currency section.
>7. Repeat process for **gothamgo**, **411** and **read our tips for visitors** link in the Saftey section.
>8. Repeat process for **ilovegotham** link in the Gotham State section.

**Websites responsiveness**
---------------------------

Website responsive layout was primarily tested on Google Chrome, Opera and Vivaldi using the Developer Tools. 
The website also worked well with Internet Explorer, Safari and Firefox.
The website also works well with smart devices.

## Desktop View's

>**Home page**
![image](README_files/images/indexpage.png)

>**Things To Do page**
![image](README_files/images/thingspage.png)

>**City Info page**
![image](README_files/images/citypage.png)

>**History page**
![image](README_files/images/histpage.png)

>**Gotham Map page**
![image](README_files/images/gmpage.png)

## Ipad Pro View's ##

>**Home page**
![image](README_files/images/iproind.png)

>**Things To Do page**
![image](README_files/images/iprothings.png)

>**City Info page**
![image](README_files/images/iprocity.png)

>**History page**
![image](README_files/images/iprohist.png)

>**Gotham Map page**
![image](README_files/images/iprogm.png)

## Ipad View's ##

>**Home page**
![image](README_files/images/ipadind.png)

>**Things To Do page**
![image](README_files/images/ipadthg.png)

>**City Info page**
![image](README_files/images/ipadcity.png)

>**History page**
![image](README_files/images/ipadhist.png)

>**Gotham Map page**
![image](README_files/images/ipadgm.png)

## Smart Phone View's ##

>**Home page**
>
>![image](README_files/images/sp-ind.png)

>**Things To Do page**
>
>![image](README_files/images/sp-thng.png)

>**City Info page**
>
>![image](README_files/images/sp-city.png)

>**History page**
>
>![image](README_files/images/sp-hist.png)

>**Gotham Map page**
>
>![image](README_files/images/sp-gm.png)

**Bugs and Problems**

I initally wrote the code with each title and image within it's own individual tag and anchor. 
![image](README_files/images/code1.png)

This became problematic for a responsive layout. As the screen size changed all the tags moved independently and away from there 
correlating title. I fixed this by wrapping an image and it's correlating title with a parent element.
![image](README_files/images/code2.png)

I struggled to get this layout to work responsively. I fixed this by using the flex-wrap property in CSS.
![image](README_files/images/code3.png)

Automated checks
================

I used the W3C's Validators to check my HTML and CSS code. I did this three ways, here are the steps I took.

>**HTML**
>![image](README_files/images/html-checker.png)
>**CSS**
>![image](README_files/images/css-checker.png)

1. **Using the websites URL address to check the HTML code**

>1. Go to https://validator.w3.org and select the URI tab. 
>2. Enter https://liamoconnor87.github.io/VisitGotham/index.html into the address bar and click **Check**.
>3. Confirm that no errors or warnings show. 
![image](README_files/images/urlindex.png)
Do the same for each page. 
>4. Enter https://liamoconnor87.github.io/VisitGotham/things_to_do.html into the address bar and click **Check**.
>5. Confirm that no errors or warnings show.
![image](README_files/images/urlthings.png)
>6. Enter https://liamoconnor87.github.io/VisitGotham/city_info.html into the address bar and click **Check**.
>7. Confirm that no errors or warnings show.
![image](README_files/images/urlcityinfo.png)
>8. Enter https://liamoconnor87.github.io/VisitGotham/history.html into the address bar and click **Check**.
>9. Confirm that no errors or warnings show.
![image](README_files/images/urlhistory.png)
>10. Enter https://liamoconnor87.github.io/VisitGotham/gotham_map.html into the address bar and click **Check**.
>11. Confirm that no errors or warnings show.
![image](README_files/images/urlgm.png)

2. **Using the websites URL address to check the CSS code**

>1. Go to https://jigsaw.w3.org/css-validator/ and select the URI tab. 
>2. Enter https://liamoconnor87.github.io/VisitGotham into the address bar and click **Check**.
>3. Confirm that no errors or warnings show.
![image](README_files/images/urlcss.png)

3. **Upload files to check the HTML code**

>1. Go to https://validator.w3.org and select the File Upload tab. 
>2. Upload index.html file and click **Check**.
>3. Confirm that no errors or warnings show. 
![image](README_files/images/upldindex.png)
Do the same for each page's file. 
>4. Upload things_to_do.html file and click **Check**.
>5. Confirm that no errors or warnings show.
![image](README_files/images/upld-things.png)
>6. Upload city_info.html file and click **Check**.
>7. Confirm that no errors or warnings show.
![image](README_files/images/upld-city.png)
>8. Upload history.html file and click **Check**.
>9. Confirm that no errors or warnings show.
![image](README_files/images/upld-hist.png)
>10. Upload gotham_map.html file and click **Check**.
>11. Confirm that no errors or warnings show.
![image](README_files/images/upld-gm.png)

4. **Upload file to check the CSS code**

>1. Go to https://jigsaw.w3.org/css-validator/ and select the File Upload tab.
>2. Upload style.css file and click **Check**.
>3. Confirm that no errors or warnings show.
![image](README_files/images/upld-css.png)

5. **Input directly to check HTML code**

>1. Go to the repository - https://github.com/liamoconnor87/VisitGotham
![image](README_files/images/github-goth.png)
>2. Click on the index.html file link. This should take you to index.html page displaying the code. From here you can highlight all the code and copy it. 
![image](README_files/images/hl-code.png)
>3. Once copied, go to https://validator.w3.org and select the Direct Input tab.
>4. Paste the code from the index.html file in to the box given.
![image](README_files/images/inputcode.png)
>5. Click **Check** to confirm that no errors or warnings show.
![image](README_files/images/index-input.png)
Do the same for each page.
>6. Copy and paste code from things_to_do.html file link on the repository page to the Validator and click **Check** to confirm that no errors or warnings show.
![image](README_files/images/things-input.png)
>7. Copy and paste code from city_info.html file link on the repository page to the Validator and click **Check** to confirm that no errors or warnings show.
![image](README_files/images/cityinfo-input.png)
>8. Copy and paste code from history.html file link on the repository page to the Validator and click **Check** to confirm that no errors or warnings show.
![image](README_files/images/hist-input.png)
>9. Copy and paste code from gotham_map.html file link on the repository page to the Validator and click **Check** to confirm that no errors or warnings show.
![image](README_files/images/gothmap-input.png)

6. **Input directly to check CSS code**

>1. Once again go to the repository - https://github.com/liamoconnor87/VisitGotham
>2. Click on the **assets** link.
![image](README_files/images/assets-folder.png)
>3. Click on the **css** link. 
![image](README_files/images/css-folder.png)
>4. Click on the **style.css** file link. This should take you to style.css page displaying the code. From here you can highlight all the code and copy it. 
![image](README_files/images/css-code.png)
>5. Once copied, go to https://jigsaw.w3.org/css-validator/ and select the Direct Input tab.
>6. Paste the code from the style.css file in to the box given.
>7. Click **check** to confirm that no errors or warnings show.
![image](README_files/images/css-input.png)