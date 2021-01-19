# What is this?

Test npm library (for learning purposes only)

# Installation

`npm i shadowizardasta --save`

Example of usage:

1) Create index.html
````
import { shadowizardasta } from 'shadowizardasta';

shadowizardasta({
  shadow_type: 'soft',
  padding: true
});
````

2) Use the lib in main.js:
````
import { shadowizardasta } from 'shadowizardasta';

shadowizardasta({
  shadow_type: 'soft',
  padding: true
});
````

3) To run local server, install parcel:
````
npm i parcel -g
````

4) To bring up the server use the command:
````
parcel index.html
````