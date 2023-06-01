`type aws configure`
add in a cli-enabled security key from iam

**Step 1:** Open the IAM Console

First, log into your AWS Management Console. Then, navigate to the IAM console by typing "IAM" into the service search bar and clicking on "IAM".

**Step 2:** Access the Users Section

In the IAM console, click on "Users" in the navigation menu on the left side of the screen.

**Step 3:** Select the User

Find the IAM user that you want to create a new Access Key for, and click on the user's name.

**Step 4:** Create a New Access Key

Click on the "Security credentials" tab. Then, find the "Access keys" section and click on the "Create access key" button.

**Step 5:** Download or Copy the Access Key

A pop-up window will appear containing the Access Key ID and Secret Access Key. Be sure to record these in a secure location - you will not be able to view the Secret Access Key again. If you wish, you can download the Access Key ID and Secret Access Key as a .CSV file.

then run `make sync_data_to_s3`

