# Weight-Converter
A simple and light-weight python program which can convert the input in lbs into kg and vice versa

# Convert this program to an app
Let's see how can we convert this program to an app

# Step 1. Install the necessary libraries
We need to install pyinstaller for this.
To install pyinstaller, run the following code in your command prompt or terminal :
 pip install pyinstaller

# Step 2. Clone this file
Next we need to clone this github repository.
For that, run the following code in your command prompt or terminal :
 git clone https://github.com/JairoJosy/Weight-Converter.git
 
# Step 3. Opening PowerShell
Now we are going to convert our python file into an app
For that go to the directory which we have just cloned.
Next, right click somewhere in the folder and from the drop-down menu select 'Open PowerShell window here'.

# Step 4. Converting the file
In the powershell windows type : pyinstaller --onefile -w 'weight-converter.py'
If the above command gives you an error such as:"pyinstaler: the term 'pyinstaller' is not recognized as the name of a cmdlet............................", then, instead of the above command type : .\pyinstaller --onefile -w 'weight-converter.py'

For any error saying 'missing packages' type: pyinstaller --hidden-import 'package_name' --onefile 'weight-converter.py'

# Step 5. Success
After typing the command ‘Hit the Enter’. 
It will take some time to finish the process depending on the size of the file and how big is your project. 

You can find the .exe file in the same directory

