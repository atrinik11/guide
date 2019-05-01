---
title: Use @if and @else to Add Logic To Your Styles
---
## Use @if and @else to Add Logic To Your Styles

```<style type='text/sass'>
  @mixin border-stroke($val){
    @if $val == light{
      border: 1px solid black;
    } 
    @else if $val == medium{
      border: 3px solid black;
    }
    @else if $val == heavy{
      border: 6px solid black;
    }
    @else {
      border: none;
    }
  }
  
  
  #box {
    width: 150px;
    height: 150px;
    background-color: red;
    @include border-stroke(medium);
  }  
</style>

<div id="box"></div>```

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/front-end-libraries/sass/use-if-and-else-to-add-logic-to-your-styles/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
