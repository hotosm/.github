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

### Humanitarian Map Style

- OpenStreetMap has many 'styles' available, to help prioritize what map features should be more prominent for users.
- Historically, this required rendering raster tiles in advance, based on a map style.
- Excellent work was done by the team for https://github.com/hotosm/HDM-CartoCSS, used to generate raster tiles.
- Going forward, OSM is using Vector tiles as a new standard (vector tiles simply contain the data, but no styling).
- It's now possible to create a custom vector tile style, based on the HDM-CartoCSS work, for which we would really value a volunteer dedicating some time to 🙏
- The repo and start of the work can be found here: https://github.com/hotosm/humanitarian-map-style

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

## Repository Summary

We have a lot of repos. Below are the ones with activity in the past year
(as of October 2026). Anything not listed is likely stale or archived.

### Core Tools

Mostly monorepos (backend + frontend + docs).

- [tasking-manager](https://github.com/hotosm/tasking-manager): coordinate remote mapping of OSM.
- [field-tm](https://github.com/hotosm/field-tm): coordinate field mapping via ODK / QField.
- [drone-tm](https://github.com/hotosm/drone-tm): community drone imagery collection and flight planning.
- [openaerialmap](https://github.com/hotosm/openaerialmap): open imagery catalog, being rebuilt on STAC.
- [fAIr](https://github.com/hotosm/fAIr) & [fAIr-models](https://github.com/hotosm/fAIr-models): AI assisted mapping, train models and predict map features.
- [raw-data-api](https://github.com/hotosm/raw-data-api): fast OSM data extracts via API.
- [osm-export-tool](https://github.com/hotosm/osm-export-tool): web UI for custom OSM exports.
- [chatmap](https://github.com/hotosm/chatmap): field mapping via WhatsApp, Telegram, Signal.
- [portal](https://github.com/hotosm/portal): central workspace across all HOT tools.

### Additional Tools

- [umap](https://github.com/hotosm/umap): we don't develop uMap ourselves, but deploy a custom branded and modified version of https://github.com/umap-project/umap.
- [ScaleODM](https://github.com/hotosm/ScaleODM): Kubernetes autoscaling for OpenDroneMap. Used by DroneTM for processing.
- [xlsform-builder](https://github.com/hotosm/xlsform-builder): share and edit community XLSForms.
- [humanitarian-map-style](https://github.com/hotosm/humanitarian-map-style): vector tile rebuild of the Humanitarian OSM map style.

### Glue Between Tools

- [login](https://github.com/hotosm/login): shared auth for all tools (login.hotosm.org).
- [ui](https://github.com/hotosm/ui) & [ui-design](https://github.com/hotosm/ui-design): shared web components with HOT theming, with a design system, assets, and CSS.
- [gh-workflows](https://github.com/hotosm/gh-workflows): reusable GitHub workflows (images, tests, docs).
- [justfiles](https://github.com/hotosm/justfiles): shared CI/CD scripts.

### Python Modules

- [osm-login-python](https://github.com/hotosm/osm-login-python): OSM OAuth 2.0 login.
- [raw-data-api-py](https://github.com/hotosm/raw-data-api-py): client for raw-data-api.
- [geojson-aoi-parser](https://github.com/hotosm/geojson-aoi-parser): parse and normalise AOIs with PostGIS.
- [pg-nearest-city](https://github.com/hotosm/pg-nearest-city): reverse geocode to nearest city.
- [osm-export-tool-python](https://github.com/hotosm/osm-export-tool-python): CLI + library for OSM exports.
- [central-webhook](https://github.com/hotosm/central-webhook): webhooks for ODK Central submissions (Go).

### AI / ML

- [fAIr-utilities](https://github.com/hotosm/fAIr-utilities): training utilities for fAIr.
- [fairpredictor](https://github.com/hotosm/fairpredictor): standalone model predictions.
- [osm-tagger](https://github.com/hotosm/osm-tagger): generate OSM tags from text and images.
- [dda](https://github.com/hotosm/dda): building damage assessment from satellite imagery.
- [tm-oam-ds-builder](https://github.com/hotosm/tm-oam-ds-builder): training datasets from TM + OAM.
- [HOTOSM-3D-TT](https://github.com/hotosm/HOTOSM-3D-TT): 3D point cloud building segmentation and heights.

### Data & Analysis

- [osm-country-exports](https://github.com/hotosm/osm-country-exports): country-scale OSM exports to HDX.
- [tm-extractor](https://github.com/hotosm/tm-extractor): trigger data extracts for TM projects.
- [osmdc](https://github.com/hotosm/osmdc): OSM completeness checker against Overture.
- [mapswipe-results-analyzer](https://github.com/hotosm/mapswipe-results-analyzer): view and export MapSwipe results.
- [hot2hdx-status](https://github.com/hotosm/hot2hdx-status): HDX dataset status dashboard.
- [freetown-uhi](https://github.com/hotosm/freetown-uhi): Freetown urban heat drone processing scripts.

### QGIS / QField

- [qgis-osm-conflator](https://github.com/hotosm/qgis-osm-conflator): merge external data into OSM (early stage).
- [qgis-pmtiles](https://github.com/hotosm/qgis-pmtiles): generate PMTiles from QGIS.
- [qfield-next-theme-plugin](https://github.com/hotosm/qfield-next-theme-plugin): cycle map themes in QField.
- [qfield-simplified-ui-plugin](https://github.com/hotosm/qfield-simplified-ui-plugin): simplified QField UI.

### Infrastructure & Ops

- [k8s-infra](https://github.com/hotosm/k8s-infra): Kubernetes cluster IaC (OpenTofu) and config.
- [windmill-scripts](https://github.com/hotosm/windmill-scripts): scheduled / automation scripts for Windmill.
- [Slack-HOTOSM-GDAC](https://github.com/hotosm/Slack-HOTOSM-GDAC): GDACS disaster alerts to Slack.

### Docs, Websites & Community

- [docs](https://github.com/hotosm/docs): tech docs index (docs.hotosm.org).
- [website](https://github.com/hotosm/website): hotosm.org (Wagtail CMS).
- [roadmap](https://github.com/hotosm/roadmap): public roadmap across all tools.
- [requests](https://github.com/hotosm/requests): triage of user support requests.
- [learnosm](https://github.com/hotosm/learnosm): LearnOSM.org training content.
- [toolbox](https://github.com/hotosm/toolbox): mapping project docs and training.

### Forks We Contribute To

- [QFieldCloud](https://github.com/hotosm/QFieldCloud), [qfieldcloud-helm-chart](https://github.com/hotosm/qfieldcloud-helm-chart), [qfieldcloud-sdk-python](https://github.com/hotosm/qfieldcloud-sdk-python): QField sync server, deployment, SDK.
- [odkcentral](https://github.com/hotosm/odkcentral), [web-forms](https://github.com/hotosm/web-forms), [odkdocs](https://github.com/hotosm/odkdocs): ODK server, web forms, docs.
- [oex](https://github.com/hotosm/oex): OSM / Overture country exports (used by osm-country-exports).
- [iD](https://github.com/hotosm/iD): OSM web editor.
- [osm-sandbox-dashboard](https://github.com/hotosm/osm-sandbox-dashboard): helm charts for OSM Sandbox dashboard.
- [zenml](https://github.com/hotosm/zenml): ML pipeline platform.
