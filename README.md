# Events Without Locks

### What is this?
The idea of this project is to allow Shiny Hunters, RNGers or whatever to be able to get Shiny from WonderCards events who are either Locked or Forced Shiny. 

Usually, people use a cheat code or a modified version of the games in order to be able to Shiny Hunt them. In fact, there's a way to just edit the file itself to be able to Shiny Hunt it. If it doesn't imply to edit your game / apply a cheat code, it still needs a way to be able to dump a save and being able to Import a File. You can find more informations about this in the "How I use this?" part.

The focus will be on Gen 5/6/7. I might support Gen 4 and 8 in the future, but it's not really a priority for me atm.


### Credits
Huge props to the [ProjectPokemon.org](https://projectpokemon.org/home/files/category/2-event-gallery/) for dumping, getting all these WonderCards during     all these years. Huge thanks also for allowing me to do that.


### How do I use this?

Find the WonderCard you want, download it from here. For that, go to any file, and click on the Download button. 

I've plans to setup some Release, but not at the moment since a lot of work is necesary. (Little note : You'll not find any item WC here, same as any WC without Shiny Locks from scratch)

#### • Injection with PKHeX
1. Find the specific wondercard or Pokémon file.
2. Drag/drop the file onto PKHeX in the spot where you want that Pokémon.

#### I want a specific Event ? How do I find it ?

The best solution is to go to the [Event Gallery](https://projectpokemon.org/home/files/category/2-event-gallery/) and search for the Event you want. You can refer by either the name fo the file, or by downloading it and comparing the names of both, since I'll not change the name of the files. Easy to figure out..

### How can I be sure that the Shiny Lock has been removed from the file ?

That's a good question. To be honnest, I'm doing that by hand, and it's about editing thousands of files. So a mistake can happen. To be double sure you'll need :

* The file (obviously)
* For Gen 5 : [PokeFinder](https://github.com/Admiral-Fish/PokeFinder/releases)
* For Gen 6/7 : [3DSRNGTool](https://github.com/wwwwwwzx/3DSRNGTool/releases)

You'll want (for both tool) to open the Event tab section with the right generation of game selected. You'll have the option to load a WonderCard. 

Load the file, and you should see "Random" next to the PID part. If you have this, then you're good to go. If not, then it's a mistake and my bad, and you can open an issue to point me where I've failed.

(You might need a game profile to setup that, just leave blank stuff, it's not necessary to have accurate informations)

![image](https://user-images.githubusercontent.com/25870563/165130018-0cff7cf9-1743-4cd1-8c81-48f262481fbd.png)

^The right display for PokeFinder (Gen 5 Event)

![image](https://user-images.githubusercontent.com/25870563/165130213-1ba2787a-a681-4230-b744-631e7164fd23.png)

^The right display for 3DSRNGTool (Gen 6/7 Event)



