# 100 Days Of Code - Log

Day 1: January 4, 2016

Today's Progress: Worked on Title Case a Sentence, not yet complete

Thoughts: I'm starting to think that the way to title case a sentence lies in the slice method.

Link to work: https://www.freecodecamp.com/challenges/title-case-a-sentence#?solution=%0Afunction%20titleCase(str)%20%7B%0A%20%20return%20str%3B%0A%7D%0A%0AtitleCase(%22I'm%20a%20little%20tea%20pot%22)%3B%0A
var spry = [];
function titleCase(str) {
  var several = str.split([" "]);
  //for (var i = 0; i <= several.length; i++) {
    //var mench = several.slice(0);
    //spry.push(mench);
  var strs = spry.join(' ');
  return strs;
}

titleCase("I'm a little tea pot");