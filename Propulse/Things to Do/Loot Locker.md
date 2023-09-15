Use remote config for prices, how much money players get for things, maps that are allowed, that kind of thing.

Will have to use loot locker to save drone setups

Figure out player names. I can always login and start a session, but disallow anything else before the Player name isn't null. To figure out what is null use a debug to figure out what the name is before setting a name.;

For the loadout. Have a template script that has a function that buys the upgrade, a function that equips the upgrade if it is owned and then saves that equipment to loot locker, and a function that modifies the drone for that equipment if it is equipped. For the buying a weapon make it so if the player does not own the weapon it shows darker than the stuff they do own. 

Have a script that just deals with setting the currency text.