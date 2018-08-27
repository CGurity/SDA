# SDA
(Secure and Documented for Activism)
https://sdamanual.org

Organizational Security documentation framework to help activist groups to write their very first and feasible security policies through facilitated activities

# Theme and front matters

To date the theme used is [Forty - Jekyll Theme](https://github.com/andrewbanchich/forty-jekyll-theme). Being modified to have in the ```_activities``` directory the pages of the second level content (the actual activities).

## Front Matter templates

### Level 1 pages (stages)

```yaml
---
layout: landing2 # or landing0, landing3, landing4, post (Changing highlight colors)
title: 01_ Research and security objectives # Title
nav-menu: true
description: "Creating the basis to develop all the minimum security policies.

Although ideally this step should be applied at the moment of conception, this methodology has been built and written to be adapted in already existing organizations." # Long description for the tiles in the home page
image: assets/images/template-01.jpg # Background image for the home page tile and page header
---
```

### Level 2 pages (activities)
```yaml
---
layout: post2 # or post3, post4 (Changing highlight colors)
sectionid: 01-01-Records-management-of-the-organization's objectives # To locate it with links in the parent page (stage - level 1)
sectionclass: h2
title: Records management of the organization's objectives
parent-id: 01-fundacion
image: null
---
```
