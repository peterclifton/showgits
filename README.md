# showgits

## Description
A script which searches for and lists git repositories at or below the current working directory.
If desired can indicate which have changes present since the last _commit_.

## Prerequisites 
- Assumes Perl is present
- Assumes Unix style file paths

## Usage 

### Example 1
- Place the script _showgits_ in your user home directory
- Go there `$ cd`
- Make it executable `$ chmod +x showgits`
- Run the script e.g. `$ showgits` or `$ showgits -h` for more details re the options.
- It will look for git repositories within your user home directory

### Example 2
- Place the script _showgits_ in a directory which is in your [PATH](https://wiki.archlinux.org/title/environment_variables#Globally) (you might have a [~/bin](https://stackoverflow.com/questions/20054538/add-a-bash-script-to-path) for example)
- Make it executable
- Run the script from anywhere - it will look for git repositories at or below the current working directory
