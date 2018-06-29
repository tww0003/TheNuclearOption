# The Nuclear Option
When workin on macOS, Eclipse will occassionally set a flag on a project that makes the project frustraitingly difficult to remove. Even `rm -rf` won't be able to remove the project. This shell script will remove that flag and nuke the project.  
  
##Installation  
  
1. Clone down the script and give it permission to run with `chmod a+x nuke`  
2. Add the file to your path.  
  
## Example Usage  
  
    # Using the nuclear option
    tyler:Projects tylerww$ nuke eclipse_project/
    Are you sure you want to use the nuclear option? (y/n) y
    done
    tyler:Projects tylerww$  
    
    # Aborting the mission
    tyler:Projects tylerww$ nuke eclipse_project/
    Are you sure you want to use the nuclear option? (y/n) n
    Mission aborted
    tyler:Projects tylerww$  
	  
##License  
Copyright (c) 2018 Tyler Williamson Licensed under the WTFPL license.
