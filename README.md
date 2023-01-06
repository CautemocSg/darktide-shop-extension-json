# Guide for setting up Darktide Shop extension's JSON filter

The easiest way to format your JSON and make sure it's correct is to use an editor service, like below:
https://jsoneditoronline.org/

With this tool you can also use a JSON "schema", which will make sure everything you are writing is also valid compared to accepted formats by the extension. To do this, open the JSON schema file in this repository and copy the JSON. Paste that into the right panel of the above JSON editor. On the left side click the Options dropdown, and click Configure JSON Schema. In the new window that opens, choose "Panel" and it should set the right side panel as the schema. Now you can use the left panel to write you filters and it will tell you if anything is configured wrong for the extension.

Here is an example of a working configuration -
https://imgur.com/a/lLQlEbo
