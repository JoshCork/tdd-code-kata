## Progress by Day

### 2/20/2018 (Day 12)

#### Kata 2


#### Kata 1

Made it through step 5 again on the first try.  Would have made it through step 6 if not for a few interuptions (because step 6 only takes about another 10 second to implement and 5 seconds to add a test case).

I also got caught up on a few crazy errors where i had my strings.index function backwards because I was hurrying too much.

I'd like to get through this again with lots of time to spare so that I can work through step 7&8 and add those to my timed results.  These should be realtively easy to incorporate as step 7 is already the case (w/out the formatting of the brakets[]).  Step 8 will be a little harder but should be relatively easy to iterate through my find delimiter function.  I'll need to do some exploration with that first.


### 2/19/2018 (Day 11)

#### Kata 1
Excellent progress.  I finished after a bit of troubleshooting just after 30 minutes.  I would have been done before had it not been for a typo in my error message and making comparing the string error to the memory location of the error.  So i used ```testCase.theErr != err.Error``` instead of ```testCase.theErr != err.Error()```

### 2/18/18 (Day 10)

#### Kata 1

Finished with 4 minutes to spare through step 4.  Getting better. Need to keep improving.  Removed the need to create a left trim function just trimming the slice directly based on the locaton of the first new line character.  Did this after the fact though.

#### Research

Need to update my Add func to return errors (but I'm not there yet).
Some good discussion on stack overflow about this: https://stackoverflow.com/questions/42035104/how-to-unit-test-go-errors

Now time to go back and do another Kata or two and get comfortable with step 4 before I move on to step 5 and error handling.\

### 2/16/18 (Day 9)

#### Kata 1: 2:17p - 2:47p

Whoa!  This went really well.  Was able to finish through step 4 on my first try of the day.

**Possible Improvements**
I could maybe combine my helper functions to return a couple of values (the delimiter and the string w/out the prefix)?
I could change my helper function into a prep string function that replaces the delimiter with commas and then returns the string pre-formatted.



### 2/9/18 (day 8)

#### Kata 1: 3:59pm

Made it through step 3, started on step 4.  Not too shabby.
Got hung up for a long while on my struct for my table driven test.  I spelled struct wrong and it took forever to figure out what the error was.

### 1/16/18 (day 6)

#### Kata 2: 4:35pm to 5pm (25 minutes)

Ugh. Almost finished with step 4.  Need to memorize a pattern for getting substrings out of a string efficently.  I think the answer can be found here:

https://www.dotnetperls.com/substring-go


#### Kata 1: 4:13pm

Finished with 7 minutes to go all the way to the same point as Friday (so slower by about 10 minutes for my first run of the day).

Spent the rest of the time figuring out how to satisfy the requirement in step 4.  What I came up with was a modification to the Add function first checking for a prefix.  I'll explore this more tomorrow.



### 1/12/18 (counting this as day 5)

#### Kata 3: 4:31pm

Yes!  Completed with 13 minutes left to go! Including functionality to take on new lines!
Spent time thinking through the way to approach the next requirement.  Need to pick up here next week.

Next steps:

- [ ] need to parse input looking for "// followed by /"

if the above is found:
	- I need to use the value inbetween those two indexes as the delimiter in my splitstr
	- I need trim that delimiter portion of the string off the front before I pass it into my splitter

If the above is not found then I don't change anything and use the range below.

#### Kata 2: 3:28pm

Fantastic Kata.  Successfully made it hrough step 2 again with table driven tests.  Also refactored my Add function to simplify it and drop my test for length as it was not necessary.  Empty strings get converted to zero anyways... which I don't understand.

#### Kata 1: 10:54am

This one went really well.  I was able to test all the cases in step 1 and step 2 succcessfully w/out issue. Need to move to table drive testing (which I did after the 30 minutes to lear how).

### 1/11/18

#### Kata 1: 4:30pm

- Didn't make it through thisone.  Mike needed some help from me on focal stuff as did Antonio.

### 1/9/18

#### Kata 2: 4:03pm - 4:36pm

Needed a few extra minutes.  Was able to get the test to pass for inputs of both "" and "1,2,3".

#### Kata 1

Good progress here.  A lot of the time was spent remember where I was at and what needed to be done.  Still working through things.

### 1/5/18


#### Kata 2

Great progress again.  My Add function got much more real but still didn't get it passing.  My input was returning a slice of length 1 with an empty string using the split function on a comma.  I just realized that I spent the rest of my time building logic for the case statement under this branching logic for the length of zero instead of one so it kept failing.  I need to go in and update that on the next go-around.

I was distracted a lot during this pomodoro/kata as I had a phone call from Kal's coach but it was the wrong coach. Drama ensued afer that and I had a hard time getting back into the right frame of mind.

#### Kata 1

Good progress here.  Got past my block on the packages stuff.  I was able to get into testing and make the test fail.  Ended looking at how to make the Add function work.

### 12/20/2017

#### Kata 1
Well I got a little further... sort of.  I was trying to follow a different pattern that Jeff was using and moving stuff to an outside package.  Didn't finish getting that working yet.

Deleted everything in controllers and main.
Checking in and starting over.


### 12/15/17

Not a lot of progress today.  Sadly a lot of interuptions and re-learning stuff.  Will pick up here next week.