<img src="https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png" style="margin: 0;">

## Milestone Project 4 (Ecommerce Django App)

## UX

## Features 

### Existing Features

### Features left to Implement


## Technologies Used 
<hr>

*The technologies we used to create the website are the follow:*
### **Front End**

<a href="https://dev.w3.org/html5/html-author/"> **HTML 5** </a> 

* Markup language used for structuring and presenting content on the World Wide Web.

<a href="https://jigsaw.w3.org/css-validator/Email.html"> **CSS 3** </a> 

* Style the web documents

<a href="https://getbootstrap.com/docs/4.3/getting-started/download/">**Bootstrap 4.0.0**</a> 

* To make the website more responsive

<a href="https://jquery.com/">**JQuery**</a> 

* For better user experience

### **Back End**

<a href="https://flask.palletsprojects.com/en/1.1.x/">**Flask 1.1.2**</a> 

* A ightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications

<a hfer="https://api.mongodb.com/python/current/tutorial.html">**PyMongo 3.10.1**</a>

* I used to connect with **MongDb**

<a href="https://www.mongodb.com/cloud/atlas/lp/try2?utm_source=google&utm_campaign=gs_emea_netherlands_search_brand_atlas_desktop&utm_term=mongodb&utm_medium=cpc_paid_search&utm_ad=e&gclid=EAIaIQobChMIpayiipL-6AIVEOR3Ch2HKwvkEAAYASAAEgK9JfD_BwE"> **MongoDb**</a>

* A document based database

## Testing
<hr>

I was testing the application manual throughout the process of it.
I used mainly <a href="https://developers.google.com/web/tools/chrome-devtools/">**DEVTOOLS**</a> for my testing. The site was tested on many browser like ( Google Chrome,
Internet Explorer, Safari and Opera ) and mobile devices such as Iphone8,6s, Huaweii P20 Lite, Samsung Galaxy S10, Samsung Galaxy A20 (Chrome, Ipad, Safari) to ensure compatibility and responsiveness.

The screen sizes tested on decision are the below:

* Moto G4 (360 x 640)
* Galaxy S5 (360 x 640)
* Pixel 2  (411 x 731)
* Pixel 2XL (411 x 823)
* iPhone 5/SE (320 x 568)
* iPhone 6/7/8 (375 x 667)
* iPhone 6/7/8 Plus (414 x 736)
* iPhone X (375 x 812)
* iPad (768 x 1024)
* iPad Pro (1024 x 1366)
* Desktop (xl screens)

To validate the HTML code I used <a href="https://validator.w3.org/"> The W3C Markup Validation Service </a> and 
<a href="https://htmlformatter.com/"> HTML Formatter</a> to use the correct format of HTML5. Showed few errors but that is mainly because of the links that we used due to Python and Flask. But the links work perfectly.

To validate CSS 3 code I used <a href="https://jigsaw.w3.org/css-validator/Email.html"> The CSS Validation Service </a>. The validation showed no error and the connection with Bootstrap was very good. 

## Deployment
<hr>

#### GitHub :
* To check my website on GitHub click <a href="https://github.com/edshuli/Yiami-DCProject">**here**</a>
* If you want to clone or downloan the repo, you can simply click on the green button "Clone or Download" and then save it in a folder
#### Heroku :
* This website is hosted on Heroku. You can check the live version here: <a href="https://yiami-project.herokuapp.com/">https://yiami-project.herokuapp.com/</a>

##### Deploy project to Heroku
* Create app on Heroku
  * Login to your acount on Heroku and create the project by setting its' name.
  * Under the settings tab you click the button **Reveal Config Vars** and I set the IP to 0.0.0.0 and the PORT to 5000 and later on we add
  MONGO_URI.

I am using  GitPod so I am use the below commands on terminal:
* Login to Heroku: **heroku login**
* Enter your credentials: **email and password**
* Create a new Git repository
  * Initialize a git repository in a new or existing directory
     * $ cd my-project/
     * $ git init
     * $ heroku git:remote -a ednaer     
* Deploy your application
  * Commit your code to the repository and deploy it to Heroku using Git.
    * $ git add .
    * $ git commit -am "make it better"
    * $ git push heroku master  

* Existing Git repository
  * For existing repositories, simply add the heroku remote
    * $ heroku git:remote -a ednaer

## Credits

### Content
### Media
### Acknowledgements 

* <a href="https://stackoverflow.com/">Stack Overflow</a>
* <a href="https://www.w3schools.com/">W3schools</a>
* <a href="https://slack.com/intl/en-nl/">Slack</a>
* My tutor and all the support from **Code Institute**

--------


