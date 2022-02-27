# Setup

- Create react app
- Install dependencies

```
npm install @material-ui/core @material-ui/icons @material-ui/lab @react-google-maps/api axios google-map-react
```

- Create folder structure
- Create styles

## RapidAPI

- Signup to rapidapi
- Search for `Travel Advisor`
- Click `Subscribe to Test` button
- Click `Subscribe` on your desired package
- copy axios options from the right tab of the `list-in-boundary` endpoint
- use that in your axios request in API

## Getting Google Maps API Key

- Create GoogleMap project going to `https://console.cloud.google.com/projectcreate`
- Name your project `project-name`
- Select your project
- Click `APIs and Services` in the sidebar and click `Dashboard`
- Click `Enable APIs and Services`
- Search for and click `Maps JavaScript API` and click `enable`
- Click `Maps JavaScript API` from the enabled APIs list
- Click `Credentials` from the sidebar, then click `+ Create Credentials`, then click `API key`
- Copy the API key and use it in the `GoogleMapReact` component

## Weather API

- Search `Open Weather Map` API and click it
- Subscribe to it
- Get the options from `Search Weather data` endpoint
- Use those options to make API call just like getPlaces call
