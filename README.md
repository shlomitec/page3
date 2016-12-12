# page3

// Create variables to hold the title and note text.
var title; 
var message;

// Assign values to these variables.
title = "Molly's Special Offers";
message = '<a href=\"sale.html\">25% off!</a>';

// Get the element with an id of title.
var elTitle = document.getElementById('title');
// Replace the content of this element.
elTitle.textContent = title;

// Get the element with an id of note.
var elNote = document.getElementById('note');
// Replace the content of this element.
elNote.innerHTML = message;

/* 
Note: textContent does not work in IE8 or earlier - see explanation on website
innerHTML should only be used when you understand issues discussed in Chapter 5
*/
