# Unofficial ArcSight Logger API Examples

Welcome to the unofficial API examples for the Microfocus ArcSight Logger.

This is an exported list of all API's and their examples, utilized using [Postman](https://www.getpostman.com/)

## Usage
First download and install Postman to be able to try out all the API examples. Newest release can be found [here](https://www.getpostman.com/)

### Downloading the API examples
Download the required package directly from github, either from cli using:
```sh
$ git clone https://github.com/arcsight-unofficial/arcsight-logger-api-examples
```
Or if you have internet access or a proxy server which does not allow git, download the newest release manually.
[Releases can be found here](https://github.com/arcsight-unofficial/arcsight-logger-api-examples/releases)

### Importing the API Collection
Open your Postman application, go to File, Import and choose the json file in this directory.

### Adding hostname and credentials.
To make the API examples much easier to use, there is certain variables that is set for you, this is hostname, port, username and password.

After importing, right click your new collection and choose Edit.

Go to the Variables tab and fill in the information in the rightmost field. This will automatically fill in that information for every API call you make.

The last additional detail is that the session token is automatically added when you try out the "login" API Example. After running it once, it will set the authToken for the rest of the session, so you don't need to manage this manually.

### Editing the API Examples
If you want to continue to receive updates, please do not change the file in this folder, as you could easily overwrite your own changes when getting the newest version through git, better to take a copy and edit that instead.