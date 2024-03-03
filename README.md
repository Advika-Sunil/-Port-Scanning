Deliverables

-	The script only accepts input of the appropriate format (e.g. if asked for a host - alphanumeric inputs, if a number - numeric only)

-	This script is interactive with the user and displays appropriate descriptive message if any of the normal query parameters have been passed to it (e.g. -h, --help, --version) 

-	The script provides the user with sufficient messages to lead them through the interactive session, as well as providing error messages when appropriate. 

-	Overall, it gives closed/open/filtered type of feedback.
  
-	The script will take three arguments
1-	Target domain(string)
2-	Starting value (numeric 0-1000)
3-	Ending value (numeric 0-1000)
 
-	In interactive mode, the script will ask the user for their target and store that value in a variable. It will then ask for two numbers: a starting port (between 0 and 99) and an ending port (between the starting number and 99). 

-	It captures and addresses any and all errors in the code, sending messages to the user when appropriate. 


-	The script will create sockets with the target domain name and port numbers and print the port status in colors.

python3 scanhost.py --help
  
![image](https://github.com/Advika-Sunil/Port-Scanning/assets/162045609/955a4b02-c31b-4eb1-a7e6-f8dd9632e31a)

python3 scanhost.py --version

![image](https://github.com/Advika-Sunil/Port-Scanning/assets/162045609/258a6373-3dea-4ae0-88a4-a562809a3f44)

python3 scanhost.py 

![image](https://github.com/Advika-Sunil/Port-Scanning/assets/162045609/95fee565-2f35-43c4-809c-78d1f507c943)

