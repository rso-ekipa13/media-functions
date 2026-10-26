# media-functions

Two Azure Functions that look after uploaded images. One runs whenever a new file lands in Blob Storage and checks it before media-service marks it as available. The other runs on a timer and removes files that have expired.

Built with Azure Functions (.NET 10, isolated worker).

Owner: Eva Vidic. Status: planned.

## Where this fits

This is one of the repositories of [Pretty Good Pigeon](https://github.com/rso-ekipa13), an end-to-end encrypted messenger built by ekipa 13 for the Cloud Computing course at UL FRI (2026/27). The architecture, plan and decisions live in [docs](https://github.com/rso-ekipa13/docs).

`main` only changes through pull requests; day-to-day work goes to `dev`.
