# Inna

Inna is an artificial chatbot (Using Dialogueflow) and a message passing application.

Requirements to run this app:

1. IDE: Xcode 9
2. Programming Language : Swift 4 (Deployment Target : 11.3)
3. Iphone
4. Need to install Cocoapods on the system. 
	Cocoapods: manages library dependencies for Xcode projects. Going to terminal and 	install cocoapods. 

	$ sudo gem install cocoapods

after successfully done installation then follow the next steps-

5. installing some pod files. 
         pod 'Firebase/Database'
         pod 'Firebase/Auth'
         pod 'Firebase/Storage'
   	pod ‘ApiAI'
   	pod ‘JSQMessagesViewController’

6. Using google's Dialogflow

Process:

	1. At first we need an mac os operating system.
	2. Then we need Xcode
	3. Then need to Pod install Firebase
	4. Installing pod file ApiAi
	5. Installing JSQMessagesViewController
	6. Then run the project and use the application. 



Features:

1. Passing message between ids

2. Passing Image

3. chatbot which give valuable information about food and restaurents in sylhet.

4. chatbot use voice and speech recognition


Description to use:

·      After running this application first view is a loading screen.

·      Next view is Login and Registration the name of view controller is LoginController, in this view the icon of Inna also used to take users profile image by tap gesture recogniser.

·      For resistration user image, username , email password is required

·       after login users can communicate

·      In the MessageControllers view ,  the button Inna take us to the Chatbot communication view.


