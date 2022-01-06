## Django Stack
You can now spin up a [Django](https://www.djangoproject.com/) app and deploy it to [Azure](https://azure.microsoft.com/en-in/) in seconds.

Using this stack as template would create a new repository for codebase and dploy the Django app on Azure.

## Prerequisites
Having a Azure account with an active subscription(Yes, that's it!! )
Deployment happens on Azure Cloud via Azure App Service.

## What are the inputs to pass while setting up the stack?
```
# Name of the Azure App which has been configured to host the website
- AZURE_APP_NAME

# Azure Publish profile
- AZURE_WEBAPP_PUBLISH_PROFILE
```

## How to get AZURE_WEBAPP_PUBLISH_PROFILE? 🔑
```
Login/Signup to Heroku -> Account Settings -> API Key
```
Check [this](https://help.heroku.com/PBGP6IDE/how-should-i-generate-an-api-key-that-allows-me-to-use-the-heroku-platform-api) out for more details on getting Heroku API Key.

## App hosted URL would be:

Once you create a repo out of this stack, you can find your website deployed at <azure_app_name>.azurewebsites.net.
```
Example: APP_NAME input by user is: sample-website
Hosted URL: https://www.sample-website.azurewebsites.net
```

## Tech Details:
- Python: 3.8
- Django: 4.1



