website
=======

An in progres static website for deginner.com. To build the website it's necessary to install [Hugo](http://gohugo.io/) and run `hugo`.


defaults: {
  enter:    'bottom',
  move:     '8px',
  over:     '0.6s',
  wait:     '0s',
  easing:   'ease',
  scale:    { direction: 'up', power: '5%' },
  opacity:  0,
  mobile:   false,
  reset:    false,
  viewport: window.document.documentElement,
  delay:    'once',
  vFactor:  0.60,
  complete: function( el ) {}
}

<div data-sr id="d1">
   <h1>I run the default animation</h1>
</div>
<div data-sr="wait 1s and enter bottom" id="d2">
   <h1>I have specific values</h1>
</div>
<div data-sr="scale down 10% and then ease-in-out 100px" id="d3">
   <h1>I have specific values too</h1>
</div>
var config = {
   enter: 'right',
   wait: '0.5s',
   move: '20px'
}

new scrollReveal(config);
