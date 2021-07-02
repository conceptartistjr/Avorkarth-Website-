---
title: "Dice Rolls"
date: 2021-06-22T09:53:44-04:00
menuid: "rulebook.dicerolls"
menu:
  main:
    identifier: "rulebook.dicerolls"
    parent: "rulebook"
    weight: 2
draft: true
---

# Dice Rolls

{{< snippet >}}<div class="bookpage-columns"><div class="bookpage-column">{{< /snippet >}}

Dice rolls are the most important part of the whole game system.
Whenever a character or creature wishes to interact with the world and there
is a chance of failure, they must roll a die. This die roll is the equivalent
of the attempt as well as the result of the action, be it good... or bad.

## Rolling

### Roll Value
The value of a roll is dependant on the character's relevant skill or attribute
value. Unlike mahy other table-top role-playing games, the characters bonuses and
values are not added to the dies's results. Instead the value is used as a check
against the value of the action the character is attempting.

### Minimum Values
Any total value (after any calculations) that is below 1 is always considered as
a value of 1.

### Difficulty Check
The difficulty check for any dice roll is the oppossing value that is compared
against the roll value. Every action has a counter, be it a characters ability to
resist a charm or to dodge an incoming attack. Difficulty checks are often called
or known as "DC" for short.

### Determining Outcomes
To see if a character's action was or will be successfull, they compare their roll
value against the difficulty check. They then roll a die  and compare the result
with the table below. The greater the difference between both values the more the
die's result leans towards a particular outcome.

### Overpowering
If the difference between a value and the DC is 10 or more, it is considered an
automatic critical success/fail. This is considered before checking the roll table.

{{< snippet >}}</div><div class="bookpage-column">{{< /snippet >}}

### Role Example
A skillful thief is attempting to stealthily hide from the nearby patrolling guard.
Being skilled at hiding in shadows, they have a value of 8 for their hide action.
The guard would counter this with a spot check to see if they notice the theif's
movement. The guard has a value of 5 for their spot action.
That would mean that the spot check rolled by the guard is less than the DC
(the theif's hide). When the guard rolls their chec, a 1 would criticaly fail,
a 2 or 3 would fail, a 4 or 5 would be a partial success and a 6 would be a success.
With the die's result, they would then read the spot skill's results in the rulebook
to determine if they notice the theif or not.

{{< img-resize "rulebook-dicerolls1-thief.png" "400x" >}}
"Lanterns do not aid the burden of inattentive eyes." - Thief's saying

{{< snippet >}}</div></div>{{< /snippet >}}

|                      | Critical Fail|  Fail | Partial Success | Success | Critical Success |
|:--------------------:|:-------------:|:----:|:---------------:|:-------:|:----------------:|
| Roller is 7+ Greater |       -       |  -   |        1        |   2-3   |         4+       |
| Roller is 5+ Greater |       -       |  -   |       1-2       |   3-4   |         5+       |
| Roller is 3+ Greater |       -       |  1   |       2-3       |    4    |         6        |
| Roller is 1+ Greater |       -       | 1-2  |        3        |   4-5   |         6        |
| Roller is Equal      |       1       |  2   |       3-4       |    5    |         -        |
| DC is 1+ Greater     |       1       | 2-3  |        4        |    5+   |         -        |
| DC is 3+ Greater     |      1-2      |  3   |       4-5       |    6    |         -        |
| DC is 5+ Greater     |      1-2      | 3-4  |        5        |    6    |         -        |
| DC is 7+ Greater     |      1-3      |  4   |        5+       |    -    |         -        |

