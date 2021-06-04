Create search and all metadata in a yaml file.

The commit triggers a script that pushes the search and metadata to Splunk Cloud, via github actions.

The script converts the yaml format to json, and pushed the search and its metadata to Splunk Cloud via curl and the REST API.
