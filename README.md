# Checks the status of a list of urls

Usage:

```bash
$ ./check <url>
$ ./check < url-list.txt
```

![demo](check-script.gif)

Runs `GET` requests against the list of URLs and prints:

- status code
- url
- time to complete request
- time to first byte (time_pretransfer - time_starttransfer)

Note: this was written on a Mac in a hacky fashion (sorry), but also not
tested on other *nix systems. If you see a problem, please open a pull request.
