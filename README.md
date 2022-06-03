## Secrets - Authentication App :lock:

I have always been interested in security and authorization systems. 
Therefore, studying the stages of improving the system for protecting user passwords is of particular interest.
In this program, I gradually learned how to store and encrypt user passwords in the database. 
From storing passwords in a local DB as text, to advanced encryption, salting and storing in Mongo DB. 
As well as authorization through Google and Facebook APIs.

### Functionality:
Last version uses Google and Facebook APIs to authorize users as well as storing their notes in database.
Users can also sign up with their own email&password to submit notes.

### Why is authentication needed?
The main purpose of authentication is to make it as difficult as you can to use someone else's (stolen, brute-force) credentials.  
Everyone has long understood that generating and remembering long passwords is not an easy task.

### Stages. :twisted_rightwards_arrows:
+ Identification.
+ Authentication.
+ Authorization.
