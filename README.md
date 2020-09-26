# update
Automate updating Ubuntu with some choices

1. Copy to /usr/local/bin (or anywhere you want, adding that location to your $PATH)
2. Make executable: `chmod +x /usr/local/bin/update`
3. Run as sudo: `sudo update`

This bash script updates the apt cache, lists upgradable packages, allows you to view individual package details or changelogs, and [coming soon: allows you to upgrade specific packages or] all upgradable packages.

From the script's "help":
```
Enter a package # to show details of that package.
Enter "c" followed by a package # to see that package's changelog (e.g., c3).
Enter "f" to perform `apt full-upgrade`.
Enter "u" to perform `apt upgrade`.
Enter "u" followed by a package # to upgrade that specific package (e.g, u4).
Enter "s" to view the list of upgradable packages. Enter "x" to exit.
```