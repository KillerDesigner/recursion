Recursion is when a method calls itself. If you want to repeat the same functionality over & over, recursion can be an elegant way to do that. It is sometimes used in place of other looping structures, such as "while" or "for" loops.

A recursive method always needs a way to wind itself down. See rocket.rb for an example of this. Note that every time the method calls itself, it decrements the original argument passed in so that the method will know when to stop calling itself.

If you have no way for a method to stop calling itself, it will continue until your computer throws an error. You may have seen an error that looks something like "Stack level too deep". This is the sign of a run-away recursive method!