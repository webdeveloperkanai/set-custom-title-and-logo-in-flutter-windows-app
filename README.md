# Set custom title and logo in flutter windows app

![image](https://user-images.githubusercontent.com/70555095/172548461-94884036-8262-4551-a0f9-208a2f7de8da.png)

You can see here I have changed Windows title and Icon both. 

## How to do 
### Step 1
Goto windows/runner/main.cpp and search for window.create function. This looks like 

![image](https://user-images.githubusercontent.com/70555095/172548735-65792e77-16f7-4b71-b96f-34508280945b.png)

Just change text in double qutation and save this file. This will change your weindow title.

### Step 2 
Goto windows/runner/resources/app_icon.ico and resplace app_icon.ico with your icon image file.

Just recompile application. It will change title and icon. 

## Follow for more updates on https://devsecit.com 
### Kanai Shil - DEV SEC IT Pvt. Ltd.
