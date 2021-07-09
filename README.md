# Using SMS as a Fallback Option for Push Notifications

This sample project demonstrates how to compose the OneSignal Web Push SDK with the OneSignal Rest API to enable SMS for users who are not subscribed to push notifications on your site. You can use this project as reference guide for implementing SMS fallback delivery in your site or app.

Interested in learning more about this project? Check out
[this blog post](https://onesignal.com/blog/using-sms-as-a-fallback-option-for-unsubscribed-push-users/).

## Running this sample

###### Setup

Your OneSignal API Key & App ID and Twilio phone number need to be set in `.env.local` before running the project.

```
ONESIGNAL_API_KEY="API Ket"
ONESIGNAL_APP_ID="App ID"
TWILIO_PHONE_NUMBER="+18001234567"
NEXT_PUBLIC_API_URL="http://localhost:3000/api"
```

1. Run `yarn` to install packages
2. Run `yarn dev` to start a dev instance of the server

Note that you will need to have a OneSignal app created before this example will
work. Check the blog post for guidance on creating an app on OneSignal.
