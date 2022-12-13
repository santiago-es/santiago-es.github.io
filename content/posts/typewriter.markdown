---
title: the infinite typewriter
date: 2022-12-12
---

"To speak is to commit tautologies." - Jorge Luis Borges, "The Library"

>“Forty two!” yelled Loonquawl. Is that all you’ve got to show for seven and a half million years work?
>“I checked it very thoroughly,” said the computer, “and that quite definitely is the answer. I think the problem to be quite honest with you is that you’ve never actually known what the question is.” 
>“But it was the Great Question! The Ultimate Question of Life the Universe and Everything!” howled Loonquawl.
>“Yes,” said Deep Thought with the air of one who suffers fools gladly, “but what actually is it?” 
>Douglas Adams, *The Hitchhiker's Guide to the Galaxy*

You would think that a society full of bullshit jobs would marvel at the invention of machines capable of producing infinite bullshit, and yet...

Chat-GPT, and artificially intelligent language models like it, will change everything, or maybe they already have. Over the weekend, the internet has spent hundreds of hours typing prompts into OpenAI's Chat-GPT3 with the enthusiasm of children tearing open gifts and the impish intent to force the ghost in the machine into increasingly elaborate hallucinations. [One user even coaxed Chat-GPT to create a virtual machine––or is it a *virtual* virtual machine?](https://www.engraved.blog/building-a-virtual-machine-inside/)  Chat-GPT is a language model, meaning it's not really running any kind of machine at all, but it knows exactly what one should look like; it can't autonomously connect to the internet but it knows that machines should be able to, and simulates it; and it certainly can't train and deploy a language model *ab initio*, but it can simulate a connection to one. 

>So, inside the imagined universe of ChatGPT's mind, our virtual machine accesses the url https://chat.openai.com/chat, where it finds a large language model named Assistant trained by OpenAI. This Assistant is waiting to receive messages inside a chatbox. Note that when chatting with ChatGPT, it considers its own name to be "Assistant" as well. Did it guess that on the internet, it is behind this URL? We can chat with this Assistant chatbot, locked inside the alt-internet attached to a virtual machine, all inside ChatGPT's imagination. Assistant, deep down inside this rabbit hole, can correctly explain us what Artificial Intelligence is. It shows that ChatGPT understands that at the URL where we find ChatGPT, a large language model such as itself might be found. It correctly makes the inference that it should therefore reply to these questions like it would itself, as it is itself a large language model assistant too.

Like Salman Khan once said of Euler's identity: if this doesn't blow your mind then you don't have a heart. But what about the things that language models like Chat-GPT won't, or better yet, *cannot* change? This blog post is some musings mostly about those things. 

First thing's first: I'm not an AI researcher––but I've had a mind for at least most of my life, I think. Over 28 years this mind, among many other things, has written a number of poems, short stories, essays, exams, mathematical proofs, music, drawn sketches, composed what must be millions of text messages and e-mails, imagined board games and conversations, constructed computer code, analyzed data, and made graphs (all badly, for the most part), and all of this it has done with language. Nevertheless, the entirety of this output could probably be approximated, some of it improved even, by Chat-GPT3 in a single afternoon of furious, nonstop typing. At the very least, Chat-GPT3 would've come in *real* handy in college when I was struggling through a class on Hegel's *Philosophy of Right*. Here's the bot producing a simple, digestible but competent summary of *Right* and Hegel's tripartite division of social life from the book. 

![](https://i.imgur.com/DZ5ZbPU.png)

Last night, I fed GPT3 a block of text from the computational methods section of a scientific preprint for which a GitHub has yet to be published. It produced a logically plausible, if technically unusable block of code. 

```
# Install the Biostrings package
install.packages("Biostrings")

# Load the Biostrings package
library(Biostrings)

# Read the FastQ files
fastq_files <- readDNAStringSet("path/to/fastq_files")

# Define the telomeric repeat pattern
telomeric_pattern <- "CCCTRR"

# Find the telomeric repeats in the FastQ files
telomeric_repeats <- matchPattern(telomeric_pattern, fastq_files, max.mismatch=6)

# Combine the ranges of each pattern
telomeric_ranges <- union(telomeric_repeats)

# Extract the telomere length and read lengths
telomere_length <- width(telomeric_ranges)
read_lengths <- width(fastq_files)

# Calculate the telomere density
telomere_density <- telomere_length / read_lengths

# Plot the telomere density
plot(telomere_density, type="l")

# Calculate the moving window average of the telomere density
moving_average <- rollmean(telomere_density, k=50)

# Plot the moving window average of the telomere density
plot(moving_average, type="l")
```


While not precisely the right syntax for some functions or able to produce the desired output (in this case, measure telomere length from a consensus sequencing read in R), this is a perfectly workable block of pseudocode which can be edited and filled-in to produce the desired outcome. For a bioinformatics noob like me, this is an invaluable productivity and learning tool. I anticipate I'll have a bot like Chat-GPT3 as a permanent consultant throughout the rest of my PhD and, likely, scientific career. I often feel inadequate or regret for being an exceptionally amateur software engineer. Inadequate because the data my experiments produce could really use an expert hand to squeeze every ounce of insight we can get from it; regret because I took classes like "Hegel's Philosophy of Right" in college instead of "Intro to Computer Science" in spite of my undergrad conveniently housing a top CS department ("an education for a life not a living..." I repeat to myself like a hail mary). Maybe I don't have to feel those feelings anymore! 

But I will. Why? Well, because I'm human, but more importantly because I was raised Catholic. When it comes to homework or actual work the potential for language models like Chat-GPT3 to make our lives easier and the quality of our work better is already immense. Imagine what will be possible with Chat-GPT4, 5, or 10! But the structures in which that work is done, the intent and motivations driving the work, and the connections we have to it will be, ultimately, man-made, human, the products of an analog conscience. Insofar as AI will contribute to the aesthetic flattening of all culture, it will merely accelerate the processes we designed and unfolded––some nitrous oxide for the bulldozers.

## Art is dead...again...part 2...redux

As impressive as Chat-GPT3 is, it is an aesthetically mediocre "writer". Here is the output of a prompt asking GPT3 to write a poem in the style of Edward Gorey.

![](https://i.imgur.com/ULZNI4u.png)

Gorey was known for his love of the macabre, gothic, and absurd. Indeed, Chat-GPT3 "knows" this because it says as much before and after it produces the poem: 

>"This poem is written in the style of Edward Gorey, with a macabre and humorous twist. It is inspired by Gorey's distinctive writing style and his love of the absurd and the uncanny.

*Inspired* is an amusing word choice for an artificial intelligence which, in reality, was inspired by my prompt. Anyways, this poem is...boring. Especially for Gorey, whose nursery-like rhymes were seeped in absurd comedy, horror, and violence.

!["Edward Gorey - the Listing Attic"](http://4.bp.blogspot.com/-pppMb2FBNmw/UkcTJz5g8XI/AAAAAAAAHzE/dIfMS2cLVa8/s1600/Gorey+1.jpg)

But in GPT3's defense, it at least got the macabre theme correct insofar as the poem takes place in a graveyard but not much further than that. It's a bit like Netflix's *Wednesday* or *Sabrina the Teenage Witch* reboot in that regard, but that's the subject for another blog post (I have thoughts!!).

I also tried to coax GPT3 into producing a poem in the style of my favorite poet, Juan Gelman. Gelman had a penchant for neologisms, wrote a significant number of love poems, political poems concerning Chile and Latin America more broadly, and often invoked themes of magical realism and nature. 

![](https://i.imgur.com/G2yrjsZ.png)

This is certainly a poem, but once again it is rather boring and not remotely in the style of Gelman. Here's Gelman's "Bellas Compañias / Beautiful Companions" and my translation below it:

>es muy común que un buitre me trabaje las entrañas no devorándolas sino más bien amándolas o como desgarrándolas para sacar a luz mis rostros últimos y  míralos me dice mira lo que te comes animal me dice el bello buitre

>it is very common for a vulture to work my entrails not devouring them rather loving them or ripping them to give light to my last faces and look at them it says look at what you eat you animal the beautiful vulture tells me

AI has a long way to go. Many have already said as much, remarking that AI writing has a certain sameness to it. But, you might say, there's nothing to say these aesthetic limitations are limitations at all, just give it time! And, sure, I believe that. I believe AI like Chat-GPT3 will improve, probably write something indistinguishable from authentic human writing, and, perhaps, a few beautiful things, too. What will be the point of art then? What will be the point of honing a craft for decades if a computer can surpass you in an instant? 

I'll let Juan Gelman answer for me (from his poem, "Confianzas/Confessions" and my translation below): 

se sienta a la mesa y escribe
«con este poema no tomarás el poder» dice
«con estos versos no harás la Revolución» dice
«ni con miles de versos harás la Revolución» dice

y más: esos versos no han de servirle para
que peones maestros hacheros vivan mejor
coman mejor o él mismo coma viva mejor
ni para enamorar a una le servirán

no ganará plata con ellos
no entrará al cine gratis con ellos
no le darán ropa por ellos
no conseguirá tabaco o vino por ellos

ni papagayos ni bufandas ni barcos
ni toros ni paraguas conseguirá por ellos
si por ellos fuera la lluvia lo mojará
no alcanzará perdón o gracia por ellos

«con este poema no tomarás el poder» dice
«con estos versos no harás la Revolución» dice
«ni con miles de versos harás la Revolución» dice
se sienta a la mesa y escribe

————

he sits down at the table and begins to write
“with this poem, you won’t take power”, he says
“with these verses, you won’t bring the Revolution”, he says
“not with thousands of verses will you make the Revolution,” he says

and more: these verses won’t help
the workers, teachers, and woodcutters to live any better
eat better or even himself eat, live better
not even to enamor a single person will they serve you

he won’t make money with them
he won’t get into the theatre for free with them
they will not give him clothes for them
he will not find tobacco or wine for them

not parrots nor scarves nor ships
nor bulls nor umbrellas will he find for them
if it was but for them the rain would drench him
he will not find forgiveness or grace for them

“with this poem, you won’t take power”, he says
“with these verses, you won’t bring the Revolution”, he says
“not with thousands of verses will you make the Revolution,” he says
he sits down at the table and begins to write

Or, in other words, why do people make art? Because they need to. We *need* to create to live. Even if it's a joke among friends, a good conversation, a song we sing to our cats in the morning by way of salutation, a particularly mercenary insult, a meme. And, of course, to share those creations with others. Even if AI never advances aesthetically, which of course it will, some people might be concerned that some mediocre pulp produced by AI might be mistaken for an insightful innovation. To quote Eric Andre when asked by Larry King why he dropped out of Berkeley College of Music: "Justin Bieber sells records." Well, Rupi Kaur sells books. 

Wait, I can hear you say, for many (like Rupi Kaur) art *is* work. What about them? There are a number of artists currently pleading with the public to avoid AI painters like Lensa, etc. because they risk putting artists out of work. Indeed, these other AIs, especially commercial ones, are certainly extracting value from the internet's vast artistic communities as the training data is made up of their collective works. And when an AI is told to create something "in the style of X", much like I did with Gorey and Gelman's poetry, whom is being extracted from and how is precisely discernible. 

Like streaming changed the market for musicians forever, so too will AI transform the market for digital artists and writers. The capitalist machine's insatiable hunger will not balk at crushing a few artists and people will not forego free or basically free art for expensive artisanal work *en masse*. Nor will artists be freed from the material needs of hunger, shelter, of life that demands they sell their labor. These are the facts of the hegemonic social system we have created and inhabit, facts of a capitalist economy. There are, scientifically speaking, few cons to the development of technology that means everyone will have to do less work; there are, nevertheless, very many anxieties surrounding that same technology in societies where the overwhelming majority of people must work or starve. The root cause of anxiety over AI is not about AI at all, it's about the organization of society. 

That said, AIs like Chat-GPT3 are not distinct or removed from the societies that created them, either. [Indeed, there is a large body of work on this subject coming from both industry and academia](https://www.vox.com/recode/2020/12/4/22153786/google-timnit-gebru-ethical-ai-jeff-dean-controversy-fired) which has been at the core of ethical tensions in the development of artificial intelligence, particularly with how AIs trained on data produced by a society totally permeated by centuries of prejudice and social, economic, religious, and racial caste can be built to not merely reproduce or enforce that problematic history. Chat-GPT3, in spite of built-in guardrails meant to protect against this, has itself fallen into this trap, for example. 

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Yes, ChatGPT is amazing and impressive. No, <a href="https://twitter.com/OpenAI?ref_src=twsrc%5Etfw">@OpenAI</a> has not come close to addressing the problem of bias. Filters appear to be bypassed with simple tricks, and superficially masked. <br><br>And what is lurking inside is egregious. <a href="https://twitter.com/Abebab?ref_src=twsrc%5Etfw">@Abebab</a> <a href="https://twitter.com/sama?ref_src=twsrc%5Etfw">@sama</a><br>tw racism, sexism. <a href="https://t.co/V4fw1fY9dY">pic.twitter.com/V4fw1fY9dY</a></p>&mdash; steven t. piantadosi (@spiantado) <a href="https://twitter.com/spiantado/status/1599462375887114240?ref_src=twsrc%5Etfw">December 4, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

This problem is not restricted to language models, either. Clinical AI tools suffer from similar problems, compounding the built-in technological bias medicine is already clumsily just beginning to reckon with (e.g. pulse oximetry, eGFR, etc. as I wrote about in an earlier blog post). But these flaws, much like the organization of our society, were created by us and can be undone by us. [For example, by fine-tuning AI models to close previously existing gaps which meant more errors and misdiagnoses for darker skin tones](https://www.science.org/doi/10.1126/sciadv.abq6147). 

The uncanny sameness of AI-generated whatever (at least, as of writing this) is, also, a reflection of the society which has produced it. This is both literally––given robots like GPT are "trained" by gorging them on petabytes of text, on the infinite excrement of the internet--and figuratively true. Instead of writing at length here, [I'll quote a recent article in n+1 on the homogenization of visual life](https://www.nplusonemag.com/issue-44/the-intellectual-situation/why-is-everything-so-ugly/):

>Writing a century ago, H. L. Mencken bemoaned America’s “libido for the ugly.” There exists, he wrote, a “love of ugliness for its own sake, the lust to make the world intolerable. Its habitat is the United States.” However mystical and psychosexual his era’s intolerability might have felt in its origins, by the 1940s the explanations were more prosaic. With the wartime rationing of steel and sudden dearth of skilled labor, concrete structural systems quickly gained appeal — as did buildings that could be made piecemeal in a factory, put on a trailer, and nailed together anywhere in the country. And as the postwar baby boom took hold, such buildings were soon in high demand, fulfilling modernism’s wildest dreams of standardization with little of the glamour. A few Levittowns later, the promise of salvation-by-mass-production would come to seem elusive: new manufacturing techniques were transforming both the buildings and the builders building them. In Prisoners of the American Dream, Mike Davis describes how, in the 1970s, “the adoption of new building technologies involving extensive use of prefabricated structures, like precast concrete, eroded the boundaries of traditional skills and introduced a larger semi-skilled component into the labor force.” If it’s cheaper to assemble concrete panels than to hire bricklayers, cityscapes will eventually contain fewer bricks.

It should be telling the most threatened group of people online in the wake of ChatGPT 3.5's launch has been those who write marketing copy for a living. There are already an uncountable number of AI-assisted native marketing articles disguised as blog posts polluting every square inch of the internet, machine optimized to win the twin wars of search engine optimization and converting your clicks into purchases. It simply does not matter if a real person is behind a listicle explaining how these 5 apps are a must for any music-lover. It will not matter if every in-podcast or Youtube sponsored ad meets the same fate. The same aesthetic revolution that brought us the mass produced pre-fab greige bourgeois shanty towns cities have become shall also descend on the "creative" disciplines––professionals writing or drawing for money to a mass audience with the intent to move product. But it will not do so because AIs write mediocre copy. Well, they do write mediocre copy...*for now*. One day, it'll be passable at the very least. But the aesthetic dimensions of what texts will be deployed will not be determined by the ghost in the machine, they'll be determined by us. A version of us anyway: the invisible, blind, and unrestrained hand of the market whose tendency to the mediocre is directly in proportion to the size of the lowest common denominator.

So, what does the future look like? The fact that there is no further physical junk produced by artificial intelligence to add to the ponderous mass of commodity capitalism's rejectemanta is, at least, a small mercy until one considers the enormous carbon expense of training and then fueling a fleet of black-box brains wired to typewriters. While I have not done the math, it is possible it is still cheaper than raising a child. There's a frightening thought. In the most radically optimistic of futures, one could consider a world like in Borges' "Library". A infinite and all-encompassing number of hexagonal rooms, all connected, containing every permutation of the 23 letters and punctuation marks imaginable in an uncountable number of shelves and books. Well, a world *figuratively* like that anyway. If the ideal language model is effectively an infinite typewriter, it would, in this metaphor, be a search engine for an infinite library of knowledge. The task of the user, the human, would be to parse this output into meaning, find the signal in the noise. But why should that be a human? Why not simply put another, similarly intelligent, robot to the task and then parse *that* filtered output into meaning. 

It's all a bit science fiction, I know, but it's better than the truth that a society on the cusp of drastically accelerating the acquisition of all knowledge will most likely not survive the next century if it does not radically change course in how it employs, treats, values the people that make it up, the things they do, the places they live, and the culture they share. 


