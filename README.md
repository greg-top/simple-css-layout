# how Simple CSS layout works
 - based on 10 columns 
 - has 2 different containers:
    - fluid (100% page width)
    - standard (fixed width - customizable)
 - has rows to separate content in containers
 - has empty columns to create gap in the row
 - has nesting columns feature
 - works with columns overflow
 - has feature to hide element on responsive device (performance bug)
 - responsive with mobile first principle

# how to create container
TODO

# how to create rows
TODO

# how to create columns
TODO

# how to create gap in the row
TODO

# how to work with columns overflow
TODO

# how to nest columns
TODO

# responsive
TODO - how to use col-* classes: when column is not changing on bigger device there is no needed to add extra class, <br> example: we have ```col-*-100```, next for tablet and large tablet ```col-*-50```, and finally for desktop we have ```col-*-30```. In this case we don't need to double tablet and large tablet classes!:<br>
```
<div class="col-mobile-100 col-tablet-50 col-dekstop-30">
   markup here
</div>
```

# how to hide elements in responsive
TODO - here is a problem with too much HTML added to code!!