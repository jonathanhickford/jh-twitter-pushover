jh-twitter-pushover
===================

Pushover notifications from twitter

For deployment on Azure using Websites and Webjobs from a git push

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
