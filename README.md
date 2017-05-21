# Analysis of tweets using Zeppelin

To try it on Wrangler 

> ssh username@wrangler.tacc.utexas.edu

> sbatch /data/projects/G-818781/script/job.slurm 

wait several minutes 
 
> tail tweets.out

you should see a line like 

> Zeppelin UI is at http://wrangler.tacc.utexas.edu:54043
 
open the URL in a browser.  Safari should work. If you are using  chrome/firefox, you may have to open it in a  incognito window

Login to Zeppelin Server with your tacc username and password

You can import the analysis note from URL directly with follwing:
 
> https://raw.githubusercontent.com/weijiax/tweets/master/note/TwitterAnalysis.json


After you are finished with Zepplein, you can go back to your login terminal and cancel the job with following command
> scancel -u <username>
