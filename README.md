# Holy Grail Appication
This is a three-tier application with a holy grail design (holy grail is a web page layout) and a full-service database. 

# Architecture
React and Superagent as client
Node and Express as server
Redis for datastore, running on top of docker

# Usage
After cloning this onto your local machine run
"npm install" followed bye "node index.js"

Dependencies can be found in package.json

# Design
When the plus or minus button in any section is clicked, the number for that section updates accordingly and the state is tracked across all components. Below is an preview of of the UI

![Holy Grail Design](https://github.com/KaylaDefi/Holy-Grail-Application/blob/main/public/icons/holyGrailDesign.png)
