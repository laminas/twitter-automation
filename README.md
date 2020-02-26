# getlaminas Twitter Account Automation

This repository contains media and tweets to put into rotation for the
[@getlaminas](https://twitter.com/getlaminas) twitter account.

## How to update the rotation

We need a **minimum of 10** tweets in place at any given time. Tweet content can
be duplicated, however, so we can have multiple files containing the same
content if we want to emphasize a particular message.

Tweet files have the `.txt` extension. It's typically best to have them named by
the date added, with a short description of the contents.

### Tweet file format

Tweet files contain one or more comment lines, followed by the tweet content
itself, which can include URLs, hashtags, and mentions.

The comment lines can be any of the following:

```text
#IMAGE=<image from media directory, minus any path information>
#IGNORE_BEFORE=YYYY-MM-DD
#IGNORE_AFTER=YYYY-MM-DD
```

### Example tweet

```text
#IMAGE=logo.png
#IGNORE_BEFORE=2020-01-01

Please Welcome the Laminas Project!

https://framework.zend.com/blog/2020-01-24-laminas-launch
```

## Recommendations

- Always include an `#IMAGE`; if you are unsure which to use, choose a logo
  based on the project to which the tweet refers.
- Put hash tags last.
- Remove obsolete content (generally anything over 3-6 months old).
