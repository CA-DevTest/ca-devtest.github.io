# Welcome to CA DevTest community

This page describes how you can contribute to the CA DevTest community and steps to follow to release your community contribution.

## Join the CA-DevTest organization

Create a github account, and request to join the organization by sending an email to ian.kelly@ca.com.

## Fork a repo or generate a pull request

If you want to contribute to an existing repository, simply fork the repository, make your changes and send a pull request. If you need help on this, you can contact for example the person who has done the latest commits to that repository.

## License to be used

Currently we want each contribution to have the following license information maintained:

THIS CODE AND INFORMATION ARE PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE IMPLIED WARRANTIES OF MERCHANTABILITY AND/OR FITNESS FOR A PARTICULAR PURPOSE. THIS CODE AND INFORMATION ARE NOT SUPPORTED BY CA TECHNOLOGIES.

http://www.eclipse.org/legal/epl-v10.html

## Release your contribution

### Add new repo
Each repository must have the license somewhere included. If your repository is an extension, the repo name should end with ext

### Update existing repo
Make sure you follow these steps

Update the new version number. Create a new tag. Example git tag -a v5.1.2 -m 'Version 5.1.2' 123456 Push the tag to github: git push --tags

