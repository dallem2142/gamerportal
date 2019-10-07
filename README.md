# The Next Generation Clancms, Gamerportal.
### Includes inherit Themesystem, Addonsystem, Vue.js Adminpage, Full Responsiv built with Symfony, Doctrine, Bootstrap. 
#### Techstack
+ PHP (Symfony, Doctrine)
+ MySQL
+ Vue.js
+ Bootstrap
+ Twig
+ jQuery 



## The Core

+ [x]  **1. Create User Register**
Registerform with Email, Password. 
Set Role "Superadmin"

+ [x]  **2. Create Login**

+ [ ]  **3. Create Adminpage (".../admin")**
Only Admins can Access this page.
Response a standard Vue.js Template. That's for the first time enough.

+ [ ]  **4. Built a Themechooser.**
Loop through the ./themes/ directory and list all Themes.
Select another Theme und set this as active. The Frontend theme must be changed and rendered the active theme.

+ [ ] **5. Built a IsUpdateAvailiable?**
Call from the Backend to another API and handle the response

+ [ ]  **6. Addons**
**6.1 Show me alle availiable Addons.**
Call for this, again another API. And Get a list from all Addons 
**6.2 Download Addon**
Click for this, at the download btn. Call again the API. GetAddon()
For this, you must be logged in on the other API. Put in the Request a Session.
When not, return you must be logged in. 
Show Loginform. 
Submit your Credentials.
Go my backend. The Call the another API. And Return the Session. Put This this in Cookie. 
You are logged in. Again click download. 
Request with your cookie, cmsversion. 
Validaten and when alright. Return the .zipfile.
Put this in addons/downloaded/...
**6.3 Install Addon**
Under Tab downloaded addons.
Loop through the downloaded addons dir.
Click install. 
The Addons installed. 
**6.4 Display Addon**
Show the Addon.

+ [ ]  **7. Switch Language**
Switch the Language in the frontend. 
When not logged -> put this as Cookie
When logged -> put in the user. 

+ [ ]  **8. Make Production and Develop Mode**
Production -> bundle and minify all CSS, JS Files. Cache everything.
Develop -> not bundle and minifiy. Cache nothing

+ [ ]  **9. Send Email Service**

+ [ ]  **10. Create a MediaPanel for Uploadimages**


