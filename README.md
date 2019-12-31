# Doing a Dispatch Shift

In this lesson we'll cover how to work the dispatch role while on shift. Be sure to check out the [Dispatch Guide](https://github.com/flatiron-labs/technical-coach-resources/blob/master/dispatch/dispatch-guide.md)
 and [Dispatch Cheat Sheet](https://github.com/flatiron-labs/technical-coach-resources/blob/master/dispatch/dispatch-cheatsheet.md) for more information.

 Be sure to also check out the [Dispatch Sheet](https://docs.google.com/spreadsheets/d/124Vvqd1Hk2DoStjW2fGXrvjPkMn2ZzMCMFqqTQOtG6s/edit#gid=1277548195) so that you know if and when you will be working the dispatch role during your shift. The sheet is also pinned in the `daily-dispatch-line` Slack channel.

## Starting Your Shift
When you start your shift:

- Check the Dispatch Sheet so you know if and when you are on dispatch
- Open up the [Expert Chat](https://learn.co/expert-chat) window
- Write `qbot in dispatch` in the `#technical-coaches` Slack channel
- Greet the other TCs on shift and see how the day has been going

Currently we use the Dispatch Sheet to determine who is in the dispatch role, and when, during the shifts for a given day. It is your responsibility to know when you should be on dispatch **before** starting your shift. If there is an error in the sheet (e.g. someone is listed as dispatch who is no longer on shift), then the other TCs on shift can decide who will cover that hour. If you have swapped shifts (more on that later!) with someone who is listed on the dispatch sheet for that shift, you are responsible for covering their time on dispatch as well.

## During Your Shift
The Technical Coach on dispatch greets all incoming chats and gets some preliminary information from the students.

If the issue is a simple question with a discrete answer (e.g. "What's the difference between `#find` and `#detect` in ruby?"), you can answer it in the chat and/or direct them to a resource (e.g. "They're the same thing :) As you can see here: https://ruby-doc.org/core-2.2.3/Enumerable.html#method-i-detect they're used interchangeably."). Similarly, if the issue is solved by something in the [Help Center](http://help.learn.co/), link them to the doc before linking the student to a coach.

If it's clear that the student will need more than a link and a few short answers, set them up to pair program by saying something like: `"Would you like to pair program with a technical coach for 20 minutes?"`

When you ask the student if they want to pair program, **make sure to add pair program (and not screen share) with a Technical Coach. This will help them get comfortable with the idea of pair programming with another developer**. This also lets them know that TCs are allotted 20 minutes per pairing.

If the student agrees, copy the question link by clicking on the clipboard:

![question link](https://s3.amazonaws.com/learn-experts/expert-chat-clipboard.png)

Paste the link into the `#technical-coaches` channel to queue up the question for the next available TC on sync support.

You will also want to periodically track the pairing that other TCs are currently on. Typing `qbot who is on?` will yield information about which TCs are active with which students and how long they've been pair programming. At 15-18 minutes, you can type something like: "`@username 15 minute mark!`", which will send a notification alerting the TC they only have 5 minutes left. If they are past the 18 minute mark, type something like: "`@username 18 minutes! Please wrap up!`". We try to be fair to our students and give them all the same amount of attention.

If you're fielding chats and see another student that is genuinely being helpful to the original poster, that's awesome. Encourage them and let everyone know you're there to help if they have problems/issues/questions. Be sure to check in periodically to track the chat and make sure the student is being helped effectively, and to intervene if necessary.

If you notice there are a lot of questions on AAQ, and the TCs in sync are free, make sure to keep them queued up. You can check the queue by typing `qbot q`. That way each student gets proper one on one support and you don't overtax yourself while on dispatch.

If you queue a student but they have already figured out the issue, you can type `qbot resolve <question_id>`. You can find the question id by typing `qbot q` - this will yield something like `https://learn.co//lessons/25366?batch_id=306&track_id=23144/&question_id=96994`. In this example you could type `qbot resolve 96994` in order to resolve the question and remove it from queue.

**Do not resolve questions for students on AAQ. Only resolve questions where the last response time by the original poster is more than one hour old.**

## Ending Your Dispatch Shift
It is your responsibility to make sure the dispatch role is filled when your shift ends. If the TC who is up next for dispatch is not yet online or is finishing up a screenshare, remind that TC that they are up next for dispatch. If you are still on shift but are now scheduled to be in sync, remain in the dispatch role until the appropriate TC is available. Otherwise, have one of the remaining TCs on shift cover until the appropriate TC is available.

Once your shift is over, type `qbot out` to end your shift.

## Resources

* [Dispatch Guide](https://github.com/flatiron-labs/technical-coach-resources/blob/master/dispatch/dispatch-guide.md)
* [Dispatch Cheat Sheet](https://github.com/flatiron-labs/technical-coach-resources/blob/master/dispatch/dispatch-cheatsheet.md)
* [Dispatch Sheet](https://docs.google.com/spreadsheets/d/124Vvqd1Hk2DoStjW2fGXrvjPkMn2ZzMCMFqqTQOtG6s/edit#gid=1277548195)
* [Qbot Commands](https://github.com/flatiron-labs/technical-coach-resources/blob/master/qbot.md)
