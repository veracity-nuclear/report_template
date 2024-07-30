This repository contains all the files to create an empty Veracity Nuclear report.
To use this, simply clone the repository and begin editing the main.tex file to
change the template into your report.

If the report is to be kept inside another repository, then from the top of the
repository it's recommended to do something like this:
```
git clone git@github.com:veracity-nuclear/report_template report
cd report
rm -rf .git .gitignore
cd ..
git add report
```
This will add the files of the report template to the other repository without
any of the git objects.
