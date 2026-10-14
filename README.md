# EPS Calendar (2018 OJT project)

An events calendar I built in May 2018 during my OJT (on-the-job training)
as an Information Technology student at Informatics in Baguio City.

**View it live:** <https://everett911.github.io/eps-calendar-2018/>

> **Archived as-is.** This repository is a record of my early work. For my
> current projects, see my
> [portfolio](https://everett-lara.vercel.app/).

## What it is

A full-page monthly calendar for an office to post three kinds of entries:

- **Events**
- **Notices**
- **Feedback**

The left side shows the month grid, with previous/next/today navigation. The
right-hand panel was designed to show the details of a selected entry: date,
title, content, rating, and who posted it and when. A colour-coded legend tells
the three entry types apart.

## Credits

This project is built on the open-source
[Calendario](https://tympanus.net/codrops/2012/11/27/calendario-a-flexible-calendar-plugin/)
jQuery plugin and its “Flexible Calendar” demo by **Codrops** (MIT licence).
`js/jquery.calendario.js`, `css/calendar.css` and the sample entries in
`js/data.js` come from Codrops. The icon font was generated with
[Fontello](http://fontello.com); see `font/LICENSE.txt`.

My work during the OJT:

- `index.html`: the EPS Calendar page, with the events detail panel and the
  legend for events, notices and feedback
- `css/custom_1.css`: the full-page layout and styling for that page

`index2.html` is the original Codrops demo, which I kept as a reference.

## What I learned

- Reading and reusing someone else's code, and working with a jQuery plugin's
  options and callbacks
- Adapting an existing design to a client's needs
- Full-page layouts with CSS positioning

## Running it

Open `index.html` in a browser, or visit the live link above. jQuery loads
from Google's CDN, so you need an internet connection. (In 2026 I switched the
jQuery and font links from `http` to `https` so they load on GitHub Pages.)
