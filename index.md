title	feature_text	feature_image	excerpt
About Alembic
## Alembic A Jekyll boilerplate theme designed to be a starting point for any Jekyll website
https://picsum.photos/1300/400?image=989
Alembic is a starting point for [Jekyll](https://jekyllrb.com/) projects. Rather than starting from scratch, this boilerplate is designed to get the ball rolling immediately. Install it, configure it, tweak it, push it.
Alembic is a starting point for Jekyll projects. Rather than starting from scratch, this boilerplate is designed to get rolling immediately. Install it, configure it, tweak it, push it.

{% include button.html text="Fork it" icon="github" link="https://github.com/daviddarnes/alembic" color="#0366d6" %} {% include button.html text="Tweet it" icon="twitter" link="https://twitter.com/intent/tweet/?url=https://alembic.darn.es&text=Alembic%20-%20A%20Jekyll%20boilerplate%20theme&via=DavidDarnes" color="#0d94e7" %} {% include button.html text="Install Alembic ⚗️" link="https://github.com/daviddarnes/alembic#installation" %} {% include button.html text="Tip me $5 💸" link="https://www.paypal.me/daviddarnes/5usd" color="#333333" %}

Features
Available as a theme gem and GitHub Pages theme
Clear and elegant design that can be used out of the box or as solid starting point
Tested in all major browsers, including IE and Edge
Built in Service Worker so it can work offline and on slow connections
Configurable colours and typography in a single settings file
Extensive set of shortcodes to include various elements; such as buttons, icons, figure images and more
Solid typographic framework from Sassline
Configurable navigation via a single file
Modular Jekyll components
Post category support in the form of a single post index page grouped by category
Built in live search using JavaScript
Contact form built in using Formspree
Designed with Siteleaf in mind
Has 9 of the most popular networks as performant sharing buttons
Has documentation
Examples
Here are a few examples of Alembic out in the wild being used in a variety of ways:

bawejakunal.github.io
case2111.github.io
karateca.org
Installation
Quick setup
To give you a running start I've put together some starter kits that you can download, fork or even deploy immediately:

⚗️🍨 Vanilla Jekyll starter kit
Deploy to Netlify{:style="background: none"}

⚗️🌲 Forestry starter kit
Deploy to Forestry{:style="background: none"}
Deploy to Netlify{:style="background: none"}

⚗️💠 Netlify CMS starter kit
Deploy to Netlify{:style="background: none"}

⚗️:octocat: GitHub Pages with remote theme kit
{% include button.html text="Download kit" link="https://github.com/daviddarnes/alembic-kit/archive/remote-theme.zip" color="#24292e" %}

⚗️🚀 Stackbit starter kit
Create with Stackbit{:style="background: none"}

As a Jekyll theme
Add gem "alembic-jekyll-theme" to your Gemfile to add the theme as a dependancy
Run the command bundle install in the root of project to install the theme and its dependancies
Add theme: alembic-jekyll-theme to your _config.yml file to set the site theme
Run bundle exec jekyll serve to build and serve your site
Done! Use the configuration documentation and the example _config.yml file to set things like the navigation, contact form and social sharing buttons
As a GitHub Pages remote theme
Add gem "jekyll-remote-theme" to your Gemfile to add the theme as a dependancy
Run the command bundle install in the root of project to install the jekyll remote theme gem as a dependancy
Add jekyll-remote-theme to the list of plugins in your _config.yml file
Add remote_theme: daviddarnes/alembic to your _config.yml file to set the site theme
Run bundle exec jekyll serve to build and serve your site
Done! Use the configuration documentation and the example _config.yml file to set things like the navigation, contact form and social sharing buttons
As a Boilerplate / Fork
(deprecated, not recommended)

Fork the repo
Replace the Gemfile with one stating all the gems used in your project
Delete the following unnecessary files/folders: .github, LICENSE, screenshot.png, CNAME and alembic-jekyll-theme.gemspec
Run the command bundle install in the root of project to install the jekyll remote theme gem as a dependancy
Run bundle exec jekyll serve to build and serve your site
Done! Use the configuration documentation and the example _config.yml file to set things like the navigation, contact form and social sharing buttons
Customising
When using Alembic as a theme means you can take advantage of the file overriding method. This allows you to overwrite any file in this theme with your own custom file, by matching the file name and path. The most common example of this would be if you want to add your own styles or change the core style settings.

To add your own styles copy the styles.scss into your own project with the same file path (assets/styles.scss). From there you can add your own styles, you can even optionally ignore the theme styles by removing the @import "alembic"; line.

If you're looking to set your own colours and fonts you can overwrite them by matching the variable names from the _settings.scss file in your own styles.scss, make sure to state them before the @import "alembic"; line so they take effect. The settings are a mixture of custom variables and settings from Sassline - follow the link to find out how to configure the typographic settings.
