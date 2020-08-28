# recipe-rs
A rust web server to host a personal list of recipes to cook again.

This web server allows federated access to a database in which recipes and the times they were cooked is stored.

## Use cases
- When thinking about what to cook, I found that I always forget about good recipes I once cooked and so tend to repeat the same few things. This web server, or more precisely a front end to it, helps me find which recipes I cooked long enough ago to cook again, but liked well enough for a repeat to be a good idea.

- After cooking I more likely than not, find some small changes I would have liked to make to the recipe based on the results. Through *recipe-rs* it is possible for me to add an image and some short notes to the recipe for me to remember the next time I try to make something.

- I never really found myself using the filtering options on existing sites/apps, but I wish for recipe tipps based on the ingredients I have on hand. If I spend the time to manually enter all the provided ingredients and correct the amount of servings, I can more precicely filter based on these parameters.

- Maybe you don't want your recipes out in the wild for everyone to see. Since *recipe-rs* is self-hosted, you and you alone are in charge of who gets to see, edit or create new recipes.

## Webpage
The first basic way to access all recipes and other data. The idea is that anybody can access all recipes, unless specified on the configuration level, while only logged in users can create new recipes to avoid spam.

## Mobile app
I would like a mobile app to access most functionality when offline, and do everything the web site can when online. This will probably be implemented as a native Android app, as that is what I need the most, but I am toying with the idea of trying out Progressive Web Apps, which would then also support iOS without me needing an iPhone.
