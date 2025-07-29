# File-Management
A beginner file management bash code


#!/bin/bash

read -p "Enter file name:" file_name

if [ -e $file_name ]; then

echo "This file name is already existing. Cannot create file."

else
	
  touch $file_name
 	
  echo "File created succesfully"

fi




