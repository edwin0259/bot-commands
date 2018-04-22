# How to contribute to maestro commands

Covered here will be how to use github to submit your changes and the format of the json file you will be working with.
_______
## Formatting of json file

Some things to note about the `commands.json` file

1. Inside the curly braces are each of the user suggested commands.

2. The string before the colon is the command name _Do not add a bang infront of the command (!) , that will be done by maestro_ . If you would like multiple names for a single command, separate the commands with a pipe character (|).

3. The value (after the colon) can either be a string representing text, image links, gif links, or it can be an array of strings (inside square brackets []). If you use an array, the bot will pick one of the items at random when the command is triggered.

Here is the `commands.json` at the moment file for reference
```javascript
{
  "rollem": ["https://media3.giphy.com/media/a6OnFHzHgCU1O/giphy.gifn 1863, Hooray! Hooray!", "https://media.giphy.com/media/pxy9QQUMF0glq/giphy.gif"],
  "rekt": "https://static.fjcdn.com/gifs/Rekt+gif+comp_e5da7a_5444027.gif",
  "dunno|idk|meh|shrug": "¯\_(ツ)_/¯",
  "cat|kat":  "https://giphy.com/gifs/cat-hacker-webs-o0vwzuFwCGAFO"
}
 
```

## Purpose

I've been getting alot of command requests, this will make it easier for me to give you the opportunity to have some of those commands added to the bot.

The vision is that a couple of these commands will be selected every month by the bot at random and will be `commands of the month`. (Because the possibilities are endless and I need a way to keep the bot incheck and under control ;).)

## Contributing

1. Click the `commands.json` file
2. Click pencil icon next to the trashcan (You should be logged into a your github account)
3. Edit the file with new commands/changes
4. Click `Purpose file change` at bottom of page
5. Click `Create pull request` on next page
6. Wait for me to look over and possibly add the changes :)

## Questions

Feel free to create a `new issue` in Github with your question.
