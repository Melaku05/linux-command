# linux-command
## Search for and Delete Any Remaining MySQL Files:
Use the following command to find any remaining MySQL files and directories:
```
sudo find / -iname 'mysql*' -exec rm -rf {} \;
```
