# jquery

this is a repo to hold different versions of jquery you may need 
and also to make them available for the toolbax application as default

# jquery ready to run files
Downloaded from jquery.com and set to the "toolbox" branch the versions you prefer for the toolbox as default

Checkout the version you need or create a new branch including the version you want

if you need them toolbox wide? then merge it to the toolbox branch

example:
# toolbox branch
./v1.8.3/jqery.min.js
./v1.8.3/README.txt

If a new version exists and you need it for the toolbox globaly:
don't drop other versions! Add your version to it:

Eg: You need verion 2.0.1 system wide:
checkout the master branch and create a new branch: "v2-0-1" (branches needs - NOT dots!)
create a folder: mkdir v2.0.1/
Download the jquery.min.js to v2.0.1/
commit & push the new vesion branch

Then checkout the "toolbox" branch and merge your version into it. result:
# toolbox branch
./v1.8.3/jqery.min.js
./v1.8.3/README.txt
./v2.0.1/jqery.min.js
./v2.0.1/README.txt

