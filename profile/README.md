### Updating projects

If you want to update a stale old mirror collecting dust that has missed some action through the years. Clone the out of date mirror from here and try to run a rebase over it from the official location

These commands might help or might even work directly without modification

```
sudo apt install git git-svn git-bzr git-cvs

git clone http://github.com/mirror/mirror

# Look for the command
cat git_mirror
# Or hope it will print the command it is trying to perform
. git_mirror
git_mirror waver bzr https://code.launchpad.net/~waver-developers/waver/trunk
```

If the rebase failed you might open a public issue if anyone is bothered that the entire history has to be rewritten. That a force push is required because the rebase failed. Everyone will probably understand and you can push the update

### Organisational overview

The purpose is to promote collaboration and connection between worlds

This is a way to discover hidden gems and everyday tools that are hiding elsewhere

Even some CVS archives have been mirrored here. Most notably and by far most complicated Cygwin. Windows in the constellation Cygnus. Everyone that has tried to use Windows know how hard it can be without the proper tools

Code search is one of the strong points of this lab and even on the phone it's relatively easy and fast to find code segments inside large projects. One reason for a mirror, or a copy, here also. Or just from laziness in creating a patch quickly without bothering about remember the login to the right lab or official lab where they usually work on the project 

### Maintenance and contacts

If you own a project and wish to add it, remove it, move it, change ownership, or hide it from this project or this lab the best way to contact us is with a public message under Issues or Discussion inside the maintenance project mirror/mirror. And be patient for a reply it will come in due time. If it is urgent you can try contacting the current and public organisation members directly 
