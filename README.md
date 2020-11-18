# Homework_Week1_
My home work BCS Week1

This is my first home work from BCS.

On this homework, I was given an original html and css file, which were already working as it should look like,
but there were some code I could've made it better for some reasons. 

According to Dictionary.com(http://dictionary.reference.com/browse/semantics), 
semantics refers to the correct interpretation of the meaning of a word or sentence.
To use a word semantically is to use it in a way that is properly aligned with the meaning of the word.
Reference: https://html.com/semantic-markup/#ixzz6e708Kjz2


First, using HTMML correctly. The tags themselves become a way to tell a machine (whether a browser, a computer, a smartphone, or another smart device) something about the meaning of the content. For example, this original code was using <div class=header>insted of <header>. Of course div tag works fine but it means <div> not <header>. Using right tag makes it better for search engine also good for screen reader.

Second, there are some images in the code but all of those were missing "alt". alt is important for who can't view the image especially for people use screen reader. Making sure everyone can understand the website.

Third, the class=contents and class=benefits are supposed to be next each other and it looked like perfect shape for it. To make this happened, I added new <div> with class name =.display-flex. So this new class I can add display element to put it next to each other.
  
Fourth, COMMENT! It is alway good idea to put comments for everyone to understand what those code are working for. 
  
In the last, there were few class sttributes working on same CSS codes. It makes much more organised if use same class attribute to all the same CSS effect if its possible. SO I have changed few of them under same class.
