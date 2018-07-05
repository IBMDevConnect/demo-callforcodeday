# Call for Code Day Workshop Steps

## Step 1: Clone the repo

`git clone https://github.com/IBMDevConnect/demo-callforcodeday.git`

## Step 2: Create Action in IBM Cloud Functions

Step 2.1 Click the Hamburger to open the menu

  ![Hamburger](readme-images/1.png)
 
Step 2.2 Select **Functions** from menu

  ![Hamburger2](readme-images/2.png)

Step 2.3 Click **START CREATING** button

  ![Hamburger3](readme-images/3.png)
  
Step 2.4 Select **Create Action**

  ![Hamburger4](readme-images/4.png)

Step 2.5 Enter **Action Name**(copy Action Name in Notepad-required in later steps) and click **Create**

  ![Hamburger5](readme-images/5.png)

Step 2.6 Copy paste the code from [ibm_cloud_functions_code.txt](https://github.com/IBMDevConnect/demo-callforcodeday/blob/master/ibm_cloud_functions_code.txt) and click on Save

![Hamburger6](readme-images/6.png)

Step 2.7 Go back to Functions

  ![Hamburger7](readme-images/7.png)

Step 2.8 Click on **API Key**

  ![Hamburger8](readme-images/8.png)

Step 2.9 Take note of **Current Namespace** and **API Key** (required in later steps)

  ![Hamburger9](readme-images/9.png)

## Step 3: Import documents to Watson Discovery Service

### Step 3.1- Create Watson Discovery Service in IBM Cloud

### Step 3.2- Create collection within Watson Discovery service

### Step 3.3- Import documents into Watson Discovery service

### Step 3.4- Take note of Username,Password,Collection ID and Environment ID of Watson Discovery service

## Step 4: Import Watson Assistant workspace

Step 4.1 Navigate to Catalog > AI > Watson Assistant

![Hamburger9](readme-images/10.png)

Step 4.2 Create Watson Assistant Service

![Hamburger9](readme-images/11.png)

Step 4.3 Launch Tool

![Hamburger9](readme-images/12.png)

Step 4.4 Import Workspace by clicking on Upload icon

![Hamburger9](readme-images/13.png)

Step 4.5 Choose a file and click on Import

![Hamburger9](readme-images/14.png)

Step 4.6 Within Dialog Tab, click on **Anything Else** node

![Hamburger9](readme-images/15.png)

Step 4.7 Within JSON Editor, update **IBM Cloud Functions username, password, namespace and action name** (which was noted in Step 2.5 && Step 2.9 )

![Hamburger9](readme-images/16.png)

Also, update **Discovery service username,password, environment id and collection id** (which was noted in Step)

![Hamburger9](readme-images/17.png)

## Step 5: Try it Out
