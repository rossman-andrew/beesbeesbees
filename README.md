# beesbeesbees
This is a project I completed as a student at [hackreactor](http://hackreactor.com). This project was worked on with a pair.

The goal of this sprint was to practice class inheritance by implementing the following classes in pseudoclassical style:

**Grub**
* an age property that is set to 0
* a color property that is set to pink
* a food property that is set to jelly
* an eat method

**Bee**
* call the Grub superclass
* set the prototype
* set the constructor
* an age property that is set to 5
* a color property that is set to yellow
* a food property that is inherited from grub
* an eat method that is inherited from grub
a job property that is set to keep on growing

**HoneyMakerBee**
* call the Bee superclass
* set the prototype
* set the constructor
* an age property that is set to 10
* a job property that is set to make honey
* a color property inherited from bee that is set to yellow
* a food property that is inherited from grub
* an eat method that is inherited from grub
* a honeyPot property that is set to 0
* a makeHoney method that adds 1 to that honeyBee\'s honeyPot
* a giveHoney method that subtracts 1 from that honeyBee\'s honeyPot

**ForagerBee**
* call the Bee superclass
* set the prototype
* set the constructor
* an age property that is set to 10
* a job property that is set to find pollen
* a color property inherited from bee that is set to yellow
* a food property that is inherited from grub
* an eat method that is inherited from grub
* a canFly property that is set true
* a treasureChest property that is set to an empty array []
* a forage method that allows the bee to add a treasure to the treasureChest

**RetiredForagerBee**
* call the ForagerBee superclass
* set the prototype
* set the constructor
* an age property that is set to 40
* a job property that is set to gamble
* a canFly property that is set to false
* a color property that is set to grey
* a forage method that returns "I am too old, let me play cards instead"
* a food property that is inherited from grub
* an eat method that is inherited from grub
* a treasureChest property inherited from ForagerBee that is set to an empty array []
* an always winning gamble method that allows the bee to add a treasure to the treasureChest