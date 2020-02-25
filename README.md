# createBigFile
Quickly creates dummy files for windows

# Usage
Open an elevated CMD.
Place Create Big File.vbs in the directory you want to create files in
Run the Craete Big File.vbs with parameters

# Parameters
/name:filename - filename of the dummy files\
/counts:n - number of dummy files created\
/Kb:n - size in Kilobytes\
/Mb:n - size in Megabytes\
/GB:n - Size in Gigabytes\
/TB:n - Size in Terabytes

# Example
Creates two files, each 5Gb\
"Create Big File.vbs" /name:test /counts:2 /GB:5

@Credit goes to Mattias Fors
