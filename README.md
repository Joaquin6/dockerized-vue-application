# dockerized-vue-application

## Overview

Create a Vue App that allows the user to view a list of objects, sort & filter the list and load a specific object's detail view. The app must use the following components:

- Vuex
- Vuetify
- Vue Router

When in doubt, air on the side of simplicity, we donâ€™t want this to be a huge undertaking for you!

## Requirements

- Must run inside a docker container
- Must poll data on a set interval from an API Data Source -- either a static file (i.e. JSON Placeholder) or an API Data source of your choosing
- Must render the data in a list view with pagination
- Must have sorting and filtering on at least 2 fields (preferrably server-side)
- Must persist sort/filter preferences on page refresh
- Must have the ability to click on an object in the list view to display extended details of the object on a separate page
- Should have reasonable test coverage (mocha or jest) which runs inside the container
- Should be visually appealing but avoid modifiying Vuetify's internal classes
- Should have a well structured, linted and easy to read codebase
