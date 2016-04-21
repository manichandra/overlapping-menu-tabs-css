# overlapping-menu-tabs-css
CSS to create a overlapping curved menu tabs

I have created this repository while learing how to add a new repository without using any tools and just using www.github.com. 

I was assigned with a task to create a curved overlapping tabv menu similar to the tabs in Sublime Text(version 2). I knew that it would be possible by using pseuso elemnts and i tried many ways but i couldnt build a perfect one. Then serached in stack overflow with multiple key words . Finally found this code by Roko C. Buljan. Saved my day 

These are the steps to design tabs. 


 - Skew the :before and :after pseudo elements,
 - set pseudos to some - offset
 - add left-top border-radius to :before and right-top to :after
 - if needed (to remove the top hard edge) add top border radius to the A element
 - add z-index:1; to the :after
 - add z-index:1; to the .active's :before element.


Thanks Roko C. Buljan.
