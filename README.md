# Resume - Armand J O Karczmarz - v0.63 - Map Added

This site is designed to show my coding skills in the website itself and it's different features. 
Then the information on the page will detail my previous work, my interests, my skill, a way to contact me and finally a downloadable CV.\
To help convey the information I will install a map that shows the different locations of the conferences and meetups I have attended. 
An email, with the required details to get back in touch with potential employers, will be sent from contact page through a contact form.
My previous work will be show through a link to my github repositories, I would like it to be displayed on the page itself but it maybe a link to my github.\
Finally I hope to design the page layout and colour scheme to show my skill in this department to engage employers and other people interests in my work.

### Version Information
Version Information is in the change log in the assets folder

## UX
These are the users I am thinking off:-

* Employers - I want to make the information they need easy to see and access with feature that help them to use this. 
i.e I am thinking of a employer user looking for my contact details, examples of my other works and the accessablity to meet up
and talk about single jobs or contracts

* Peers - I want to make my work easily accessable and have a way to contact me. i.e I am thinking of fellow coders wanting to see
my coding and possible use, ask for permition to use my code and have a way to ask to work with me on their projects

## Features
* Index Page
    * About Me section
        * I want a section that gives a small summery of what I do, mostly my skills
        * I want a seciton that gives a small summery of how I do my job, how I schedule my work
        how I work or have worked in teams and my methods of coding (structure and practice)
        * Finally I would like a section that gives a small summery of why they should hire me
    * Personal Information section
        * My full name
        * My home addess, possible bussiness address in the future
        * Ways to contactm me, email and phone number

* Resume Page
    * My Skills section 
        * A description of my frontend development skills
        * A description of my backend development skills
        * A way to show how confidant I feel in the coding languages I know
    * Work History section
        * I would like a timeline of the different companys or contracts I have done
        * I would like my title at that job desplayed
        * I would like contact details of the bussiness if they are okay giving a reference

* Contact Page
    * I need a form that asks for the input from the user
        * It must ask for the users email
        * It must ask for the users name
        * Finally it must ask for input of information detailing the reason for contacting me
            * For contracts, collabiration or other requests
    * I need a submit button that sends this information as a email to my email

* Download Link
    * A navigaton and footer link that downloads my CV from the assets section of the page

### New Features
* Interests Page
    * I'd like a map that shows the conferences and meetups I have attended
        * Idealy I'd like a google maps interactive map with the markers on
    * I'd like the rest of the page to be populated by my interests, i.e. groups I attend and I am interested in
        * These will be coding groups not my personal interests to keep the target audiances focus on my coding enthusiasm and skill

### Existing Features
* Index Page
    * About Me section
        * I want a section that gives a small summery of what I do, mostly my skills
        * I want a seciton that gives a small summery of how I do my job, how I schedule my work
        how I work or have worked in teams and my methods of coding (structure and practice)
        * Finally I would like a section that gives a small summery of why they should hire me
    * Personal Information section
        * My full name
        * My home addess, possible bussiness address in the future
        * Ways to contactm me, email and phone number

* Resume Page
    * My Skills section 
        * A description of my frontend development skills
        * A description of my backend development skills
        * A way to show how confidant I feel in the coding languages I know
    * Work History section
        * I would like a timeline of the different companys or contracts I have done
        * I would like my title at that job desplayed
        * I would like contact details of the bussiness if they are okay giving a reference

* Contact Page
    * I need a form that asks for the input from the user
        * It must ask for the users email
        * It must ask for the users name
        * Finally it must ask for input of information detailing the reason for contacting me
            * For contracts, collabiration or other requests
    * I need a submit button that sends this information as a email to my email

* Download Link
    * A navigaton and footer link that downloads my CV from the assets section of the page

* Interests page
    * A Conferences and Meetups section
        * I would like a bold title
        * I would like a map that use the google maps api to show the locations
        of the previous conferences and meetups
    * Interests section
        * Idealy I would like to split this into four sections these sections need:-
            * Bold headers to seperate them
            * A ruff description of the organisation/group
            * Why I like to work for/with them
            * A link to more information about these groups

### Features Left to Implement
* Index Page
    * Complete Structure - Needs personal information adding

* Resume Page
    * Complete Structure - Needs personal information adding

* Contact Page
    * Complete Structure - Needs code adding to send information to my email

* Download Link
    * Complete Link - Needs a CV in the assets area to link to

* Interests page
    * A Conferences and Meetups section
        * Complete, personal locations needed to be added
    * Interests section
        * The structure is complete but personal information needs to be added
	
## Technologies Used

* Font Awesome
    * Used to improve UX, gives context to titles and hyperlinks

* Hover.css
    * This is used to apply effects to the buttons for a better UX, shows a response to their input so they know there input has been processed

* Bootstrap
    * The website uses bootstrap for easy feature addition

## Testing
1. Ratios in smaller screens
    * On smaller screens I tested if things looked natural the ratios I tested where:-
        * 360 x 640 and 640 x 360
            * Intially I had an issue with:-
                * Social Logo sizes
                    * To ammend this when going down to a smaller screen I reduced there size by varying degrees till it look reasonable on the page
                * Content is allined next to each other instead of ontop of each other.
                    * I changed there alignment so that they would site ontop of each other in small screen rations, 
                    making a downward flow instead of them sitting next to each other.
                * Image Warping
                    * The image was changed so that it would always keep ration and fit in the space it had,
                    this meant it had a background which I coloured to make it stand out more. 
                    I believe this make it stand out more even though it wasn't my initial intention.
                * Text size
                    * Text for headers is reduced to fit better and not take to much space on the page to allow better flow.
                    * Small text is enlarged on small screens to be more readable for the user.
        * 768 x 1024 and 1024 x 768
            * The same issue form the smaller screen size where present at this size, 
            but working with a smallest to largest work method it looks okay with the changes already made
            * Intital when changing to the 1024 x 768 ration the buttons didn't look entirely correct, 
            but afer consideration I changed the icon size slightly to look slightly small on all sizes which resolved this issue
        * PC Screen with varying window sizes (transition between sizes)
            * After the corrections made on the smaller screens I couldn't see any issues with the transitions or the maximum size window
2. Hover effect on buttons
    * When testing I noticed that on smaller screens that covered up some of the buttons underneathe it, 
      for example home slightly covered up contracts
        * To fix this I have reduced there slide down size slightly which has removed this issue
    * When they slide down the colour didn't look entirely right as I left it to a grey from some of my other code
        * To make a better apperance I change it to a black with low opacity, 
        so that it looked like a shadow
3. Links
    * I check that all links went to the correct locations
        * These all worked except the index.html link which I forgot to change for some pages and was fixed
        * Download link couldn't be check as it currently has nothing to download
4. Form Functional
    * It appears to take the data correctly and refuses to submit unless there is data in all fields which is the desired result
        * This will be tested further once the link to my email is done
5. Testing links to and from Interests page
    * All working correctly and the spacing looks okay colour needs to be added to it's navigation button
    * The Interests page orignally didn't look correct when opened using the navigation bar
        * After investigation I had forgoten to change the CSS link after importing from index.html
            * This has been rectified
6. Testing Map
    * Map move and zooms
        * The API runs correctly
    * Locations added are show and zoomable
        * When the compressed location are click, 
        it zooms in and any locations that are closed together will still be compressed 
        and have the same click features 
    * Zoom resets
        * The zoom of the map resets to the orignal zoom that shows the a lot of countries
## Reference
