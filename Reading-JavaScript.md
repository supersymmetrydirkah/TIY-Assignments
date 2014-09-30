```javascript
var pubnub = PUBNUB({
	publish_key   : "demo",
	subscribe_key : "demo"
});
```
* Variable: = pubnub
* String: = "demo"

```javascript
  var pos   = message['pos'] || [100,100]
    ,   mouse = Sprite.create({
        image : {
            url : 'http://www.pubnub.com/static/mouse.png',
            width : 600,
            height : 30,
            offset : {
                top : 36,
                left : 0
            }
 ```           
* Variable: = message
* String: = http://www.pubnub.com/static/mouse.png
* Value: = Number 600, Number 30, Number 36, Number 0 
* Array: = Number 100

```javascript
 var pos = get_pos(e)
    ,   msg = {
            'pos'   : pos,
            'click' : 1,
            'uuid'  : uuid
```            
* Variable: = pos
* Value: = Number 1

```javascript
var Sprite = {
    /**
     * Adds to screen and creates DOM Object
     */
    create : function(sprite) {
        sprite.intervals = {
            animate : 0,
            move    : {}
        }
```        
* Variable: = Sprite
* Operators = '*', 
* Value: = Number 0

```javascript
       var offset = offset || {};
        if (typeof offset.top == 'number')
            sprite.image.offset.top = offset.top;
        if (typeof offset.left == 'number')
            sprite.image.offset.left = offset.left;

        PUBNUB.css( sprite.node, {
            backgroundPosition : '-' +
                (sprite.cell.size * cell + sprite.image.offset.left) +
                'px -' + sprite.image.offset.top + 'px'
        }
```        
* Variable: offset
* Conditional Statement: if (typeof offset.left == 'number'), if (typeof offset.left == 'number')
            
* Operators: `-`, `+`, `*`

```javascript
var current_time = start_time
            ,   end_time     = start_time + duration
            ,   start_prop   = sprite[property] || 0
            ,   distance     = value - start_prop
            ,   update       = {}
            ,   ikey         = property + value;

            Sprite.stop_move( sprite, ikey )
```
* Variable: current_time
* Operators: `-`, `+`
* Value: number 0

```javascript
   var posx = 0
    ,   posy = 0;

    if (!e) return [0,0]
    
* Variable: posx
* Conditional Statement: if

   if (!position) {
            position = 0;
            Sprite.stop_animate(sprite);
        }
```        
* Conditional Statement: if (!e) return [0,0], if (!position)
* Variable: Number 0

```javascript
      var current = now()
        ,   diff    = current - start_timer
        ,   mill    = (''+diff).split('').slice(-3).join('')
        ,   sec     = Math.floor(diff / 1000) % 60
        ,   min     = Math.floor(diff / 60000);

        sec < 10 && (sec = "0" + sec);
        min < 10 && (min = "0" + min);

        timer.innerHTML = [min, sec, mill].join(":");
    }, 60 )
```    
* Variable: current
* Operators: `+`, `/`, `%`, `-`
* Value: Number 10, Number 0, Number 1000, Number 60000, Number 60, Number -3,

```javascript
   var audio = soundbank[sound] || (function(){
                var audio = soundbank[sound] = p.create('audio');

                p.css( audio, { display : 'none' } );

                p.attr( audio, 'prelaod', 'auto' );
                p.attr( audio, 'autoplay', 'true' );

                audio.innerHTML = p.supplant(
                    "<source src={file}.wav>"+
                    "<source src={file}.ogg>"+
                    "<source src={file}.mp3>",
                    { file : sound }
```                    
* Variable: audio
* Boolean: true
* String: "<source src={file}.wav>", "<source src={file}.ogg>", "<source src={file}.mp3>"

```javascript
   var posx = 0
    ,   posy = 0;

    if (!e) return [0,0]
```    
* Variable: posx
* Conditional Statement: if (!e) return [0,0]
* Value: number 0
