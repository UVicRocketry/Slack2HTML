
# Instructions for SlackUP process:

Note (Because of Slack the only people able to perform an Export of the teams data are the admins)
Instruction on how to export: https://get.slack.help/hc/en-us/articles/201658943-Export-your-team-s-Slack-history

1.	Start your Slack Export which will give you a folder of json files
2.	Download Xampp with php (unless you already have a php compiler installed)
    Download for Xampp:  https://www.apachefriends.org/download.html
3.	Put the php script “slack2html.php” inside your export folder. 
4.	The next step has 2 options:
    1.	Add  “C:\xampp\php” to your environment PATH 
        Then in the export folder type “php slack2html.php”
    2.	Go in the export folder and type C:\xampp\php slack2html.php
5.	The php script should generate all your html files in a folder named slack2html in the directory that your export folder is contained. (1 UP)
6.	Once you have your html files, upload them to the SlackUP drive in a folder named after the date of your backup.
