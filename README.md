# Flatiron Dark Sky API Hackathon 

## Instructions 

For this project we will be splitting up into groups of 3-4 and building either a CLI app, Sinatra, Rails or React app that implements the Dark Sky API. Choose whatever tool makes the most sense for your team (if no-one knows how to use Rails or React, but knows basic Ruby then do a CLI).

#### Teamwork (Pair Programming)

You will have around 120 minutes to work on the project as a team. Please work as a team, There should only be one person writing on the keyboard at a time (make sure to rotate who is actually coding). The rest of the team will help guide who is driving the code. Make sure that everyone gets at least 2  15 minute sessions each, to work on the project (!!SET A TIMER!!). 

#### Getting your DarkSky API KEY

Our DarkSky api does require an API KEY. To get the api key follow these instructions:

1. Go To [https://darksky.net/dev/](https://darksky.net/dev/)
2. Click on Signup (only one user in the group needs to register)
3. Fill in your details in the form and click Register
4. Check your email for confirmation email
5. Click on link in confirmation email
6. You should see a "Welcome to the Club!" screen that states you are successfully activated. 
7. Click the login link and sign in with your newly created credentials
8. Once you login you should see your "Secret Key". It should look something like "3243kjfsja3wuaruajkasfaipu3rjhsfjsdfa"
9. Save this key somewhere in your application as this will be required to access the API endpoint. 
10. You should also see a sample API call below your secret key with a link. Click on the link and look at the response. This is the data we will use to make our app interactive. It gives you details for minutely, currently, hourly, and daily weather. 
11. Make note that the API URL is `"https://api.darksky.new/forecast/" + YOUR_SECRET_API_KEY + "/" + latitude + "," + longitude`


#### Accessing the API with Faraday

If you are building a Ruby App I would recommend using the __Faraday gem__ to get access to the data quickly. 

You can find the documentation at [https://github.com/lostisland/faraday](https://github.com/lostisland/faraday)


#### Starter Code

1. CLI - [CLI Starter Kit](repo)
2. Sinatra App - [Corneal Gem](https://github.com/thebrianemory/corneal)
3. Rails App - [Rails Gem](https://github.com/rails/rails)
4. React App - [Create React App](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwi-jcup2_fUAhXE5SYKHduKCbQQFggmMAA&url=https%3A%2F%2Fgithub.com%2Ffacebookincubator%2Fcreate-react-app&usg=AFQjCNFClfRovodlePaq7LjL5UL4NYx-xA)

