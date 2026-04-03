Tools
ShareX Configuration
Click here to download the easy setup file if you're running ShareX 11.5 or greater.
Click here to see the ShareX config if you're running a version less than 11.5.
API
The API is located at https://litterbox.catbox.moe/resources/internals/api.php
There is only 1 request type for Litterbox - fileupload. All uploads are anonymous (you don't need an account/userhash).
File uploads
File Uploads
reqtype="fileupload" time="1h/12h/24h/72h" fileToUpload=(file data here)
cURL to API
If you want to make curl requests to the API, here is an example. Allowed values for "time" are 1h, 12h, 24h, and 72h.
curl -F "reqtype=fileupload" -F "time=1h" -F "fileToUpload=@cutie.png" https://litterbox.catbox.moe/resources/internals/api.php
If you have any questions or have created something, email me.