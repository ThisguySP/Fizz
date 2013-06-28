Fizz
====

Fizz is a nice little Bukkit plugin the function of which (while difficult to describe) boils down to this: It sets a Permissions plugin group for all players who join the game to their phpBB forum group.

The long version of that is a story best told in steps:

1. Fizz begins by looking up the first user ID that matches the minecraft username based on a custom profile field.
2. Then, it takes that user ID and matches it with its primary group ID.
3. After getting the primary group ID, it translates that based on its own special table to a Permission plugin's group's name. It sets the joined player to the group it's matched.

Easy as 1, 2, 3, eh?

For configuration help, visit the comments left for you in config.yml. I promise they're easier to understand than this plugin's function!
