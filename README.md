# API Fetching Practice
This project is a webpage powered by Javascript that consumes the [Met API](https://metmuseum.github.io/) in order to display art in a carousel. The webpage styling and coding outline was modified from [this CodeBase](https://codesandbox.io/p/sandbox/ajax-fetch-and-axios-lab-template-8yn8xq?from-embed=).

## Table of Contents
- [Installation](#installation)
- [Live Site](#livesite)
- [Usage](#usage)
- [Features](#features)
- [Acknowledgements](#acknowledgements)
  
## Live Site
I deployed the main branch via Netlify.
[https://main--tubular-ganache-6c2c23.netlify.app/](https://stupendous-scone-024eb9.netlify.app/)

## Installation
The main branch can be viewed via live site. However, to view the axios branch you will need to follow the instructions below.

##### Clone the repository
`git clone https://github.com/steph2017/SBA316.git`

##### Navigate to the project directory
`cd your-repo-name`

##### Delete files
These files are important for the live site but not needed for the local installation.

`rm -r .htmlnanorc dist`

##### Run the project
npm run build


## Features

- A Dropdown populated by a class of data within the API (Breed)
<img width="711" alt="image" src="https://github.com/steph2017/308A.4_Lab/assets/34190698/26dab6a9-db89-43fa-85af-681e789ae1c0">

- A Carousel of images based on a data fetching request "filtered" by the breed id selected in the dropdown.
  <img width="1424" alt="image" src="https://github.com/steph2017/308A.4_Lab/assets/34190698/d101ece8-c3af-45c2-b9a4-aa2897fed45a">

  
- An information section powered by infromation in the Breed class:
  <img width="1217" alt="image" src="https://github.com/steph2017/308A.4_Lab/assets/34190698/64e26c80-c8ee-433e-b915-0e613c911e61">


 
## Usage
- Simply use the dropdown to select your cat breed and click the green submit button to get results.

## Acknowledgements
This was made possible by:
- Instruction from [Tishana](https://github.com/tishana) and [Manara](https://github.com/Manara-Ali) under the [Per Scholas Software Engineering Immersive]https://perscholas.org/courses/software-engineer/
- The Per Scholas Product Development Team for the [borrowed code](https://codesandbox.io/p/sandbox/ajax-fetch-and-axios-lab-template-8yn8xq?from-embed=).
- [Nadir Kerem](https://github.com/nadirkerem) for directing me to [Netlify](https://app.netlify.com/) to deploy the project and helping to troubleshoot errors like providing the [StackOverFlow article](https://stackoverflow.com/questions/67087634/parcel-js-tree-render-is-not-a-function) that ultimately led me to my solution.
- Helpful troubleshooting resources such as [MDN Web Docs](https://developer.mozilla.org/en-US/) and [Stack Overflow](https://stackoverflow.com/).
