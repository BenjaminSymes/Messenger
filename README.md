# Kotlin Messenger
Android App Messenger

This was a tutorial project I found online to help learn about Android App development. Full credit goes to LetsBuildThatApp.com. 
This app is fully functional and uses Google Firebase as the database to store users.

This is a simple android application that sends messages to different users, similar to text messaging or Facebook messenger. This application was made about 1 year ago, for the purpose of working with Kotlin to understand it better, as it is the official Google supported language for Android development. I did not create this from scratch, as I followed a video tutorial that I found online. It walked through step by step how to create the UI, create and save users, create and save messages, etc. I felt this project was useful in helping me understand how mobile applications work behind the scenes and how they send and store data.  

Although I did not make this program, I did write out the lines step by step and saw how each update effected the application as a whole. It was not as easy as copying what the instructor was demonstrating; many times, my version would fail to compile and run, even though I followed the steps exactly as displayed. I often had to research on my own why the application was failing to run and make the necessary adjustments. 

One modification I decided to implement was incorporating a timestamp into the messages so they would be saved in the proper order. Before, messages would be sent properly to the right person, but would be out of order when loading the history of messages. I did this by adding a val timestamp variable in the chatmessage class. This grabs the time stamp of when the message was sent and adds it into the fields of the message in the firebase database. After implementing this change, the chat bubbles were arranged based on time sent, which makes more sense when viewing previous messages. I felt this was an important change to be made when working with this chat application.


