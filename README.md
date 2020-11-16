
# Ticket GUI

A tool that revolutionized ticket reviews for a desktop support team

<br/>

Company: Healthesystems


Year: 2014


Purpose: During my tenure at Healthesystems, IT support tickets were created in SharePoint and the only way to view consolidated metrics data was with an Excel spreadsheet that connected to SharePoint. In order to save the team some time, I created a PowerShell script to automate the steps of gathering the needed information and sending out a daily email report to the team, which showed important metrics and tickets of concern.


My Role: I assumed the task on my own initiative (with permission).


Outcome: The daily ticket report was able to pull much more data than what was previously available, and it was interesting enough to management that I was asked to create similar reports for other teams. Our team used the daily ticket report email to review tickets as part of our continuous improvement.


Technical Details: a non-GUI ticket-data upload script ran via a scheduled task. It triggered a VBScript macro in an Excel spreadsheet which retrieved fresh data from SharePoint and then dumped it to CSV. The script then read the CSV data, and uploaded it to a SQL table. Then, an email report script ran several SQL queries and formatted the results as HTML. It then sent the generated email message to the team. The screenshot shows a GUI written in PowerShell and compiled into an executable by PowerShell Studio. The GUI streamlined the ticket review process for our team. I added JIRA support later on since that was likely to supersede SharePoint as the next ticket platform.


### Previewing this Project
![](http://kentpmckinney.github.io/kpm-achievement-ticket-gui/TicketGUI.png)

<br/>

### Technologies Used

<code>PowerShell</code>
<br/>
<br/>

### Authors

[kentpmckinney](https://github.com/kentpmckinney)
<br/>
<br/>

###### <sub>Copyright&copy; 2020 [kentpmckinney](https://github.com/kentpmckinney). All rights reserved.</sub>