# witai
scribbles for using witai 

understanding  : entity extraction 
parse message into structured data..... categorising the user input

END USER : what does he want to do ? Example : 
How is the weather today ?
Book a restuarant
Open the garage door.


PROBLEM : same intent , multiple ways to say it .....

Intent extraction example weather done ...

Intent extraction for date time done 

Intent extraction for location done.. tip about need to double check location if our services uses that intensely

https://duckling.wit.ai/  open source linguistic parser

https://wit.ai/docs/recipes#which-entity-should-i-use   

built in strategies 

search strategies  : the way the parser works across each sentence ....

trait 
free text
keywords


Extracting an entity that is a substring of the message... Tell jordan that i will be late. wit/message_body 

Differentiate entities with different roles : according to their role in the message


Roles :  Roles when you want to recognize 2 entities of the same type but that have a different roles in user request.
i want to go from NY to SF . ny sf both are locations with two rolels source and destination 




conversation : predict the next action your bot should perform . 
Context and user query ...

State machines and triggers : context refers to some node on the state machine , a user query can act as a trigger for bot converse back....

STORIES !!!




Cavaet  : Designing conversational bots 
Design guidelines :
https://developers.google.com/actions/design/

https://www.sas.upenn.edu/~haroldfs/dravling/grice.html

http://www.cog.brown.edu/courses/cg45/lecture%20slides/gricean%20maxims.pdf

https://developers.google.com/actions/design/checklist

Learn general wit ai recipes and then design bot flow.








