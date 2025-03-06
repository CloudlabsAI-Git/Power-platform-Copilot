# Module 1: Create a canvas app with Copilot in Power Apps

## Lab Scenario

In this exercise, you'll take on the role of a software developer tasked with creating a user-friendly canvas app using Power Apps Copilot. Your objective is to build an app designed to manage customer information effectively. Start by using Copilot to quickly generate a table with essential columns such as Customer ID, Full Name, Email, and Phone Number. Then, populate the table with sample data and make necessary adjustments, such as modifying column data types. Finally, design the app's interface to display and interact with the data, test its functionality, and publish the app for user access. This lab will showcase how Power Apps Copilot can streamline app development and enhance productivity.

## Lab objectives

In this lab, you will complete the following tasks:

- Task 1 – Create Power Platform environment.
- Task 2 - Create an app with Copilot.
- Task 3 - Make edits using Copilot to edit your app.


### Task 1 – Create Power Platform environment

 In this task, you'll create and configure a new Power Platform environment to support app development and deployment. You'll set up essential details and adjust settings to meet your organizational needs.
 
1. In the new browser tab, navigate to the **Power Platform admin center** by visiting `https://aka.ms/ppac`.

2. On **Sign into Microsoft Azure** tab you will see login screen, in that enter following email/username and then click on **Next**. 
   * Email/Username: <inject key="AzureAdUserEmail"></inject>

      ![screenshot of the prompt ](../Media/image7.png)

3. Now enter the following password and click on **Sign in**.
   * Password: <inject key="AzureAdUserPassword"></inject>
   
      ![screenshot of the prompt ](../Media/image8.png)

   * Select **Next** on the **Action Required** prompt, and follow the below steps:

      1. On the **"Keep your account secure"** page, select **Next** twice.

      1. **Note:** If you don’t have the Microsoft Authenticator app installed on your mobile device:

         - Open **Google Play Store** (Android) or **App Store** (iOS).
         - Search for **Microsoft Authenticator** and tap **Install**.
         - Open the **Microsoft Authenticator** app, select **Add account**, then choose **Work or school account**.

      1. A **QR code** will be displayed on your computer screen.

      1. In the Authenticator app, select **Scan a QR code** and scan the code displayed on your screen.

      1. After scanning, click **Next** to proceed.

      1. On your phone, enter the number shown on your computer screen in the Authenticator app and select **Next**.
            
      1. If prompted to stay signed in, you can click "No."
      
      1. If a **Welcome to Microsoft Azure** pop-up window appears, simply click "Maybe Later" to skip the tour.

      >**Note**: Close the welcome tour prompt. 

4. In the site navigation, click on **Environments**, then click **+ New** on the toolbar.

   ![screenshot of the prompt ](../Media/env-(1).png)

5. Create a new Environment with the following settings:

   - **Name**: **Copilot (1)**
   - **Group**: **None (2)**
   - **Region**: **United States - Default (3)**
   - **Type**: **Sandbox (4)**
   - **Add a Dataverse data store?**: **Yes (5)**
   - Keep all other settings unchanged, Click on **Next (6)**. 
  
      ![screenshot of the prompt ](../Media/copilot-final-1-1-1.jpg)  
 
6. On the **Add Dataverse** tab, under **Security Group**, click the **+ Select** button. Then, under **Open Access**, choose **None (1)** and click **Done (2)**.

   ![screenshot of the prompt ](../Media/select-2.jpg)

7. Select **Save (2)**, on the **Add Dataverse** prompt.

   ![screenshot of the prompt ](../Media/non-1.png)
 
8. In the list of environments, your **Copilot** environment should now show as **Preparing**.

   ![screenshot of the prompt ](../Media/copilot-env-1.png)

      >**Note**:Your practice environment will take a few minutes to provision. Refresh the **Environments** list if needed.
 
9. When your environment shows as **Ready**, select your **Copilot** environment by selecting the ellipses next to the name to expand the drop-down menu and select **Settings**.
 
      >**Note**: Browse through the various sections under **Settings** that interest you, but refrain from making any modifications.

## Task–02: Create an app with Copilot.

In this task, you'll use Power Apps Copilot to quickly create a canvas app, including generating and populating tables with data. You'll then design the app interface and test its functionality.

1. Open a new browser tab and navigate to [https://make.powerapps.com](https://make.powerapps.com) to access Power Apps.

   >**Note:** Make sure you are in the **Copilot** environment that you created in the previous task.

      ![screenshot of the prompt ](../Media/copilot-(1).png)

1. On the **Power Apps** portal, from the left navigation menu, select **Apps (1)**. Now, inside the Apps pane, select **Start with data (2)** option.

   ![screenshot of the prompt ](../Media/powerapps(1).png)

1. On the **Start with data** page, Enter the following prompt to search for an AI-generated table **build an app to manage real estate showings (1)** , Select the **Send (2)** button.

   ![screenshot of the prompt ](../Media/describe-data-start.png) 

   >**Note:** Select **Got it** on the pompt.

1. It will generate three tables: **Property**, **Agents**, and **Showings**. However, we only need a single table named **Real Estate Showings**, which includes all three. To do this, select **Table Options** under the Copilot pane.

   ![screenshot of the prompt ](../Media/power-apps(2).png)

1. Under **Table options**, select **One table (1)** and then click **Apply (2)**. This will generate the required table for this lab.

   ![screenshot of the prompt ](../Media/table-options(1).png)

   ![screenshot of the prompt ](../Media/newtableshwings.png)

1. Once Copilot AI generates a table based on your prompt, review the tables to see the columns that have been created initially.

   ![screenshot of the prompt ](../Media/build-answer.png)

1. In the text box at the bottom of the Copilot pane on the right side of the screen, type the following text: **add a column to track client full name**. Then, click the Send button.

   ![screenshot of the prompt ](../Media/clientfullname(1).png)

   >**Note**: Copilot notifies you that the table is updated, and the new column should show as being added to the tables.

1. If you want to check the data or columns of the table, select the **ellipses (1)** icon on the **Real Estate Showing** table and choose **View data (2)**. From here, you can rename, delete, update, and add the required columns.

   ![screenshot of the prompt ](../Media/viewdata(1).png)
   
1. Enter the following text: **add a column to track client email**. Then, click the Send button.

   >**Note**:
   - The data that's generated in your table might vary from the data that's shown in the table in the screenshots for this lab.
   - The Suggestions section in the lower-left corner of the screen provides you with different suggestions on how you can add to and modify your table.

1. Enter the following text:	**add an option for “Completed” to the Status column**. Select the Send button.

   ![screenshot of the prompt ](../Media/status-completed.png)

1. Enter the following text in the Copilot pane text box: **add 5 more rows of data in all the three tables**, Click Send. This action will insert five new rows of data for each existing column in your table.

    ![screenshot of the prompt ](../Media/power-apps(3).png)

1. In the text box, in the lower part of the Copilot pane to the right of the screen, enter the following text: **add a column to track Client Address**. Select the **Send** button. 

   ![screenshot of the prompt ](../Media/client-address-09.png)

1. In the text box, in the lower part of the Copilot pane to the right of the screen, enter the following text: **add a column to track ID**. Select the **Send** button. 

1. Select the **ellipses (1)** icon on the **Real Estate Showing** table and choose **View data (2)**.

   ![screenshot of the prompt ](../Media/viewdata(1).png)

<!-- 1. Select the **ID** column header from the table.	From the dropdown menu, Select the **Edit** column option.
   
   ![screenshot of the prompt ](../Media/01/copilot-edit-column-1.png)
  
1. In this example, you need to change the Data type from "Single line of text." To do this, go to the Edit column pane, select **#Autonumber** from the Data type dropdown menu, then click **Save**. Finally, select the **Close** button in the lower-right corner of the Edit table dialog.

   ![screenshot of the prompt ](../Media/01/save-column-1.png) -->

1. Make sure your table looks similar to the image below.

   ![screenshot of the prompt ](../Media/final-table-2.png)

1. Select **Save and open app** twice to open the app.

      ![screenshot of the prompt ](../Media/saveandapp.png)

      >**Note**: Your table may have several columns. Consider removing any columns that you do not plan to use:The list of columns that you need are: **ID ,	Address , Date , Time , Status , Agent Name, Client Full Name, Client Email.**

      >**Note**: When you first open the app, you might see a welcome message.just click the **Skip** button.

11. The app that has been built for you should show in **Edit** mode.

    ![screenshot of the prompt ](../Media/new-screen-1.png)


## Task–03: Make edits using Copilot to edit your app.

In this task, you'll use Power Apps Copilot to make edits to your app, such as modifying existing elements, adding new features, and adjusting data. Copilot will guide you through streamlining and enhancing your app’s functionality and design.

<!-- 1. In the Data pane on the right side of the **Property** table, click the **ellipsis (three dots)**. From the menu that appears, Choose **Edit** data.

   ![screenshot of the prompt ](../Media/copilot-edit-data.png)

1. Select the **Client ID** column header from the table.	From the dropdown menu, Select the **Edit** column option.
   
   ![screenshot of the prompt ](../Media/01/copilot-edit-column-1.png)
  
1. In this example, you need to change the Data type from "Single line of text." To do this, go to the Edit column pane, select **#Autonumber** from the Data type dropdown menu, then click **Save**. Finally, select the **Close** button in the lower-right corner of the Edit table dialog.

   ![screenshot of the prompt ](../Media/01/save-column-1.png) -->

1. On the **Real Estate Showings screen (1)**, select **RecordsGallery1 (2)** to display Real Estate Showings and then select the **Title1 (3)** and then set the Text value to the following formula: **ThisItem.'Address' (4)**.

   ![screenshot of the prompt ](../Media/realstateshowingsscreen.png)
  
1. Select the **Subtitle1 (1)** and then set the Text value to the following formula: **ThisItem.'Client Email' (2)**.
    
1. Select the **Body1 (1)** and then set the Text value to the following formula: **ThisItem.'Status (statecode)' (2)**

1. A single record in the gallery should now resemble the following image.

   ![screenshot of the prompt ](../Media/finalpoint.png)

1. On the app's main screen, select the **Form control**.

   ![screenshot of the prompt ](../Media/formmaincontrol.png)

1. On the **Form1**, open the **Edit fields (1)** drop-down, expand the **ID (2)** field and under **Control type**, select **View text (3)**.

   ![screenshot of the prompt ](../Media/editfields-01.png)

1. Make a new request for a property that shows in the app by selecting the **Play** button from the upper part of the screen.

    ![screenshot of the prompt ](../Media/01/copilot-play-1.png)

1. In the left pane, select the **+ New** button.

    ![screenshot of the prompt ](../Media/01/copilot-new-1.png)

16. Though you could modify the form to automatically fill in the fields for you, for this lab, you'll complete this step manually to observe how the app works.

    ![screenshot of the prompt ](../Media/ocean-hill.png)

17. Fill in the fields with the following information:

   - Agent Name - < Your name >

   - Client Full Name - < Your name >

   - Client Email - < Your email >

   - Date - < Any future date >

   - Time - < Any future time >

   - Status - Completed

   - Address - 210 Pine Road, Portland, OR 97204

      >**Note** : This address is one of the addresses from the Microsoft Excel file in Module 1, and it's the same file that you uploaded and turned into the Real Estate Properties table.Though you'd usually have a lookup field to the Real Estate Properties table, this lab doesn't provide one to keep it simple.

      ![screenshot of the prompt ](../Media/outputcome.png)

1. Select the check mark in the upper-right corner of the screen.

1. Select the X in the upper-right corner to close out of the app.

   ![screenshot of the prompt ](../Media/closethepane.png)

1. If a dialog appears saying Did you know?, select OK.

1. The new request is added to the left of the list of requests.

1. From the upper part of your screen, select the Save button to save the new app that you created.

      ![screenshot of the prompt ](../Media/copilot-save.png)

1. If the system prompts you, save the app name as Real Estate Showings.

1. Exit the app to return to the Power Apps home page.

## Summary 

In this lab, you have accomplished the following:

- You have set up and configured a new Power Platform environment to support app development.
- You have used Copilot to quickly build a canvas app and add data.
- You have refined and modified the app’s design and functionality with Copilot’s assistance.

