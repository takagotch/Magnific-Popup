### Magnific-Popup
---
https://github.com/dimsemenov/Magnific-Popup

```js
$(document).ready(function(){
  $('.image-link').magnificPopup({type:'image'});
});

$('.test-popup-link').magnificPopup({
  type: 'image'
});

$('.parent-container').magnificPopup({
  delegate: 'a',
  type: 'image'
});

$('#some-button').magnificPopup({
  items: {
    src: 'path=to-image-1.jpg'
  },
  type: 'image'
});

$('#some-button').magnificPopup({
 items: [
   {
     src: 'path-to-image-1.jpg'
   },
   {
     src: 'http://vimeo.com/123123',
     type: 'iframe'
   },
   {
     src: $('<div>Dynamically created element</div>')
     type: 'inline'
   },
   {
     src: '<div>HTML</div>',
     type: 'inline'
   },
   {
     src: '#my-popup',
     type: 'inline'
   }
 ],
 gallery: {
   enabled: true
 },
 type: 'image'
});

$.magnificPopup.open({
  items: {
    src: 'some-image.jpg'
  },
  type: 'image'
});

$('.image-link').magnificPopup({
  type: 'image',
  callbacks: {
    elementParse: function(item){
      console.log(item);
    }
  }
});


$('.some-button').magnificPopup({
  tClose: 'Close (Esc)',
  tLoading: 'Loading...',
  gallery: {
    tPrev: 'Previous (Left arrow key)',
    tNext: 'Next (Right arrow key)',
    tCounter: '%curr% of %total%'
  },
  image: {
    tError: '<a href="%url%">The image</a> clould not be loaded.'
  },
  ajax: {
    tError: '<a href="%url%">The request</a> failed.'
  }
});
```

```
```

```
```

