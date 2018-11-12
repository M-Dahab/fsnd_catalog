# This is the CRUD project in Udacity's Full Stack Nano Degree.
In this project, the aim is to use `Flask` framework to implement a basic catalog web application that contains categories and items inside them.
Also, It will use `oAuth2` for authentication/authorization.

## Dependencies
* `python3`.
* `Flask` framework.
* `sqlalchemy` ORM.
* `oauth2client` package.

## How to run

* Clone the repo and install dependencies.
* Create Google [Web Client Credentials](https://console.developers.google.com/apis/credentials) for `oAuth2`.
* Copy and rename `client_secrets.json.example` to `client_secrets.json` and update its content with your credentials created in the previous step.
* Run `python3 app.py` then visit the [app](http://localhost:5000/).
* For the JSON endpoints, visit:
    * `/categories/<category_id>/items/<item_id>/JSON/` to get a JSON representation of a specific item.
    * `/categories/JSON/` to list all categories in JSON format.
