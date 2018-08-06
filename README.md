# quick-meet-up

Features:-
-----------------
1. Shows you a list of online users ranked according to your preferences and pre-requisites in your vicinity(according to some default field of radius).
2. Lets you chat with the online users(includes calling, attaching files).
3. Users get to block and report the other users.

Ranking Algorithm:-
------------------
1. User specifies prerequisites and then the other relatively less critical requirements.

2. The whole list of online users would be divided into three tiers.

  2.1. Top tier contains users who have satisfied the prerequisites + the other requirements(including the proximity requirement).
  
  2.2. Middle tier contains users who have satisfied the prerequisites + the other requirements(but have failed to satisfy the proximity requirement).
  
  2.2. Lowest tier contains users who have failed to satisfy the prerequisites but have satisfied the other requirements.  
      2.2.1. This would be based strictly on the number of requirements satisfied and proximity is not considered.
  
Future Scope:-
---------------
1. Video Calling(I guess?).
2. Explore Channels.
3. Custom field of radius.
