can we automatically fetch data from just the URL???

*   *Pins* and *boards* are ideas directly borrowed from Pinterest
    -   There are no board sections; we use tags to categorize instead
    -   Each pin must have an **artist** (unless it really is unknown)
        +   a list or a single string
    -   **Source** will play an important role in our pins;
        each source has a URL and the platform it belongs to
        (`tumblr`, `twitter`, etc.)
    -   Ideally the images should be inferred from the source link,
        but if it is impossible, we may provide more explicit links
        in the data tag...

*   Things in `project.json`
    -   *artists* -- links to an artist's social media
    -   *tags* -- defining tags and what they mean
    -   *backups* -- these are analogous manually done caches in case
        URLs break in the future
