# HTML 
- structure page 
- tag
  - tells browser type of content 
  - homepage should be called index.html 

## Two Ways To Create New File 
1. click file icon below folder name 
2. mouse, right click new file 

- Inside the body tag, everything gets rendered/displayed to web browser  

- inside head tag
  - title tag 
  - meta tag 

### Inspect Element Chrome Dev Tools 

- CMD + OPTION J  
  - javascript console 
- CMD + OPTION + I 
  - Developer Tools 

strong tag 
- bold text 

em tag 
- italize text 

small tag 
- make text small 

heading tags
- six tags 
- number 6 is least important 

unordered list with ul tag 
- list item or li inside container 

ordered list with ol tag 
- list items or li inside ol container 

division tag 
- group content into containers 
- block level container 
- no visual effect in web browser 
- start on new line 

span tag 
- inline container for content 
- generic inline container 
- don't start on new line 

break tag 
- cause line break 

horizontal rule 
- long line 

img tag 
- need src attribute 
```html
<img src="path to source">
```
  - alt attribute 
    - use by screen readers that display images for accessibility 
    - text represenation of image or describe image 
``` html
<img src="image" alt="Azumi #8999">
```


# Code Blocks
1. use back three back ticks ```
2. immediately after three backticks put language then line break 
3. when you ready to finish code snippet, use three closing backticks ```

anchor tag 
- create hyperlinks 
- syntax
``` html
<a href=" ">Text User Clicks to navigate to hyperlink   </a>
```
- href attribute is hyperlink reference 
  - website you want user to go to when they click text inside 
  - styled differently by the browser to look like a hyperlink 

Create a hyperlink to different pages inside website your website 
1. create about.html
2. create a ```<a href="about.html"> ``` inside index.html page 

blockquote tag
- quote something from another website 
- you can add attribute site 
```html
   <blockquote site="path to source " > 
```

```python
thisList = ['apple', 'orange', 'doctor strange']
print(thisList)
```

inline styling
- use the 
```html
<p style="property:value">
```
comments
- control + forward slash echo # project
