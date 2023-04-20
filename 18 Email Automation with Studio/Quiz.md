## Quiz Questions

#### Q1. The Send Outlook Mail Message activity will work without having Microsoft Outlook installed.
- [x] False

#### Q2. You are retrieving some Outlook mail messages and you are filtering them using the following expression:
"[Received] >= '" + DateTime.Today.AddDays(-2).ToString("d") + " 00:00AM' AND [Received] < '"+ DateTime.Today.ToString("d") + " 00:00AM'"
 This means that you are looking for...
- [x] All mail messages received in the previous two days.


#### Q3. Review Question - Collections are largely used for handling and processing complex data. Which one of the following is the most encountered collection with a dynamic size?
- [x] List


#### Q4. What is the supported variable type in the Output property field of all Get Mail activities (POP3, IMAP, Outlook, Exchange)?
- [x] List(MailMessage)


#### Q5. If you are using the For Each activity to loop through a list of MailMessage variables, what should you set the TypeArgument property to?
- [x] System.Net.Mail.MailMessage


#### Q6. What activity can you use to send an email without entering the username and password of the email account?
- [x] Send Outlook Mail Message


#### Q7. Which of the following properties are found in the Get Outlook Mail Messages activity?
- [x] MailFolder


#### Q8. The location from where we can retrieve the messages
- [x] Mail Folder


#### Q9. You are using the 'Save Attachments' activity and you have specified a local folder to download the files. What will happen if there are duplicate file names in the folder?
- [x] The old files will automatically be overwritten. 


#### Q10. Review Question : Which one of the following is used to pass data from one workflow file to another in UiPath Studio.
- [x] Only Arguments
