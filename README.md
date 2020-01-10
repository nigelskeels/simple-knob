# simple-knob
Simple Web Component and CSS based knob

Web components and css only, no dependencies!!


Import the component
```
<script type="module" src="knob-component.js"></script>
```

Use the component
```
<knob-component id="knob1" value="100"></knob-component>
```

Adding some extra parameters
```
<knob-component id="knob1" value="100"></knob-component>
```

Adding a listener for value changes
```
  var el = document.getElementsByTagName("knob-component")[0]
  document.addEventListener('knobuievent', function (ev) { 
          console.log("knobuievent",ev.detail) 
  }, false);
```