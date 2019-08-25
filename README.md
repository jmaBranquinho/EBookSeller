# EBookSeller

#Test
To test the payment api you can use any dummy data and the following test card number: 4242 4242 4242 4242.

It will redirect you to a success page which will say something like "you will receive an e-mail with the e-book in the nest few minutes".

Note: Nothing will be sent to your e-mail and no real purchase will be handled by stripes. It will remain locked in Test Mode which only accepts the test card number above.

#To Run Locally
The app is running in Heroku and is associated to my Stripe account.
All the keys are configured as variables in Heroku as well as in keys_dev.js, which I added to the .gitignore.
When the app is running on Heroku it uses the configured variables. On the other hand, if the app is running locally it will look for the keys in keys_dev.js.

Therefore, to test it locally you need to create the keys_dev.js file as well as a Stripe account and use the given keys.
