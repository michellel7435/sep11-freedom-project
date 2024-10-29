# Entry 1
##### 10/29/24

## Context: 
For my year-long project, me and my partners ( Simran and Nancy ) had chosen to make a game about rhythm such as a game like the piano where you have a song and you have to click on the keys on time. The tool I chose to use was animejs because the tool was newer and if I want to do a rhythmic game then I need to have animation within that game to make it process and look better. This tool also interested me because of the variety of codes or animation it provides, there was a lot options that would be able to help me make this game.What makes me interested in choosing this game is that music captives me and I feel like this game can help captives others interests as well. This would be a more complicated rhythm game since there are 3 people with 3 different tool, so what we would be doing is making questions that you have to answer on beat/rhythm such as how you click on the piano keys and so on.

## Content:
I've been using my tool for 2-3 weeks now and tinkering with it such as using the examples on [AnimeJS](https://animejs.com/documentation/#cssSelector) and coding it onto JSBin to get an idea of my tool and trying to understand how to use it. I also had been watching videos on my tool to go more advance such as watching a video on [SVG Path, Morphing, Line Drawing](https://www.youtube.com/watch?v=mAKYW_1f-dw&t=482s) which can help me if I want to create or form shapes to my liking. Another video I watched was a basic [AnimeJs Tutorial](https://www.youtube.com/watch?v=uRDLFXxihgc) which helped me develop an idea of animejs and how to use it properly. 

Tinker:                                                  
I was going through website of [AnimeJS](https://animejs.com/documentation/#cssSelector) and came across an animation, "DOM Node / NodeList" which the code is represented below. The code would image a sort of shape that would translate 270 right.

```js

<script>
      var elements = document.querySelectorAll('.dom-node-demo .el');

      anime({
        targets: elements,
        translateX: 270
});
</script>
```
The code was unable to work without the div class needed which isn't presented in the website documentation which I watched a video on [AnimeJs Tutorial](https://www.youtube.com/watch?v=uRDLFXxihgc). DIV Class:
```js
    <div class="dom-node-demo">
      <div class="el"></div>"
    </div>
```
I also needed to add a CSS to my code in order to show up. CSS:
```js
.el {
  width: 400px;
  height: 100px;
  background-color: black;
}
```
This tinkering was able to help me have an understanding that I need to always add a class to my animejs codes in order for it to work and show up.
## Engineering Design Process (EDP)                                                  
Currently I am in the first step of the engineering design process where defining the problem is the process. The problem might be how we can be beneficial towards people and how it can help them in a way. So that's why we are making the game interactive by asking questions to test your minds on the specific topic.

## Skills: 
#### Organization
Gaining organizational skills allowed me to make use of my resources effectively and efficiently. I can effectively manage my time, energy, and workspace when I am organized, and I can finish all of the tasks assigned to me. Whenever I reorganized my work, I found that it had increased my performance and helped me be more productive. When my stuff are disorganized and I'm having trouble finding anything, having organizational skills can be helpful. If I reorganize everything in a certain order or put the work in its proper area, it will make it easier for me to comprehend and for the viewers to discover things without trouble.

#### Time Management
Time management has become an important skill toward me because it's not just for one of my classes but for all my class. I always feel stressed when I have a lot of things to do and almost all of my work is due on the same date, so what I tend to do is do those work whenever I can, such as my free times at school. Time management is important because it helps you stay organized and it eases my mind whenever I'm stressed over multiple tasks at once but I try to focus on one at a time whenever I can.

#### 

## Next Steps
[Next](entry02.md)

[Home](../README.md)
