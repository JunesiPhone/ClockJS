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
Projects is used in many iOS Widgets and OPWs http://junesiphone.com/OPW