Key Points:

Web storage lets you store data in the browser. There are 2 different types of storage: local and session storage

Modernizr let you detect if an HTML5 Storage is available:

if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}

- Most browsers have “5 megabytes” which is how much storage space each origin gets by default. One thing to keep in mind is that you’re storing strings, not data in its original format. If you’re storing a lot of integers or floats, the difference in representation can really add up. Each digit in that float is being stored as a character, not in the usual representation of a floating point numb

- “QUOTA_EXCEEDED_ERR” is the exception that will get thrown if you exceed your storage quota of 5 megabytes. 

- Javascript booking 420 has additional info on web storage


