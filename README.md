# subscribers-picture

Get big picture with logos of your subscribers based on their emails.

This is a simple python script `subs2pic.py` that:

1. Reads csv file `emails.csv` with emails of your subscribers.
2. It checks which emails are from public email providers.
3. For work emails the logo is downloaded with ClearBit free logo API.
4. Logos are saved in `imgs` folder. Based on downloaded images a big picture with all logos are created.

## Run example

```
# clone the repo

# run the script

```

## Details

1.  To decide if email is from free email provider I have used [this file](http://svn.apache.org/repos/asf/spamassassin/trunk/rules/20_freemail_domains.cf)
2.  [Logos provided by ClearBit](https://clearbit.com)
