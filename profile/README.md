# Hi there 👋 Welcome to the Humanitarian OpenStreetMap Team (HOTOSM)!

## ☀️ About HOTOSM

We are dedicated to humanitarian action and community development through open mapping. We work together to provide map data for disaster management, risk reduction, and contributing Sustainable Development Goals. Check our [website](https://www.hotosm.org).

## 🌞 About HOT Tech and Innovation

We aim to create and nurture *just* tech to amplify connections between **humanitarian** needs and open map data. We have a small core tech team, but we rely on YOU for contributions and collaborations to make all this magic happen! 

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

As mentioned above, it's possible to assist on any of our tools - just comment on an issue to get started!

However, we do have a few projects that are worth highlighting as in need of assistance by volunteer developers right now:

### Frontend: XLSForm Builder

- Full details can be found advertised [here](https://www.hotosm.org/volunteer-opportunities/tech-volunteer-opportunities).
- This project has two goals, and primarily uses **TypeScript** for:
  - A small community-driven web page for users to share and access existing XLSForms used for field mapping projects.
  - A dedicated XLSForm builder interface, with drag-and-drop components, instead of Excel editing.
- The full repository and issues to work on can be found [here](https://github.com/hotosm/xlsform-builder)

> [!IMPORTANT]
> This project is primarily aimed at frontend developers, skilled using TypeScript to
> create good user interfaces and experiences.

### Backend Modules

- We have various backend **Python** modules listed [here](https://docs.hotosm.org/modules/backend) that are
  used throughout our tools.
- These modules are primarily developed and maintained by volunteers, and we could really use your help keeping them
  up to date! See the issues on each repository to know what bugs or features need to be implemented.
- Some key projects in need to assistance:
  - Like maths & deep Python coding? Help improve our [drone flightplan](https://github.com/hotosm/drone-tm/tree/develop/src/backend/packages/drone-flightplan)
    generation module, perhaps adding support for new drones!
  - Like QGIS and refining user experience? Help craft a better workflow with our [QGIS Field Mapping](https://github.com/hotosm/qgis-field-mapper) plugin!
  - Like SQL and PostGIS algorithms? Help add additional splitting criteria and optimizations to our
    [Field Splitting module](https://hotosm.github.io/fmtm-splitter)! 

> [!IMPORTANT]
> These modules are primarily aimed at backend developers, skilled using Python for data extraction,
> and analysis, in addition to writing installable software packages.

### DevOps: Kubernetes

- We have recently undergone a transition to [run our tools via Kubernetes](https://github.com/hotosm/k8s-infra).
- While we are able to maintain the day-to-day operations of the cluster, we really require support on
  **packaging our tools** using Helm charts and other means.
- If you have experience writing and maintaining installable packages for Kubernetes, please reach out!

### Translations: ChatMap

- We're asking asking for your help to have [ChatMap](https://chatmap.hotosm.org) (the app for converting chats to maps) in more languages!
- Currently available in English, Spanish, Portuguese and German. 
- These are the texts that need to be translated from English: https://github.com/hotosm/chatmap/blob/master/src/int/en.json
- Other translations can be found here: https://github.com/hotosm/chatmap/tree/master/src/int
- You can help by posting your translations in the #chatmap Slack channel or by creating a PR in GitHub if you’re more tech-savvy.

> [!IMPORTANT]
The ChatMappers will be eternally grateful! 
