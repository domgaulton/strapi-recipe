# Strapi application

A quick description of your strapi application

# Strapi
* `npm run develop` - starts server on `http://localhost:1337`
* Quick start - https://strapi.io/documentation/3.0.0-beta.x/getting-started/quick-start.html

# Heroku Hosting
* `git push heroku master` || https://strapi.io/documentation/3.0.0-alpha.x/guides/deployment.html#heroku
* https://dashboard.heroku.com/apps/strapi-recipe
* Admin - https://strapi-recipe.herokuapp.com/admin
* Login - https://strapi-recipe.herokuapp.com/admin/auth/login
* API Example - https://strapi-recipe.herokuapp.com/recipes

# Bugs
* First time you deploy you need to make sure that you set recipes to findable (See quickstart);
```
Navigate to PLUGINS - Roles & Permission.

Click the pencil edit icon to the right of the Public Role.
Scroll down under Permissions, find Recipes. Click the checkbox next to find.
Click Save
```