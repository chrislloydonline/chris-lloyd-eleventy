---
layout: layouts/post.njk
title: Functions
templateClass: tmpl-post
eleventyNavigation:
  key: Functions
  order: 6
---

<script>
function outputMessage() {
    console.log('Output message');
};

console.log('Task 1 Start');
console.log('------------');

outputMessage();

console.log('------------');
console.log('Task 1 End');

console.log('Task 2 Start');
console.log('------------');

outputMessage();

console.log('------------');
console.log('Task 2 End');

console.log('Task 3 Start');
console.log('------------');

outputMessage();

console.log('------------');
console.log('Task 3 End');
</script>