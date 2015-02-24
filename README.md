----
This is instruction for setup Ruby on Rails on Windows 7 x64.
----
Contains steps, which are needed to properly work in Ruby on Rails.
----

1. Install Railsinstaller
  
Link:  http://railsinstaller.org/en
  
2. Install SSL certificate
  
Link:  http://curl.haxx.se/ca/cacert.pem
  
Setup environment variable in Windows: Control Panel \ System \ Advanced System Settings \ Environmenta Variables \ 
Add in Environmental Variables line: Variable: SSL_CERT_FILE , Value: path to 'cacert.pem' file.

3. Install URU - application to manage multiple versions of ruby
  
Link:  https://bitbucket.org/jonforums/uru/
  
Create PATH line for URU in Environmental Variables
Install by typing in cmd: PATH\uru_rt admin install
Add ruby: PATH\uru_rt admin add system

4. Install ConEmu
  
Link:  https://code.google.com/p/conemu-maximus5/

ConEmu replaces bash from git - easier to handle multiple tabs, saves views after exit.
