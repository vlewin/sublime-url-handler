sublime-url-handler
===================

Open a 'subl://' files with Sublime Text from your browser (Linux)

## Install
`cp sublime-handler /usr/bin`  
`chmod +x /usr/bin/sublime-handler`  

`cp sublime-handler.desktop /usr/share/applications`  
`sudo update-desktop-database`  

## BetterErrors gem
Create an initializer and put the following line:      
`BetterErrors.editor = :sublime if defined? BetterErrors`

