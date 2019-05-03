# AndroidThirdAssigment --By Pradip Kandel
This is a simple android application which aims to use some most important features of android programming. Here, I have used the features like Shared Preference, Splash Screen, Fragments, Action Bar, Menu, ViewPager, TabLayout, Recycler View and so on. First of all, splash screen loads which checks whether the user is logged in or not through shared preference. If user is not logged in, it redirects user to login fragment (inside MainActivity) and ask user to fill username and password. If user is not registed yet, user can go to register page, enter all the required details and get registered. This user details are saved to shared preference. Once user is registered, user can login with username and password. If username and password match the username and password registed in shared preference, then the user is redirected to dashboard page else user is not allowed to access dashboard page. The dashboard page displays the items in a recycler view. From the menu bar in the dashboard page, user can go to Add New items page and add new items. These items are saved to a text file in the internal storage. Then in the dashboard page, the same item details are retrieved in recycler view. For recycler view, I have created a model class, itemAdapter class and a sample row resource layout file. Images are not saved to internal or external storage rather they are saved to res/drawable file and retrieved from the same location when displaying items. On the dashboard page, we can see items with their name and when we click the image of the items, we are redirected to new page which displays all the details of that clicked item. On the dashboard page, I have created a menu where there is a option to logout. When we click on this option, we are asked to confirm through the use of dialog box. If user clicks OK in the dialog box, the user is redirected to login page. In this way, this application works. 
