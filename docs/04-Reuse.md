# Re-Use

Reusing code is the cornerstone of productive programming. Reusing libraries and packages built by other people is very common. Reusing your own code - packing it up into little re-usable blocks is also very handy.

Designing your programs such that you can re-use them will bring you great benefits. The code will be easier to build and understand, this means you'll have less trouble building it, take less time and likely have fewer bugs. 

In this section we'll explore personal re-use of something you built by making our own Scratch blocks.

> We are like dwarfs standing upon the shoulders of giants, and so able to see more and see farther than the ancients.
– Bernard of Chartres, circa 1130


## Implementing blocks

Let's begin by making some blocks of our own.

\BeginKnitrBlock{task}<div class="task">
  1. Do the [Characters worksheet](worksheets/scratch_characters.pdf). 
  2. Make sure you define two characters and two behaviours per character
      * can you make `broadcasting` work between your characters? [^4] 
  3. Discuss with a friend (or write in your design journal) about how `Make a Block` works. Come up with a description for a person new to blocks.
  4. When might you use `Make a Block`?
  5. I asserted that re-using blocks results in fewer code bugs. Discuss how that be justified?
</div>\EndKnitrBlock{task}

Hopefully through these exercises you've seen that code re-use is a timesaver - once you've worked out how to actually implement the code in new block that is.  

## Fixing some bugs

Let's get a bit more practice and intuition about how blocks work by fixing some broken ones. 

\BeginKnitrBlock{task}<div class="task">  1. Do the [Blocks debugging worksheet](worksheets/scratch_blocks_debugging.pdf)
  2. Discuss the following: 
      * How big or small do blocks have to be? 
      * Would you ever want a huge block that did lots, or are smaller specific task blocks best? 
    * Is there an optimal level of re-use?
</div>\EndKnitrBlock{task}

## Abstraction

A big plus to constructing blocks is that they are a tool for abstraction - they allow us to combine multiple small abilities into one larger, unifiying ability. This means that the amount of thinking we have to do about how our program works is less. In turn this means it is easier for us to progam. 

## A major insight - its blocks all the way down

If the concept of blocks seems like it might be a bit generally applicable, you're getting the key lesson of this section. All programming is either defining or re-using blocks of code. In this section with Scratch, its mostly been that our blocks have been a few commands that we want to re-use a couple of times. At different layers the blocks might be different levels of organisation of software. Some blocks with a few commands in each might be strung together into a bigger block called a script or program. A few scripts or programs might be strung together into a workflow, and there are levels under and above each of those. Beginning to think of programming at different levels of abstraction is a significant step in building your conceptual model of how programs and software in general works. 

## In this section we ...

\BeginKnitrBlock{roundup}<div class="roundup">
In this section we built and used some custom blocks. We've seen how they can be reused, and remixed - a process called abstraction and modularisation. These practices vastly reduce work for the programmer and increase integrity of our programs. 
</div>\EndKnitrBlock{roundup}

[^4]: Don't panic if this doesn't work - broadcasting in Scratch highlights a technique in which we make different processes or scripts 'talk' to each other through messages. Its not a core technique by any means but the metaphor of 'talking' is here particularly strong - and it's quite fun - so its worth a go.

