# weibo_dataset
----------------------------------- 
The research-used weibo dataset in ICUPN, including social network, spread path and cascades.
This is the raw data and it must be modified before use to remove duplicate datas.
The cascade file contains the information of a certain message, the format of which is:

    <message_number>\tab<source_user_id>\tab<retweet_number>\tab<retweets>
    <message_id>:     the unique id of each message, ranging from 1.
    <source_user_id>:   the unique id of source user.
    <retweet_number>:   the total retweet number of each source geted from weibo(including every comments).
    <retweets>:       the retweets of this message, each retweet is split by " ". Within each retweet, it records 
    the targets of the retweet, the format of which is <user>:0.

The dataset has been anonymized and is limited to only use in research.

Downlowd link: https://pan.baidu.com/s/1XbUTtAa5PAbKtJGeI6t0lg 

password: awud
