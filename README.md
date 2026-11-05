# Solar System — HTML/CSS school project

**Context:** School assignment.

A static solar-system page with inner-planet cards and an outer-planet table, created as an HTML/CSS assessment.

## Implementation

**Technologies:** HTML, CSS.

- Planet images and descriptive content.
- Card and table layouts.
- A bundled image-resource link list in image/resource_link.txt.

## Run locally

Requires Git, Python 3 for the local server, and a modern browser. No build step is included.

```sh
git clone https://github.com/TigerOneTank/planet-system-html-exam.git
cd planet-system-html-exam
python -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/index.html`. On Windows, `py` can replace `python`. External APIs, fonts, scripts, or embeds require internet access.

## Learning focus

Practices semantic content grouping, images, tables, and CSS layout.

## Known limitations

- Navigation links use # placeholders rather than section destinations.
- Some astronomy text is dated or inaccurate; this is a programming exercise, not a scientific reference.
- No JavaScript application logic or automated tests are included.

## Repository context

The original file contents match [html-exam](https://github.com/TigerOneTank/html-exam), where they are nested under `html exam/`. This repository is the main portfolio reference.

## Review scope

The November 2026 portfolio review inspected the source and local file references. No browser compatibility or live external-service test is claimed. Existing coursework and contribution history are retained.
