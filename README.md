
# common-transit-convention-traders-bruno

This is the Bruno collections repo for CTC Traders API

## Getting Started

### Prerequisites
Install the nodejs to download the external packages which are required to read the values from the API responses
* [Node.js](https://nodejs.org/en/download)
* [Bruno](https://www.usebruno.com/downloads)

### Important things to consider
1. Untick the **Store and Send Cookies automatically** from the **Preferences** option in Bruno app Because Bruno is not handling the cookies automatically when running the collections, so we're setting and getting the cookies in individual Auth token requests
2. Import Postman environment variables into Bruno Global Environments variables because Environments variables can't be shared between multiple collections in Bruno

### Running the AuthToken Collections
1. Import the **02_Bearer Token CTC API.json** collection
2. Copy the **package.json** and **bruno.json** files from **AuthToken** folder to the 02_Bearer Token CTC API folder which is created after importing the **02_Bearer Token CTC API.json** collection in your machine
3. Run the `npm install` command from the terminal
4. Run the Auth token collection for the required environment from the 02_Bearer Token CTC API folder

