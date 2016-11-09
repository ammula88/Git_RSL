This repo provides the git securepush and securefetch operations for RSL implementations.

Set Up Instructions:

 We can setup the securepush and securefetch operations in two different ways.
 
1.	Git custom commands:
To implement these custom commands, users must name these scripts as git-<command name> and they have to add the path of these scripts in their local PATH environment variable.
2.	Git alias:
The users can create a Git alias to our git-securefetch and git-securepush bash scripts using
the following commands.

git config –global alias.securefetch ’<git-securefetch script path>’
git config –global alias.securepush ’<git-securepush script path>’
