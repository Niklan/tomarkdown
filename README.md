# tomarkdown
Drupal 7 module for migration HTML content to Markdown.

# Installation.

0. **Create BACKUP** for your database. And try this module on dev site. Do not use it on production.
1. Navigate to module folder and use command `composer install`.
2. Then you can safely enable module.
3. Navigate to config form `admin/config/content/formats/tomarkdown`. And set up your settings.
  [](http://i.imgur.com/4gwIuhC.png)
4. Click _Migrate_ and wait :)

I write it for my own [blog](http://niklan.net/). I migrate all body values of my blog entry from HTML to MD. So there is now support for this module, use it on your own risk, if you have any questions, welcome to the issues. 
