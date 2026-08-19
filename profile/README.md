# Hi there 👋 Welcome to the Humanitarian OpenStreetMap Team (HOTOSM)!

## ☀️ About HOTOSM

We are dedicated to humanitarian action and community development through open mapping. We work together to provide map data for disaster management, risk reduction, and contributing Sustainable Development Goals. Check our [website](https://www.hotosm.org).

## 🌞 About HOT Tech and Innovation

We aim to create and nurture *fair* and *just* tech to amplify connections between **humanitarian** needs and open map data. We have a small core tech team, but we rely on YOU for contributions and collaborations to make all this magic happen! 

## 🌈 How to Contribute

As with any open source community, there are many projects and tools that we are working on at the same time. You can see that reflected in the number of repositories we have.

How to get started:
1. Check the 6 pinned repositories below - these are our core open source projects we are working on.
2. Check the README file for repositories with activity - you will likely see a reference to a product roadmap that will give you an indication of ongoing work.
3. Read the [contributing guidelines](https://docs.hotosm.org/become-a-contributor) & start by looking for any issues labelled [Good First Issue](https://github.com/search?q=org%3Ahotosm+label%3A%22good+first+issue%22&type=issues).

Please also check the [HOT Tech Docs](https://docs.hotosm.org). It is primarily intended for a software development audience.

If you are just beginning your open source contributor journey, then start by watching this [comprehensive Github Guide to HOTOSM](https://www.youtube.com/watch?v=kibi_YJ6qXo&ab_channel=HumanitarianOpenStreetMapTeam)!

Still unsure where to start your contributor journey, reach to our Networks and Engagement Lead (tech community) - [Petya](https://github.com/petya-kangalova) 

## 📑 Useful resources 

Join the [HOT Tech and Innovation Working Group](https://wiki.openstreetmap.org/wiki/Humanitarian_OSM_Team/Working_groups/TechandInnovation) - a welcoming and inclusive open space to connect, contribute, collaborate, innovate and share ideas for geospatial tech for humanitarian purposes! Meetings are held on the second Tuesday of the month at 10:00 and 18:00UTC!

Join the [HOTOSM Slack workspace](https://slack.hotosm.org/). The main channel for any tech discussions is:

[#geospatial-tech-and-innovation**](https://hotosm.slack.com/archives/C04DPFNB9GR)

Other relevant tech Slack channels you might be interested in joining:
- #imagery-coord
- #openaerialmap
- #tasking-manager
- #tasking-manager-testing
- #tasking-manager-alert
- #field-mapping-tasking-manager
- #export-tool
- #machine-learning
- #chatmap

## 🤲 Current Volunteer Projects

You can help out on any of our tools, just comment on an issue to get started!

That said, here are the projects where we could really use a hand right now.

### XLSForm Builder (TypeScript)

We use XLSForms for all of our field mapping. Editing them in Excel is painful, so we want a better way.

- The examples showcase and uploader are done, meaning users can share and browse XLSForms already used in real projects.
- Next up is the big one: an XLSForm editor in the browser, with drag and drop components, built around [getodk/web-forms](https://github.com/getodk/web-forms).
- Repo and issues: [xlsform-builder](https://github.com/hotosm/xlsform-builder)

Best suited to frontend devs who enjoy building interfaces people actually like using.

### OpenAerialMap (Python / TypeScript)

[OpenAerialMap](https://openaerialmap.org) hosts openly licensed drone and satellite imagery for anyone to use. We are rebuilding it around [STAC](https://stacspec.org).

- Backend: STAC metadata extensions, catalog ingestion, the imagery upload pipeline.
- Frontend: the uploader, plus map based search and browsing of the catalog.
- Also wanted: documentation, UI / UX design, and testers.
- Repo: [openaerialmap](https://github.com/hotosm/openaerialmap), with [docs here](https://docs.imagery.hotosm.org).

A good fit if you like cloud native geospatial (COG, PMTiles, STAC), or want to work across the whole stack.

### Field-TM (Python / TypeScript)

The [Field Tasking Manager](https://github.com/hotosm/field-tm) coordinates field mapping campaigns, tagging map features with information verified on the ground via ODK.

- It's used in the field today, but doesn't get much dedicated development time from us, so help here goes a long way.
- Backend is Python (Litestar), frontend is HTMX and TypeScript.
- Test coverage and translations are always welcome.
- Not a developer? Using the tool and writing up clear bug reports is just as useful to us.
- Start with the issues labelled [good first issue](https://github.com/hotosm/field-tm/labels/good%20first%20issue).

### AI Detection Models (Python)

We want AI assisted feature detection to take some of the grunt work out of mapping, building on research done with UC Berkeley in [osm-tagger](https://github.com/hotosm/osm-tagger).

- Training and evaluating detection models.
- Preparing and cleaning training datasets.
- Getting predictions into a workflow where mappers can review them, before anything reaches OSM.

Aimed at data scientists and ML engineers, ideally ones who care about keeping a human in the loop.

### QGIS OSM Conflator (Python)

- [qgis-osm-conflator](https://github.com/hotosm/qgis-osm-conflator): merge an external dataset into existing OpenStreetMap data, accepting or rejecting each change as you go. This is very early stage and needs a lot of work to get off the ground, so there is plenty of room to shape it.
If you know PyQGIS, or enjoy conflation and data quality problems, contact the team to get started.

### Backend Modules (Python)

We maintain a set of small Python modules used across our tools, listed [here](https://docs.hotosm.org/modules/backend). They are mostly volunteer maintained and could do with some love:

- [geojson-aoi-parser](https://github.com/hotosm/geojson-aoi-parser): parse and normalise an area of interest using PostGIS. Used anywhere we accept a user drawn area.
- [drone-flightplan](https://github.com/hotosm/drone-tm/tree/develop/src/backend/packages/drone-flightplan): generate drone flight plans. Good if you like maths, and there are always new drones to support.
- [area-splitter](https://github.com/hotosm/field-tm/tree/dev/src/backend/packages/area-splitter): split a mapping area into tasks using SQL and PostGIS. More splitting criteria and optimisations needed.

Take a look at the issues on each repo to see what needs doing.
