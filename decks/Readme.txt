Hello, This is the Devbot (A modified WindBot) For DevPro.
Firstly always keep a backup of the files if you intend to modify anything and please do NOT modify stuff you don't understand.
There is a high chance of breaking the bot and requiring to re extract, Anyway allow me to go over the basics.
The F/L list file.
This is here to show you what formats the deck is legal/illegal in. Please note that Devbot games have "Don't check deck" enabled meaning it'll just give whatever is in the .ydk file. 
You could play with a 5 card deck if you wish, you could play with 60 copies of the same card etc etc. This is just if you want to test and want a more "Releastic Experience"
It can be modifed to adjust these changes but I'l go over that later.
Why does it only have (AI_RandomDeck) 
You see becasue I can't detirme exactly how it's intending to pick it (Im still going over the code adjusting things to try and fix it) It just picks a random deck everytime.
Rather then have it Unclear and just say a deck thats probably not going to be picked I've made it blantantly apprent that it will be random to avoid confusion.
Does the AI have any other decks?
Yes it does, they are extremely old and in general not fun to play against. They can be found in the "Decks" folder and then Other. Please not AI_Lightsworn is broken and the bot will not play anything
Can I modify these decks?
You can but when modifying these you need to be extremely careful in what gets changed. I'l be going over the most common cards to swap with Forbidden cards to make it TCG Legal.
Please note if a card does not have excessive scripting telling it what to do it'll just ignore it. (For example giving the AI Pendulum call + pendulums it won't ever use any of them)
Firstly copy the deck(s) you want to adjust from the "Decks" Folder into the "Deck" folder. Then open up deck edit and swap with the following cards 
I'd personally advise swapping those cards with the following. Upstart Goblin, Maxx "C", Galaxy Cyclone, Cosmic Cyclone, Royal Decree, Pot of Desires, Mirror force, Dimensional barrier
If it crashes/stops using that deck after saving it and putting it back just place the orginal back in your deck folder and request some help with modifying the deck.
Can I edit what the bot says? 
You can, its in Dialogs, Default.json (Right click Open as notepad) just make sure to keep a backup incase you corrupt it before modifying anything incase you need to restore it. If you have problems request help.
Can I make it default to "New Master Rule/Master Rule 4?" 
As far as I know not currently, Need to find where that value is set and change it.

Still have any questions/need help feel free to post on the Staff beta server. - Dragon




