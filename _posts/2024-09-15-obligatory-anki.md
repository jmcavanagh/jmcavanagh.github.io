---
layout: post
title:  "Using Anki for Science and Math"
author: "Joe"
tags: learning
---
Lots of people use Anki for learning languages or trying to memorize lots of facts in medical school. There are also lots of other uses, from memorizing poems to programming languages. You can use it to connect faces to names if you're not a face person, memorize quotes to sound wiser than you are, or even how to tie knots. Here, though, I'm going to focus on making an easy-to-read, skimmable guide on how I've used it to study science and math.

# What I do
#### Definitions
The first and most obvious thing that I thought of memorizing with Anki are definitions. Definitions might sound arbitrary, but you'll need to know them if you're going to read papers. Often, definitions also point to very useful concepts for understanding the world--- and at the end of the day, it's this concept that you'll want to know. This is why I prefer cards asking me to define a term to cards asking me to give a term corresponding to a definition. Typically I prefer the "cloze typing" format for this.

<details> 
<summary> example (physics) </summary>
![ex](assets/firstorderphasedefinition.png)
A first order phase transition is one which has {{c1::a discontinuity in the first derivative of Free Energy}}
</details>

#### Connecting concepts to the real world
I also like having go-to examples for my cards. I've found that examples connecting to the real world help me remember a concept and think more concretely about that topic.

<details> 
<summary> example (physics) </summary>
Transition from liquid to gas is a {{c1::first}}-order transition.
</details>

#### Numbers of things
I've found that a lot of expert intuition takes the form of knowing the relative sizes of various things. This is great for sanity-checking, making connections, visualizing, analogizing, and all sorts of other goodness. Knowing a single number is trivia, but knowing a web of numbers and their connections to each other is an intuition.

<details> 
<summary> 
  example (normal-world) 
</summary>
  A blue whale can reach lengths of `{{c2::30 meters}}` and weigh `{{c1::200 tons}}`.
</details>

<details> 
<summary> 
  example (biology) 
</summary>
  The genome of {{c2::an E. Coli bacterium}} is about {{c1::5 Mbp (5,000,000 base pairs)}}, with about {{c3::4000}} protein-encoding genes
</details>

<details> 
<summary> 
  example (chemistry) 
</summary>
  A concentration of 1 Molar is equivalent to one molecule per {{c1::cubic nanometer (nm^3) or yoctoliter}}
</details>

<details> 
<summary> 
  example (physics) 
</summary>
  The peak blackbody emission wavelength of humans is about {{c1::10 microns (1000 cm^-1)}}
</details>

<details> 
<summary> 
  example (computers) 
</summary>
  FLOPs of RTX 4090
  80 Trillion
80 TFLOPs
https://en.wikipedia.org/wiki/FLOPS#Hardware_costs
</details>

(I learned about this method from Drake Thomas)

#### Proofs and derivations.
You can also use anki to memorize proofs, derivations of physical principles, or chain-of-thought reasoning by outlining the proof and using fill-in-the-blank (cloze) deletions on multiple steps. This means that you'll get quizzed on completing or justifying every step of the proof, given the rest of the proof as context. This can be tedious to make, and require a complete understanding of the proof, yet are *extraordinarily powerful* when done well. I can reproduce, entirely from my head, a proof for why the squareroot of 2 is irrational or the reason why minimizing the free energy of a system in the canonical ensemble is equivalent to maximizing the universe's entropy (and also the assumptions that go into these)

(I learned about this from Paul Raymond-Robichaud)

#### Reasons for why things are the way they are
Another great thing to do is to memorize the *reasons* for why things are the way they are, which works great for algorithms and biology (anything which is, in some sense, designed to serve a certain purpose). You can also use these sorts of cards to tether formulas to intuitions.

#### Explanations for how things happen
Another type of card that I like are cards that ask how something happens. A common format I like is to show a picture fo a process and then ask something like "how does this happen". These can get out of hand easily (as in, it's easy to make cards that ask too much and take too much effort. These are called "leeches" and you want to destroy them every time you find them; spaced repetition is supposed to be nearly effortless). Typically these cards don't involve explaining more than two "steps" of a process.

# How I decide what to put in anki vs other notes
My anki deck is a part of me. A piece of my soul resides within it. My memories may fade, time may shape me into a new person, but probably 90% of the cards I have now will remain unchanged. If there is some permanent essence of who I am, it has a .colpkg file extension.

Because of the permanency of my deck, I only put in things that I care about, things that I *want to become part of me*. I try to make sure that the information comes from a relatively credible source, such as a textbook so I don't pollute my memory-horcrux with falsehoods. Typically, if I read a textbook, I take (e)paper notes, then I convert the parts of the notes I think would make good cards into cards. I do this for lots of science and math stuff.  I also try to do this when I read a paper.

Separately, I do use note-taking software (Obsidian) but there's very little overlap between what I put in my anki deck. Typically, I put things into my anki deck after I learn them, and I put things in Obsidian so that I don't have to learn them.

I typically use obsidian for taking notes that I can quickly reference. I mostly use it for things like documentation and arbitrary stuff (like what syntax means what in some python library). I don't put these in anki because although they're useful (for a short time) they're kinda arbitrary, and I am not very interested in arbitrary facts since they don't point towards the interesting truths of the world.

# What I have found to fail
As much as a miracle cure that Anki is, I haven't been able to get it to work with everything. It's easier to learn the right practices if there are also examples of wrong practices.

### Structures of molecules
A month after I started using Anki, I had a thought: "Wouldn't it be awesome if I could just memorize the structures of tons of molecules! I could end up making lots of connections between all of these and see things that others cannot!"

Unfortunately, this didn't work nearly as well as I thought. I did have the success of learning all of the most biologically-relevant amino acids, but then ended up getting extremely mixed up on trying to learn the different nucleotides. I tried cards along the lines of "draw X molecule from scratch" or "which molecule is this picture" and both were quite difficult if it had been more than a month. One I start adding new molecules I'm going to try formulating the cards to ask about the structure of a molecule in terms of another.

### Anything that bores or annoys you
Anki works best when you review it every day. Reviewing it every day sounds like a daunting task, but I find my reviews fun. It usually takes less than 10 minutes and I feel like I'm sharpening my skills with every review. If it felt like a chore, I wouldn't have stuck with it. In fact, there were a few occasions where it did feel like a chore, and as soon as I realized that I wasn't looking forward to the reviews, I deleted all of the "problem cards". If it gets in the way of your fun, it gets in the way of your desire to review. If it gets in the way of your desire to review, it gets in the way of your frequent reviews. You must not dread anki, you must not treat it like a chore. If your card causes you to avoid reviewing, gouge it out and throw it away. It is better to give up on one card than to lose the benefits of spaced repetition in general.

###


