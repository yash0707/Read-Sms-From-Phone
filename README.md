# Read-Sms-From-Phone
This is the sample app for how to read the phone messages and write it in text file in your phone External storage.

# NOTE:- 
1. This app gives you all the details of the particular message.
    If you need the body of the message then see the commented line in fetchInbox() function in MainActivity.java.
    
2. In some phones u may need   " Uri uri = Uri.parse("content://sms/conversations"); " or 
    in some phones " Uri uri = Uri.parse("content://sms/"); " inside fetchInbox() function in MainActivity.java.
    


