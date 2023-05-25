# rapyd-curl-request-signature
Make a GET request to List Countries and start testing the Rapyd API. 

### What do you need to start
* Rapyd Account (https://dashboard.rapyd.net/sign-up)
* In order for webhooks to work properly it is necessary to expose the corresponding port of your computer to the outside world (by default port 5000). There are many ways to achieve this. You can use the ngrok application (https://ngrok.com) which will generate a random web address for you and redirect all traffic to a specified port on your local machine
* Python 3+ and cURL (if older operating system)

### How to run rapyd_curl_gen.py
* Log in to your Rapyd account
     * Make sure you are using the panel in "sandbox" mode (switch in the bottom left part of the panel)
     * Go to the "Developers" tab. You will find your API keys there. Copy them to the version of your sample file 
     * If you want to include webhooks, go to webhook_signature_validation.py and enter the URL where the application listens for events. By default it is "https://{YOUR_BASE_URL}/api/webhook" and mark which events should be reported to your app
* Run your version of rapyd_curl.gen.py
* Copy the response from curl to the end
* Paste in the response 

### Get Support
* https://community.rapyd.net
* https://support.rapyd.net
