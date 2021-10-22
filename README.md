
# APEX Documentation for Dash

With this instructions you can build an offline [APEX](https://apex.oracle.com) documentation for [Dash](https://kapeli.com/dash).
The process is very straight forward:

* Download/Install [dashing](https://github.com/technosophos/dashing)
* Download APEX API and JS HTML docs and extract them in these directories respectively.
content/aeapi/
content/aexjs/

* Run 
```
./dashing build apex201
``` 

Dashing will use `dahsing.json` to create a docset by parsing the HTML documents and identify the different sections.

