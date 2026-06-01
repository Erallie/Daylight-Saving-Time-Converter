# Seasonal Time Converter
This tool is a webpage that displays a timestamp from one timezone in the user's local time, accounting for daylight saving time. This means it takes the timestamp and the displays it in **both** daylight time *and* standard time, according to the user's local timezone.

I made this because I live in Arizona, and we don't have Daylight Saving Time. But almost all of my events are online, and a lot of them are year-round, so I need to manually convert it to everyone else's timezone so they understand I'm in MST, **not** MDT. This tool just makes it a lot easier.

To use it, to go the link: `https://erallie.github.io/Seasonal-Time-Converter/?t=XX:XX&tz=Country/City` where:
- `XX:XX` is the time in 24-hour time.
- `Country/City` is the IANA time zone identifier.

For example, if you want to display 1pm in Arizona time, you would do:
- `https://erallie.github.io/Seasonal-Time-Converter/?t=13:00&tz=America/Phoenix`

You can *also* go to this page in order to generate a link more easily:
- https://erallie.github.io/Seasonal-Time-Converter/generator.html

Feel free to use whenever!
