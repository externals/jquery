# jquery

this is a repo to hold different versions of jquery you may need.

This master repo only hold this readme to upgrade the branches


# jquery ready to run files
Downloaded from https://jqueryjs.com/ and set to the "packages" branch to have
the versions an application may need.
If you want several versions of jquery this will be your primary branch to choose
    # git checkout packages

If you just need a special version then checkout the branch you need or create
a new branch including the version you want.
If you need several versions? Then merge it to the packages branch an switch
back to the packages branch.



# Examples/ Howto add new versions

## branch master
    ./README.txt (copy of this readme)


## branch of vA-B-C
    ./vA.B.C/jquery.js
    ...
    ./vA.B.C/README.txt (README of jquery vA.B.C)
    ./README.txt (copy of this readme)


If a new version exists and you need it globaly/ in packages branch:
Don't drop other versions! Add your version to the packages branch or create
and checkout your version.

Eg: You need verion 2.0.1 system wide:
checkout the master branch and create a new branch: "v2-0-1" (branches needs - NOT dots!)
create a folder: mkdir v2.0.1/
Download the file *.js/*.css to v2.0.1/
commit & push the new version branch

Then checkout the "packages" branch and merge your version into it. result:
# packages branch
    ./vA.B.C/jquery.js
    ./vA.B.C/README.txt
    ./v2.0.1/jquery.js
    ./v2.0.1/README.txt
    ./README.txt                        #(copy of this readme on creation time)
    ./plugins/v1/**                     # Mixed plugins for jquery v1.*
    ./plugins/v1/datatables/v1****/     # Mixed versions for datatables
    


# Changelog

    2018-09
        Adds datatables plugin (v1.10.18) @see packages branch plugins/v1/

    2018-07
        Adds contextMenu (v2) plugin for jquery v1*  @see packages branch plugins/v1/
        Adds toast (v1.3.2) plugin for jquery v1*

    2017-09
        Adds Version v1.8.3
        Adds Version v1.12.4
        Adds Version v3.1.1

