# replace-script
The replace script should look recursively through the given path (that is, in all files and directories, and in directories beneath those) for any filename and/or file contents that match oldpattern and replace it with newpattern.

Make sure to make the files executable if needed.

# run-test
The run-test script creates or deletes a series of directories then two java files to be use the replace-script file on. 

# Syntax
run-test: ./run-test [teardown | setup]

replace: ./replace [PATH OLDPATTERN NEWPATTERN] 
