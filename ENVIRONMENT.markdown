# Development Environments

In DevOps, it's important to be able to have a portable development environment. In the interest of that, 
there are some methodologies and configurations that can help with consistent environments.

---

## Git

Configuration:
>Git works pretty well out of the box after just a couple lines, configuring the username and email address. But
>there are many things that you can tune to make your experience even smoother than git already is. Which is 
>very smooth.

[git-scm.com](https://www.git-scm.com/book/en/v2/Customizing-Git-Git-Configuration)

Commit templating:
>Commit templating allows for a consistent methodology of describing the commits from any given developer, 
>making the whole project much easier to manage as well as work on. This prevents the problems of commits 
>without descriptions or reasons, as well as confusing but useful commits from late night hackings.

[a good example and what I use](https://gist.github.com/adeekshith/cd4c95a064977cdc6c50)

## Editors and IDEs (or VIM is best):
  Jokes aside, vim is just one of many editors and I happen to be very comfortable with it. Whatever editor you
  do use, make sure that it's extensible. As you learn more or gain more structure, you'll find the ability to
  use plugins becomes vital. I'll be a lot more help with vim than other editors of course. Editors and IDEs are
  a huge area of debate and likely always will be. Essentially, it works out to what you can get the most quality
  work done using.
  
  ### [VS Code](https://code.visualstudio.com/)
  A case can be made for Microsoft's offering, in my own opinion it's on par with xcode.
  
  ### XCode
  
  ### SublimeText

## Dependencies

  ### Yarn and NPM:
  If we're going to use node, ruby, or really almost anything, we're going to need management for depepndencies.
  Easily overlooked in a small project, dependencies become a lot of work to upkeep, even though they're quite a
  small job to actually manage. A perfect one for automation to take over! Many parts of this can work into a 
  continuous integration strategy, removing an entire section of work for human programmers.
  
  ### Snyk.io
  
## Continuous Integration
  ### Travis
  ### Circle
  
# WORK IN PROGRESS OBVIOUSLY #
