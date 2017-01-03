# ClockJS

Easier way to handle clocks in widgets.

# Usage

```javascript
clock({
  twentyfour : false,
  padzero : false,
  refresh : 1000,
  success: function(clock){
    document.getElementById('time').innerHTML = clock.hour() + ':' + clock.minute();
  }
});
```

Created and maintained by @JunesiPhone http://junesiphone.com
Projects this is used in and many other iOS Widgets http://junesiphone.com/OPW