# What is invite tracking
Invite tracking is a system to track current invites in server and their uses, and check which invite was increased which is mostly the invite used

And here we know the inviter, we can include it in the welcome message, and it can be stored in the database so people cannot lie about their invites anymore!

# How to enable
it is enabled by default.

# How to check user invites
Use `/invites <mention user>`

# Notes
1. Re-inviting a user overrides old invite in database, so no duplications
2. This required Manage Server permission
3. You don't need to enable the system to write the inviter in the welcome message, if you used older versions and your `welcome.json` wasn't updated, here is the placeholder: `${#inviter == null ? \"Unknown\" : #inviter.getAsTag()}` it is Unknown when we couldn't find the inviter, or inviter and their tag if we successfully found them