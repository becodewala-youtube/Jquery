
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

