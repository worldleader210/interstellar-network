# How to contribute

Your contributions to the Stellar network will help improve the world’s financial
infrastructure, faster.

We want to make it as easy as possible to contribute changes that
help the Stellar network grow and thrive. There are a few guidelines that we
ask contributors to follow so that we can merge your changes quickly.

## Getting Started

* Make sure you have a [GitHub account](https://github.com/signup/free)
* Create a GitHub issue for your contribution, assuming one does not already exist.
  * Clearly describe the issue including steps to reproduce if it is a bug.
* Fork the repository on GitHub

## Making Changes

* Create a topic branch from where you want to base your work.
  * This is usually the master branch.
  * Please avoid working directly on the `master` branch.
* Make sure you have added the necessary tests for your changes, and make sure all tests pass.

## Submitting Changes

* <a href="https://docs.google.com/forms/d/1g7EF6PERciwn7zfmfke5Sir2n10yddGGSXyZsq98tVY/viewform?usp=send_form">Sign the Contributor License Agreement</a>.
* All content, comments, and pull requests must follow the [Stellar Community Guidelines](https://www.stellar.org/community-guidelines/). 
* Push your changes to a topic branch in your fork of the repository.
* Submit a pull request to the [repository interstellar-network](https://github.com/stellar/interstellar-network) in the Stellar organization.
 * Include a descriptive [commit message](https://github.com/erlang/otp/wiki/Writing-good-commit-messages).
 * Changes contributed via pull request should focus on a single issue at a time.
 * Rebase your local changes against the master branch. Resolve any conflicts that arise.
 
At this point you're waiting on us. We like to at least comment on pull requests within three 
business days (and, typically, one business day). We may suggest some changes or improvements or alternatives.

## Making Trivial Changes

### Documentation
For changes of a trivial nature to comments and documentation, it is not
always necessary to create a new GitHub issue. In this case, it is
appropriate to start the first line of a commit with 'doc' instead of
an issue number. 

# Additional Resources

* [Bug tracker (Github)](https://github.com/stellar/interstellar-network/issues)
* <a href="https://docs.google.com/forms/d/1g7EF6PERciwn7zfmfke5Sir2n10yddGGSXyZsq98tVY/viewform?usp=send_form">Contributor License Agreement</a>
* [Explore the API](http://docs.stellarhorizon.apiary.io/)
* [Readme for interstellar-network](https://github.com/stellar/interstellar-network/blob/master/README.md)
* #stellar-dev IRC channel on freenode.org
* #dev channel on [Slack](http://slack.stellar.org)


This document is inspired by:

https://github.com/puppetlabs/puppet/blob/master/CONTRIBUTING.md 

https://github.com/thoughtbot/factory_girl_rails/blob/master/CONTRIBUTING.md 

https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md
"name": "interstellar-network-widgets",
  "version": "0.0.12",
    "description": "The interstellar-network-widgets module provides network connected widgets.",
      "keywords": [
          "stellar",
              "interstellar"
                ],
                  "scripts": {
                      "test": "gulp test",
                          "postversion": "git push && git push --tags"
                            },
                              "author": "Stellar Development Foundation <stellar@stellar.org>",
                                "license": "Apache-2.0",
                                  "repository": {
                                      "type": "git",
                                          "url": "http://github.com/stellar/interstellar-network-widgets.git"
                                            },
                                              "dependencies": {
                                                  "angular-cookies": "^1.3.15",
                                                      "stellar-sdk": "~0.2.11",
                                                          "lodash": "^2.4.1",
                                                              "interstellar-core": "~0.0.3",
                                                                  "interstellar-sessions": "~0.0.3",
                                                                      "interstellar-stellar-api": "~0.0.3",
                                                                          "interstellar-network": "~0.0.8",
                                                                              "interstellar-ui-messages": "~0.0.2"
                                                                                }
/**
 * Program to Communicate with other humans in the galaxy
  * 
   * This program provides a function to send a message to other humans in the galaxy.
    * Note: This program assumes a hypothetical scenario where humans have established communication with extraterrestrial beings.
     * 
      */

      import flash.external.ExternalInterface;
      import flash.utils.setTimeout;

      function communicateWithGalacticHumans(message:String):void {
          try {
                  // Log the message to monitor performance and track anomalies
                          trace("Sending message to galactic humans: " + message);

                                          // Simulate communication delay
                                                  setTimeout(function():void {
                                                              // Send the message to the galactic humans
                                                                          ExternalInterface.call("sendGalacticMessage", message);
                                                                                  }, 1000);
                                                                                      } catch (error:Error) {
                                                                                              // Log any errors that occur during communication
                                                                                                      trace("An error occurred while communicating with galactic humans: " + error.message);
                                                                                                          }
                                                                                                          }

                                                                                                          // Example usage
                                                                                                          var message:String = "Hello, fellow beings in the galaxy! How are you?";
                                                                                                          communicateWithGalacticHumans(message);Hi, any humans from other plants speak English?                                                                                
                                                                                }