# Angular.Rails -> Ready.App


**Barebones Rails application with AngularJS built into the Asset Pipeline**


### Currently only one way to get started


```
git clone https://github.com/learric/Angular.Rails

mv Angular.Rails _YOUR-APP-NAME_

cd YOUR-APP-NAME

rails s
```


Then open a web browser to [http://localhost:3000/](http://localhost:3000/). If there is a form field inside of a green box, begin entering your name. If 'Hello, **YOUR-NAME**' appears in green, _CONGRATS!_


Next, open

1. app/assets/javascripts/home.coffee
2. app/views/index.html.erb
3. config/application.rb

and change **_AppName_** to whatever your app is named. Try [http://localhost:3000/](http://localhost:3000/) again to make sure the changes worked.