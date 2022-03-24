## This is a demo how to create JOB in jenkins ##

Step 1 : Browse for  "install jdk 8"
step 2 : Download and install it.

## set up the path in the environment variable ##
 step 1:  In system properties > advance tab > click on environment variable.
 step 2:  In system variables copy the path from  jdk & jre folder to java_home & jre_home
 step 3:  Set up the bin folder for jdk in path variable 
 step 4:  To check java is installed, open CMD & run java -version
  
## Install jenkins ##

 step 1: Browse for "install jenkins" 
 step 2: Download LTS >windows
 step 3: Unzip the downloaded file 
 step 4: Run exe file
 step 5: Go to your browser and type localhost:8080 (default port)
 step 6: Create username & password for jenkins (follow the on-screen instructions) 

## Create a job in jenkins ##
 
 step 1: In jenkins dashboard ,select new item
 step 2: Enter an item name & selete freestyle project > ok.
 step 3: In General > description as: "This is my first Jenkins job"
 step 4: In Build > select 'Execute windows batch command' and input: echo "hello this is my first jenkins demo : %date% : %time% "
 step 5: Apply & save.
 step 6: Select build now > click on build history that appears.
 step 7: To see the output select console output.
