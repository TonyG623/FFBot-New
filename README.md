To run. 

1. Edit the credentials in post_daily_threads.py.
2. Edit your yaml file for your sub, you can see examples of the football and hockey one in sub.
3. Make sure you have wikis set up for each job. It looks in `/wiki/ffbot/wiki_ame` by default. Wiki name is defined in the credentials. The bot pulls the text for the post from wikis then adds the index charts underneath the text thats in the wikis.
4. Run the python script on some sort of chron job `python post_daily_threads fantasyfootball.yaml`. I personally use a jenkins build. However, it can work from anywhere.

Disclaimer
1. This code was written... like 6 years ago. I would do things a lot differently these days. It isnt my best work but it does the job.
