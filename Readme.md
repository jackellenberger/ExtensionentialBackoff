# Exponential Backoff in an Extension

I have a problem that I like to call "reddit". I don't like reddit becuase I'm there all the time and the content is good maybe once a day. I'm in the [CGPgrey camp](http://www.cgpgrey.com/blog/what-is-reddit) of "reddit is as good as you make it", and you can only make it good by cutting out all the subreddits that are trash. Having done that, you're left with small, tight knit communities that make good content sparsely.

So why am I checking reddit every time I open a browser? Because I'm an idiot and can't retrain my muscle memory. This extension will do it for me! The desired feature set is:

1. Establish a per domain view rate setting
2. Should that rate be exceeded, redirect to a timer that gives the amount of time until you're next allowed to view that domain, and closes itself after a short interval
3. If that page is opened again, double the time until next allowed view
4. Allow for linked pages to go through unobstrucuted - If a supmigo sends a link, I want to see it. Just stop me from doing ctrl+t+ctrl+l+"redd"+enter
5. Allow for non-exponential timers. Cause that might actually be super annoying. 
6. Present an override switch in a way that is easy to hit if you have time to burn, but not if you have some project breathing down your neck

Also, some strech features may include:
1. A "last visited" counter on certain pages to shame me out of visiting sites so often

I'll probably come up with some more features. 

You may be saying to yourself, "that's all well and good, but where is the relephant xkcd?". [Here it is.](http://xkcd.com/862/) (check the alt text)