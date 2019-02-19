# Hack Monmouth Website

This repository contains the code for the [Hack Monmouth Website](https://hack.futuremonmouth.co.uk/)

## Contributing to the website

We'd love to see as many people as possible contributing to the website, so here's what you'll need:

   * [Setup an account on Github](https://https://github.com/join) (it's free!)
   * If you're not familiar with GIT to manage documents and code, follow the [BitBucket Getting Started Guide](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud)
   * Once you're happy with what you need to do, follow the [Forking Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow) process to get your own copy of the repository, make your changes, and submit a "Pull Request".
   * You should see a message in #website on our slack organisation with a link to a preview of the code
   * Once everyone is happy with the changes, the code will be approved
   * Now the robots take over - the code will be merged into our main repository and published to the website automatically!

## So how does all of this work?

The website is written using a platform called [Hugo](https://gohugo.io/) and allows anyone to contribute to the content by using [Markdown](https://en.wikipedia.org/wiki/Markdown) to format the document.

When a Pull Request has been accepted and merged, [Github](https://github.com/) notifies [Netlify](https://www.netlify.com/) that there is new code available.  Netlify then converts the Markdown into HTML (the code used to create web pages) using Hugo, and publishes it for the world to see.

Both Github and Netlify are configured to send messages to Slack letting the community know that changes are available or have been published.

## Copyright

The content of this website is copyright (c) Hack Monmouth.
