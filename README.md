# 2018 Reddit Suspicious Accounts Release

On April 11, 2018 Reddit released its [2017 transparency report][1], along with a [list of 944 accounts][2] that the site's administrators suspect belonged to the Russian Internet Research Agency.

>   To give you more insight into our findings, [here is a link to all 944 accounts][2]. We have decided to keep them visible for now, but after a period of time the accounts and their content will be removed from Reddit. We are doing this to allow moderators, investigators, and all of you to see their account histories for yourselves.
>
>   -- /u/spez

## Harvesting mode

This dataset is an archive all public comments, submissions and user data beloging to these accounts, retrieved on Aprile 11, 2018 at ~17:00 CEST (GMT+2) from the Reddit API and stored as CSV. As of the extraction, **one of the 944 accounts had been taken down** and a 404 status was returned for its profile. Each sheet contains selected and relevant fields from the objects returned by the API.

The data has been harvested through the excellent [PRAW](https://praw.readthedocs.io/en/latest/) library. A `log.txt` file is made available.

## Contents

The following files are made available:

*   `seed.csv` : the [original][2] user list as released by Reddit
*   `data/users.csv`: user data related to each of the released accounts
*   `data/comments.csv`: comment history from each of the released accounts
*   `data/subissions.csv`: submissions from each of the released accounts
*   `data/log.txt`: data extraction log

## Legal

Comment releases [have been a thing for a long time][4]. All information provided were publicly available and searchable as of the extraction. No data is apparently classifiable as PPI. Nothing in the [Reddit API TOS][5] explicitly prohibits harvesting publicly available data. All legal stuff should be directed at inbox [/at/] albertocoscia [/dot/] me.

Where applicable, this data is released under a [CC0][6] license and is public domain.

[1]: https://www.reddit.com/r/announcements/comments/8bb85p/reddits_2017_transparency_report_and_suspect/
[2]: https://www.reddit.com/wiki/suspiciousaccounts
[3]: https://praw.readthedocs.io/en/latest/
[4]: https://www.reddit.com/r/datasets/comments/3bxlg7/i_have_every_publicly_available_reddit_comment/
[5]: https://docs.google.com/forms/d/e/1FAIpQLSezNdDNK1-P8mspSbmtC2r86Ee9ZRbC66u929cG2GX0T9UMyw/viewform
[6]: https://creativecommons.org/publicdomain/zero/1.0/legalcode
