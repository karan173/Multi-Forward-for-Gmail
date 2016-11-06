##Introduction
[Multi Forward for Gmail](https://chrome.google.com/webstore/detail/multi-forward-for-gmail/jjmdplljmniahpamcmabdnahmjdlikpm/related) is a Chrome extension to forward multiple emails at once through the Gmail website. The extension currently has greater than 70K users on the Chrome web store.


##How To Use?

1. Install the extension from the [Chrome webstore](https://chrome.google.com/webstore/detail/multi-forward-for-gmail/jjmdplljmniahpamcmabdnahmjdlikpm/related).
2. Go to Gmail and select the mails to forward.
3. Click on the Multi forward icon on the Gmail toolbar.
4. Authenticate if necessary.
5. Enter the recipients.
6. Click on the Multi-Forward button to forward the selected mails.
7. Wait till the forward completes.

Alternatively, see this tutorial [video](https://youtu.be/JYXCpS7KS_g)

##FAQs

1. *Is there a daily limit on the number of emails one can forward using the extension.*  
Yes. A total of about 100 mails can be forwarded in a day using this extension. This limit is imposed by Google itself. However, if you have a Google Apps for Work/Edu/Gov account, then you can forward about 1500 mails per day.

2. *What permissions are necessary for this extension to work and why?*  
While authentication the extension, the user must agree to grant the following permissions-

  a. View and manage your mail.  
  This is needed because the extension needs to forward the emails. Note, this permission could have been more granular, but  it is not so because of a limitation with Google Apps Script.

  b. Know who you are on Google.  
  The extension needs to know your identity (email id).

  c. View your contacts.  
  This is needed to autocomplete email recipient suggestions.

  d. View and manage data associated with the application.  
  This is needed since the extension stores the number of emails you have sent in the current day for better error reporting.

3. *Where should I report issues?*  
Issues can be reported at the extension's [Github Page](https://github.com/karan173/Multi-Forward-for-Gmail/issues/new).

##Notes

Some notes about this extension-  

1. Whenever you forward a thread(a group of related emails clubbed together in Gmail) using this extension, the extension will forward the last/latest message of that thread. Since this may be confusing to some users, it is recommended that users [turn off the Conversation View in Gmail.](https://www.google.comsearch?q=gmail+turn+off+conversation+view)

2. The extension adds the label multi-forward to the forwarded threads. This allows you to easily find the forwarded emails in the Gmail web interface.

3. Currently, some inline images are not correctly rendered in forwarded emails. 

4. In case some emails were not forward successfully, check Gmail's SENT folder to find which emails were forward successfully.

##Privacy
This extension is perfectly safe. The only data stored for each user is the no. of emails sent in the current day using the extension. This is done for better error reporting to the user.

This extension is developed by karan173[at]gmail[dot]com.

