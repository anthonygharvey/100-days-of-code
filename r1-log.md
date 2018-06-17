# #100DaysOfCode Log - Round 1 - Anthony Harvey

The log of my #100DaysOfCode challenge. Started on May 20, 2018.

## Log

### R1D1 
I learned about restricting routes to users that are logged in.  I also learned about hashed and salted passwords, which are VERY interesting and important.  Rails has a class method called has_secure_password method that does all of the heavy lifting of hashing a password and prepending a salt (to counter rainbow tables) through the BCrypt gem.  I used BCrypt in my [Developer Journal](https://github.com/anthonygharvey/developer_journal) app, but it's learn more detial about how it encrypts passwords! 

### R1D2&3
I worked on authentication in Rails yesterday and today.  The more I learn about Rails the more I love it!

### R1D4

I worked on a simple Rails app and implemented OmniAuth to login with a Facebook email and password.  This was my first time using OmniAuth and it seems cool.  I like the idea of making it as easy as possible for users to signup for my apps with a ubiquitous service like Facebook.  I plan to learn more about other providers (strategies in Rails) like Google, Twitter and Amazon for my upcoming Ruby on Rails project!

I also signed up for two Meetups for next week!  These will be my first meetups and I'm excited to get plugged into the Charlotte developer scene.  The first Meetup is [Turning Pro: Advice on Making the Switch to Professional Developer](http://meetu.ps/e/FfF23/Dt3Gn/f) on May 30 and the second is [Web Performance Techniques](http://meetu.ps/e/FdMRb/Dt3Gn/f) on May 31.

### R1D5
Added OmniAuth with GitHub to a TodoMVC Rails app.  I'm learning more about the security provided by using OAuth, which is amazing considering how fast the authentication happens!

### R1D6
Worked on a small Rails project combining form helpers, models that interact and a simple sessions system.  I finished building the models and passed the tests.  I'll work on the forms and sessions tomorrow!

#### R1D7
More progress today on the Rails project.  It's starting to come together but there are a lot of pieces.  Tomorrow I'll work on building out the views.

### R1D8
I finished my small Rails app and started planning my Rails portfolio project.  I definitely see the value in taking time to plan a project before writing the first line of code!

### R1D9
I updated the plan for my Rails portfolio project today and started mapping out the models and relationships.  I also received some great news today, I won a diversity scholarship to [MongoDB World 2018](https://www.mongodb.com/world18)!  I'm beyond excited and can't wait to attend!  Today was also the start of the MongoDB for Node.js Developers course on MongoDB University, so I started that as well.

### R1D10
I made some updates to my models and relationship maps for my Rails project.  I'm glad I took the time to plan it out because it made coding the models and relationships much easier!  I also went to my first Meetup!  The title of the meet up was [`Turning Pro: Advice on Making the Switch to Professional Developer](https://www.meetup.com/charlottedevs/events/250514891).  The speakers were great and I met a lot of awesome developers in the community.  I definitely will be going to more!

### R1D11
I learned more about testing with Rspec today and practiced on a scratch app.  I plan on adding tests to the models in my Rails app tomorrow!  I definitely see the benefits of TDD!

### R1D12
I finished all of the model validation and association tests for my Ruby on Rails project.  I used the rspec, factory_bot, facker and shoulda gems.  I'll start building and testing instance and class methods tomorrow.  I'm starting to like Test Driven Development!

### R1D13 & 14 (Fri & Sat)
I made a lot of progress on writing instance, class and scope method tests for my models; and writing methods to make those tests pass.  Practicing TDD definitely forces you to think about what you're implementing before you actually do!

### R1D15 (Mon)
I took Sunday off and spent time with my family.  Today I dove back into the [MongoDB for Node.js Developers](https://university.mongodb.com/courses/M001/about) course (I will get my professional certification once I finish!).  I really like the document format.  Patterns are starting to become more apparent now what I know more Ruby on Rails!

### R1D16 (Tues)
I finished and submitted the first week homework assignments for the MongoDB for Node.js Developers course today.  I'm learning more and more about MongoDB, Express and Node.js.  I also finished writing all of the model tests for my Ruby on Rails project along with coding all of the class, scope and instance methods to make those tests pass (52 in all).  I also began working on the controllers and views.  It's fun to start seeing an idea that I've had for a while start to take shape!

### R1D17 (Wed)
I made a lot of progress today on my Ruby on Rails project.  I added user authentication, controllers for each of the resources and stubbed out the views.  I'll work on the scrapper component of the project and adding OmniAuth tomorrow.  I'm excited about the scrapper part of the project!  Access to an API would be great, but the website I want to pull information from does not offer one for a certain part of the website I'm interested in.

### R1D18 - 27 (Thurs - Sat)
I completed about 95% of the scraper component on Thursday!  It grabs all of the info I need but I had to refactor it for the items that are lazily loaded.  My initial approach was to recursivly grab the "see more" URL at the end of each page as it was generated and use it to scrap the next lazily loaded page.  I decided against it at first to avoid too many hits to the website and tried the waiter-scroll gem.  I used the waiter-scroll, selenium and even JavaScript, but the all seemed too hacky and brittle.  So I went with my first approach and made it work!  The website I'm scraping is one of the largest in the world (I'm sure they can handle my requests!) and the lists that I'm scraping don't have that many lazily loaded pages.

I updated the scraper Fri - Mon (day 19 - 22) to account for edge case  (if the product was added to a list and subsequently discontinued or if no restock ETA was available), wired the controllers and views, styled the app with [Material Design Lite](https://getmdl.io/).  I also finished week 2 of the [MongoDB for Node.js Developers](https://university.mongodb.com/courses/M001/about) course!

I finished my Ruby on Rails project on Friday! and deployed my previous project: [Developer Journal](https://developer-journal.herokuapp.com)!  The developer journal was my second project at Flatiron School and I built it to fill a gap in apps I was using to keep track of my learning/coding "streaks".  You can read more about the app on the [about page](https://developer-journal.herokuapp.com/about) and learn how I built it by checking out my GitHub [repo](https://github.com/anthonygharvey/developer_journal).

The Ruby on Rails project was a lot of fun and I learned a lot!  I deployed it to Heroku today and, after I make a few styling adjustments and add an about page, I plan to spread the word about the beta launch.  The actual launch will be once I update it with JavaScript for my next projects!

I love being able to take an idea and create something to share with the world!