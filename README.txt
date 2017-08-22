# jquery

this is a repo to hold different versions of jquery you may need.

# jquery ready to run files
Downloaded from jquery.com and set to the "packages" branch to have the versions the application may need.

Checkout the version you need or create a new branch including the version you want.

if you need several versions? then merge it to the packages branch

example:
# branch of v1-8-3
./v1.8.3/jquery.min.js
./v1.8.3/README.txt (copy of this readme)


If a new version exists and you need it globaly:
don't drop other versions! Add your version to the packages branch or create and checkout your version:

Eg: You need verion 2.0.1 system wide:
checkout the master branch and create a new branch: "v2-0-1" (branches needs - NOT dots!)
create a folder: mkdir v2.0.1/
Download the jquery.min.js to v2.0.1/
commit & push the new version branch

Then checkout the "packages" branch and merge your version into it. result:
# packages branch
./v1.8.3/jquery.min.js
./v1.8.3/README.txt
./v2.0.1/jquery.min.js
./v2.0.1/README.txt

