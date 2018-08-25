---
title: Match Numbers and Letters of the Alphabet
---
## Match Numbers and Letters of the Alphabet

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/javascript-algorithms-and-data-structures/regular-expressions/match-numbers-and-letters-of-the-alphabet/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
#eg Code

let egString = 'I love to Code 189';
let myRegex = /[a-z0-9]/gi;    // this regex will search through alphabets range a to z and numerical range of 0 to 9 at right end 'g' stands for global of how much time the specified regex or pattern occurs and 'i' stands for case Insensitive


//when you check

let result = egString.match(myRegex);
// you will get every result
Play around tweak the range and see results

Thanks
