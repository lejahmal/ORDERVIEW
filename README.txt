installation 

Here's a step-by-step guide:

............................................................Install Java:......................................................................

 depending of your computer settings for X64 install 
jdk-8u381-windows-x64
jre-8u381-windows-x64
or Download JDK and JRE from the Oracle website.

instructions.
Locate the Java Installation Directory:

Typically, it's in C:\Program Files\Java\jre-x.x.x, where x.x.x is the version number.


..................................................Set the JAVA_HOME Environment Variable: ..................................................

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
In the "Variable name" field, type: CLASSPATH In the "Variable value" field, paste the path to your JRE installation directory. it will be C:\Program Files (x86)\Java\jreX\lib\ext\QTJava.zip
 Click "OK" 


...................................................to save and Edit the System Path Variable:.....................................................

Find the Path Variable: In the same "Environment Variables" window, 
find the "Path" variable under "System variables" and 
click "Edit."

Add the JRE bin Directory:

Click "New" and paste the path to your JRE's bin directory. This is usually C:\Program Files\Java\jre-x.x.x\bin.

Click "OK" to save the changes.


.....................................................Optional: Verify the Installation:............................................................


Open a new command prompt window.

Type java -version and press Enter.

If the JRE is installed correctly, you should see the Java version information.


.......................................................  install ORDERVIEW and folders ............................................................. 

create a Directory C:\OrderView
locale your OrderView.exe file 
double click to open

...........................................Example of how to create offline and plot data in orderview to get chart ................................


in this directory C:\OrderView add manually .txt file for example create CAC40.txt

With YAHOO FINANCE
go to yahoo https://finance.yahoo.com/quote/%5EFCHI/history/ using mozilla firefox browser
click "Toggle reader View" button in mozilla firefox toolbar 
copy all data using Ctrl+A and Ctrl+C and paste it into CAC40.txt file 
REMOVE THE LAST EMPTY LINE AFTER COPY ALL DATE IN THE FILE
remove all header stuff in the data you have copy and replace it by a single line containing word "Data"
file will look something like this

Data
Nov 18, 2024 	7,274.40 	7,289.78 	7,234.59 	7,278.23 	7,278.23 	-
Nov 15, 2024 	7,256.58 	7,319.53 	7,236.48 	7,269.63 	7,269.63 	66,901,200
Nov 14, 2024 	7,247.92 	7,319.09 	7,220.05 	7,311.80 	7,311.80 	71,041,000
Nov 13, 2024 	7,217.49 	7,256.47 	7,158.25 	7,216.83 	7,216.83 	62,925,600
Nov 12, 2024 	7,346.72 	7,365.28 	7,217.78 	7,226.98 	7,226.98 	78,448,900
Nov 11, 2024 	7,395.09 	7,452.60 	7,387.52 	7,426.88 	7,426.88 	-
Nov 8, 2024 	7,440.12 	7,440.95 	7,330.21 	7,338.67 	7,338.67 	67,218,200



with INVESTING.COM
go to https://www.investing.com/indices/france-40
click "Historical Data" on the "General" tab section 
keep times frame "Daily" edit the date interval depending to your need 
copy all data using Ctrl+A and Ctrl+C and paste it into CAC40.txt file
remove all stuff in the data you have copy that are not data formated and replace the first line by word "Data"
file will look something like this

Data
Jun 05, 2025	7,837.34	7,811.18	7,838.88	7,802.82	9.23M	+0.42%
Jun 04, 2025	7,804.67	7,795.06	7,843.21	7,779.36	60.84M	+0.53%
Jun 03, 2025	7,763.84	7,752.28	7,765.46	7,699.24	58.27M	+0.34%
Jun 02, 2025	7,737.20	7,714.91	7,744.28	7,668.90	59.19M	-0.19%
May 30, 2025	7,751.89	7,776.04	7,811.49	7,747.90	126.16M	-0.36%
May 29, 2025	7,779.72	7,866.77	7,869.92	7,779.72	38.40M	-0.11%
May 28, 2025	7,788.10	7,825.42	7,853.66	7,787.58	59.92M	-0.49%


save all change 
open ORDERVIEW APP Again
go to " FIND NEW ASSET HERE " button type the name of the file you wnat to plot chart for example CAC40
click ENTER on your keyboard or the search button in app to plot candlestick chart 

enjoy

