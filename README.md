# Web Development Basics
Since finishing the developer bootcamp I attended ([DBC](https://en.wikipedia.org/wiki/Dev_Bootcamp)) and starting my first software engineer job at [Optoro](http://optoro.com/), several friends have asked me for tips on starting their web development journey. Since I found myself giving the same advice repeatedly, I put together this readme to be a bit more [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) with my life.

The resources I've gathered here came from web communities/forums, tech meetups, and the code-study group at my company. There's a lot to explore out there, and I think this collection is good start.

If anything on this guide could be improved or should be changed, just make a pull request and/or email me at gabezurita@gmail.com.

Prior to beginning, it’s important to be aware of resources to help get you unstuck or to learn more:

## Getting Unstuck
As you're progressing through these tutorials, you will at times find yourself feeling stuck. This is normal. Just keep going, and use the following to get yourself unstuck (more details on these later):
> 1. Think – letting your mind struggle with a problem is an important part of the learning process
> 2. Read [the documentation of the language you're learning](http://devdocs.io/ruby~2.4/) and [experiment](https://medium.com/@ArielTeague/the-scientific-method-and-programming-d327594f6e39)
> 3. Search exising questions on Stackoverflow, Google, or Reddit
> 4. Post a new question on Stackoverlfow, Reddit, or similar online forum
> 5. If forums fail, ask a question in a slack community such as #DCTechSlack
> 6. When nothing else works, ask a more experienced friend

## General Tips (on the above)
* [Stack Overflow](https://stackoverflow.com/) - this site will become a close friend of yours. Just use google to find answers to common questions here. For a more focused google search, input the error message you’re getting and limit the search to stackoverflow by including "site:stackoverflow.com" in your search string--see [this link](https://www.google.com/search?ei=PRJWW5DJOMjBjwTW2oqAAw&q=%22no+implicit+conversion+from+nil+to+integer%22+ruby+site%3Astackoverflow.com&oq=%22no+implicit+conversion+from+nil+to+integer%22+ruby+site%3Astackoverflow.com&gs_l=psy-ab.3...9291.9872..10082...0.0...106.465.4j1......0....1..gws-wiz.......0i71.EoxpbF8ncwE) for an example. More google search tips [here](https://www.reddit.com/r/LifeProTips/comments/3yis0k/lpt_how_to_get_the_most_out_of_googlesearch/). 
* If there are no posts around your error message, feel free to create a new post asking for help. [Here's some guidelines on how ask for help on Stack Overflow](https://stackoverflow.com/help/how-to-ask).    
* Spend some time attempting to understand why the found solution works. When we understand is when we grow, so give yourself the chance to learn. It's not about the destination, but journey along the way.
* Typing code to learn syntax is an important aspect of learning to program. Do not copy/paste solutions you find on the internet, be sure to type them out.
* No man is an island. Get connected to other people who are attempting to learn. There's lots of online and in-person communities, e.g. [DCTech Slack](http://www.dctechslack.com/) and [DC Code Newbie Meetup](https://www.meetup.com/CodeNewbie-DC/).

## Other Useful Bits
* Get a text editor to edit code – [Atom](https://atom.io/) is a good one, but there's many alternatives out there.
* [Time Management - Pomodoro Timer](https://cirillocompany.de/pages/pomodoro-technique) - Generally speaking, it’s easy to get distracted or to spend one’s time inefficiently – using the Pomodoro Technique will help you get more done. Here’s a useful [Pomodoro Cheatsheet](http://i.imgur.com/zB4YdEi.png)
* Podcasts are a great way to get introduced to various tech topics. [Codenewbie](https://www.codenewbie.org/podcast) is excellent for new developers.
* If you're feeling distracted or anxious, [try meditating](https://www.youtube.com/watch?v=qxyVCjp48S4). Here's a [one minute meditaiton](https://www.youtube.com/watch?v=c1Ndym-IsQg) you can do to give yourself a break and bring back your focus. Just focus on your breath for bit and then get back to the task at 

# Concepts and Languages
Here’s some resources to explore, and languages to learn (from top to bottom):

## Web Infrastructure
Let's learn about the infrastructure apps run on
* Watch: The Internet -- <a href="https://www.youtube.com/watch?v=AEaKrq3SpW8" target="_blank">How does it work?</a>
* Read: Web concepts -- <a href="http://skillcrush.com/2012/08/19/the-internet-vs-the-web/" target="_blank">Internet vs. Web</a>, <a href="http://skillcrush.com/2012/10/01/web-browsers/" target="_blank">Web Browser</a>, <a href="http://skillcrush.com/2012/07/03/web-server-2/" target="_blank">Web Server</a>
* Read: <a href="http://skillcrush.com/2013/03/28/websites-vs-web-applications/" target="_blank">Web site vs Web App</a>
* Read: Domain concepts -- <a href="http://coding.smashingmagazine.com/2011/05/25/introduction-to-dns-explaining-the-dreaded-dns-delay/" target="_blank">DNS intro</a>, <a href="http://skillcrush.com/2012/04/24/dns/" target="_blank">DNS in-depth</a>, <a href="http://skillcrush.com/2012/07/03/ip-address-2/" target="_blank">IP Address</a>
* Read: <a href="http://skillcrush.com/2012/04/02/html/" target="_blank">What's HTML?</a>

Now, on to the nitty gritty: web developemnt! In the below secion, I've linked various free online courses. As an alternative to any of the below, Udemy has excellent content, though their courses tend to be expensive. Be sure to look for sales there–you can regularly get $200 courses for only $10 (yes, 95% off!). Do not pay full price, as [Udemy regularly has sales](https://www.reddit.com/r/learnprogramming/comments/6rc5tf/how_often_do_udemy_courses_go_on_sale/) (just like a mattress store).

## [HTML](http://devdocs.io/html/) & [CSS](http://devdocs.io/css/)
HTML (Hypertext Markup Language) and CSS (Cascading Style Sheets) are two of the core technologies of the web. HTML provides the structure of the page, CSS the (visual and aural) layout, for a variety of devices. Check [World Wide Web Consortium (W3C)](https://www.w3.org/standards/webdesign/htmlcss) for more info.
* [Codeacademy](https://www.codecademy.com/learn/web) ←great and free, but there’s excellent paid options: [code school, or treehouse](https://www.reddit.com/r/learnprogramming/comments/1dvhrt/codecademy_vs_code_school_vs_treehouse/)
* [Flexboxfroggy](http://flexboxfroggy.com/) and/or [CSS Garden](http://cssgridgarden.com/) + [CSS Grid Tutorial](https://mozilladevelopers.github.io/playground/)
* Now make make a website on your computer through this [Codeacademy tutorial](https://www.codecademy.com/articles/local-web-page)!

## [JavaScript | ECMAScript](http://devdocs.io/javascript/)
The programming language the web (currently) runs on. Here's [some good reasons to learn it](http://www.bestprogramminglanguagefor.me/why-learn-javascript).
* [Codeacademy](https://www.codecademy.com/learn/javascript) - Free course and a good enough intro
* [Javascript30](https://javascript30.com/) - 30 days of free, JS code challenges by [Wes Bos](https://twitter.com/wesbos)
* [ES6.io](https://es6.io/) - Excellent, paid, JavaScript course (also by the above author)  
* [Eloquent in Javascript](http://eloquentjavascript.net/) - Great JS book, though a perhaps too detailed for an intro

## [Ruby](http://devdocs.io/ruby/)
A beginner friendly programming language for the back-end. Feel free to go work on these things at a programming meetup such as [this one](https://www.meetup.com/dcruby/)!
* [Codeacademy](https://www.codecademy.com/learn/learn-rails) (it’s good to know [how to read Ruby error messages](https://learn.co/lessons/ruby-lecture-reading-error-messages) for this)
* [A good article giving you a general outlook on Ruby](https://hackhands.com/beginners-guide-ruby/)
* [Ruby Essential Training](https://www.lynda.com/Ruby-tutorials/essential-training/47905-2.html?srchtrk=index:1%0Alinktypeid:2%0Aq:ruby%0Apage:1%0As:relevance%0Asa:true%0Aproducttypeid:2)
* [Good book on Ruby](http://poignant.guide/)
* Learn a little more about Ruby through [Ruby Koans](http://rubykoans.com/) -- or feel free to come back to this later
* [Exercism -- more difficult exercises](http://exercism.io/languages/ruby/about) -- feel free to skip for now and come back to it later

## [SQL](https://www.reddit.com/r/explainlikeimfive/comments/1jid0b/eli5_what_is_a_database_and_what_is_sql_language/)
It's important to learn to work with data (the backbone of applications)
* [Codeacademy](https://www.codecademy.com/learn/learn-sql) and/or [this well made SQL tutorial](http://sqlzoo.net/wiki/SELECT_basics).
* If you'd like to go more in depth, there's some free, [self-paced Stanford SQL classes](https://lagunita.stanford.edu/courses/DB/SQL/SelfPaced/about) you can explore.

## [Git](https://guides.github.com/introduction/git-handbook/)
Managaging change in application development is important for progress to be possible, and this is the standard tool for that
* [Tutorial](https://learngitbranching.js.org/)—some useful resources on [the site](http://try.github.io/).
* [Thoughtbot video on how git is used in some tech companies](https://thoughtbot.com/upcase/videos/git-workflow)

## [Ruby on Rails](http://devdocs.io/rails/)
Let's start making web apps! Ruby on Rails does a lot of work behind the scenes to make web app development more accessible, and it's the framework behind many successful tech startups.
* [Codeacademy](https://www.codecademy.com/learn/learn-rails)
* Get more Rails practice through [Rails for Zombies](http://railsforzombies.org/)
* Development Environment – this part can be challenging, so hang in there! If you haven't got a laptop in which you can make web apps, you have a few operating system options:
    1. OSX – this is the easiest alternative, given that most rails tutorials are written for apple's OS. If you haven't got a one, buy a Used or Refurbished [Macbook](https://www.amazon.com/Apple-MacBook-15-4-Inch-Laptop-Yosemite/dp/B00PZLRWVE/ref=pd_sbs_147_4?) and configre your [Rails environment](https://gorails.com/setup/osx/10.14-mojave)
    2. [Ubuntu](https://help.ubuntu.com/lts/installation-guide/s390x/ch01s01.html) – this is more challenging than OSX, but far cheaper (or free). If you want to go the open source route, [set up Ubuntu](https://howtoubuntu.org/how-to-install-ubuntu-18-04-bionic-beaver) on a PC you're no longer using, a second hard drive, or buy a used or refurbished laptop for cheap, then configure your [Rails environemnt](https://www.howtoforge.com/tutorial/ubuntu-ruby-on-rails/)
    3. Windows: Most Rails tutorials assume OSX or Ubuntu. Developing ruby on Windows is (strongly) not recommended. If you cannot access any of the above options, try [coding on your browser](https://aws.amazon.com/cloud9/?origin=c9io) with a [Cloud9 Ruby on Rails environment](http://railsapps.github.io/rubyonrails-cloud9.html).
* Finally, it's time to make your first web app! This alternative example app from [RailsTutorial](https://www.railstutorial.org/book/beginning) is free and excellent. Another option is [this one](https://emkaydeum.wordpress.com/2016/04/28/tutorial-build-a-rails-app-using-the-nasa-astronomy-photo-of-the-day-api/)
___
## Additional Resources
* This [reddit post](https://amp.reddit.com/r/learnprogramming/comments/43dvma/best_online_courses_you_took/) has some great Computer Science courses
* [edEx course](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-11)
* [Online Community Resource (such as /r/learnprogramming)](https://www.reddit.com/r/learnprogramming/wiki/index)
* [Progressive Web Apps](https://developers.google.com/web/ilt/pwa/)
* Programming Puzzles: [The Human Resource Machine](https://tomorrowcorporation.com/humanresourcemachine) and [Bandit](http://overthewire.org/wargames/bandit/)
* Programming Katas: [Code Wars](http://www.codewars.com/)
* [Linux](https://bash.cyberciti.biz/guide/Main_Page)
* Learning a javascript framework such as [Angular](https://thinkster.io/a-better-way-to-learn-angularjs) and then building a rails app with it is a good exercise. Once you've gotten past that, you can then [build a rails app with an Angular frontend](https://thinkster.io/tutorials/angular-rails).

## Next Steps
* Volunteer in a programming project through the [Code for America Brigade](http://brigade.codeforamerica.org/brigade/)
* Contribute to an [open source project](https://github.com/MunGell/awesome-for-beginners)
