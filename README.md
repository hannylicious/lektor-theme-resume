# Lektor Resume

![screenshot](https://github.com/hannylicious/lektor-theme-resume/blob/master/images/screenshot.PNG "Screenshot")

Resume is a simple Lektor theme ported from [startbootstrap](https://startbootstrap.com), which is designed to fit the style of someone who wants a site they can link others to as well as a place to blog about what they're developing in addition to talking about previous projects.

It uses Bootstrap 4, Jquery and Font-Awesome 4 out of the box. It also comes with integration to Google Analytics.

There is a fully functional example-site on the way - but it is not up yet.

This comes with some example/dummy content just to give some idea of what goes where and how everything is laid out.

This theme is under development still - it will probably get further from the original version it was ported from as time goes on.

# Configuration

Add params in the `.lektorproject file`

```ini
[theme_settings]
first_name = Roger
last_name = Williams
name = Roger Williams
street = 123 Somewhere Dr.
city = Chicago
state = Illinois
zip = 60007
phone = (312)555-4567
email = your_email@yourdomain.com
about = info_about_you
site = rogerwilliams.com
googleanalytics = your_google_analytics_id
facebookID = your_facebook
twitterID = your_twitter
instagramID = your_instagram
githubID = your_github
gitlabID = your_gitlab
codepenID = your_codepen
linkedInURL = your_linkedin
googleplusID = your_googleplus
profilepicture = profile_picture_asset_url
googleanalytics = your_google_analytics_id
slackURL = https://join.slack.com/...
comments = yes
```

Optionally turn on add Disqus Comments on the blog posts with lektor-disqus-comments plugin. Configure it with [this](https://github.com/lektor/lektor-disqus-comments#lektor-disqus-comments).

## License

Resume is licensed under the [MIT license](LICENSE.md)
