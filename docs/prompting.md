# Prompt Guidelines for AI Art Tutorial (Copilot)
**By C. Reimer**

After using Microsoft's Copilot/Designer AI for a little while and sharing the results, I was encouraged by colleagues to write up a summary of what I've observed so far and share my 'prompt engineering' toolkit. For the most part this tutorial will be aimed at a casual audience looking to use AI to produce character or landscape art for personal use, but general guidelines will be covered as well.

## General Guidelines
To start with, some observations that apply to multiple types of image output.

### Keen Wording is Key
Firstly, _do not_ tell Copilot what you want outright, it will often find a way to sidetrack or ignore you due to erroneus associations with keywords or particular words rousing its censorship.  For instance, if your prompt included the word "avatar", do not be surprised if the output is cross-pollinated by styles from either the animated show or James Cameron's movie of the same name.

As well, avoid at all costs specifying quantities, as AI image generation doesn't typically recognize the significance of items such as 'two suns', 'three horses', 'no clouds'.  A more effective wording for these would be 'binary suns'/'multiple suns', 'small group of horses', and 'cloudless'/'clear sky' respectively.

### Pay Attention to Word Order & Structure
Order your words in such a way that ambiguity is reduced and adjectives refer to their correct targets.  The prompt "An oil painting of a knight on a horse with black armour" could give you a horse wearing black armour instead of, or in addition to, the knight.

### Add Framing Words
Context helps pin down some details that AI could otherwise take great creative liberties with, including background, setting, poses, and more.  I prefer to separate these out with commas in my prompts, such as "Please draw a \[main content], **\[Pose and/or expression]**, **\[description of background imagery]**, **\[define artstyle]**"

### Prepare for Unforseen Outcomes
A prompt may lead to extreme variations that have little or nothing to do with the intent of your initial request.  Sometimes these 'happy accidents' are the most interesting images the AI makes.

### Cleanup
Cleanup is not nearly as exciting as having a machine make interesting images at your bidding, but rest assured, it doesn't have to be too dull.  If your images have features that you don't like or they have more fingers than there are piano keys, they can usually be corrected. Download and edit them locally with the Microsoft photos app **'generative erase'** tool or use the more powerful online version by selecting **'Edit in Designer'** on the Copilot interface first.  

A note for the desktop version of the generative erase tool; you do not need to be particularly careful with the brush.  As long as you capture the whole item you want to erase under the brush stroke(s), it typically leaves surrounding areas unharmed, especially if the item is visually distinct from the surroundings.  I've actually used generative erase several times to polish smeared edges from previous erasures simply by capturing a narrow strip of pixels defining an edge or seam.

## Styles
The flavour of a piece is an essential component that modifies almost every aspect of the result in some way.  Try to keep in mind the essential lines, colours, shapes, and even subject matter of various artstyles, as Copilot seems to do better when working with familiar material, just as humans tend to.

For instance, something made in the style of "art deco" or "art nouveau" will be starkly different in tone than, say, "american gothic", with different (simulated) painting mediums, lighting, and levels of detail.  Keep in mind that any of these can be combined in your prompts as well, though adding too many may make the resulting theme 'muddy' for lack of a better term.

With that out of the way, let us highlight a few arbitrary art movement keywords and the traits that they can evoke from Copilot:  
1. **Art Deco** -->  A 1900s-1920s theme, tends towards lavish solid materials, well-defined edges and shadows, favours architecture
2. **Art Nouveau** --> A turn of the (20th) century style, favouring beautiful, organic, warm colourful scenes, card decorations

As well as some artstyle keywords:
1. **Sketch** / **Colour sketch** --> Great for Hyborean/gothic/lovecraftian horror B&W sketches, or older styles of comic and book illustration, concept art, etc.
2. **Illustration** --> More of a pencil/colour pencil look, lines/strokes may be visible
3. **Oil painting** --> Realistic classical painting, especially for portraits and landscapes
4. **Watercolour** --> A gentle artstyle with a vivid, sketched appearrance
5. **Gritty comic** --> Fantastic semi-realistic look for characters and scenes, more well-defined edges and transitions than the 'Fantasy' prompt alone
6. **Cyberpunk** --> Merging flesh and wires, circuit and sinew, this prompt often impacts backgrounds and characters severely, but can be well worth it
7. **Fantasy** --> Likely due to the influence of TTRPGs and comics, this prompt induces soft, 'modern' fantasy images with a pleasing (but not always memorable) look
8. **Hyborean** --> Old-fashioned, muscular barbarian style art
9. **Fey** --> Fey is a word with multiple meanings, but in the present it often refers to elvish themes and tends to yield magical flair and insect wings
10. **(Un)seelie** --> A good partner word to prompts for fey characters, seelie and unseelie refer to Scottish folklore surrounding good and bad fey respectively

## Form & Expression
Form and expression are basic building blocks of character pieces such as portraits or cover art.  A good grab-bag of the many terms in English for expressions and states of being is very useful here:
1. **Lithe** --> Lean and muscular traits that might bias outputs towards feminine forms
2. **Withered** --> Shriveled, weak, bent over, useful for non-humanoids too
3. **Emaciated** --> Starved, ultra-lean creatures, ribs showing, patchy fur, etc.
4. **Husk** --> Withered output on overdrive, bias towards much more corpse-like features
5. **Sunken eyes** --> Deep dark eyes, weary looking
6. **Smirk**, **coy**, **sneer**, **cruel** --> Expression words that all involve subtleties of facial muscles without showing teeth
7. **Snarl**, **screech**, **bellow**  --> Expression words that show a sizeable amount of teeth
8. **Ornate**, **embroidered**, **intricate**, **carved** --> Detail words with different meanings, I find they work best with metal, cloth, fine details, and stonework respectively

<figure>
  <img src="{{site.url}}/assets/images/ai/Gnome.png" alt="A hunched gnome with a lot of character, clutching a quaint shortbow" width="640"/>
  <figcaption style="text-align: center; font-style: italic; color: grey;">A hunched gnome with a lot of character, clutching a quaint shortbow
  </figcaption>
</figure>

## Colour
Colours are one area of prompts that usually work fairly well without elaboration.  However, there is one particular tip that has served me well for avoiding the vaguaries of phrases such as "bright pink" or "deep blue"; classics often produce especially rich colours compared with generics.  The method is simply to use the traditional names for specific well-known colours derived from historic dyes and pigments.  

Here are a few examples that you can try:
1. **Indigo**, **cerulean** --> Deep famous blues
2. **Turquoise** --> A unique blue-green from copper ore
3. **Lavender** --> A delightful soft purple hue
4. **Ebon**, **sable**, **charcoal**, **jet** --> Dark colours from hardwoods, furs, fuel, and gems
5. **Vermilion** --> Bright, intense red from the mercury ore cinnabar
6. **Scarlet** --> A deep and dark red
7. **Ochre** --> Deep earthy oranges, browns, yellows

## Armour & Fashion
What character is complete without a personalized style?  In history and literature, one tends to pick knowledge of these things up like stray pennies on the sidewalk.  Hopefully this list speeds that process up.  Copilot is generally quite good in this area with minimal nudging.

### Armour
1. **Quilted/Padded tunic** --> A fantastic look for non-metallic armour, a densely packed textile-based protection that is historically abundant as well as easy to embellish with other prompts
2. **Brigandine** --> Metal armour with plates or strips of metal embedded into the reverse side of a more flexible material, sometimes giving the outer layer a stiff, studded appearrance
3. **Chitin** --> Chitin is the name for the material that composes arthropod shells, like insects, crabs, etc. and produces very exotic armour images

### Fashion
1. **Robe** --> The most basic of clothing, can be altered with words such as **'hood(ed)'**
2. **Frogging** --> A personal favourite, a back-and-forth embroidery and buttons detail on the uniforms of European military officers a few centuries past, now found on elaborate jackets of hotel staff
3. **Greatcoat** --> A WWI and earlier style of overcoat, perfect for portraying war-weariness and wet, muddy conflicts

## Exotic traits
In science fiction and fantasy images, there is often a demand for the unusual.  If you are interested in producing an image of bug-people from Venus or such, then there are a few things to pay attention to in the prompt. 

### Scales & Skin
If you want scales, go with 'scaled skin' or 'scales', not 'lizard skin', unless you want a full-body lizard-man complete with reptile eyes.  I think Copilot tends to break things into parts, so lizard skin becomes 'lizard' + 'skin' or 'lizard' + 'lizard skin'.  There are many types of scales as well, and per the suggestions in earlier sections, knowing the true names is invaluable:
1. **Scales** --> Your basic lizards, snakes, fish, etc.
2. **Scutes** --> Tough scales mixed with horn, often banded or reinforcing other scaly hides, found in crocodiles, turtles, birds, etc.
3. **Osteoderms** --> Protective bony nodules found in and under the hides of some creatures, synonymous in many cases with scutes, but more commonly associated with extinct mammals
4. **Pebbly** --> Skin like a toad, rough and bumpy but not truly scaled

<figure>
  <img src="{{site.url}}/assets/images/ai/Purple Frog.png" alt="A character with pebbly toad-like skin" width="640"/>
  <figcaption style="text-align: center; font-style: italic; color: grey;">A character with pebbly toad-like skin
  </figcaption>
</figure>

### Horns
These are some of the most tricky in my experience.  They come in many styles but Copilot has a limited ability to pick up on modifications such as "Shorter" or "less curly".  In order to get the horns you want, try to specify "**location**, **surface**, and **direction**", i.e. "knobbled horns sweeping past temples" or "pearlescent smooth horned brow".  Alternatively, break the advice from earlier and ask for the _specific_ type of horns you want directly, i.e. antelope, gazelle, moose, etc.

### Ears
A simple aspect but one that can be very inconsistent in the end product.  Here are a few observations to help with prompting this trait:
1. **Pointed** --> Ears you could use to catch radio signals, this tends towards excess
2. **Elvish** --> Ears are generally the correct shape but the size remains highly variable, favouring large sizes
3. **Narrowed** --> More reasonably sized, good for half-elves and more standard elves
4. **Tapered/Tapering to a point** --> Bizarrely, this seems to work extremely consistently for ears in the human, half-elf, and LotR movie elf sizes

### Wings

<figure>
  <img src="{{site.url}}/assets/images/ai/Monarch.jpg" alt="A character with monarch butterfly wings" width="640"/>
  <figcaption style="text-align: center; font-style: italic; color: grey;">A character with monarch butterfly wings
  </figcaption>
</figure>

## Landscapes
<figure>
  <img src="{{site.url}}/assets/images/ai/City Walled.png" alt="An example cityscape in a planetary romance or science fantasy style" width="640"/>
  <figcaption style="text-align: center; font-style: italic; color: grey;">An example cityscape in a planetary romance or science fantasy style
  </figcaption>
</figure>

<figure>
  <img src="{{site.url}}/assets/images/ai/Jupiter Station.png" alt="A contrasting vista of a space station hanging in the turbulent atmosphere of a gas giant" width="640"/>
  <figcaption style="text-align: center; font-style: italic; color: grey;">A space station hanging in the turbulent atmosphere of a gas giant
  </figcaption>
</figure>

## Conclusion
I hope you have gained something from this article.  Concerning AI art, my view is that the program makes art with the human as a director or patron commissioning the work.  Please use this remarkable tool responsibly and get some great images.

Happy prompting!
