Use remote config for prices, how much money players get for things, maps that are allowed, that kind of thing.

Will have to use loot locker to save drone setups

Figure out player names. Allow them to change their names whenever but make sure a default name gets set maybe? Or figure out how to initially set it.

To get information from loot locker AI, in the function when it successes you can do like session.name and it will return the name of like session.messageid or something like that and it will return the message id if it has been gotten from the function if is in. Check the API docs for what you can get from each function.

For the inventory have it so when the player does not owns a item it shows darker. Create all of the needed keys for the equipment on the same script. Set other keys on a different script if needed. Make a separate script for modifying the drone based off of equiped items. Have that script check what times are equiped for each category.