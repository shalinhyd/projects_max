# projects_max
# this scripts are made to view .sh files exits,work or not.

touch shalin_file 

touch sample.txt 

vi sample.txt

This is a sample

:wq

touch script00.sh

chmod +x script00.sh

vi script00.sh

if [ -f /tmp/sample.txt ]; then

echo "exist"

else

echo "not exist"

fi

:wq

touch boom_file

touch line.txt

vi line.txt

This is line one 

This is line two 

This is line three ,

This is line four ,

:wq

touch script.sh

chmod +x script.sh

vi script.sh

if [ -f  /tmp/line.txt ]; then

 echo  "This is line one";
 
 echo  "This is line two";
 
 echo  "This is line three";
 
 echo  "This is line four" ;
 
 else 
 
 echo "error in the lines " 
 
fi

touch numbers.txt

vi numbers.txt

2

4

6

8

:wq

touch script1.sh

chmod +x script1.sh

if [ -f /tmp/number.txt ]; then

echo "2"

echo "4"

echo "6"

echo "8"

else

echo "error with numbers"

fi




