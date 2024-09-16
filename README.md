# rlb-ftp-http-server-sfn
Setup a Brightsign device as a ftp/http web server for Simple File Networking / Web Folder publishing

### Who would want to use this application?:
- Users who don't know or can't be bothered to setup a HTTP web server for Simple File Networking / Web Folder Publishing

### How to get started:

1. Download and unzip the content of rlb-ftp-http-server-sfn.zip file to a blank SD card.
2. Modify the autorun.brs file so it includes the required static network settings for the server

<img width="934" alt="image" src="https://github.com/user-attachments/assets/19e6f598-8f44-4157-8c8d-a913001ff340">

3. Insert the SD card with the unziped file in a Brightsign device (whilst the power connector is unplugged)
4. Insert the power connector in the player and wait for the Brightsign device to display at the top of the screen the URL for the group1 folder on the HTTP web server

<img width="827" alt="image" src="https://github.com/user-attachments/assets/ab0342ee-80a6-4479-bd2c-827cb56026db">

5. In a web browser enter the equivalent URL for your Brightsign Device "http://player-ip-address:3000/set-credentials to set a username and password for the ftp server and click on the "Set Credentials" button

<img width="454" alt="image" src="https://github.com/user-attachments/assets/9db4a967-0650-4711-a1da-9c79ec4220bd">

6. Create a BrightAuthor Presentation and publish it using the "Web Folder" publishing method 
7. Click on the "Schedule" tab, select under "Destination" "Type" > "Web Folder" > "FTP Site"

<img width="1130" alt="image" src="https://github.com/user-attachments/assets/5bdfbcaa-2052-4962-b459-7cf023448f5a">

8. Click on the "+" sign next to "Select Location"
9. On the Add FTP Location panel Select "FTP" for the "Protocol"
10. Enter the Brightsign device IP address (same IP address that you would have entered in step 2)
11. Enter the Username and Password that you have set in step 5
12. For "Remote Path" enter "/group1". Please note that you can use folders from /group1 to /group10 to publish different content to different groups of players
13. Click on "Submit"

<img width="968" alt="image" src="https://github.com/user-attachments/assets/a2aecea8-3cb9-4d9c-9da8-6ec701da0104">

14. Under "Options" > "Player Configuration" > "URL for Web Folder" enter the URL that is displayed on the player screen (also mentioned on Step 4), then click on the "Publish" icon to publish the presentation onto the HTTP web server using the FTP protocol. 

<img width="1342" alt="image" src="https://github.com/user-attachments/assets/40856605-4503-4795-8f74-11aca4931db5">

If it all went as expected the player should take 5 minutes before checking if there are any new content published to the HTTP web folder then download the new content to finally start playback of the newly published content!

**Disclaimer: Use at Your Own Risk**

The software provided is offered "as-is," without any warranties or guarantees of any kind, either express or implied. By using this software, you acknowledge and agree that any reliance on the information, functionality, or services provided is solely at your own risk. 

The developers and publishers of this software do not assume any responsibility for any damages, losses, or negative consequences that may arise from its use, including but not limited to data loss, system failures, or any other issues that may occur. 

It is your responsibility to ensure that you have proper backups and safeguards in place before using this software. By continuing to use this software, you agree to indemnify and hold harmless the developers and publishers from any claims or damages arising out of your use of the software.

If you do not agree with this disclaimer, you should refrain from using the software.




   




    
