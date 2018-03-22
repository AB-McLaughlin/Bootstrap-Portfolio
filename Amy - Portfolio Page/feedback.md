# Feedback

**Compare the new index.html and bootstrapstyles.css to your current version in order to see the changes I made to help you along.** 

These are all very common issues my Jr. Level Engineer who has been in the field for 4 years makes regularly that causes him to have CSS issues as well, so don't get too discouraged considering you have been doing this for only 3 weeks. I see a lot of natural organizational tendancies in your code that tells me you will excel when we begin to build out bigger projects with more code. These are my points of feedback and things to watch out for as you continue to work through the assignment:

* Some of your html and css markup contained some typos, which cause certain css to apply differently than you expected. Examples: <p1> <p2> which do not exist as html tags. This is why you were needing to add <br> tags between your paragraphs to apply proper margins, since the p1 and p2 tags didn't know what the p tag styles were supposed to be.

* Pay special attention to your closing tags to ensure they match up to the opening tags. There were some tags nested differently than you expected that may have been causing you some problems as well. Linting your code (ensuring proper tab spacing), will help to alleviate some of these issues. Line folding in your IDE will help you to see which tags are nested funny. See attached video to see what I mean. 

* Remember that in Boostrap, you are using classes to style various page elements, and it won't know if you intentionally reused a class or not, so it will always apply whatever css it is designed to apply. With that said, I found a place where you were using Bootstrap class names incorrectly. In that case, I decided to make it an ID so you would see it easily.



