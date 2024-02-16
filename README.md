Terminal screenshot tool, which takes the 
console output and renders an output 
image that resembles a user interface
window. The idea is similar to what
carbon.now.sh, instaco.de, or 
codekeep.io/screenshot do. Instead of 
applying syntax highlight based on a 
programming language, termshot is using
the ANSI escape codes of the program 
output. The result is clean screenshot (or 
recreation) of your terminal output. If you
want, it has an option to edit the program 
output before creating the screenshot.
This way you can remove unwanted 
sensitive content. Like time, watch, or 
perf, just place termshot before the 
command and you are set.

For example, termshot --show-cmd -- 
lolcat -f <(figlet -f big foobar) will 
create a screenshot which looks like this:
