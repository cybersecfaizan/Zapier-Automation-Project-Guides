# Automatically Save Gmail Attachments to Google Drive 📧

[![download-4.jpg](https://i.postimg.cc/5NtLD4kH/download-4.jpg)](https://postimg.cc/Jt9skL8m)

&nbsp;

## Objective  

This guide explains how to set up an automation in **Zapier** to save email attachments from your **Gmail** account directly to a **Google Drive** folder named **Gmail Attachments.** This automation will help ensure that important files are always backed up and easily accessible in your **Google Drive**.

This task involves creating a **Zap** in Zapier, where a specific trigger (receiving an email with an attachment) will initiate an action (saving the attachment to **Google Drive**). Once set up, this automation will run seamlessly in the background, saving you time and effort.

## Business Use Cases

Automatically saving Gmail attachments to Google Drive offers a range of business benefits for teams in various departments. For instance, accounting departments can streamline invoice and receipt archiving by ensuring all financial documents received via email are automatically organized and securely stored in a dedicated Google Drive folder. Similarly, sales teams can enhance collaboration by automatically saving client proposals and quotes to a shared folder. In a customer support context, automating the storage of email attachments like screenshots or logs into organized folders improves response times and accuracy.

## Step 1: Setting up the Trigger

First, log in to Zapier and click on the **Create** button.

&nbsp;

[![image15.png](https://i.postimg.cc/RZQTqh5C/image15.png)](https://postimg.cc/18XFj93b)

From the drop-down menu, select **Zap.** A **Zap** is a workflow that connects your apps to automate tasks.

&nbsp;

[![image16.png](https://i.postimg.cc/nz54NQ72/image16.png)](https://postimg.cc/KkP3Mj03)

In the **Trigger** box, search for and select **Gmail.** This will populate the App field with the Gmail app. The **trigger** is what initiates your **Zap.** Triggers are useful because they allow you to automate repetitive tasks without manual intervention. By defining a specific event as a trigger, you ensure that whenever that event happens, the necessary actions are executed automatically.

&nbsp;

[![image6.png](https://i.postimg.cc/VkRjmhnd/image6.png)](https://postimg.cc/3kkyZnLT)

Next, click on the **Trigger Event** box and from the dropdown select **New Attachment.** This trigger will cause the **Zap** to run whenever a new email with an attachment is received in your **Gmail** account.

&nbsp;

[![image11.png](https://i.postimg.cc/K8yNZLWs/image11.png)](https://postimg.cc/hfpxsJc9)

If this is your first time using **Gmail** with **Zapier,** you'll need to connect your **Gmail** account. Click on the **Account** field and enter the Gmail address you'd like to set up this automation with. Follow the prompts to authorize **Zapier** to access your **Gmail** account.

&nbsp;

[![image9.png](https://i.postimg.cc/9Mv9LH5N/image9.png)](https://postimg.cc/KkD4YVYn)

After connecting your account, you will now configure the trigger. You can specify any conditions, such as filtering emails from specific senders or with certain subject lines. Since we're saving attachments from all emails, leave these fields blank and click **Continue**, where we'll be taken to the **Test Tab** of our trigger.

&nbsp;

[![image13.png](https://i.postimg.cc/TPtqqs3Z/image13.png)](https://postimg.cc/zLRgq0Wj)

Click on **Test Trigger** to ensure everything is working correctly. **Zapier** will pull in the most recent email with an attachment from your **Gmail** account.

&nbsp;

[![image17.png](https://i.postimg.cc/T1DVxYJ6/image17.png)](https://postimg.cc/bSqDHP5C)

Testing in **Zapier** ensures that the configured steps are accurate, allowing for any necessary adjustments before proceeding to the subsequent triggers and actions in the workflow.

In this case, Zapier will pull in the most recent email with an attachment from your Gmail account. If everything has been set up correctly up until now, you should see this:

&nbsp;

[![image18.png](https://i.postimg.cc/mZzNC8f5/image18.png)](https://postimg.cc/23YZfd5Q)

Notice how **Test** has a green check mark next to it. This indicates that the test was successful and that you’re now ready to move on to setting up **Actions**.

## Step 2: Set Up the Action

After testing the trigger, click on the **Action** box. In the pop-up menu, search for and select **Google Drive.**

[![image1.gif](https://i.postimg.cc/SNL9fPZD/image1.gif)](https://postimg.cc/3dRWKtQv)

An action is a task that your automation performs when it's triggered by a specific event. After the trigger initiates the Zap, the action is the step where something actually happens as a result. Actions can include sending an email, creating a document, updating a spreadsheet, or uploading a file. It carries out the task we’d like to automate, in this case saving email attachments to a Google Drive folder.

In the **Action Event** dropdown in the **Setup** tab, select **Upload File.** This action will save the email attachment to your specified **Google Drive** folder.

&nbsp;

[![image2.png](https://i.postimg.cc/gcCyD8Gk/image2.png)](https://postimg.cc/9zBqX44v)

Now, ensure the account field is populated with the same **Google** account you connected in the trigger setup. Click **Continue** to move on to the **Configure** Tab.

&nbsp;

[![image12.png](https://i.postimg.cc/1zmrFSsG/image12.png)](https://postimg.cc/mPn9x0ck)

Now, click on the **Drive** field and select **My Google Drive** from the menu.

&nbsp;

[![image3.png](https://i.postimg.cc/BQ2Twbv5/image3.png)](https://postimg.cc/zVXHyJK3)

Next, in the folder field, select the folder where you’d like to store the attachments from emails. In my case, I’m going to select the folder named **Gmail Attachments.**

&nbsp;

[![image7.png](https://i.postimg.cc/Bv7H11h3/image7.png)](https://postimg.cc/t1PYK7Qv)

Finally, click on the **+** symbol in the **File** box and choose **Attachment (Exists but not shown).**

&nbsp;

[![image5.png](https://i.postimg.cc/43xpd1Qw/image5.png)](https://postimg.cc/68F8bnSG)

From here, click the **Continue** button.

&nbsp;

[![image4.png](https://i.postimg.cc/bw8xXPG7/image4.png)](https://postimg.cc/4mL7trQP)

You should now be at the **Test** tab. Click on **Test Step** to test your Zap.

&nbsp;

[![image14.png](https://i.postimg.cc/G29PMjB9/image14.png)](https://postimg.cc/47khyVQT)

If your test was successful, there should be a green check mark next to **Test**, and the publish button should appear at the bottom of the **Action** window. Click on it to publish your Zap, which will make it go live.

&nbsp;

[![image10.png](https://i.postimg.cc/fym9FqMW/image10.png)](https://postimg.cc/dZQ3ZB7g)

## Conclusion

**Congratulations!**

Your **Zap** is now active. All email attachments sent to the chosen email will be automatically saved to your selected folder in **Google Drive.**

To verify the setup, send yourself an email with an attachment and check if it appears in the **Google Drive** folder you've designated. This automation will now run continuously, ensuring your email attachments are securely stored in **Google Drive.**