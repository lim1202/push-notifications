# Push Notifications codelab

forked from [GoogleChrome/push-notifications](https://github.com/GoogleChrome/push-notifications)

The cURL command to send a request to GCM to issue a push message looks like this: 
`curl –header “Authorization: key=<PUBLIC_API_KEY>” –header “Content-Type: application/json” https://android.googleapis.com/gcm/send -d “{"registration_ids":["<SUBSCRIPTION_ID>"]}”`
