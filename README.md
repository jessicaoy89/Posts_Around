# Posts_Around
###### A web service with Go and React: Mini Social Network

## Table of Contents:
- [Installation](#installation)
- [Project Motivation](#project-motivation)
- [File Descriptions](#file-descriptions)
- [Results](#results)
- [Licensing, Authors, Acknowledgements](#end)

## Installation
For front-end visualization, NPM package manager was used for this node.js platform. To visualize implementation without losing features, several libraries need to be installed including: create-react-app, react-google-maps, react-grid-gallery, antd. 
For back-end implementation, it was built entirely on google cloud platform with Go language and a number apis directly imported from google's libraries. Developers can upload the .go files to their VM instances of the google cloud compute engine, then use `go run *.go` to start the program.

## Project Motivation
This social network project is motivated by the following topics:
- What are the image and video posts around me? Follow-up questions include, can I see where are these posts, what are the events there?
- What are all the posts with face? (or to filter human activities)
- I also want to upload my own posts with comments.

## File Descriptions
The source code and environment configurations for back-end implementation are stored in the "Dockerfile" and for front-end realization are stored in the "build.zip" files to provide simple delivery and deployment options.
There are also four `.go` files and a src folder containing front-end `.js` and `.css` files available here to showcase the source code aimed to realize the above topics and questions. 

## Results
The plain web page output can be viewed [here](https://prod.db4q5u3ngzr7w.amplifyapp.com/). For cost reasons, the back-end GCP instances are currently stopped, please be free to reach out to me if you wish to communicate about the details and visualization of this project.
<a name="end"></a>
## Licensing, Authors, Acknowledgements
Credits are be given to engineers from Google, Facebook, and Uber for advice on use case and technical problems. Otherwise, feel free to use the code here as you would like!
