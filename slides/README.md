# Taming the Beast of Software Releases

This is a talk I gave at [All Day DevOps 2023 ](https://www.alldaydevops.com/) on October 26, 2023.

## Abstract
Releasing software is hard. Did you package the right version? How did you arrive at a version number? Did you remember to write the release notes? Did you deploy it to the right location, with the right configuration? What if you could do a release in minutes instead of hours and know that every step on your release check list was properly completed? I spent over 15 years as a leader on a large commercial open source project struggling with this very problem. With dozens of contributors and over 1million lines of code, part of my role was to make sure that our releases went out on time and didn't miss any steps. In this session I will share with you the development processes and tools I use to automate every aspect of the release and ensure that releases on my current projects run smoothly. We'll look at examples in Node, using GitHub to assist where needed, and walk through putting some of these principles into action.

## Running the Presentation
The slides are written using standard markdown and are rendered using [Presenterm](https://github.com/mfontanini/presenterm) on the command line. To run the presentation, clone the repo and run the following commands:

```bash
presenterm slides/taming-software-release.md
```
