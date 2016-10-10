# particle.js 
[![Build Status](https://travis-ci.org/geoffgu/particle.js.svg?branch=master)](https://travis-ci.org/geoffgu/particle.js)
## How to use?
Example:<br/>
    `new particle({
      element: 'canvas',
      imagePath: '/images/logo-float.png',
      cropStartPointX: 0,
      cropStartPointY: 0,
      cropX: 60,
      cropY: 30,
      startingPointX: 30,
      startingPointY: 15,
      destinationX: 0,
      destinationY: 0,
      duration: 300,
      pointOffsetEnable: false,
      pointOffsetLevel: 4,
      timeOffsetLevel: 100,
      spacingEnable: false,
      spacingLevel: 2
    }).render();`

Just config your arguments, easy to use in your project. BTW, you may need webpack and babel loader to run this es6 component.
