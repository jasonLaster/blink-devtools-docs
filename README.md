# Blink DevTools Docs 

The DevTools frontend is an amazing application and well architected source. 

The only problem is that, its internals are not well documented. I'm putting together these 
docs so that I can better understand what is going on. 


## Shape of the notes
The notes are beginning to look like a spec, where class functions and properties are documented.
I'll try to provide some top-level explanations where I think i understand what's going on.

## Files
Many of the devtools files are thousands of lines long and include several large classes. 
To simplify things and make classes more discoverable, I've split many of the classes into their own files.
Where I did that, I created a folder for the namespace of the class and added the file in the folder.

## Plans
I don't plan on creating the comprehensive docs for devtools. There are several reasons for this
1) devtools is primarily an application and as such won't be extended in the same ways as library code
2) devtools is an active project and a large codebase, I can't make any promises that it'll be kept up to date or will ever be comprehsinve
