Steps to Install and Activate
Open Command Prompt as Administrator

Copy the path to the folder with the downloaded files

Navigate to the folder using the copied path

cmd
Copy
cd "Copied_Path"
Run the setup command

cmd

```setup.exe /configure configuration.xml```
After installation completes, open PowerShell as Administrator

Execute the activation command

powershell


```irm https://get.activated.win | iex```
A window will appear—select option 5

Then choose option 2

Done! It should now work.

Notes:
Replace "Copied_Path" with the actual path to your files.

Be cautious when running scripts from the internet (irm = Invoke-RestMethod). Ensure the source is trusted.

Let me know if you need any modifications!