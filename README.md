# SignUp-Page
This is a newsletter signup application. It prompts the user for their details which gets saved to the mailing list of newsletter and can be used to deliver accordingly. I have used the [Mailchimp](https://mailchimp.com/) API's where you can see the details of the users who have already signed up. After entering the details it takes the users to a success page if they have successfully signed up or to a failure page if there was some error during the process.
To set up the project :-
* Download the project folder and cd into it.
* Create a file with name `.env`
* You will need to set your own unique id and API key by signing up on [Mailchimp](https://mailchimp.com/). Once API key and unique id is generated, add it in your `.env` file.
I have added a **.env_sample** file to show how to configure a .env file. But, you should add it in your **.env** file only.
* Open the terminal in your project folder and enter the following commands
```
 npm install
 node app.js
```
* Open `localhost:3000` in your browser.

You can see the lists of people who have subscribed in the Audience section of Mailchimp webiste with the details they have entered. 
