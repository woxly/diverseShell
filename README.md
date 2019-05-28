# diverseShell
Make your bash pretty

## Importing the library
- Download the Repo
- Drag the config file into the same directory as your bash script
- Open your bash file that you want to make diverse and add this line to the top
```
source diverseShell.config
````
## Uses the Library
- Most importantly use the Reset
-- This is for cleaning the palette so you don't make everything a little too diverse, yknow
```
reset="${dsRE}"
```
- Change Background Color of text
```
backgroundred="${bRed}"
```
- Change Font/Foreground Color of text
```
fontred="${fRed}"
```
- Change style
-- Bold
-- Dim
-- Underline
-- Blink
-- Invert
-- Hide
```
${dsB}	# Bold/Bright
${dsD}	# Dim
${dsU}	# Underline
${dsBLINK}	# Blink (Doesn't work with most Terminal-Emulators)
${dsIN}	# Invert
${dsHIDE}	# Hidden (useful for passwords)
```
