# Demo for Lappeenranta weather forecast

Part of Twinverse project.

Weather forecast mainly for winter maintenance.

Currently (time of writing 21 Oct 26), we mainly serve the site through GitHub Pages.

Current big questions are:
- Should we show a Lappeenranta map at full 60-meter resolution?
- Which variables: a) snowfall and temperature, b) snowfall, temperature and something more?, c) something else?
- If we have a table alongside the map, which locations should it include?

For local server while developing, you can use a simple HTTP server such as Python's built-in one:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.
