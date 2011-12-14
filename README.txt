= eArchive Readme =

== Directories ==
code/        -- All code for this project.
reports-src/ -- The source reStructuredText, figures, and others used for generation of the reports.
reports/     -- Build reports as PDF files.

Additionaly README.txt s exist in each of the above mentioned directories.

== Maintiner notes ==
If you are cloning this repo from git, use:
    git clone --recursive https://github.com/pitfail/earchive

If it is already cloned normally, do this to initialize:
    git submodule update --recursive --init

To update this repo, do this:
    git pull --recurse-submodules
    git submodule update --recursive --init
