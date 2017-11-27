# tubular 
A bower installable fork of the jQuery tubular plugin that places a YouTube video of your choice into your page as a background.
## installation
Install via bower:
```

```
## usage
```
<script type="text/javascript" src="/js/jquery.tubular.1.0.js"></script>	
```
Call tubular on your wrapper div, the outermost containing div below the BODY tag.  
```
$().ready(function() {
    $('#wrapper').tubular({videoId: 'idOfYourVideo'}); // where idOfYourVideo is the YouTube ID.
});
```
## Options
* ratio: 16/9 // usually either 4/3 or 16/9 -- tweak as needed
* videoId: 'ZCAnLxRvNNc' // toy robot in space is a good default, no?
* mute: true
* repeat: true
* width: $(window).width() // no need to override
* wrapperZIndex: 99
* playButtonClass: 'tubular-play'
* pauseButtonClass: 'tubular-pause'
* muteButtonClass: 'tubular-mute'
* volumeUpClass: 'tubular-volume-up'
* volumeDownClass: 'tubular-volume-down'
* increaseVolumeBy: 10 // increment value; volume range is 1-100
* start: 0 // starting position in seconds



