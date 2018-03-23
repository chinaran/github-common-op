# github-common-op
github common operation

## Contributing

1. Fork it
2. Create your feature branch
   `$ git checkout -b my-new-feature`
3. Commit your changes 
   `$ git commit -am 'Added some feature'`
4. Push to the branch 
   `$ git push origin my-new-feature`
5. Create new Pull Request (on github website)

## Syncing a fork from remote
1. List the current configured remote repository for your fork
	`$ git remote -v`
2. Specify a new remote upstream repository that will be synced with the fork 
	`$ git remote add upstream https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git`
3. Verify the new upstream repository you've specified for your fork 
	`$ git remote -v`
4. Fetch the branches and their respective commits from the upstream repository 
	`$ git fetch upstream`
5. Check out your fork's local master branch
	`$ git checkout master`
6. Merge the changes from upstream/master into your local master branch
	`$ git merge upstream/master`
7. Sync to you own github repositoriy
	`$ git push origin master`
