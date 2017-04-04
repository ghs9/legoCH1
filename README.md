# legoCH1
Lego EV3 1st project.

Team 1

Gabriel Summers   ghs9@uw.edu

Jayden Tan        jayden91@uw.edu

## Agreements:
  1) We are available MWFSaSu all day. TTH available 10-12:30
  2) We will use github to host our journal and code.
  3) simple plan is to use the RileyRover basic body build 

## 3/28/2017
  1) Made team
  2) Counted out pieces of kit
     * They all were there
  3) Set up lock and both of us practiced opening it.
  4) Set up git repo
     * Both are now contributers.
  5) Read the challenge 1 description.
      * We need to research biased random walk.
      * We think the walk shouldnt be too bad.
      * The sensors shouldnt be too much of a pain.
          * We want to have the ultrasonic mounted on top front,
          * two touch sensors in front.
      * Movement will be with treads for now.
  6) Plan to meet 3/29/17, 1:30PM, CP206D
  
## 3/29/2017
  1) Team met in CP 206 at 1:30PM
      * There was a class in the CP 206D lab so we just sat in the lounge and planned our robot.
  2) Once the class left the lab we went in and started building our bot.
      * We have settled on the RileyRover design for now, with two touch sensors modified on.
  3) We want to begin coding for RobotC but it requires a firmware update for our EV3 board which we do not have a usb for.
      * We looked for a usb but cannot find one. May have to do that tomorrow.
  4) From 2:45 to 4:30 we worked on building the robot.
      * Building the car was easy, but attaching the sensors was difficult.
          * We built a cage that sticks out the front and attached two swiveling arms that would press the sensors. This worked but we are concerned that there will be a skinny obstacle in front that it doesn't hit.
          * altered to have one bar in the center that would press both arms if hit in center. This does not work very well.
          * Removed arms and instead had one arm in the center that would press both if hit center, left if hit from left, right if hit from right. This seems to work the best.
          * Now we address issue of some parts that swivel "drooping". We attached more bars, added support to EV3 board. It works and looks pretty cool.
          * Tested it (without actually running cause we dont have usb to update firmware) manually by pressing it up against obstacles and it works like it should.
          * We have a concern that the sensers may be stuck pushed half in after bar presses against them if the spring inside the sensor doesn't push hard enough to clear the arm. This is something that we will be able to see better once we get code running.
  5) We plan to meet again durring class tomorrow, 3/30/17 at 8:00AM
  
## 3/30/17
  1) Team met for lab starting at 9:09AM
  2) Liscence is expired on mindstorms for the RobotC environment.
      * Talked to Fowler and Lab manager. They said they would send an email and get it sorted out.
  3) While waiting for liscencing issue, we ran demo program already installed on the brick. It seems to work perfectly but it is a limited test (just back and forth movement).
  4) We tried to connect USB from brick to computer, nothing happended.
  5) Jayden is now trying a different coputer to see if the IDE will work.
      * It didn't.
  6) We used the lego graphical IDE because that works and made a simple program that runs forward and then runs backward. This works perfectly and it ended up in relatively the same spot (about 3in off).
  7) Plan to meet monday 4/3/17 at 1:30PM
  
  ## 4/3/17
  1) Team met for lab starting at 2:00PM
  2) Jayden went to the lab first. He found out that the Robotc IDE is still expired. We could not test our robot without the IDE activate.
  3) We have decided to download the 10 day free trial for RobotC for lego mindstorms so we can start working on it today.
      * The VM that we are downloading the trial to is having some issues so we are restarting it.
  4) We have been viewing some internet resources on RobotC for when we get started writing code.
  5) While Jayden tries to download the trial on his laptop. I go through online tutorials on RobotC.
  6) We could not download the trial successfully on the laptop so we are now going to Snoqualmie building to check out a surface. Hopefully that works.
      * This doesn't work since we cannot download software onto the library's surfaces.
  7) We are calling it a day and plan to meet tomorrow during class. 4/4/17 at 8:00AM
  
  ## 4/4/17
  1) Team met for class today at 8:00AM
  2) We realize that only certain computers in the lab have the correct liscence for the RobotC so now we are downloading the kernal to our EV3 brick.
  3) We wrote a simple program to move forward.
  4) next we wrote a program to test bumpers and play sounds.
  5) Now we are writing a program that moves left and right.
  6) Now we combine the three programs we wrote to move forward, if it gets touched reverse and go in the opposite direction.
      * Syntax errors with method call vs. startTask().. We ended up siding with a simple method call.
  7) Now we test it in the explorer's space. It generally explores but sometimes has issues detecting when both of them are pressed.
      * We have added a wait to when the first sensor is triggered to when the trigger handler is called to allow time for both of them to be pushed.
      * We have also added a push bar to the front and increased stability of middle axel to ensure that both have a higher chance of being hit if they should be.
  8) Testing it in the explorer's space, this new design and sensor handler function work a lot better but there are still improvements to be made.
  9) We plan tomorrow, 4/5/17 at 3:30PM. For now we have made good progress for today.
  
  
