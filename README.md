# Flatboard v1
Flatboard is a project template folder structure. It's designed to be used for projects which do not use any type of automated version control. Instead, version control and revisions are manually managed. 

Flatboard creates a "flat" folder interpretation of workflow concepts such as branching, tagging, releasing, versioning and revisioning.

   

### Basic usage
#### Cue-folder
Folders with names wrapped in curly brackets are called *cue-folders*. They denote format, naming conventions, and arguments with which to name folders with, which reside in the same folder as the cue-folder.

#### Cue-folder-template
Cue-folders which end in an underscore indicate that there are subfolder cue-folders nested inside of the cue-folder, we refer to them as *cue-folder-templates*. These type of folders are used for creating empty starting point directory structures. To use, copy and paste the folder, name the pasted folder accordingly.

[ a working draft ]

   

### Naming versions
#### Parent-position-compatible
*Parent-position-compatible* is the term Flatboard uses to refer to a convention for naming versions, in which the name denotes its compatibility with previous versions. 

The rule:   
**The number right of a decimal must be compatible with the number left of that decimal.**

For example:   
v1 is always compatible with v1.1, v1.2, v1.3, etc.  
v1.1 though may **not** be compatible with v1.2, v1.3, v1.4, etc.  
v1.1 is compatible though with v1.1.1, v1.1.2, v1.1.3, etc.  

   

### Syntax meanings for labels
###### Double dashes ( -- ) 
"is a" relationship

###### Double underscores ( __ )
label delineator; can denote any relationship other than "is a", ie. has a, is for, uses a, is part of.
