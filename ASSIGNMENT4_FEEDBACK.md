Hi Edu!

Good stuff!

As you see below you've easily met the requirements for a Godkänt grade, unfortunately you have a few things to fix to earn a VG grade.

I understand you have started with the new course, so please let me know whether you are happy with the G or want to get the VG.

*************************************

CRITERIA FOR GRADING

*************************************

GODKÄNT:
-------------------------------------

Connect to an API ✅

User fired event to launch the fetch ✅

Data is returned and handled efficiently ✅

Display more than one property of the returned data ✅

RWD
  Desktop ✅
  Mobile ✅
 
-------------------------------------

VÄLGODKÄNT:
-------------------------------------

Error handling when fetching the data ❌

Append arguments to the request ❌
   You have the input in place, but have hardcoded the limit of 5.

Multiple calls to the API ❌ ✅
   The fetch fires more than once, but since the url is constant no new data is returned

Code style ✅
  CSS - have a aspace before the closing  } 
        have an empty line between selectors eg: 

  .footer-bottom{
    background: #000;
    width: 100vw;
    padding: 20px 0;
    text-align: center;
  }
  .footer-bottom p{
    ...

    Should be:

  .footer-bottom {
    background: #000;
    width: 100vw;
    padding: 20px 0;
    text-align: center;
  }

  .footer-bottom p {
    ...

  HTML - the script tag at line 30 should be in the head section
         the script tag at line 32 should be a separate file and linkd like line 30.
         Semantic naming on the buttons! 
  JS - a few unneeded empty lines
       the imgs should have an alt attribute added to them