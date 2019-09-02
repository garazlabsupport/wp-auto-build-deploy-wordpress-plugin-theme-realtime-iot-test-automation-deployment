# WP Auto Build Deploy - Wordpress Plugin Theme Realtime IoT Test Automation &amp; Deployment

Product URL: [shop now](https://garazlab.com/product/wp-auto-build-deploy-wordpress-plugin-theme-realtime-iot-test-automation-deployment/)

WP Auto Build Deploy solves all your problem regarding development, build, test, deployment processes of Wordpress plugin, themes. Every time you push changes to the branch of your Git repo, our plugin will detect the “push” event and re-run the unit tests, integration tests, functional test and deploy. It helps you write and ship code with less friction.

Ever since I built my first WordPress plugin, the process of deploying the code to the WordPress.org Subversion repository has been a painful one. With Git as the widespread VCS flavor of choice, switching to SVN for plugin deployment has always been jarring and felt alien to my workflow.

You want to be a good developer. You want to use version control for your code and manage it on GitHub. Your intentions are good. But getting the code from GitHub and onto Wordpress.org websites is painful because all of them are manually with no Git and no SSH. There’s no easy way and soon you find yourself fixing bugs in the built-in WordPress editor or copying single files through an FTP client. Shame on you. There went version control and future maintainability! WP Auto Build Deploy gets you back on track!

Have you ever set up automated deployments for a plugin, theme to WordPress.org? That’s it! Our WordPress site has been deployed to our server. It helps you write and ship code with less friction. We were tired of convoluted development, build, test, deployment processes and tools that take you away from doing your best work. This plugin fixes that, and we’re just getting started. An all-in-one solution for development, build, test, deployment processes.

The WP Auto Build Deploy plugin lets you install and update WordPress themes and plugins, directly from your laptop to Wordpress.org with full testing. WP Auto Build Deploy will update your plugins and themes automagically on every push.

Using an external CI service (such as Travis) to automatically trigger a deployment to Wordpress.org plugin repository on your remote git repo. Every time you push changes to the branch of your Git repo, WP Auto Build Deploy will detect the “push” event and re-run the pipeline. This plugin has quickly become popular due to its support for a huge array of different technologies and a great UI. It uses Docker containers to run all of its actions in. It uses the official PHP version of 5.6 to latest, nightly builds. It copy your files to your Wordpress.org via SSH.

Testing your plugin, themes before handing it over to the users is no longer optional. With the advent of a lot of recent browsers and mobile devices, the graph has registered a further rise. Now you can easily unit test, integration test, functional test on your server environment using this plugin.

As responsible developers we should be running these tests during development to ensure new code doesn’t affect existing code. Having Travis run these tests automatically so we don’t have to remember is awesome! Adding deployment to the list of tasks Travis performs turns it into a continuous delivery service as well, automation.

Continuous integration usually involves running some kind of testing as a first phase; in this plugin we set up a Nginx web-server on Travis CI to run acceptance and functional like tests.

## What WP Auto Build Deploy do?

After you Git push :

1. Build your plugin, theme files.
2. Run the unit tests, integration tests, functional test for your plugin, theme on your server environment.
3. Run continuous integration on server environment.
4. Run continuous deployment on server environment.
5. Not testing the site as a whole but just a plugin or a theme.
6. Test your plugin in several different PHP, Wordress versions available on your server environment.
7. Run CodeCeption integration test, acceptance test, functional test.
8. Run CodeSniffer for WordPress Coding Standards checks.
9. Run WordPress Coding Standards checks.
10. Deploy plugin, theme zip file to Wordpress.org.
11. Run JavaScript Code Style checker.
12. Run PHP Compatibility sniffs.
## Do I need a WP Auto Build Deploy plugin?
1. Everyday you push lots of changes of your plugin & theme to your Wordpress.org. It kills your time a lot.
2. Let WP Auto Build Deploy deploy your themes and plugins directly from Git push.
3. Enable your code automagically update on every Git push.
4. Stop copying and pasting files over FTP, it's insecure.

## Features of WP Auto Build Deploy plugin:
1. Never again copy files over FTP.
2. It has automatic deployments to the server when code is pushed to the master branch, I’ve gotten used to not having to physically do anything to deploy the code!
3. Secure your code with SSH deployment.
4. Works out-of-the-box.
5. You have a WordPress plugin, theme on the repo, but also hosted on GitHub. To automatically deploy your plugin, theme to the WordPress.org repo.
6. Continuous integration usually involves running some kind of testing as a first phase; in this plugin we set up a Nginx web-server on Travis CI to run acceptance and functional like tests.

## How WP Auto Build Deploy plugin works?
Follow these steps to work with WP Auto Build Deploy in minutes!

1. Get WP Auto Build Deploy. Download the plugin files.
2. In the WP admin, go to Plugins -> Add New and upload the plugin files before activating the plugin.
3. Go to the WP Auto Build Deploy menu on left sidebar. This is the settings for the plugin, theme you want to deploy to Wordpress.org.
4. Please enter Wordpress.org username, plugin/theme folder name, plugin/theme version.

Thats it! Now for each push on Git branch, it will trigger build, test, deploy to Wordpress.org.

## To get started with Travis CI
1. Go to Travis-ci.com and Sign up with GitHub.
2. Accept the Authorization of Travis CI. You’ll be redirected to GitHub.
3. Click the green Activate button, and select the repositories you want to use with Travis CI.
