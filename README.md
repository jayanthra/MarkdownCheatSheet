# Markdown cheet sheet

## Headers

Use # to change type of headers

## Word styling
_italic_ **bold** ~~strikethrough~~

## Load Image

##### Basic image loading with tooltip
![Image](https://source.unsplash.com/random/200x200 "image caption")

##### Load image with url as variable
![Image][myimage]

##### Load image using src tag
![<img src="https://source.unsplash.com/random/200x200">](https://source.unsplash.com/random/200x200)

[myimage]: https://source.unsplash.com/random/200x200

## Text/Image link

[I am a text link](https://github.com/jayanthra)

Image as a link
[![](https://source.unsplash.com/random/50x50)](https://source.unsplash.com/random/200x200)

## Lists

##### Unordered list
- Item 1
- nested
- Item 2
- Item 3

##### Ordered list

1. Item 1
    - Nested item 1
    - Nested item 2
1. Item 2
1. Item 3

## Horizontal Rules
Dont cross the line keep space

---

## Blockquote

> Time and tide waits for none
>
> Nose is the groin of the head 
> -**Dwight Schrute**

## Code Block

```js
var greeting = 'Hello'
console.log(greeting);
```
Did you try using `let`

```diff
-var greeting = 'Hello'
+let greeting = 'Hello'
```

## Tables

|Name|Age|Designation|
|:----|:---:|----:|
|Dwight|34|Assisstant to the Regional Manager|
|Jim|32|Co Manager|
|Michael|45|Regional Manager|

> The : is used to align

## Checkbox 
* [x] Call customer
* [ ] Make Sale
* [ ] Make Money

