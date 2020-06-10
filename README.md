<img src="https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png" style="margin: 0;">

## Milestone Project 4 (Ecommerce Django App) 
## Tech For You

**For a live version of the site click <a href="https://ecompro4.herokuapp.com/">Tech For You.</a>**

### About Tech For You
<hr>

*During these difficult period of Corona more and more people where forced to work from home.*
*So this website is here to provide all the tech equipment that you need to get your job done with comfort and plesure.*

The site contains the following:

* Search, browse and add  products to cart without registration
* There is a Login and Register fuctionality.
  
  * Registered Users can checkout and buy products from this site.


## UX
<hr>

*This website is built to meet the needs of people who are work remotely and of course for people you are interested in tech. Is an e-commerce store with a very simple and clear layout. The project is responsive and you can access it through all modern browsers and mobiles*

## Features
<hr>

### Existing Features

* **Navigation**
  * The main logo leads to HomePage.
  * The search icon allows users to searh a product by keyword. 
  * The button Shop Now directs you to all Product.
  * Account button allows users to logIn to the exsting acount.
  * If they are not registered then they can create an account. 
  * Log out allows users to log out.
  * **Logged In**
    * You are able to access payment
    * You are able to logOut
  * Flash messages appear after login/register, update/delete/add and purchase a product
  * There is a sort option, where the user can sort the products based on their preferences
  * **Sort**
    * Price (low to high)
    * Price (high to low)
    * Rating (low to high)
    * Rating (high to low)
    * Name (A-Z)
    * Name (Z-A)
    * Category (A-Z)
    * Category (Z-A)
  * Products
    * Image
    * Name
    * Price
    * Rating
    * Category
  * Product Details
    * There is a short description of the product
    * Image of the product
    * Name
    * Price
    * Category
    * Buttons
      * Quantity: where you can add more than item
      * Add to Cart: where you add product to cart
      * Keep Shopping: where you redirected to all products
  * Stripe Payment integration
  * Confirmation email after purchase and verify email after register

### Features left to Implement
  * Add more images on the products Details
  * Add filter to search option
  * Add some customer reviews
  * Add social account registration

## Technologies Used 
<hr>

*The technologies we used to create the website are the follow:*
### **Front End**

<a href="https://dev.w3.org/html5/html-author/"> **HTML 5** </a> : Markup language used for structuring and presenting content on the World Wide Web.

<a href="https://jigsaw.w3.org/css-validator/Email.html"> **CSS 3** </a>: Style the web documents

<a href="https://getbootstrap.com/docs/4.3/getting-started/download/">**Bootstrap 4.0.0**</a>: To make the website more responsive

<a href="https://jquery.com/">**JQuery**</a>: For better user experience

<a href="https://en.wikipedia.org/wiki/JavaScript">**JavaScript**</a>: used to program the behavior of Web pages.

<a hfer="https://www.python.org/">**Python**</a>: programming language.

<a hfer="https://aws.amazon.com/">**AWS**</a>: service offered by Amazon Web Services that provides object storage through a web service interface.

<a href="https://docs.djangoproject.com/en/1.11/">Django</a>:  a Python-based free and open-source web framework, which follows the model-template-view architectural pattern.

<a href="https://stripe.com/ie">Stripe</a>: a payment company that allows individuals and businesses to make and receive payments over the Internet



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


**I added manual testing by clicking every element on page which can be clicked.**

#### Search form

* Available all the time on menubar
Try to submit empty form and verify that an error message about required fields appear - form doesn't have required attribute. After submiting returning page with all available products.


### Log in / Register 
Both the Sign In and Sign Up form were tested and they work. 
The user cannot be registered if the form has an invalid email address, then an error will be appeared notified the invalid address.
Also the required attribute is added to the 'username', "email" and 'password' fields so if those fields are not filled in then the user will be asked to fill in this fields and the form will not be submitted. 
If all fields are valid then the user will get a flash success message.
If an exsiting user tries to register then a flash message will appear saying that 'Sorry username already exists!' that will appear if the username if taken from another user.
If an exsting user tries to login with an unvalid username or password a flash message will poped-up alerting with the message 'Invalid username/password'.

### Admin
As a normal user if you try to get in to admin (expected to fail with no access and no button to press)
Add/edit and delete products only as an admin

### Buttons
All buttons were working perfectly and they redierect to the right pages.
Click Home link (redirect to homepage)
Click logo/brand link (redirect to homepage)
Click Log in link (redirect to login page form)
Click Register link (redirect to registration page form)
Click Cart link (redirect to cart page)
Click Logout link (user is logged out)
Click Back to top arrow icon (page is scrolling up)


### Cart page
Try to submit empty form and verify that an error message about required fields appear
Try to submit the form with valid input and verify that a success message appears
Try to submit the form with invalid input and verify that a error message appears
Click Remove - item is deleted from cart (message appears)
Click Keep Shoppig button (user is redirected to products page)
Click Checkout button (user is redirected to checkout page)
Payment user details/ credit card form

### Checkout page
Try to submit empty form and verify that an error message about required fields appear (required message appears)
Try to submit the form with valid input and verify that a success message appears (user is redirected to homepage and message appears)
Try to submit the form with invalid input and verify that a error message appears (use different card number cause error message appears)
All fields in user details form have required attribute. Credit card forms has required attr set to false as there is some issue and payment cannot be successfully proceed.

For Stripe payment test following details need to be used:

Card number - 4242424242424242

CVC - any 3 digit number

Expiry date - any date in the future

Scrolling up and down all the pages

## Deployment
<hr>

#### GitHub :
* To check my website on GitHub click <a href="https://github.com/edshuli/e-commerce-project4">**here**</a>
* If you want to clone or downloan the repo, you can simply click on the green button "Clone or Download" and then save it in a folder
#### Heroku :
* This website is hosted on Heroku. You can check the live version here: <a href="https://ecompro4.herokuapp.com/">https://ecompro4.herokuapp.com/</a>

##### Deploy project to Heroku
* Create app on Heroku
  * Login to your acount on Heroku and create the project by setting its' name.

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
Sources for this projects:
 * <a href="https://codeinstitute.net/5-day-coding-challenge/?utm_term=code%20institute&utm_campaign=a%252526c_BR_IRL_Code_Institute&utm_source=adwords&utm_medium=ppc&hsa_net=adwords&hsa_tgt=kwd-319867646331&hsa_ad=417953888762&hsa_acc=8983321581&hsa_grp=61892761125&hsa_mt=e&hsa_cam=1653311402&hsa_kw=code%20institute&hsa_ver=3&hsa_src=g&gclid=CjwKCAjwssD0BRBIEiwA-JP5rIaasKahTTABTKWT4xmR40LKT7dZEzrptN8NROsKin-YuzzBeu_qbxoCZsoQAvD_BwE">Code Institute</a>
 * <a href="https://docs.djangoproject.com/en/1.11/">Django</a>
 * <a href="https://www.w3schools.com/">W3schools</a>
 * <a href="https://stackoverflow.com/">Stack Overflow</a>

### Media
The homepage photo was taken from <a href="https://unsplash.com/t/wallpapers">Unsplash</a> a source for freely usable images.


### Acknowledgements 

* <a href="https://stackoverflow.com/">Stack Overflow</a>
* <a href="https://www.w3schools.com/">W3schools</a>
* <a href="https://slack.com/intl/en-nl/">Slack</a>



* A big big Thank You all the support that I got from **Code Institute** -  Teachers, Tutors and of course my mentor Sandeep Aggarwal.

--------


