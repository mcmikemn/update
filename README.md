# update
Automate updating Ubuntu with some choices

1. Copy to /usr/local/bin (or anywhere you want, adding that location to your $PATH)
2. Make executable: `chmod +x /usr/local/bin/update`
3. Run as sudo: `sudo update`

This bash script updates the apt cache, displays a list of upgradable packages, allows you to view individual package details or changelogs, and [allows you to upgrade specific packages (coming soon)] or all upgradable packages.