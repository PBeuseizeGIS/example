How to contribute

I'm really glad you're reading this, because we need volunteer developers to help this project come to fruition.

Testing

We have a handful of Cucumber features, but most of our testbed consists of RSpec examples. Please write RSpec examples for new code you create.

Submitting changes

Please send a GitHub Pull Request to opengovernment with a clear list of what you've done (read more about pull requests). When you send a pull request, we will love you forever if you include RSpec examples. We can always use more test coverage. Please follow our coding conventions (below) and make sure all of your commits are atomic (one feature per commit).

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

$ git commit -m "A brief summary of the commit
> 
> A paragraph describing what changed and its impact."
> 
Coding conventions

Start reading our code and you'll get the hang of it. We optimize for readability:
We indent using two spaces (soft tabs)
We use HAML for all views
We avoid logic in views, putting HTML generators into helpers
We ALWAYS put spaces after list items and method parameters ([1, 2, 3], not [1,2,3]), around operators (x += 1, not x+=1), and around hash arrows.
This is open source software. Consider the people who will read your code, and make it look nice for them. It's sort of like driving a car: 
Perhaps you love doing donuts when you're alone, but with passengers the goal is to make the ride as smooth as possible.

Thanks
