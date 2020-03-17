# CATS
Children Assistant to Tell Stories (CATS). A cute companion to tell bed time stories to kids.
https://youtu.be/lAQgH3bdj7Q

## Try it out
https://instagram.com/a/r/?effect_id=2806648022754425&ch=NzU0MDk4YThkNzk4MWYzZjc3ZWI5NjczYWY2ZWIzZDU%3D

## Inspiration
I got the idea of a storytelling companion from one of my undergraduate colleague's thesis which discusses about a chat bot that tells stories to children and at the same time learns and converses with them. Although my submission is only an effect that reads a story based on a simple user interaction and not an actual chat bot (e.g. Google Home), I am inspired with the interactive possibilities that AR can bring in the future.

## What it does
The cute cat reads to you _The Hare and the Tortoise_ story (shortened cut audio clip for demo purposes) when a user taps **Play Story**. The cute cat also appreciates your affection and _**meows**_ while changing the background particles when you pet it!

## How I built it
I got the [cute cat model from Sketchfab](https://sketchfab.com/3d-models/cat-cute-5af376ba056040fd82e389b4b030e084) and built the animation and effect using Spark AR Studio v.83. 
I made use of the following:
<p> 1) Interaction Patches (Screen Pinch, Rotation, Object Tap) - to trigger interaction and animation for the cat model
<p> 2) Animation Patches (Loop Animation and Transition) - to animate the cat when it is tapped and when it reads the story
<p> 3) Audio Patches (Single-clip, Multi-clip controller, Pitch Shifter, Reverb) - for the background sound effect, the story audio clip, and cat meowing
<p> 4) Animation Sequence - to change the background particles when the cat is tapped

## Challenges I ran into
One of the challenges I ran into was finding a suitable audio clip in the right format. Of course majority of the story audio clips I found was in the .mp3 format, and I tried to convert them to the required .m4a format for Spark online; however, the converted .m4a file still cannot be imported into Spark. What worked for me was I had to use a 3rd party software Audacity to manually edit the audio clip (e.g. splitting to mono, adjusting the bit format and Hz rate, etc.) into a correct .m4a format. Another would be that some capabilities like background segmentation and camera texture cannot be rendered into Instagram as an effect, so I omitted these effects to be able to test it in the Instagram app.

## Accomplishments that I'm proud of
<p> 1) My long-search for the perfect meow audio file was worth it XD
<p> 2) I'm glad that the pitch shifter and reverb patches for the meow sound effect came out well and sounded natural. 
<p> 3) I'm also glad that the loop animation and transitions for the cat came out smooth

## What I learned
<p> 1) There are abundant resources such as Sketchfab.com out there that has a ton of ready-made 3D models you can download and play with for Spark AR Studio. 
<p> 2) Spark AR Studio patches are very useful and the studio is a great platform for creating AR experiences.

## What's next for Cute Assistant to Tell Stories (CATS)
I envision that in the future AR models can be interactive chat bots as well-- being able to learn speech input via microphone and in turn converse with users. For CATS, it could be the next favorite children story companion :)

All this wouldn't be possible with [leandrodreamer](https://sketchfab.com/leandrodreamer)'s [cute cat model](https://sketchfab.com/3d-models/cat-cute-5af376ba056040fd82e389b4b030e084) and [Storynory](https://www.storynory.com/the-hare-and-the-tortoise) children audio clips!!!!!!
