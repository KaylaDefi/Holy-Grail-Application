# Holy Grail Application
This is a three-tier application with a holy grail design and a full-service database. 

# Architecture
React and Superagent as client,
Node and Express as server,
Redis for datastore, running on top of Docker.

# Usage
After cloning this onto your local machine run
"npm install" followed by "node index.js"

Dependencies can be found in package.json

# Design
When the plus or minus button in any section is clicked, the number for that section updates accordingly and the state is tracked across all components. Below is a preview of the UI

![Holy Grail Design](https://github.com/KaylaDefi/Holy-Grail-Application/blob/main/public/icons/holyGrailDesign.png)
