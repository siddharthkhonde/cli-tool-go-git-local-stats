Run go install and

1. cli-tool-go-git-local-stats -add /path/to/folder will scan that folder and its subdirectories for repositories to scan
2. cli-tool-go-git-local-stats -email your@email.com will generate a CLI stats graph representing the last 6 months of activity for the passed email. You can configure the default in main.go, so you can run gogitlocalstats without parameters.

Being able to pass an email as param makes it possible to scan repos for collaborators activity as well.
