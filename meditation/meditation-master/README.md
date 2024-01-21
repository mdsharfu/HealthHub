

## Welcome to I am...Meditation & Affirmations

![Mock up](wireframes/meditation-app-screenshot.png
)
This is a family friendly meditation/affirmation site designed for both adults and children. It is a space to come to when you need to take some time out of your day to re-center and re-focus yourself.

In those moments when you or your children are feeling off balance and off kilter with life. Taking two minutes out of the day can really make a difference.

I was inspired to create this website as I am a big advocate for mental health and wellness. I have found meditation and mindfulness to be a great support for me in my personal life during challenging and difficult times.

Thank you for visiting my project!  
If you have any feedback or questions, head over to my GitHub contact details and feel free to reach out to me.

You can view the live website [HERE](https://lolaedun.github.io/meditation/)



## **UX**

### **User Goals**

* The website has to work well on all kind of devices like mobile phones, tables and desktops.
* The website has to be fun and interactive.
* Visually appealing website.
* Website should be easily tailored to the individual adult/child.
* Meditation/Affirmation should be shareable.



### **User Stories**

* As a user, I would like to choose timing of meditation/affirmation.
* As a user, I would like to set my meditation/affirmation environment to suit my needs.
* As a user, I would like to be able to switch off sound but keep timer and video going.
* As a user, I would like to be able to have access to meditation regardless of the device i'm using.
* As a user, I would like to be share my meditation or affirmation with a friend.


### **Site owners Goals**
* To build a simple API with family friendly affirmations.
* To create different user modes.
* To collate different background sounds for meditation.
* To collate different background images/videos to sync with meditations.



## Wireframes

These wireframes were created using [Balsamiq](https://balsamiq.com/) during the Scope Plane 
part of the design and planning process for this project. I have created wireframes for phone, tablet and Desktop in a pdf which you can 
view here:



### [View all wireframes here](wireframes/meditation-wireframes.pdf)

### Fonts

- **Pacifico** as the headline text brings a sense of fun with it's brushscript text

-  **Roboto** as body text adds a friendly tone and pairs well with Pacifico. It adds a very simple and easy to read style.

### Icons

media player buttons, toggle switches, button icons.

### Logo 

I designed a simple logo to not distract the user during meditation and for branding purposes.

The logo consists of a person sitting in a classic cross legged meditation pose with the text "I am..." underneath it. The font used is Roboto. The colours used for both the logo and font is white. In addition, the favicon is the person sitting in meditation pose with no text and the chosen colour is black to make it stand out more.

The white logo matches the colour of the fonts and buttons used on the website.

![Logo](assets/images/readme-logo.png)

### Colours Mood board and Mockups

- Pastel, soft colours, relaxing imagery, texture, nature, movement.

![Mood board](wireframes/meditation-mood-board.png)

# Features
## Existing Features

### Elements on the page


#### Play icon
On the play button I have added event listeners to start the background music and video as well as the default countdown timer or selected time.

The pause icon displays as soon as play is activated. Pressing the pause button will pause both audio and video playback
#### Next and Previous icons
The next button will fire up a new background image/video when pressed as well as queue up a new background audio and new affirmation. It will also load the timer to default or previously selected time.

I have purposely chosen to not autoplay video and sound when the previous or next buttons are pressed to give the user the ability to set their meditation space and requirements before starting.

#### Affirmations

I created an object array for affirmations that are assigned to specific image/video. These affirmations change when the next or previous buttons are clicked.

I chose affirmations that work well for both children and adults to make it a family friendly space.
#### Time Select buttons

There are three time options to choose from which will activate the countdown timer. These timing options are suitable for the beginner meditator, the busy parent or personal lifestyle and for children to get comfortable with the idea of taking short times out of their day to go within on a daily basis.

#### Timer countdown

The default time begins at 10mins. If the user selects a different time from the selector buttons then the countdown will automatically update. At the end of the countdown, the timer will automatically reset to the previously chosen time. 

I have also ensured the seconds are displayed in double digits from number 9, but left the minutes to display in single digit for a cleaner and more simple look.

#### Background Image/Video

I have chosen use background video over images and ensured this plays well across various devices. The video version assists with helping to sit through the meditation/affirmation for longer periods and provides a form of guided imagery.

I have opted for simple imagery/videoes that dont distract from the ability to see the buttons and affirmations as well as to ensure a relaxed state is quickly achieved without too much going on. Footage of nature has helped me to achieve this goal.

#### Welcome modal

There is a welcome message for the first time user and beginner meditator to optimize their time on the website during meditation. I have include screenshot to guide the user in setting their meditation space.


#### Mute Button

Sound can be muted on the screen or on users device if they would prefer a quiet meditation or are in a space where having the sound on will bring unwanted attention to the user.

### Features Left to Implement

- child mode
- add gong sound at the end of meditation or audio fade

### Languages
This project uses the following programming languages:
- HTML
- CSS 
- JavaScript
## Technologies Used

- [Git](https://gist.github.com/derhuerst/1b15ff4652a867391f03) to handle version control.
- [GitHub](https://github.com/) to store and share all project code remotely.
- [Imgbb](https://imgbb.com) to store external images for this project that were not entered into the database.
- [Balsamiq](https://balsamiq.com/) to create the wireframes for this project.
- [Am I Responsive](http://ami.responsivedesign.is/) to create the website mockups
- [Canva](https://www.canva.com/) to design mood board, graphics and video for the website.
- [ColourLovers](https://www.colourlovers.com/palettes) to find inspiration for my colour palette.
- [Add this]() social share buttons

### Libraries

- [Bootstrap](https://www.bootstrapcdn.com/) to simplify the structure of the website and make the website responsive easily.
- [FontAwesome](https://www.bootstrapcdn.com/fontawesome/) to provide icons for the website.
- [Google Fonts](https://fonts.google.com/) to style the website fonts.




## **Testing**



#### User story:
**As a user, I would like to choose timing of meditation/affirmation.**

* **Plan**  
My plan is to create 3 buttons for the user to choose various time options from.

* **Implementation**  
I created 3 simple buttons that highlight on hover. These buttons trigger the timer countdown when clicked.
![time select](wireframes/screenshots/ux-timing.png)
* **Test**

    When I hover over the timer selector buttons they get highlighted to make it easier for the user to read over the video.

    I clicked on the 2 min selector button and the default countdown updates to the correct time. Pressing the play button the countdown timer begins along with the music and video. The seconds display in double digits and the minutes in single digit.

    When the countdown timer gets to zero, it automatically resets back to 2 mins.

    When I click on the previous and next buttons. The 2 min timer is still selected.

    I repeated the above steps for the 5 mins and 10 mins selectors.


* **Result**

    Hover on buttons working as expected.

    2 min timer working with no visible issues.

    5 min timer pauses when music ends on a shorter track (noticable on 2nd page). It works with no issues on a longer track.

    10 min timer pauses when music ends on a shorter track (noticable on 2nd page). It works with no issues on a longer track.

* **Verdict**  
Shorter audio tracks have been replaced with longer tracks and countdown timer works to the full length selected. I opted for this instead of looping the music to the timer as I felt this might take away from the user experience during meditation.


#### User story:
**As a user, I would like to set my meditation/affirmation environment to suit my needs.**

* **Plan**  
My plan is to create simple and quick options for the user to create a meditation space that suits them from selecting background image/video to selecting audio and times.

* **Implementation**  
A media player was added to allow the user to select different audio synced with an image/video background by selecting the previous or next buttons.

The audio and video can be paused should the user need this option.

![media player](wireframes/screenshots/media-player.png)
![media player2](wireframes/screenshots/media-player2.png)
* **Test**
The media player buttons (previous & next) were tested to select background image/video.

The play and pause buttons were also tested to make sure they work.

* **Result**
Previous and Next buttons move easily through the various background image/video options.
Play button works only when clicked twice and plays a new soundtrack for meditation.
Pause button pauses both audio and video playback.

* **Verdict**  
All media buttons are working as expected except for the play buttton which has been reported in the bugs section. 


#### User story:
**As a user, I would like to be able to have access to meditation regardless of the device i'm using.**

* **Plan**  
To create a responsive website that works across various devices.

* **Implementation**  
I have added media queries to various screen sizes to improve user experience.

![Responsive1](wireframes/screenshots/responsive1.png)
![Responsive2](wireframes/screenshots/responsive2.png)
* **Test**
Tested various screen sizes and phone devices.

* **Result**
All working and displaying as expected.

* **Verdict** 
Site is responsive and working as expected.

#### User story:
**As a user, I would like to be share my meditation or affirmation with a friend**

* **Plan**  
To add social share buttons to footer of page

* **Implementation**  
I used the "add this" tool kit to create a simple and customized share button that expands on hover to keep the site looking clean and minimalistic.

![Social Share](wireframes/screenshots/social-share.png)

* **Test**

Tested on mobile and various devices.

* **Result**
All working and displaying as expected.

* **Verdict** 
Share button is responsive and working as expected.

## **Validation Reports**

[HTML Validation](wireframes/validations/html-validation.png)

[CSS Validation](wireframes/validations/css-validation.png)

[JS Validation](wireframes/validations/js-validation.png)

      

## **Bugs**

### **Play button works only when clicked twice**

* **Bug**  
The play button doesn't work on the first click. It will only work when clicked twice.

* **Fix**       
changed the media player class in js file to a new id name as it was conflicting with css styling under the same name.

* **Verdict**    
Play button works with single click once page has fully loaded.

### **Timer goes into minus at end of countdown**

* **Bug**  
The timer goes into minus at the end of meditation for a split second before resetting to zero. This only seems to happen on a laptop device. Smaller devices don't seem to be affected.

* **Fix**       
I haven't yet been able to find what could be causing this problem.

* **Verdict**    
Yet to be resolved.

### **White line on the right side of desktop view**

* **Bug**  
There is a white line on the right hand side of the screen

* **Fix**       
change min width and height of video (#bg-img) to 100% instead of 100vh

* **Verdict**    
Video displays full width on desktop screensize.

### **Blue outline box on question icon**
* **Bug**  
There is a blue outline box on mobile view after clicking on the question icon modal.

* **Fix** 
I set the a tag outline to none.

* **Verdict**
Blue outline box no longer shows on mobile device when clicked.

## **Deployment**

This project was deployed via GitHub by executing the following steps.
After writing the code, committing and pushing it to GitHub:

1. Navigate to the repository on github and click **Settings**.
1. From there, go to the **Pages section** on the left hand tab within Github.
1. Select **master branch** on the dropdown menu, and click save.
1. Now the website is live on **https://lolaedun.github.io/meditation/**
1. Any time commits and pushes are sent to Github, the Github Pages site should update shortly after.



To run the project locally:

1. Click the **green Clone or Download button** on the Github Repository
1. Using the **Clone with HTTPS option**, copy the link displayed.
1. Open your IDE, and ensure the Git Terminal is open.
1. Change the working directory to the location where the cloned directory is to go.
1. Use the **"git clone" command** and paste the url copied in the second step.


## Credits

### Content - Media - Inspiration

I have used the following websites to gather ideas, information,code examples, background images and sounds for the overall content of my website. This website would not have been possible without all these amazing resources: 

* [Ben Sound](www.bensound.com)
* [Dev Ed](https://www.youtube.com/watch?v=oMBXdZzYqEk&ab_channel=DevEdDevEd)
* [Traversy Media](https://www.youtube.com/watch?v=QTHRWGn_sJw&ab_channel=TraversyMediaTraversyMediaVerified)
* [fesliyanstudios](https://www.fesliyanstudios.com/royalty-free-music/downloads-c/peaceful-and-relaxing-music/22)
* [Pixabay](https://pixabay.com/music/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=music&amp;utm_content=2055)
* [Google Chrome Momentum](https://chrome.google.com/webstore/detail/momentum/laookkfknpbbblfpciffpaejjkokdgca?hl=en)
* [I am, I can](https://www.dk.com/uk/book/9780241420256-i-am-i-can/)
* [Bianural Beats Meditation](https://www.binauralbeatsmeditation.com/)
* [I awake](https://www.iawaketechnologies.com/)
* [Yuval Ron Music](https://yuvalronmusic.com/)


### Acknowledgements

First of all, I would like to thank my mentor Simen ([Eventyret_mentor](https://github.com/Eventyret)) for guiding me throughout this project. He helped me to break down my project into manageable chunks and saved me from tearing my hair out a few times!

I also want to thank the slack community for jumping in to provide feedback on my project. Special shout out to: Nick Lennon and Mike Avgeros for helping to test out my site.