# miniresource
demo https://codepen.io/gnjo/pen/XWbKLwd
```
//pug
script(src="https://gnjo.github.io/minire/minire.js?v=1")
button aa
video.se(autoplay style="display:none")
img.im
```
```
/*
//se[n]
0:crystal
1:damage
2:foot
3:open
4:slash
5:stair
//im[n]
0:bishop
1:chest
2:crusader
3:darkmage
4:elf
5:knight
6:mage
7:shinobi
8:treasure
9:witch
10:city
*/
 let fn={};fn.q=(s)=>{return document.querySelector(s)}
 fn.q('.se').src=se[0]//
 fn.q('.im').src=im[0]//
```
