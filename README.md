The ig2atom script retrieves the Instagram homepage, parses it, and outputs an atom feed.

To use ig2atom, you need a `sessionid` cookie from Instagram. Log into Instagram in your browser, then retrieve the value of the cookie through your browser's settings.

Run `ig2atom SESSIONID`, replacing `SESSIONID` with the value of the cookie. The script should output an atom feed to stdout.

The script can be used in newsbeuter by adding a line with the contents `"exec:ig2atom SESSIONID"` to newsbeuter's `urls` file.
