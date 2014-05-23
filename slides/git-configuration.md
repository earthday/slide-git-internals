##  git configuration

~/.gitconfig

```
$ git config --global user.name "Bright Chen"
$ git config --global user.email bright.chen@autodesk.com
```

.gitignore

```
# Build Folders (you can keep bin if you'd like, to store dlls and pdbs)
[Bb]in/
[Oo]bj/

# mstest test results
TestResults

## Ignore Visual Studio temporary files, build results, and
## files generated by popular Visual Studio add-ons.

# User-specific files
*.suo
*.user
*.sln.docstates

# Build results
[Dd]ebug/
[Rr]elease/
x64/
*_i.c
*_p.c
*.ilk
*.meta
*.obj
*.pch
*.pdb
*.pgc
*.pgd
*.rsp
*.sbr
*.tlb
*.tli
*.tlh
*.tmp
*.log
*.vspscc
*.vssscc
.builds

# Visual C++ cache files
ipch/
*.aps
*.ncb
*.opensdf
*.sdf

# Visual Studio profiler
*.psess
*.vsp
*.vspx

# Guidance Automation Toolkit
*.gpState

# ReSharper is a .NET coding add-in
_ReSharper*

# NCrunch
*.ncrunch*
.*crunch*.local.xml

# Installshield output folder 
[Ee]xpress

# DocProject is a documentation generator add-in
DocProject/buildhelp/
DocProject/Help/*.HxT
DocProject/Help/*.HxC
DocProject/Help/*.hhc
DocProject/Help/*.hhk
DocProject/Help/*.hhp
DocProject/Help/Html2
DocProject/Help/html

# Click-Once directory
publish

# Publish Web Output
*.Publish.xml

# NuGet Packages Directory
packages

# Windows Azure Build Output
csx
*.build.csdef

# Windows Store app package directory
AppPackages/

# Others
[Bb]in
[Oo]bj
sql
TestResults
[Tt]est[Rr]esult*
*.Cache
ClientBin
[Ss]tyle[Cc]op.*
~$*
*.dbmdl
Generated_Code #added for RIA/Silverlight projects

# Backup & report files from converting an old project file to a newer
# Visual Studio version. Backup files are not needed, because we have git ;-)
_UpgradeReport_Files/
Backup*/
UpgradeLog*.XML
```