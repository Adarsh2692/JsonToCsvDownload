# JsonToCsvDownload
Fetch data on every change in input box and download CSV file on submitting the JSON data received
I have linked the input box to a javascript function which calls the required API everytime there is a change in the input box.
Once user selects a particular option from the input box and submits the form, the data is downloaded in CSV format by applying some formatting.
Here, we will be receiving nested JSON data from the api. I have flattened the JSON data such that "abc":{"pqr":"xyz"} will be stored as abc.pqr=xyz so that it is completely displayed in CSV format
