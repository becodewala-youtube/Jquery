
# Jquery🚀

- Javascript Library
- Write less do more
- Simplifies javascript 
- Run exactly same with Other Browsers
- Released in Aug 2006


## Links🔗

 - [Jquery Plugings](https://plugins.jquery.com/)
 
## Plugins example 👾

 - Countdown
 - Cropper - Image crop
 - 3D Slider
 - Interactive Polaroid Photo
 - Online Signature
 - 360 Rotate images
 - Image merge edit draw maker
 - Credit Card Interaction
 - Background animation
 
## How to implement in your code? 🤔

- By Installing into projects
- By Using CDN
   - CDNJS
   - jsDeliver
   - Google
   - Microsoft


## Syntax 🔍


```bash
  $(selector).action();
```
- For Example
 ```bash
  $("para").hide();
```


## Select 🔍

To Select HTML Tags

```bash
  $("button")
```
To Select ID Tags

```bash
  $("#Id_Name")
```
To Select Class Tags

```bash
  $(".Class_Name")
```
To Select All Elements

```bash
  $("*")
```
To Select Specific Tags with Specific class

```bash
  $("p.Class_Name")
```


## Event 👆

- Examples 1

```bash
  $("#button").click(function(){
  alert("Clicked");
  });
```
- Examples 2

```bash
  $("#button").click(function(){
  $("#para").hide();
  });
```
- Examples 3 - onclick button will be hidden

```bash
  $("#button").click(function(){
  $(this).hide();
  });
```
- Examples 4 - double click

```bash
  $("#button").dblclick(function(){
  $(this).hide();
  });
```



- Example 5 - Multiple Event

```bash
 $("colored-div").on({
 click: function(){
  $(this).css("background-color",red);
 },
 mouseenter: function(){
  $(this).css("background-color",green);
 },
 mouseleave: function(){
  $(this).css("background-color",blue);
 }
 });

```


## Important
- When our document got ready the execute the inside function
```bash
- $(document).ready(function(){
  $("colored-div").on({
  click: function(){
  $(this).css("background-color",red);
 }
});

```

- OR
```bash
- $(function(){
  $("colored-div").on({
  click: function(){
  $(this).css("background-color",red);
 }
});

```

- Alert will show before 3s
```bash
$("#btn").click(function(){
  $("#colored-div").hide(3000);
   alert("div hidden");
});
```
- Use callback function
```bash
$("#btn").click(function(){
  $("#colored-div").hide(3000,function(){
   alert("div hidden");
   });
});

```

## Effects
- Our div will be displayed and hidden in one second
```bash
$("#btn").click(function(){
  $("#colored-div").hide(1000);
});
$("#btn2").click(function(){
  $("#colored-div").show(1000);
});

```
- Let's Animate
```bash
$("#btn").click(function(){
  $("#colored-div").animate({
   opacity: '0.5',
   height: '20px',
   width: '100px'
   },5000);
});

```
- Stop Animation
```bash
$("#btn2").click(function(){
  $("#colored-div").stop();
});
```
- Chaining
```bash
  $("#btn2").click(function(){
  $("#colored-div").css("color","red").slideUp(2000).slideDown(1000);
});
```





