# Windows Commands Cheatsheet

## Commands

### Symbolic links

Create a symbolic, or *soft*, link at `<link>` pointing to the file `<target>`  
`> mklink <link> <target>`  

Use `/D` when you want to create a *soft* link pointing to a directory  
`> mklink /D <link> <target>`  

Use `/H` when you want to create a *hard* link pointing to a file  
`> mklink /H <link> <target>`  

Use `/J` to create a *hard* link pointing to a directory, also known as a directory junction  
`> mklink /J <link> <target>`  


## Glossary
* **Symbolic or Soft Link**
* **Hard Link**


## References
* https://www.howtogeek.com/howto/16226/complete-guide-to-symbolic-links-symlinks-on-windows-or-linux/
