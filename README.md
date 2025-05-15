## String Theory API Tests

This repository contains sample requests for the String Theory APIs (https://string-theory.finance/api).

### Getting Started

1. Clone this repository locally `git clone git@github.com:Ellisande/string-theory-bruno.git`
2. Install Bruno (https://usebruno.com)
3. Import the project into Bruno using the "open collection" function

You are now ready to hit a local instance of String Theory with Bruno

### Executing requests against other environments

If you have a String Theory running somewhere you can configure Bruno to be able to hit it using the following steps:

1. Click on a collection
2. In the top right corner there is a drop down that will say "local" or "No Environment"
3. Click on the drop down and select "Configure"
4. Press the "+Create" button to create a new environment, and give it a meaningful name
5. Click "+Add Variable" and add a new variable called `base_url`, the value should be the root URL of your String Theory API instance
6. Click "+Add variable" and add a new varaible called `api_key`, click the box that says "secret", and finally paste in your String Theory API key for the environment you intend to hit
7. Click "save" to save the changes for your environment
8. Click "active" to use this as your active environment for requests

You are now ready to use Bruno for your custom environment!
