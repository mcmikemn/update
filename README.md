# update
Simplify updating Ubuntu with some options.

## Installation
1. Copy to /usr/local/bin (or anywhere you want, adding that location to your $PATH)
2. Make executable: `chmod +x /usr/local/bin/update`

This bash script updates the apt cache, lists upgradable packages, allows you to view individual package details or changelogs, allows you to upgrade specific packages or all upgradable packages, and allows you to remove old unneeded packages.

## Usage
1. Run as sudo: `sudo update`
   1. Optionally, use an "f" switch to run `apt full-upgrade` (all upgradable packages) without prompts: `sudo update f`
   2. Optionally, use a "u" switch to run `apt upgrade` (all upgradable packages) without prompts: `sudo update u`
   3. Optionally, use an "a" switch to run `apt autoremove` (remove unneeded packages) without prompts: `sudo update a`

##### From the script's "help":
```
Enter a package # to show details of that package.
Enter "c" followed by a package # to see that package's changelog (e.g., c3).
Enter "u" followed by a package # to upgrade that specific package (e.g, u4).
Enter "a" to perform `apt autoremove` (remove unneeded packages).
Enter "f" to perform `apt full-upgrade` (all upgradable packages).
Enter "u" to perform `apt upgrade` (all upgradable packages).
Enter "s" to view the list of upgradable packages.
Enter "x" to exit.
```
