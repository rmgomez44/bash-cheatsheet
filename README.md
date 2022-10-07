# bash-cheatsheet
simple + medium complexity tasks in command line 


#### OneLiner to Create a directory if doesnt exist
dirname=thumbnails
[[ -d ${dirname} ]] && echo "${dirname} found" || mkdir ${dirname}
