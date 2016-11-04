# Finding-Aids
Testbed for finding aid versioning

## Why GitHub for finding aids?
GitHub, though intended as a repository for open-source code, is also notable for its distributed [version control functionality](https://en.wikipedia.org/wiki/Distributed_version_control). This functionality is more robust than that of OneDrive or other content management systems, and allows for multiple versions of documents to exist concurrently without eliminating any one archivist's changes. The GitHub administrator can determine which changes, if any, to incorporate into the final document, and a log of additions and subtractions to the "master" copy of code is still maintained.

## Using GitHub-- Basic Functionality for Finding Aid Versioning

1. When a finding aid is ready to be modified to reflect additions or reprocessing, move a copy of the EAD to the GitHub EAD repository folder. 
2. Open GitHub desktop. Click the "Branch" icon" on the top left and create a new branch using the call number of the collection to be changed as the Branch name. Click the "Publish" button to add a branch to the repository.
3. Enter a description of your change to the repository (e.g. "Adding EAD to prepare for processing"), hit the "Commit" button, and then hit the "Sync" button to push the finding aid to the online repository. 
4. Make changes to the finding aid in Oxygen. Save the EAD with your changes in the repository folder.
5. With the secondary branch selected in GitHub Desktop, enter a summary (e.g. "Added accession 2013-024") and description (e.g. "Changes were made to titleproper, unitdate, acqinfo, processinfo, etc.) under the list of changes. When you're happy with how these look, click "Commit", and then "Sync" to publish to the branch.
6. Click "Pull request" to submit the request. Tag the finding aid reviewer (@bhouston1982 for the moment) to notify.

## Reviewing Changes
1. Go to the Pull Requests tab and click on the request most relevant to the finding aid you're reviewing.
2. Once you've opened the pull request, go to the Files Changed tab. You have a few options at this point if changes need to be made:
a. For minor changes, you can edit directly in the editor by clicking on the "pencil" button on the top right of the window. Changes will automatically commit to the in progress branch.
