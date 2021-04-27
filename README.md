# Austin-Washington
Descrpition: Similar to Tuber API
Steps To Install And Run The Program
1.	The First Step Is Downloading The latest “tuber” package directly from github : https://github.com/soodoku/tuber or install it from cran using install.packages("tuber")
2.	Choose the file directly from your desktop using install.packages(file.choose(), repos=NULL), or simply run library(tuber)
3.	Inside of Tubers Package will be a set of instructions on how to get an authentification credentials through google developer tools. Start by heading to this website: https://developers.google.com/youtube/v3/getting-started (None of the information has to necessarily be valid, were simply trying to get authorization to access YouTubes API.
 
4.	After Creating a new project create new credentials that will allow you to gain yt authorization ids and passwords. (Make sure to not use a web based application for some reason that doesn’t work). 
  
From There using your client id and client secret, use function yt_oauth, after being authorized R should kick you back to a google landing screen that then gives you an 
