jh-twitter-pushover
===================

Pushover notifications from twitter.  For deployment on Azure using Websites and Webjobs from a git push

Based on https://github.com/outadoc/twitter-mentions-pushover

To run locally, set the environment variables

```
#!/bin/bash
export twitter_consumer_key="xxx"
export twitter_consumer_secret="xxx"
export twitter_access_token_key="xxx"
export twitter_access_token_secret="xxx"
export pushover_api_token="xxx"
export pushover_user_key="xxx"	
export follow_user_ids_csv="xxx,xxx,xxx"
```

NB - user ids are numeric.  Can convert with
http://tweeterid.com/

To run on Azure set the app settings to match these key values

![Azure Screenshot of App Settings](/App_Settings.png)


