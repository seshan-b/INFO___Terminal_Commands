# Clean up Linux Ubuntu CLI

`**df -h`** — To check your machine’s disk usage and see how much free space is left, you can run the following command in your terminal.

**`sudo apt-get autoclean`** — This terminal command deletes all .deb files from /var/cache/apt/archives. It basically cleans up the apt-get cache.

`**sudo du -sh /var/cache/apt`** — Check to see how much you can free up from apt folder. This folder builds up over time. 

**`sudo apt-get clean` —** This terminal command is used to free up the disk space by cleaning up downloaded .deb files from the local repository.

**`sudo apt-get autoremove` —** This terminal command used to remove packages that were automatically installed to satisfy dependencies for some package and no longer needed by those packages.

**`sudo apt-get update`** — We use the update option to download package information from all configured sources such as the Internet.

`**sudo apt-get upgrade`** — The upgrade option will install available upgrades of all packages currently installed on the system from the sources such as the Internet. New packages will be installed if required to satisfy dependencies, but existing packages will never be removed. If an upgrade for a package requires removing an installed package, the upgrade for this package isn’t performed. Hence, this is a safer option in all cases.

<aside>
ℹ️ `**find . -name "node_modules" -type d -prune -print | xargs du -chs**` — Find all Node modules in folder and all it’s child folders.
<br/>
<aside>
🚫 Do not use it in the parent folder where the NVM “Node Version Modules” are stored otherwise you might have to reinstall NVM again.  Sometimes it might mess up the set up. **Be extra careful when using this command.**

`**find . -name 'node_modules' -type d -prune -print -exec rm -rf '{}' \;**` — Delete Node modules when using this command. You cannot run `npm` after that and might have to reinstall your whole Linux Distro for it to work again. 

</aside>

</aside>

<aside>
ℹ️ `**find . -name ".DS_Store"`** — To find all the `.DS_Store` files in all subdirectories on my machine.
<br/>
<aside>
🚫 `**find . -name ".DS_Store" -delete`** — To find all the `.DS_Store` files in all subdirectories on my machine and delete it. Make sure you are in the correct directory before you run this command.

</aside>

</aside>

---