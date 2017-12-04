# add-content.js
Creating a Basic JavaScript
var today = New Date();
var hourNow = today.getHours();
var greeting;

if (hourNow > 18) { 
 greeting = 'Good evening!';
} else if (hourNow > 12) {greeting = 'Good afternoon!';
} else if (hourNow > 0) { greeting = 'Good morning!';
} else { greeting = 'Welcome!';
}

document.write('<h3>' + greeting + '</h3>);
