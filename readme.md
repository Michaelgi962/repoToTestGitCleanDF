# Intro

The purpose of this git repo is to test the functionality of the 'git clean -df' command

Supposedly, the 'git clean -df' command deletes all unstaged modified, unstaged newly created files, and unstaged newly created folders beyond the last commit

# Body

## Test A 

### is a newly created file and folder deleted and are the modifications made to an existing file removed when using the 'git clean -df' command?

create fileA -> commit -> modify fileA -> create fileB -> create folder -> use 'git clean -df' command -> was the modification removed and was the newly created file and folder deleted?

__No, the unstaged and modified existing file was not deleted, and yes, the newly created file and folder were deleted.__

## Test B

# Is a newly created and modified unstaged file deleted?

create file -> modify file -> use 'git clean -df' command -> was the file deleted?

__Yes, the newly created and modified unstaged file is deleted.__

# Conclusion  

_The 'git clean -df' command deletes all unstaged newly created files and all unstaged newly created folders._
