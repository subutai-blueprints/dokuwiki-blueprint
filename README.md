# dokuwiki-blueprint

Dokuwiki is a web application that requires mail service, so that when building this blueprint users are asked to supply a working SMTP server and email account that emails can be delivered from. A typical way of doing so is using a Gmail account.

For example your Gmail account is `myawesomeapp@gmail.com` whose password being `TOPSECRET`, then answers to several of the questions are:
 * emailUser: `myawesomeapp`
 * emailAccount: `myawesomeapp@gmail.com`
 * emailPassword: `TOPSECRET`
 * emailServer: `smtp.gmail.com`
 * emailPort: `587`
 
If you have 2FA setup, then you have to create an App password for it to work, otherwise you may still receive a scary `Review blocked sign-in attempt` alert, which you have to be sure that you understand the risk, approve the sign-in attemp, and turn on `Less secure app access` at https://myaccount.google.com/lesssecureapps.
