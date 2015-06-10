# restws_settings
Starting point for a RestWS feature

Blog post: [https://echo.co/blog/getting-started-backbone-js-and-restws-drupal-7](https://echo.co/blog/getting-started-backbone-js-and-restws-drupal-7)

Read more about the RESTful Web Services module: [https://www.drupal.org/project/restws](https://www.drupal.org/project/restws)

# install

Clone the repo into your site's modules directory. Then download backbone and
underscore.

```bash
mkdir -p $(drush dd)/sites/all/libraries
cd $(drush dd)/sites/all/libraries
curl -L https://github.com/jashkenas/backbone/archive/1.2.1.zip | tar -xf - && mv backbone-1.2.1 backbone
curl -L https://github.com/jashkenas/underscore/archive/1.8.3.zip | tar -xf - && mv underscore-1.8.3 underscore
```

Then enable the module.
