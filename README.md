user-media-screenshot v1.0

Example:
var getScreen = require('user-media-screenshot');
getScreen(function(image){
  $('#my-image').attr('src', image);
});