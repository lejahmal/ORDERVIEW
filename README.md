# ORDERVIEW

installation 

Here's a step-by-step guide:



Install Java:

depending of your computer settings for X64 install 
jdk-8u381-windows-x64
jre-8u381-windows-x64
or Download JDK and JRE from the Oracle website.

instructions.
Locate the Java Installation Directory:
Typically, it's in C:\Program Files\Java\jre-x.x.x, where x.x.x is the version number.


........................................Set the JAVA_HOME Environment Variable:..............................................

Open System Properties
Right-click on "Computer" and select "Properties
Click on "Advanced system settings"
Click on the "Environment Variables" button.

Create a New System Variable:
Under "System variables," 
click "New."
In the "Variable name" field, type: JAVA_HOME
In the "Variable value" field, paste the path to your JDK installation directory. it will be C:\Program Files\Java\jdk-x.x.x
Click "OK" 

Create a New System Variable:
Under "System variables," 
click "New."
In the "Variable name" field, type: CLASSPATH In the "Variable value" field, paste the path to your JRE 
installation directory. it will be C:\Program Files (x86)\Java\jreX\lib\ext\QTJava.zip
Click "OK" 


...............................to save and Edit the System Path Variable:.....................................................

Find the Path Variable: In the same "Environment Variables" window, 
find the "Path" variable under "System variables" and 
click "Edit."

Add the JRE bin Directory:
Click "New" and paste the path to your JRE's bin directory. This is usually C:\Program Files\Java\jre-x.x.x\bin.
Click "OK" to save the changes.


...............................................Optional: Verify the Installation:..........................................

Open a new command prompt window.
Type java -version and press Enter.
If the JRE is installed correctly, you should see the Java version information.

......................................  install ORDERVIEW and folders ..................................................... 

create a Directory C:\OrderView
locale your OrderView.exe file 
double click to open

...........................Example of how to create offline and plot data in orderview to get chart .......................


in this directory C:\OrderView add manually .txt file for example create CAC40.txt
go to yahoo https://finance.yahoo.com/quote/%5EFCHI/history/ using mozilla firefox browser
click "Toggle reader View" button in mozilla firefox toolbar 
copy all data using Ctrl+A and Ctrl+C and paste it into CAC40.txt file 
REMOVE THE LAST EMPTY LINE AFTER COPY ALL DATE IN THE FILE
copy this following line header 

Date 	Open 	High 	        Low 	        Close Adj       Close          Adjusted close   Volume

remove all header stuff in the data you have copy and replace it by this previous line . file will look  
something like this

Date 	Open 	High 	        Low 	        Close Adj       Close          Adjusted close   Volume
Nov 18, 2024 	7,274.40 	7,289.78 	7,234.59 	7,278.23 	7,278.23 	-
Nov 15, 2024 	7,256.58 	7,319.53 	7,236.48 	7,269.63 	7,269.63 	66,901,200
Nov 14, 2024 	7,247.92 	7,319.09 	7,220.05 	7,311.80 	7,311.80 	71,041,000
Nov 13, 2024 	7,217.49 	7,256.47 	7,158.25 	7,216.83 	7,216.83 	62,925,600
Nov 12, 2024 	7,346.72 	7,365.28 	7,217.78 	7,226.98 	7,226.98 	78,448,900
Nov 11, 2024 	7,395.09 	7,452.60 	7,387.52 	7,426.88 	7,426.88 	-
Nov 8, 2024 	7,440.12 	7,440.95 	7,330.21 	7,338.67 	7,338.67 	67,218,200

save all change 
open ORDERVIEW APP Again
go to " FIND NEW ASSET HERE " button type the name of the file you wnat to plot chart for example CAC40
click ENTER on your keyboard or the search button in app to plot candlestick chart 

