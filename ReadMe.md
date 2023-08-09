***) Chapter 1
*)
system = for all users
global = for all repo
local = for local repo

*)
git config --global user.name "nmsh911"
git config --global user.email coding911@gmail.com

*)
 setting default editor
git config --global core.editor "code --wait"
with the wait flag we tell terminal to wait until we close new vscode instance
Replace "code --wait" with the appropriate command for opening Visual Studio Code on your system. The --wait flag is used to wait for the editor to be closed before proceeding, which is the expected behavior for Git operations.

git config --global -e
this will open our default editor to edit all the global settings

git config --global core.autocrlf true


***) Chapter 2
*) 
Posh-git, an optional lib

*) for unstaging a folder and its contents
git rm --cached "D:/Other Setups 2/tig/folder skip/skip.txt"
