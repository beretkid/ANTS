![Cool Preview Image](https://github.com/beretkid/ANTS/blob/main/git/download%20-%202026-05-13T141326.372.png)

ANTS, why do they draw on a weird canvas doohicky?? i don't know! but you have an ungodly amount of them, so you might as well make them scribble all over something!
(Sorry for the mildly long readme, you do not need to read the readme even though it is telling you to.)
FAQ:

"What is this game even about..": This is a zero player drawing.. game(?) you will never paint on any canvases yourself, rather your ANTS do it.
                                Think of it as walking in a random pattern with a comicly large paintbrush attatched to you to make a random painting of that pattern
                              exept theres also 456 people doing the same exact pattern as you, and theres 2766 people that are doing other patterns and occasionally
                            want to beat the shit out of you because they think their pattern is cooler. we all did that when we were kids, i remember it like it was yesterday!

"Are you sure these things are ants??": No silly! thats why they are called 'ANTS' not 'ants' very different; i have no clue what they are but they definitely arent ants!

"What does the shake button do?": basicly just shake all the ANTS around, good for if you don't want them to clump up, and or just want to annoy them.

"Whats the weird Movestyle customizer doohicky?": that is an editor for setting all ANTS movestyles to a specific thing you want.

"How do i open the settings/main menu again?": n is to re-open the main menu, m is to do the same but for the settings menu.


"What in the airplane controls is that settings menu!?": First of all, don't judge me, im very sensitive about my menus. but second of all yea it is pretty bad

"Why do some ants behave differently from others?": What a convient question to get out of the FaQ section and move into a nerdy explaination of mutations for ANTS! 

all ANTS have three main mutables (basicly means changable if you don't know what that means) Variables in them.
one is their movestyle, two is their behavior mutations, and three is their color. all of thease get passed down, and occasionaly get changed slightly
through an ANTS children/spawn/kids/offspring.




v is the direction it moves every tick/frame with radians (its ok if you don't know what that is, as it will very rarely/never will be of importance to you.)
Movestyle is the calculation it runs and adds the result of said calculation to v.

very occasionally it makes 2 other movestyles for the x and y values, but this will only really ever happen if you edit one to do that.

"where is it getting thease calculations from???"

You should not have said th--NERD SHIT AHEAD!!! (look what you have done, we are all going to perish now.)
Basicly it has a list of functions, variables, and operators to use. when it generates/changes a movestyle

When it generates one, it essentaily throws a bunch of those into a horrible tasting but pretty looking stew. occasionnaly it barfs a rng number into there too. delecious!
an example of said stew of doom would look like :

random(-1,1)+t%random(-1,1)-cos(v)

"That Calculation dosen't make any sense at all.."
good! it isnt supposed to!

It also occasionnaly modifys existing parts of a movestyle, like when an ANT mutates.
Nerd shit over. (I lied to you, mistagullibleoverherepeoplegeddaloadovdisgi!)

Don't worry the rest are significantly less nerdy! (And quicker if you just wanna read this and be done with it)

Second is behavior mutations
First of all, they have little to no relation to the movestyles. 
instead it is a list of different variables that influince an ANTS personal behavior in-game.

You will probably never notice them visualy, exept maybe a few, so don't be CREEPY and stalk some poor ANT to see if they have one.
you can stalk them for litterly any other reason though, i don't really care.

third is their color.

this is simply just an rgb value that has a chanace to have its numbers fucked with everytime a new ANT is born.

Heres a list of what all the not-very-self-explanitory settings do (In no particular order):



Fade: This setting makes the canvas slowly get all pixels to whatever "bColor" is.

BColor: This is the color that the canvas will fade will try to fade to.

FadeSpeed: the amount of ticks that pass before the game begins to set each pixel closer to bcolor

Fade amount: how mutch closer it sets it to bcolor each time

Erode: randomly removes a pixel somewhere on the canvas, pretty simple.

OneAnt: Kills all ANTS exept one, good to analyse specific movepatterns, this also will make the remaining ant immortal

GameSpeed: how mutch time (In milliseconds) passes each frame/tick

ViolentAnts: Toggles wether ANTS will try to violently maim/dismember/kill/brutalize/slaugther/act violent twoards other ants from rival teams

FreeForAll: ANTS will no longer care if they are in the same tribes, and inter-ANT-ion.. sorry i mean INTERACTIONS will treat them as if they are from an enemy team.

UseLines: Changes wether ANTS will draw with lines, or dots

ForceColor: Toggles whether all ANTS will have their color ignored and instead use whatever "ColorToForce" is set to instead.

ColorToForce: This is the color All ANTS will use if forcecolor is enabled.

GrainyBackGround: Makes it so when the game fades the pixels a bit, it will jumble/fuck with the values of pixels that are the same color as bColor.

Grain amount: the maximum amount the game will shift background pixels.

Ant Size: How big (in pixels) ANTS will be drawn as, usually you would keep this at 1, but you could really set this to anything.

AntsMutate: Changes whether ANTS will have a chance to be alterred in any way when they are born, change this if you basicly want them to just clone themselves

AntAgression: The global chances for ANTS to get into combat; This is also changed by the ants personal agression mutation value.

DesiredPop: the population the birthrate will try to get it to by decreasing/increasing the chances of a birth each tick.

Reactive Population: this changes the birthrate system to work on a faction-to-faction level.

antAgression: The 0.5/x chance for other ants (If violence is enabled) to try to kill eachother, helpfull if you don't want them to drive themselves to extinction too fast
