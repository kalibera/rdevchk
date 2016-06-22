# rdevchk
Generated on Wed Jun 22 19:56:36 UTC 2016 using [rchk](https://github.com/kalibera/rchk).

[rchk](https://github.com/kalibera/rchk) is a set of offline bug-finding
tools that look for PROTECT bugs in the C code of GNU-R and R packages. 
This site presents results from the tool run periodically on recent
versions of GNU-R ([R-devel](https://svn.r-project.org/R/trunk/)).

The directory structure of the presented results corresponds to where
binaries and shared libraries are left after building R.  Hence, bug reports
for the core are in [src/main](src/main).  *Rchk* contains several bug
finding tools; the most interesting is *bcheck*, hence the most interesting
results for the R binary are [src/main/R.bin.bcheck.md](src/main/R.bin.bcheck.md).

Each report has a hyperlinked markdown version (suffix `.md`) suitable for
viewing online and a raw ascii version (no suffix).

The commits into this automatically generated git repository correspond to
commits to the R subversion repository, preserving the original commit
messages.  One can thus view reports also for older SVN revisions.  Still,
not all SVN revisions are checked individually.

Most errors currently reported for GNU-R are (hopefully still) false alarms,
because we have fixed the real errors.  This site thus also shows errors
that were [possibly introduced](possibly_broken.md) between two consecutive
checked versions and errors that were [possibly fixed](possibly_fixed.md). 
The hypelinks go to where the suspected errors are (new version for
introduced errors, old version for fixed errors).

