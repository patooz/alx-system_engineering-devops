alias ls="rm *" - a script that creates an alias.
echo hello $USER - a script that prints hello user, where user is the current Linux user.
export PATH="$PATH:/action" - Add /action to the PATH. /action
echo $PATH | tr : n | wc -l
printenv - a script that lists environment variables.
set - a script that lists all local variables and environment variables, and functions.
BEST="School" - Create a script that creates a new local variable.
export BEST="School" - a script that creates a new global variable.
echo $((128+TRUEKNOWLEDGE)) - a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
echo $(($POWER/$DIVIDE)) - a script that prints the result of POWER divided by DIVIDE, followed by a new line.
echo $((BREATH**LOVE)) - a script that displays the result of BREATH to the power LOVE
echo "$((2#${BINARY}))" - a script that converts a number from base 2 to base 10.
echo {a..z}{a..z} | tr   n | grep -v oo - a script that prints all possible combinations of two letters, except oo
