# Journal Club update pipeline

When adding or updating Journal Club slides:

1. Preserve the supplied slide file in `talk_slides/` and follow the existing title, presenter, date, and `[Talk Slides]` link format. Include an original-paper link only when applicable and provided or verified.
2. Update both the homepage Journal Club section (`index.html`) and the chronological Full List (`talk/index.html`). Keep the Full List grouped by month, newest first.
3. On every update, review all homepage Coming Talks against the current date in the user's timezone. Move every talk with a date strictly before today into homepage Finished Talks, preserving its slide and paper links. Keep homepage Finished Talks limited to the two most recent individual talks, newest first, with no month headings. When dates tie, preserve their existing order. Remove older entries only from the homepage; retain all talks and slide files in the Full List and `talk_slides/`. A talk dated today stays in Coming Talks unless the user says it has finished.
4. Preserve the existing styling and all archive entries. Check that each new entry appears exactly once in the Full List and in the appropriate homepage section, that Finished Talks contains exactly the two most recent available finished talks (or all if fewer than two exist), and that its slide file exists.
5. Commit and publish within the user's authorized scope, then verify the live homepage, Full List, and slide links. Report any pending deployment or failed checks accurately.
