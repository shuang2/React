# Live action strategy, REACT. 

## How do you create a turn based fighting game. 

The game though turn based should simulate the same feeling as fighting games. As such it should be relatedly fast paced. Different characters is a goal, one working character what I want to finish over the summer. 

There will be an energy based system. Most basic blocks attacks and whatever shouldn’t cost energy, however in order to do damage you must spent energy. There will be a rock - paper – scissors – lizard – spock  


## There are 5 basic attacks a character can execute. 

Punch – Loses to Grab and Block – Wins against Kick and Charge 
Kick – Loses to Punch and Block – Wins against Grab and Charge
Block – Loses Against Grab and Charge – Wins against Kick and Punch
Grab – Loses to Kick and Charge – Wins against Punch and Block
Charge – Loses to Kick and Punch – Wins against Block and Grab 

## Basic game.
Each character has 10 starting health. When a character’s health drops below 1 they lose. Every 3 seconds each character gains 1 energy. Energy can be used to execute advanced actions and to execute attacks. 

In order to start an attack chain it costs 1 energy. That is to say, in order to attack you need to spend one energy. Out of the 5 basic actions 3 of them cost 0 energy to execute. Punch, Kick and Grab cost 0 energy. Punches are faster than kicks, kicks are longer ranged than grabs and grabs can counter punches. 

## Basic Combat
When the attacker attacks they choose one action as well. If they win the other player loses one life. However, if the defender wins the pick they are not able to hit the attacker, they merely negate the attack and gain the opportunity to counter attack if they choose to. However, if the attacker hit’s the attack they have another chance to attack again. Defender wins in the case of ties as the attacks counter each other. (Note that this does not apply to charge) 

There are 3 advanced options, these options cost energy. The first two of these actions are Block and Charge. Like the other three options these options wins against 2 other options and wins against 2 other options. These options are special. You cannot attack with a block and you cannot defend with a charge. Attacking with a charge takes 1 more energy than normal, increasing the attack cost to 2. Winning with a charge deals 2 damage and decreases the energy cost of the next attack by 1. Winning with a block will gain the defender 1 energy. 

The last action is dodge. Dodge cost 3 energy to use. Dodge is a defensive action and cannot hit. When you dodge you immediately gain initiative and counter the opposing attack. 

Example 1: Attacker chooses punch and defender chooses kick. Defender takes one damage. Attacker gains initiative. 

Example 2: Attacker chooses grab and defender chooses kick. Defender wins and negates attack. Defender gains initiative. 

Example 3: Attacker chooses charge defender chooses block. Defender takes 2 damage and attacker gains initiative. Their next attack costs 1 less energy. 

Example 4: Attacker chooses punch defender dodges. Defender gains initiative. 

## Cooldowns: 
Using any attack will put it on cooldown of 10 seconds. Whenever a player is hit, all attacks that they have on cooldown have their cooldown increased by 3. 

## Characters: 
Each character will have a unique ability. Normally a constant effect. They will also have 2 unique actions. One is a free action (costs 0) and one special action (costs 1 or more). Also each character will have a finisher attack, costing 7 energy. 

Basic Character – Binam:
Unique ability – None
