# SAGAR AMUNDLA
I am a very enthusiastic person, and this trait has been a part of me since my childhood. I did my Bachelors in Information Technology. I am doing my masters in Northwest Missouri State University. I would like to explore the places, watching movies & Surfing through internet.


****

![Sagar](sagarimage.jpeg) 


****

## Sports:

Sports are physical activities or games that involve physical exertion and skill. They are often organized into competitive events or played for recreational purposes. Sports can be individual or team-based and are popular worldwide like Squash Ball,Hockey,Boxing,football,tennis
|NAME|REASON|NO.OF HOURS|
|----|------|-----------|
|Squash Ball|Physical Skill|1 hour|
|Hockey|a team sport|45 min
|Boxing|Strength&Fitness|1 hour
|football|a team sports|1 hour
|tennis|fun|2 hour|


****


## Quotes

>Amateurs built the Ark, professionals built the Titanic-___BEN CARSON___

>Learn to value yourself, which means: fight for your happiness-*AYN RAND*

>A person can die, but his goodness remains forever -___CHANAKYA___


****


## Code Fencing:

>[My Stackoverflow link](https://stackoverflow.com/questions/60051847/an-scss-function-to-give-order-to-elements)



```

@mixin stripes($direction, $colors) {
  $length: length($colors);
  
  @if $length > 1 {
    $stripes: ();
    
    @for $i from 1 through $length {
      $stripe: (100% / $length) * ($i - 1);
      
      @if $i > 1 {
        $stripes: append($stripes, nth($colors, $i - 1) $stripe, comma);
      }
      
      $stripes: append($stripes, nth($colors, $i) $stripe, comma);
    }
    
    background-image: linear-gradient($direction, $stripes);
  } @else if $length == 1 {
    background-color: $colors;
  }
}

USAGE:

body {
  @include stripes(to right, #8e44ad #2c3e50 #2980b9 #16a085 #27ae60);
}
```
<br>


[Striped gradient mixin](https://css-tricks.com/snippets/sass/striped-gradient-mixin)



















