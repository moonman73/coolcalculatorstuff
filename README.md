# coolcalculatorstuff
About:
I finally got a Ti-84 Plus CE after my college algebra professor basically sat me down and told me to stop showing up with my TI-30 I've used since grade school. RIP a real one. Anyways I realized pretty quick these
things can do all kinds of crazy stuff if you can suffer the indignity of using the worst possible code interface. Seriously, whoever came up with a desktop program to "make it easier" and then proceeded to
make none of the fucking key shortcuts for token entries work, forcing you to dig through the god awful catalog and double click every time you want a specific token that it arbitrarily decided isn't represented
in text is a dick. 

Anyways, I'm just kind of making these programs as I go along with my math degree. I'm not a CS major or hobby coder outside of making the worlds worst sides scroller in Gadot a decade ago and some python classes 
in high school, so I make no guarantee that they are not disgusting to look at. They do work though, I basically sit down and just try to figure out how to mash a formula into the Ti Basic for 8 hours until it works
every time. All the programs here seem to give the right answer when tested against as many edge cases as possible, and I have tried to make the UI at least somewhat intuitive, you probably wanna know enough
about the equations and math you're doing to understand what the variables are and what the outputs mean though, its not gunna solve everything for you. 
A lot of these programs are somewhat redundant but focus on automating specific, repetitive busy work. For instance, the Ratroots program does the Rational Root Theorem and gives you the list of all possible zeroes 
of a number. Technically, you can just use the y= function of the calculator to find the actual zeroes, or the polynomial root finder to do the same instantly, but this is useful for when your professor wants you to
write out all possible zeroes for whatever reason though, since it just finds all the factors of P/Q and then mashes them together automatically so you aren't doing 20 division problems by hand.

If you have a Python capable Ti-84, you can do a lot of these in Python if you want them faster or better, but I wrote them in Ti Basic so that as many people could use them as possible. This should work on all
Ti-84, Ti-83 calculators so long as they have Ti Basic and an up to date OS. It does not require jailbreaking or any other shenanigans.

Install Guide:

Download TI Connect CE from the Texas Instruments website. Use the cable that comes with your calculator to connect it to your PC. Open TI Connect. There are only three possible buttons you can press on the sidebar, 
one of them brings you to the program page, it looks like 3 boxes. You can then click "Open Program", open the program you want, scroll through the code if you care to, otherwise just click the "Send to Calculator" 
button, it looks like a little arrow pointing at a calculator. You can change the name of the program or choose to send it to RAM or Archive, it doesn't matter, Archive just shields it from deletion if your 
calculator crashes. Once you've named it or chosen what memory to store it in, just click send. It should be installed basically instantly, these things are like, sub kb level small.

Use Guide:
On your TI-84, press "prgm", its pretty much in the center of the buttons. If you have a python equipped calculator, press 1 to select your Ti Basic repository, if you don't have this function, it should just 
instantly go to the Ti Basic page. You should see your programs here, with "EXEC" highlighted in black. You can scroll through the options and hit enter to select, or just press the number button associated with 
each program. An * in front of a program name just means its stored in archive and is safe from crashes wiping it, if its stored in your RAM, there will be no *. When you click on a program, it will bring up
prgm"program name", just hit enter once to run the program. It should automatically ask for the values of the variables needed, for instance, in "All Integer Factors of N", it will say to Enter N to find the 
Int Factors, and specify that N>0, so just enter the numeric value, for example, 32, and hit enter. It will spit out a solution set of all the factors of 32, as well as a reminder that these are +/-.
You can double hit enter on most programs to rerun them, useful for if you're trying to find multiple factor sets of multiple numbers quickly, for stuff like P/Q by hand or finding a GCF of a real number.
A quirk of the programs is that you do not seem to be able to move your cursor back into the program results to select a solution and copy/paste, but you can just write down the results on a piece of paper
for whatever the next step of your work is, so maybe try that. 

