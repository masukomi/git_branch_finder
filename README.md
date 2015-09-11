# Git Branch Finder

You know that work you did but can't remember which branch it was in?

This is a tool to help you find it. It will iterate over all your local
branches and either grep the last commit (with `--stat`) or grep 
the entire codebase. 

It will tell you which branch it was looking in, and output the matching
info if it finds it.

## Usage

	Usage: branch_finder <grep_string> <search_type>
	search types: last_commit, codebase
	
	# Example: 
	branch_finder some_new_method_i_made codebase
	# searches for that new method name anywhere in the codebase


## Contributing

PRs: Keep 'em coming. I'm especially interested in new search types being added.
