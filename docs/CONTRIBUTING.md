## Contribution guidelines

If you wish to contribute to the bot, follow these steps:

1. Fork this repository
2. Create a new branch called `beta-(discord-username)`
3. Do whatever changes you wish to do and create a pull request with the following information furnished in the request message: `The cog you wish to change | What did you change`
4. Send a review request to `alfadelta10010`.
5. Wait for approval from the reviewer. Your PR may be directly accepted or requested for further changes.

**Under no circumstances is anyone allowed to merge to the main branch.**

## File Structure

`bot.py` - The main bot file. Has commands to load and unload other cogs<br>
`start.py` - A file to ensure bot restart. Do not touch.<br>
`cogs/helpers.py` -  Contains functions for admins, to look up users, and to verify and devarify users.<br>
`cogs/misc.py` - Contains functions pertaining to confess, count members, mute, and various others. 90% of issues exist here.<br>
`cogs/server.py` - Contains functions pertaining to server-based activities, like ping report, etc.<br>
`cogs/verification.py` - The most critical cog. Contains all commands pertaining to parsing the information of SRNs and PRNs, and the verified users file.<br>
`docs/sample_batch_list.txt` - Contains samples of the batch_list_20XX.csv file<br>
`docs/verified_example.csv` - Contains sample of the verified.csv file<br>
