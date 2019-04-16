# Diversity Initiative Meetings

There are (rougly) biweekly meetings about diversity. These meetings are
held in the `#diversity-meetings` channel on the [Symfony Slack][1].

Calendar with chat meeting dates are available in:
* [Google Calendar][3]
* [ICS format][4]

### Upcomming meetings
* [Thursday, 18th April 2019, 21:00 CEST](meetings/2019-04-18.md)
* [Thursday, 2nd May 2019, 20:00 CEST](meetings/2019-05-02.md)

### Past meetings
* [Tuesday, 2nd April 2019, 15:00 CET](meetings/2019-04-02.md)
* [Monday, 18th March 2019, 18:30 CET](meetings/2019-03-18.md)
* [Thursday, 28th February 2019, 20:00 CET](meetings/2019-02-28.md)
* [Sunday, 17th February 2019, 16:00 CET](meetings/2019-02-17.md)
* [Sunday, 3rd February 2019, 16:00 CET](meetings/2019-02-03.md)
* [Tuesday, 15th January 2019, 11:00 CET](meetings/2019-01-15.md)
* [Thursday, 3rd January 2019, 20:00 CET](meetings/2019-01-03.md)
* [Sunday 16th December 2018, 18:00 CET](meetings/2018-12-16.md)

### Meeting log generation
Chat logs are exported from the Slack channel using Slack's admin tools.
This requires admin rights.

After that, these logs are converted into html using [Slack Export Viewer][2]:
`python app.py -z export.zip --channels=diversity-meetings --no-sidebar --no-external-references`,
where `export.zip` is the download of the slack chat log export. 

Note that python3 is recommended due to better unicode handling.

[1]: https://symfony.com/slack
[2]: https://github.com/hfaran/slack-export-viewer/pull/93
[3]: https://calendar.google.com/calendar?cid=NjVmbnBqNDZkbHFhZmVza2pxaHZicGhhdXNAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ
[4]: https://calendar.google.com/calendar/ical/65fnpj46dlqafeskjqhvbphaus%40group.calendar.google.com/public/basic.ics
