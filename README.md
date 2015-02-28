----
This is instruction for setup Ruby on Rails on Windows 7 x64.
----
Contains steps, which are needed to properly work in Ruby on Rails.
----

A. Install Railsinstaller
  
Link:  http://railsinstaller.org/en
  
B. Install SSL certificate
  
Link:  http://curl.haxx.se/ca/cacert.pem
  
Setup environment variable in Windows: Control Panel \ System \ Advanced System Settings \ Environmental Variables \ 
Add in Environmental Variables line: Variable: SSL_CERT_FILE , Value: path to 'cacert.pem' file.

C. Install URU - application to manage multiple versions of ruby
  
Link:  https://bitbucket.org/jonforums/uru/
  
Create PATH line for URU in Environmental Variables
Install by typing in cmd: PATH\uru_rt admin install
Add ruby: PATH\uru_rt admin add system

D. Install ConEmu
  
Link:  https://code.google.com/p/conemu-maximus5/

ConEmu replaces bash from git - easier to handle multiple tabs, saves views after exit.

E. Install SourceTree

Link: http://www.sourcetreeapp.com/

SourceTree is git client with GUI - easier to manage branches, follow changes and commit files.
