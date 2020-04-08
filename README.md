# Assistant for No Man's Sky
### General management around the App

[![Supported by the No Man's Sky Community Developers & Designers](https://img.shields.io/badge/NMS%20Community%20Developers-supported-green?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAyMy4wLjEsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iTGF5ZXJfMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgeD0iMHB4IiB5PSIwcHgiDQoJIHZpZXdCb3g9IjAgMCAxMDAgMTAwIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCAxMDAgMTAwOyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+DQo8c3R5bGUgdHlwZT0idGV4dC9jc3MiPg0KCS5zdDB7ZmlsbDojMjMxRjIwO3N0cm9rZTojMjMxRjIwO3N0cm9rZS13aWR0aDowLjkyOTtzdHJva2UtbWl0ZXJsaW1pdDoxMDt9DQoJLnN0MXtmaWxsOiNDQzM2NTY7fQ0KCS5zdDJ7ZmlsbDojRkZGRkZGO3N0cm9rZTojMjMxRjIwO3N0cm9rZS13aWR0aDowLjkzO3N0cm9rZS1taXRlcmxpbWl0OjEwO30NCgkuc3Qze2ZpbGw6I0ZGRkZGRjt9DQoJLnN0NHtmaWxsOiMyMzFGMjA7fQ0KPC9zdHlsZT4NCjxwb2x5Z29uIGNsYXNzPSJzdDAiIHBvaW50cz0iNDkuOTUsOTUuMDcgNzcuNTEsMzguNDUgNDkuOTUsMjcuNjMgIi8+DQo8Zz4NCgk8cGF0aCBjbGFzcz0ic3QxIiBkPSJNNjcuNywyOS43OWMtMC40MS0xLjQyLTEuMDItMi44NC0xLjc4LTQuMDZsLTUuMjgtNS4xM2MtMS4xNy0wLjcxLTIuNDktMS4yNy0zLjkxLTEuNTd2LTUuNjloLTcuNjd2NS42OQ0KCQljLTEuMzcsMC4zNi0yLjY0LDAuODYtMy44MSwxLjUybC0zLjc2LTMuNWwtNS4xMyw0Ljg3bDMuNjYsMy42NmMtMC44NiwxLjI3LTEuNTIsMi42OS0xLjkzLDQuMjFoLTQuOTh2Ny40Nmg0LjgyDQoJCWMwLjMsMS41MiwwLjkxLDMsMS43Myw0LjMybC0zLjQsMy4ybDUuNTgsNS4zOGwyLjY0LTMuNDVjMS4zNywwLjg2LDIuODksMS41Nyw0LjU3LDEuOTh2NC41N2g3Ljgydi00LjYyDQoJCWMxLjY4LTAuNDEsMy4yLTEuMTIsNC41Ny0xLjk4bDMuMTUsMy43Nmw0LjgyLTUuMjhsLTMtMy45NmMwLjY2LTEuMjIsMS4xMi0yLjU0LDEuNDItMy45MWg1LjEzdi0zLjk2TDY3LjcsMjkuNzl6IE01Mi45MiwzOS44NA0KCQljLTMuNzEsMC02LjctMy02LjctNi43YzAtMy43MSwzLTYuNyw2LjctNi43YzMuNjYsMCw2LjY1LDMsNi42NSw2LjdDNTkuNTcsMzYuODUsNTYuNTgsMzkuODQsNTIuOTIsMzkuODR6Ii8+DQo8L2c+DQo8cG9seWdvbiBjbGFzcz0ic3QwIiBwb2ludHM9IjQ5LjU1LDUuMDIgMjIuNDksMzguNDUgNDkuMDQsOTUuMDcgIi8+DQo8cG9seWdvbiBjbGFzcz0ic3QyIiBwb2ludHM9Ijc2LjY1LDM3LjE0IDQ5LjA4LDI2LjMgNTAuMzgsNC45MyAiLz4NCjxnPg0KCTxyZWN0IHg9IjM4LjgiIHk9IjI3LjM0IiBjbGFzcz0ic3QzIiB3aWR0aD0iNC44IiBoZWlnaHQ9IjMzLjYiLz4NCgk8cGF0aCBjbGFzcz0ic3QzIiBkPSJNNDEuNjUsMjYuMmgtMC44OWMtMS4wOCwwLTEuOTYtMC44OC0xLjk2LTEuOTZ2LTAuMjhjMC0xLjA4LDAuODgtMS45NiwxLjk2LTEuOTZoMC44OQ0KCQljMS4wOCwwLDEuOTYsMC44OCwxLjk2LDEuOTZ2MC4yOEM0My42LDI1LjMyLDQyLjczLDI2LjIsNDEuNjUsMjYuMnoiLz4NCgk8cG9seWdvbiBjbGFzcz0ic3QzIiBwb2ludHM9IjQxLjIsNjkuNzQgMzguNTUsNjMuMDkgNDMuODUsNjMuMDkgCSIvPg0KPC9nPg0KPHBvbHlnb24gY2xhc3M9InN0NCIgcG9pbnRzPSI0OS41NSwyNS45NyA0OC4zNywyNi44MyA0OC4xOSwyOC43IDUwLjIxLDI5LjI4IDUzLjA1LDMwLjQ0IDU5LjE1LDMwLjc4IDc4LDM4LjMxIDc0LjkxLDM2LjQ1ICIvPg0KPC9zdmc+DQo=)](https://github.com/NMSCD)

#### Apps
- [Website](https://nmsassistant.com)
- [Google Play Store](https://play.google.com/store/apps/details?id=com.kurtlourens.no_mans_sky_recipes, "Google Play Store")
- [Apple App Store Store](https://apps.apple.com/us/app/assistant-for-no-mans-sky/id1480287625, "Apple App Store")

#### Social
- [Twitter](https://twitter.com/AssistantNMS?ref=nmsAssistant)
- [Discord](https://discord.gg/q3aFBQM?ref=nmsAssistant)
- [Facebook](https://facebook.com/AssistantNMS)
- [Steam Community Page](https://steamcommunity.com/groups/AssistantNMS)
- [NoMansSky Social](https://nomanssky.social/AssistantNMS)

## Feature Requests / Issues / Bugs
Please feel free to let me know if there is an issue with the App by logging an issue here or sending an [email](mailto:nms@kurtlourens.com).

If you would like to help add languages to the app please make a pull request into this [repository](https://github.com/NoMansSkyAssistant/Languages) or send an [email](mailto:nms@kurtlourens.com).

## Builds
The Mobile Apps are built and released to the [Google Play Store](https://play.google.com/store/apps/details?id=com.kurtlourens.no_mans_sky_recipes, "Google Play") and [Apple App Store Store](https://apps.apple.com/us/app/assistant-for-no-mans-sky/id1480287625, "Apple App Store") using CodeMagic 

- [![Codemagic build status](https://api.codemagic.io/apps/5d9da9057a0a9500105180bf/5da07d2e7338b0000f046ba3/status_badge.svg)](https://codemagic.io/apps/5d9da9057a0a9500105180bf/5da07d2e7338b0000f046ba3/latest_build) - Android & iOS (Production)
- [![Codemagic build status](https://api.codemagic.io/apps/5d9da9057a0a9500105180bf/5e180f76d95f1f258ec86619/status_badge.svg)](https://codemagic.io/apps/5d9da9057a0a9500105180bf/5da07d2e7338b0000f046ba3/latest_build) - Android (Production)
- [![Codemagic build status](https://api.codemagic.io/apps/5d9da9057a0a9500105180bf/5d9da9057a0a9500105180be/status_badge.svg)](https://codemagic.io/apps/5d9da9057a0a9500105180bf/5d9da9057a0a9500105180be/latest_build) - Android (Alpha)
- [![Codemagic build status](https://api.codemagic.io/apps/5d9da9057a0a9500105180bf/5d9dc56b7a0a95000a475d84/status_badge.svg)](https://codemagic.io/apps/5d9da9057a0a9500105180bf/5d9dc56b7a0a95000a475d84/latest_build) - iOS Build

The Web App is built and deployed using Azure DevOps
- [![Build Status](https://dev.azure.com/khaoznet/NMS%20Assistant/_apis/build/status/NMS.Assistant.WebApp?branchName=master)](https://dev.azure.com/khaoznet/NMS%20Assistant/_build/latest?definitionId=46&branchName=master) - Build
- [![Deployment Status](https://vsrm.dev.azure.com/khaoznet/_apis/public/Release/badge/b8fd530f-a5ad-4a72-bdf7-c0346b9759ee/7/14)](https://vsrm.dev.azure.com/khaoznet/_apis/public/Release/badge/b8fd530f-a5ad-4a72-bdf7-c0346b9759ee/7/14) - Deployment

The Website is built and deployed using Azure DevOps
- [![Build Status](https://dev.azure.com/khaoznet/NMS%20Assistant/_apis/build/status/NMS.Assistant.Web?branchName=master)](https://dev.azure.com/khaoznet/NMS%20Assistant/_build/latest?definitionId=37&branchName=master) - Build
- [![Deployment Status](https://vsrm.dev.azure.com/khaoznet/_apis/public/Release/badge/b8fd530f-a5ad-4a72-bdf7-c0346b9759ee/5/11)](https://vsrm.dev.azure.com/khaoznet/_apis/public/Release/badge/b8fd530f-a5ad-4a72-bdf7-c0346b9759ee/5/11) - Deployment

![fontExample](https://github.com/NMSCD/About/raw/master/banner/current-small.png)
