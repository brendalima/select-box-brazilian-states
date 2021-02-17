# Box Selection for Brazilian States

This is a simple application directly adapted from [OpenLayers example code](https://openlayers.org/en/latest/examples/box-selection.html) for box selection tool for maps. This adaptation allows for brazilian states to be selected on a map and listed accordingly, instead of the original selection for countries.

## Features

- Use click selection to select a single state on the map;
- Use ctrl + drag to create a box selection and select multiple states on the map;
- Navigate on the map through drag and/or scroll.

## Instructions

You can run this application locally by cloning this repository through:

```
git clone git@github.com:brendalima/select-box-brazilian-states.git
```

This should import the package file containing the dependencies used, which are:
```ol``` and ```parcel-bundler```

To install these dependencies, you can simply run:
```
npm install
```
This should automatically locally install all the necessary dependencies.
To start running the application, use:
```
npm start
```

Note: for test running this application, it is advisable to use a Chrome extension such as [Moesif CORS](https://chrome.google.com/webstore/detail/moesif-origin-cors-change/digfbfaphojjndkpccljibejjbppifbc?hl=en-US) or [Allow CORS](https://chrome.google.com/webstore/detail/allow-cors-access-control/lhobafahddgcelffkeicbaginigeejlf) to avoid problems with local urls. You should turn off these extensions after using them for the purpose of tests.
