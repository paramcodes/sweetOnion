# SweetOnion

It's a web based game where 2-players can battle.

- It will be based on elo rating system. every new user would start with 1000 rating and can as low as 35. every win would lead to +100 and lose -100

- in every match, each player gets a HP of 100 and whoever runs out first will lose.

- every player would have some set of skills
FistPunch -> it would deal a damage of 25 to the opponent
CrabHammer -> it can be used max. 2 times per match, it would deal a damage of 50 but would lock the turn of attacker so he/she will be frozen for one round and opponent will be able to use 2 moves.
Ghillie -> it will hide the one who uses it, so any move by the attacker on the next turn would inflict any damage. whoever has ghillie enabled it will show in the UI
Reverse -> it will inflict damage to the opponent in the next turn with whatever move they it or if it's ghillie then that too will be transferred to the user who has used Reverse so that will work as protection unless ghillie breaks. and if used reverse then it will be raverse would cancel the reverse and nothing would happen.

- for the 1st mvp we won't add any login yet, everyone can play as guest or use their twitter/X username which will be shown as their name during match or if guest then some random name with prefix guest_
