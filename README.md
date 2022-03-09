pwd prints out the current file path/directory
cd changes the current directory -- like opening a folder; could be used to explore a folder within a folder sequentially.
	shortcuts:
		cd .  = explores current directory
		cd .. = explores the parent directory (main directory)
		cd ~  = directs to home directory (main)
		cd -  = takes you to the previously opened directory
ls is used to list directories -- show all folders within any file that begins with a . (period) is hidden/ignored
	shortcuts/flags:
		ls -a = lists ALL, even hidden filenames
		ls -l = shows detailed information, metadata shit
			shows:
				file permissions
				number of links
				owner name
				owner group
				file size
				timestamp of last modification
				file/directory name
		ls -R = recursive 
		ls -r = reverse order
		ls -t = sorts by modification time, new first
touch creates files
file command displays description of the file type
cat reads files -- simple display
less simplifies the output of files, allows for the navigation page by page
	shortcuts:
		q  	      = used to quit out of less view
		pg up/pg down = navigates the page vertically
		g	      = moves to the beginning of the file
		G	      = moves to the end
		/search	      = basically control+f
		h	      = help
history shows the list of previously ran commands
clear deletes the history, clears up the page
cp copies files [cp (filename) (desired copy location)]
	IMPORTANT: copying files to a directory with a file with the same name will OVERWRITE the old file
mv moves files and can also rename them -- same functionality as cp
	rename files: mv oldname newname
	moving files: mv filename /desired/location
		separate files by spaces if more than one is being moved
	IMPORTANT: moving files to a location containing a file with the same name will overwrite the old file
mkdir creates directories/folders for storage
rm removes files
	IMPORTANT: ONCE FILES ARE REMOVED, THEY'RE GONE FOR GOOD
	flags:
		rm -f = forces the removal of files, even when protected
		rm -i = will give a prompt
		rm -r = removes subsidiaries within directories
find -- search function through windows directory, same thing just plug in a file name within a directory and it's good
help lists commands
man opens the manual
whatis shows what the command does
alias/unalias simplifies commands, like defining variables
exit self explanatory


