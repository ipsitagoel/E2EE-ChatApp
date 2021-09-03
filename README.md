# End-to-End Encrytpted Web Chat App
This is an end-to-end 2048-bit RSA encrypted messenger web app.

Check out the website here: https://end-to-end-encrypted-chat-app.herokuapp.com/

This  chat  application  is  an  implementation  of  a  security-first messenger application. It is a web app that harnesses the technique of cryptography to implement an end-to-end 2048-bit RSA encrypted messenger. It 
utilizes HTML, CSS, Vue.js  for  coordinating  the  frontend  functionality  along  with  a  Node.js backend  using  Socket.io  for  sending  messages  between  users.  The  concepts are implemented in Javascript and are mostly intended to be platform-agnostic. 
The  UI  of  this  chat  application  has  been  made  using 
neumorphism, one of the latest design trends. It’s aesthetic is marked by minimal 
and real-looking UI. 
Moreover, the application is responsive which enhances it’s usability.

### Tests
To  test  this  encrypted  chat  application  we  have  used  PortSwigger’s  Burp  Suite  Community 
Edition  which  is  an  application  security  testing  software  used  for  penetration  testing.
We  tested  our  end  to  end  encryption  application  against  a  non-encrypted  chat  application 
by  performing  pen-testing  with  a  kind  of  man  in  the  middle  attack.

The non encrypted message can be intercepted and manipulated with Burp Suite. On the other hand, our End to End encrypted chat application has an encrypted message passed 
to the server and therefore the message is encrypted with RSA.
