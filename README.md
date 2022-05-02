# My Portfolio Site #
The purpose of this project was to create a portfolio site that hosted basic about me information as well as links to my GitHub and LinkedIn. CSS and HTML were used to format the site and the site is hosted as a static site on Microsoft Azure.

## Steps to Replicate and Personalize This Site ##
1. Clone this repository to local computer
2. Rename the directory to reflect the new project name
3. Delete .git folder
4. Open index.html
    - In the head section under the title either remove lines 8-15 or update to your Google Analytics tracking tag
    - Under the header division ID change your name, university, and degree
    - Change the href links to your GitHub and LinkedIn profiles
    - Under the contentTitle division class change the bio to your bio
    - The last line of code (line 51) remove/change the Google Analytics tracking number
5. Open style.css to adjust any background or text colors
6. Delete profile.jpg and update it with your picture saving with the same name.
7. Set up a static web page in Azure
    - Go to Azure Portal
    - Create a resource group named after your GitHub site
    - Create a static web app and place it in your resource group
        - Name your app
        - Choose a location relevant to where you are (i.e. Iowa --> Central US)
        - Choose GitHub as the deployment source and hook up your account
            - Select the repository your code is in as your source for the site
8. Search to the site that Azure populates for you and you should see your code after a few minutes.
9. Continue updating and adjusting index.html and style.css and pushing to GitHub and your Azure site will reflect the changes.