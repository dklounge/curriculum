# Project: Advanced Active Record Associations
*Estimated Time: 4-6 hrs*

*Don't forget to use Git to save your projects!*

This final chapter of the RoR Tutorial will require you to have users following users while the other project will give you a chance to build the back end for an application that looks suspiciously like a popular event hosting site.

## Project: Ruby on Rails Tutorial

You're on the last chapter!  This one will require you to implement the final piece of functionality that makes microblogging what it is -- allowing users to follow each other.  With your now excellent knowledge of associations, you should be able to see that you'll run into some naming issues (you won't get too far with a User who `has_many :users`).  It's a many-to-many relationship that uses the SAME model for both sides ("self-referential")!

As an added bonus, you'll get a chance to touch a bit of AJAX when making it so the buttons for following don't actually refresh the page with each push.  Hooray learning!

### Your Task

1. You've got a User model.  Write down how you would implement (and name) the associations necessary to make one user follow another.  You'll get a lot more out of the tutorial chapter if you think it through first.
2. Do the [Ruby on Rails Tutorial Chapter 11](http://ruby.railstutorial.org/chapters/following-users#top), "Following users".

## Additional Resources

* [Railscast on Many-to-Many Self-Referential Relationships (2010)](http://railscasts.com/episodes/163-self-referential-association?view=asciicast).  This is old but should be helpful to see the concept covered.
* 