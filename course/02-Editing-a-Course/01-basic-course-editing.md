# Basic Course Editing

### Editing a course will be very straight forward if you have prevous git experience

- First go to your user page, at https://www.learn-byte.com/user.  

 - Next select `View on Github` next to the course you would like to edit. 

 - Finally, copy the clone url and run `git clone` in a local terminal window like so:

 `git clone https://github.com/learn-byte/your-repository-name.git`

 If you'd like to learn more about cloning a repository from Github, [check out the official documentation](https://help.github.com/en/articles/cloning-a-repository).

 Open the cloned repository in your favorite text editor, we recommend [Visual Studio Code](https://code.visualstudio.com/).

 ![new-repo](https://raw.githubusercontent.com/learn-byte/docs/master/assets/images/new-repo.png)

 --- 

 ### Courses are written in Markdown language

 Markdown is a lightweight markup language that allows for easy formatting of text.  For all the rules and capabilities of markdown refer to [The Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).  

 Anything that works in markdown should be fair game for designing your courses.  
 
 Remember to keep the content short! Short content keeps it easy for learners to consume and for you to revisit and make changes easily. 

 --- 

 ### Adding the content back to Github

 All the benefits of Github version control are granted to your course.  Make branching strategies and send pull requests to friends for review!

 To add your content back to github simply run from your root course directory: 

 `git add .`

 `git commit -m 'new stuff!`

 `git push origin master`

 Learn more about [Github and commiting changes here](https://guides.github.com/introduction/flow/).
