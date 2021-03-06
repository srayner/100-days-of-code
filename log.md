# 100 Days Of Code - Log

### Day 1: January 15, 2017

**Today's Progress**:
* Started new ZF3 CMS project.
* Created skeleton application.
* Setup entities and database SQL.
* Added doctrine ORM dependency.

**Thoughts:** Took a little while to get back into Zend Framework. This is my first ZF3 application. ZF3 seems fairly similar to ZF2. The
main difference I've found so far is that you no longer have the service locator inside the controller. Instead you use dependency injection
to insert the dependencies required.

**Link to work:** [Sodium Application](http://github.com/srayner/sodium)


### Day 2: January 16, 2017

**Today's Progress**:
* Continued with new ZF3 CMS project.
* Added author form.
* Added author add view script.
* Created add action in author controller, need refactoring to use dependency injection.

**Thoughts:** In typical Zend fashion they make things difficult for new users. Form view helpers cannot be used out of the box. Weirdly I seemed
to have zend-form installed, but the view helpers are not available. After adding zend-form to composer.json and running composer update, they become
available. However Zend-form seems to depend upon zend-i18n, but codepencomposer does not install this for us, so I had to add that to composer.json aswell.

**Link to work:** [Sodium Application](http://github.com/srayner/sodium)

### Day 3: January 17, 2017

**Today's Progress**:
* Started tribute page to Carrie Fisher.

**Thoughts:** Learnt about the filter css property for making images greyscale. Taking longer than expected. I should finish it tomorrow.

**Link to work:** [Codepen Page](https://codepen.io/srayner/full/ZLBRaw/)

### Day 4: January 18, 2017

**Today's Progress**:
* Continued with tribute page.
* Improved header. Modified line height and margins so it behaved better right down to narrowest width.
* Worked on the image container to have border, radius corners and white background.
* Added quote to bottom of page.
* Lightened the grey background a bit.

**Thoughts:** I need to add media breaks so the well can progresively take up more percentage width as the widow width reduces.

**Link to work:** [Codepen Page](https://codepen.io/srayner/full/ZLBRaw/)

### Day 5: January 19, 2017

**Today's Progress**:
* Finished tribute page.
* Added two media queries to change text height and max width of image and list.

**Thoughts:** Reminded myself how media queries work. It was good to practice some CSS for a change, as I normally only program back end stuff.

**Link to work:** [Codepen Page](https://codepen.io/srayner/full/ZLBRaw/)

### Day 6: January 20, 2017

**Today's Progress**:
* Started creating my portfolio page.
* Added most of the html
* Added a google font and started with basic css styles.

**Thoughts:** I find it really hard to think of good content/wording. This project should give me more practice with css.

**Link to work:** [Codepen Page](http://codepen.io/srayner/pen/JEWzvX)

### Day 7: January 21, 2017

**Today's Progress**:
* Continued with my portfolio page.
* Started to add media breaks into css.
* Added two screenshot images.

**Thoughts:** This is good practice but I don't enjoy css.

**Link to work:** [Codepen Page](http://codepen.io/srayner/pen/JEWzvX)

### Day 8: January 22, 2017

**Today's Progress**:
* Started working through basic Javascript in FreeCodeCamp.

**Thoughts:** Finding it hard to make time to do this every day.

### Day 9: January 23, 2017

**Today's Progress**:
* Wrapped example code into a php class for transforming flat data into a tree structure. 

**Link to work:** [github.com](https://github.com/srayner/NavTree)
