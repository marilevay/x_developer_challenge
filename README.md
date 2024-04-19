# X Developer Challenge - Project

## Identify Endpoint

[Manage Tweets > Post a Tweet](https://developer.twitter.com/en/docs/twitter-api/tweets/manage-tweets)
[Search Tweets](https://developer.twitter.com/en/docs/twitter-api/tweets/search)
[User lookup](https://developer.twitter.com/en/docs/twitter-api/users/lookup)

## Code Samples

[Samples](https://github.com/twitterdev/Twitter-API-v2-sample-code)

## Python environment set up
You will need to have Python 3 installed to run this code. The Python samples use requests==2.24.0 which uses requests-oauthlib==1.3.0.

(Optionally) It is common and recommended not to install required package globally, but locally under project subfolder using venv:

```
python3 -m venv venv
source venv/bin/activate
```
You can install these packages as follows:

```
pip install requests
pip install requests-oauthlib
```

## Using Grok into the Project

All the Grok APIs powering grok.x.ai are personalized to your user and thus should not be used to create derived applications.

Use the Chat SDK instead if you wish to implement an app that is powered by Grok and will serve other users.

The main distinction between the Grok SDK and the Chat SDK is that Grok conversations are stateful (i.e. they are persisted on our servers) and you can see all your conversation on grok.x.ai.

The Chat SDK allows you to have conversations with Grok in a stateless fashion. Stateless in this context means that conversations are not stored on the server and every request to the API contains the entire conversation history. Use this SDK to implement custom applications that are based on Grok.

[Chat SDK](https://developers.x.ai/python-sdk/chat/)
