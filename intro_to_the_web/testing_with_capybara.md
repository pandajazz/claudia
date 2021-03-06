# Testing with an Automated Browser and Capybara

[Back to the Challenge Map](README.md)

Recall that a web application is a kind of program that sends and receives messages over *HTTP*. The content of these messages is typically HTML.

In order to test an object like a web application, then, we need a tool that is able to send/receive messages over HTTP as well as process HTML.

**Automated browsers** are one such technology. **Automated browsers** are like browsers such as Chrome or Safari, except that they are able to receive instructions **programmatically**, not just from mouse clicks or keyboard presses. How do we write these instructions? In Ruby, we can use **Capybara** as an add-on to RSpec to compose our instructions.

In this challenge you will learn how to use Capybara to send instructions to an automated browser.

### Learning Objectives covered
- Understand what an automated browser is.
- Understand what Capybara is used for.
- Send instructions to an automated browser with Capybara

### Challenge setup

To complete this challenge you will need to have Firefox installed.

### To complete this challenge, you will need to:

- [ ] Make sure you have installed Firefox browser on your machine (you can use `brew cask install firefox` if you haven't).
- [ ] List `capybara` and `selenium-webdriver` in a Gemfile.
- [ ] make sure bundle install works - you may need to manually install xcode if you haven't already.
- [ ] install Firefox GeckoDriver, `brew install geckodriver`. If firefox does not work for you after installing geckodriver, it is also possible to use [gem 'chromedriver-helper'](https://github.com/flavorjones/chromedriver-helper).
- [ ] Open up *PRY* and require both `capybara/dsl` and `selenium-webdriver`.
- [ ] Within the REPL, `$ include Capybara::DSL`.
- [ ] [Set Capybara's default driver](https://github.com/jnicklas/capybara#selecting-the-driver) to be selenium.
- [ ] Use Capybara's `visit` command to take the automated browser to [http://capybaraworkout.herokuapp.com/](http://capybaraworkout.herokuapp.com/).
- [ ] Refer to a [capybara cheat sheet](https://thoughtbot.com/upcase/test-driven-rails-resources/capybara.pdf) and complete the capybara workout.
- [ ] Explain to your pair partner what jobs `capybara` and `selenium-webdriver` do.

### Resources

- [Selenium](http://www.seleniumhq.org/)
- [Capybara Cheat Sheet](https://thoughtbot.com/upcase/test-driven-rails-resources/capybara.pdf)
- [geckodriver brew formula](http://brewformulas.org/geckodriver)
- [mozilla geckodriver](http://brewformulas.org/geckodriver)

### [Walkthrough](walkthroughs/testing_with_capybara.md)


![Tracking pixel](https://githubanalytics.herokuapp.com/course/intro_to_the_web/testing_with_capybara.md)
