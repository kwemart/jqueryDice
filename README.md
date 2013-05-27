#jqueryDice

A simple dice plugin with a simple rolling animation

##Requirements

[jQuery](http://jquery.com)

##Usage

  <div id='dice'></dice>
  <script>
    $(function(){
      $("#dice")
        .dice()
        .click(fucntion(){ $(this).dice("roll"); });
    });
  </script>

##Options

  $(element).dice({
    diceSize : Size of dice in pixel (default 20),
    duration : Dice rolling duration in milliseconds (default 500)
  });
  
  
  $(element).dice("roll"[, v]);
  
  // v : target value. Default is random.
  
  $(element).dice("option", opt);
  
  // opt : An option object (like above)
  
##Demo

[Click](http://dev.lazygyu.net/test/dice/jqueryDice/example.html)
  
  
