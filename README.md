# CS-360


    Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
    
      The app was designed in order to be an alternative to other event planners already on the market. With a simple UI, this app was intended to allow users to add events to a local SQLite database which would then display events to a RecyclerView allowing for users to plan events and schedule accordingly. Unfortunately, I was unable to get the RecyclerView to display, resulting in a black screen whenever the MainActivity was loaded. Before the RecyclerView was added, events were properly added to the SQLite database, but I was unable to add the rest of the CRUD methods as testing the RecyclerView took up too much time. 
    
    What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
    
     Provided bug fixes are completed, the UI for the app is designed in a way that meets users names. Pressing on a date on a calendar should sort the events by that date. Pressing the FAB brings up a different activity that calls the addEvent function from the SQLite database manager class. 
    
    How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
    
      I primarily tried to approach the development of this app by using object oriented design principles. I had separate classes for the database, RecyclerView, event object, and user object. Additionally, each activity was also a different class. I think the methodology I used was a good idea, but more focus should have been done on testing. I left a lot of testing until too late in the design process and was unable to have a working product at the end. 
    
    How did you test to ensure your code was functional? Why is this process important and what did it reveal?
    
      If there is one lesson to be learned from this project it is the importance of proper testing. I did not conduct regular testing throughout the design of the database adapter and RecyclerView classes and ended up spending more time debugging than actually creating code. In hindsight I should have been regularly testing throughout to make sure that everything worked correctly.
    
    In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
      I feel like the aspect of the app I was most successful with was the class structure. While the app did not work in the end, I know that it will be very extensible and portable once the bugs are ironed out. 
