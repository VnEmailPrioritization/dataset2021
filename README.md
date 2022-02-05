# Vietnamese Email Prioritization Dataset
Following is the meaning of the columns in the CSV file:
1. The email message's id. This is just a simple integer id starting at 1.
2. The email's priority label (0 to 4). The 5 labels (from 0 to 4) are 'delete', 'read-not-important', 'read-important', 'reply-not-urgent', 'reply-urgent'.
3-8. The number of emails in each priority level that were sent by the email's sender.
9. The email's subject. Words are separated by commas.
10. The email's body. Lines are separated by '|', words in a line are separated by commas.
