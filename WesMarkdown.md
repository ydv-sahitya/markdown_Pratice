

### This is Paragraphs and text Decoration.

I **love** you.

I _really_ love you. I really *love* you;

prince is ~~really cool~~ . using ~ HERE.


### Heading markdown.

note: use # and ##

# heading 
## heading two
### heading three



<http://sahit.com>

## this is one way using it.

[My gihub account](http://github.com/sahit)

[Hackeryou.com](http://hackeryou.com "this is where i teach")

Note: putting link between text is not very readable. In next
 example we learn how to create readable links.

**Example:**

 if you want to learn React, you can learn at React for beginner.com -
 [sahi][1] did a great job in this.


 [sahit][1] also teaches at [HackerYou][hack] where you can come an learn with him in person. checkout
 their site for more into.


 [1]: https://sahit.com  
 [hack]: https://hackyou.com



# Markdown Image

![Wow great](https://unsplash.it/500/500?random " nice road with nice view.")


![amazing landscape][Landscape]

 <!-- here I am not using ! sign , so pic is hidden in the link. -->
[a link](https://unsplash.it/500/500?image=1000)

note: if I want to small size for the pic. 

[![](https://unsplash.it/50/50?image=1000
)](https://unsplash.it/500/500?image=1000)  


earlier this syntex. looks little funky.

so here I can use Html src.

[<img src="https://unsplash.it/50/50?image=1000">](https://unsplash.it/500/500?image=1000)

I can use it that too.



### Note if something you can not do with markdown. you can use html for that.


<img src= "dog.jpg" width= "500" height="500" alt="">

<style>
  img {
    width:100px;
    height:100px;
  }
  </style>


<figure>
 <figcaption> hi some one/</figcaption>
</firgure>


[Landscape]: https://unsplash.it/500/500?image=1000




### list __ordered, unordered, bullets and nesting.


## Ingredients 

+ milk 
+ eggs
+ bread 
+ becom

## steps

1. combine ingredients
    * sift the flower.
      * common this works well. 
2. Lick the bowl
3. gentely tir together
    * sift the flower 
  
        this is inline.
        
        ![](https://unsplash.it/500/500?image=1000)

        ``` js
        const john = 4;
        console.log(john);
        ```
        
<!-- nest the picture inside.  -->
    
1. Bake at 350 for 20 mintues. 


## Line Breaks, Horizontal ules and BlockQuote.

 ## Line Breaks
 ravi is cool.<br>
 He is really is.

 I love you. 

 ## Horizontal Rules.

 something

 ---

## block Quotes 

> You miss 100% of the shots you don't take. 
> 
> -**wayne Gretzky**.


## code Blocks.

Here is my code :

``` js
 var x = 200;
 const dog = 'snickers';
```

```php
$age = 50;
$name = "wes";
echo strtoupper($name);
``` 
          
```
const sahi = 100;
```
Hey did you try `var x = 100;` ?

```diff
var x = 100;
- var y = 200;
+ var y = 300;
```


## tables .......

|Dog's Name| Dogs' Age|
|:---------:|:----------:|
|Snickers| 2|
|Prudence| 8|


## Github Treats. 

* [ ] Get Milk
* [ ] crack Eggs
* [ ] cook becon

<!-- check out in github if its working or not -->
* [*] cook becon  

- [ ] this is something

<!-- # mastering Markdown

Hell there - welcome to mastering markdown.

I'm **super exicted** to have you along for the ride.

:ph

```javascript

const name = 'prince singh';
let age = 100;
```
 -->
