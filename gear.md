{% include_relative header.md %}

Keep Track of the Guild Gear.

Easy to use and simple. 

Example of bot commands:
- `!gear ap:269 dp:296`
- `!ap 269`
- `!dp 296`

## Text Commands

<section class='flex col left' >
<section markdown="1">

### Short Commands

- `!ap xxx` - Updates the current AP.
- `!aap xxx` - Updates the current AAP.
- `!dp xxx` - Updates the current DP. 
- `!accuracy xxx` - Updates the current ACCURACY.
- `!eva xxx` - Updates the current EVASION
- `!dr xxx` - Updates the current DAMAGE REDUCTION
- `!link xxx.(png/jpg)` - Updates the current LINK. Also supports image as attachment.
- `!class Ninja` - Updates the current CLASS.
- `!level 61` - Updates the current LEVEL.
- `!trinaaxe/axe/trina III` - Updates the current TRINAAXE. Please choose one of the following: I/II/III/IV/V
- `!plan https://bdoplanner.com/PersonalLumberFist` - Updates the link to the gear planner. Please choose one of the following: bdoplanner, bddatabase

</section>
<section markdown="1">

### Commands

- `!help` - provides information to what commands are available. Note some commands are only available for specific discord roles.
- `!feedback message` - This will send the message to my masters. I also respond to this command in pm.
- `!gear` - displays your current gear or updates current one, to update
- `!gear @member @member` - displays the gear of mentioned members 
- `!gear ap:xxx aap:xxx dp:xxx accuracy:xxx link:link.png plan:bdoplanner class:xxx level:xxx trinaaxe:I/II/III/IV/V` - updated the current stats. Supports image as attachment.
- `!list` - This will provide a list with all members, sorted alphabetically.
- `!list score/total/aap/ap/dp/level/accuracy` - This will provide a list with all members, sorted by the stat. Note Only one stat can be used at a time.
- `!list class` - This will provide a list with all members, filtered by class.
- `!stats` - This will provide information about the guild average stats.
- `!top ap/aap/dp/level/score/accuracy 10` - This will provide a list with top members by stat.

</section>
<section markdown="1">

### Officer Commands

- `!remind` - This will send private messages reminding guild members to set their gear.
- `!remind level:xxx` - Reminds everybody who is below the level.
- `!remind total:xxx` - Reminds everybody who is below the total gear score.
- `!delete` - Deletes the gear information.
- `!delete @mention` - Deletes the mentioned member gear.
- `!delete ID` - Deletes the member gear by id (use if the member cannot see gear channels).
- `!roles` - Creates Role(Guild Member). You have to assign manually the role to members. FYI I need permission to create the roles (Manage Roles Permission).

</section>
</section>

## Screenshots

<section class='flex col'>
<section markdown="1">

### Example

<img src='https://media.discordapp.net/attachments/435789412974985217/436509845282095115/unknown.png' class='zoom'/>

</section>
<section markdown="1">

### Commands

<img src='https://cdn.discordapp.com/attachments/223778593711456256/461462400068091915/unknown.png' class='zoom'/>

</section>
</section>