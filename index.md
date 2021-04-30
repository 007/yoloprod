# #yoloprod

## A DevOps Philosophy

#yoloprod is a way to understand your organization's maturity with regard to production operation.

There are three levels of #yoloprod:

### #yoloprod v0 : true #yolo

At version zero, #yoloprod has its most common understanding. You are #cowboyOps, doing whatever you need to do with no safety net. Live fast and die young.

This is the most dangerous level, but probably the most productive - in the short term.  Everyone can go and fix whatever just broke on prod, but that's a good thing because it's always going to break.  Everything here is a snowflake. Data loss is inevitable, and accepted as a cost of moving fast and breaking things. Security is for suckers.

### #yoloprod v1 : rational #yolo

Version one introduces rational contemplation of what "production" means. You realize that you only live once, you don't get a do-over, so don't screw it up.

You have processes.  You separate concerns.  You have least-privilege, at least mostly.  You implement the Dinosaur Hat Rule - nobody touches prod unless they obtain the ridiculous dinosaur hat.  You don't start a deploy after 1pm, and not ever on a Friday.

This level feels like an improvement over the Wild West chaos of v0, and it might be.  You don't break things, but you can't move fast.

### #yoloprod v3 : happy #yolo

Version three (wait, what happened to two?!) of #yoloorod is the ideal. It's #yolo with guard rails, and enough process and automation to keep you safe without slowing you down.

You do whatever you want.  The guard rails keep you from breaking the world.  If you happen to break something, congratulations!  You just found an edge case.  Someone (maybe you) will be along shortly to add another rail to prevent the same problem in the future.  And your change has been rolled back automatically, so don't worry about that, either.

Your team releases six times an hour, and Fridays are usually eight or nine.


