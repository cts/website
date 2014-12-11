Project Setup
-------------

*  Install Jekyll: `gem install jekyll`
*  Install s3_website: `gem install s3_website`
*  Create a configuration `cp s3_website.yml.example s3_website.yml`
*  Customize your configuration with your own access key and secret

To Update Website
-----------------

1.  Rebuild the site: `jekyll build`
2.  Upload the diff: `s3_website push`

**Make sure you also check your changes into git and push them to origin!**

