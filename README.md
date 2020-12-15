# Design Patterns for Disaster
This is a team learning activity meant to suss out the importance or lack thereof of design patterns

Scenario: There has been a disaster that has left 200,000 people in need of food. Enter World Kitchen to the rescue. Chefs know how to feed people and there are some with time and crews (and extra staff) to do just that! 

You are on the consultation team to provide feedback on how the Head Chef should allocated chefs and resources to best serve food to 200,000 people for at least 30 days during this crisis. This is a daunting task. The head chef(HC) must convince some number of chefs to the "Relief Kitchen". There is only a few days for HC to "personally" make these calls and get this plan into execution. Once HC enlists the help of his collegues they will take it from there. 

## The HC's asking for your expertise (definately not to cook!)
How many chefs does the HC need to convince? Remember that there will be 1 in 5 that might not make it, how many backups should HC have just in case? He is counting on you to give him a recommendation and sadly there is not enough time to take everything into account but maybe some kind of design pattern will help but then again maybe it won't!?

In any system obviously resources must be limited and contraints applies so here they are:

## Stadiums
There are two stadiums that are available for use. Each can hold several thousand people. The only way people  find out about the second stadium is to be turned away when arriving at the first or being asked to migrate to make room for those coming in. Each Stadium ideally can feed 50,000 people per day.

## Kitchens 
There are enough supplies for the military to build 10 kitchens between the two stadium. Because of the excess of volunteers these kitchen can appear almost instantaniously after the disaster happens and will be ready to start feeding people day 1 of disaster. Chefs will absolutely not work together.(Too many cook in the kitchen will not be a thing here!)Chefs will rotate between kitchens but it will take away 1 day of food production. Oh and because the kitchens are used so heavily the maintenance must take place every 10 days. Yep, that also takes away 1 day.

## Chef w/Crew
The Chef must have complete control over a kitchen for an entire day. Nothing else will do. One Chef/crew team can feed 5000 people normally. I mean they gave up running a resturaunt for this relief effort, seems like a reasonable demand! A chef can choose to add a batch of 5 extra staff members (very good amatuer cooks who volunteer). We all want that to mean that the kitchen can now feed 10000 per week. But really its 8000 per week because amatures make mistakes under pressure. All Staff and crew must take direction from one and only one chef. 

## Food
All of the chefs will be serving chicken and rice to those in need. This is delicious and easy to make in bulk. There is as much food as a chef needs but if the organization finds that food is going to waste the donors will pull funding. Given that chicken spoils after 5 days from delivery. Food delivery takes 1 day

## People in need
It is heart wrenching but unfortunately people have lost every ambition except to feed themselves and thier families. The total people who need to stay out of "Hangry" mode are 200,000. After 3 days of not having any food people begin to become unruly. (They will loot kitchen that are under maintenance if they have to!)
But these people are also resilient they will walk a full days journey if they are not hangry so that other in there communities don't starve. (They need to go back every now and again anyways to see if they can start rebuilding or not). They are told that if they do not volunteer to migrate when asked everyone in the stadium after capacity is reached (50000, remember?) will get half rations.
