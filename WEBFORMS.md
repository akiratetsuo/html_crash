# WEB FORMS 



web forms 
- capture user information 
- normally composed input fields so user can input information  
```html 
<input type=" " >
```
## Form Tag 
- inside form tag is where all input field go 
```html
<form action=" TELLS WEB BROWSER WHAT TO DO WHEN FORM IS SUBMITTED" >
```

- Action Attribute 
    - has to do with PHP and server-side data 


- type attribute = text
    - single line of text 
``` html
<form>
    <input type="text">
</form>
```

type attribute 
- selects type of user input 

id attribute 
- value must be unique 
- no other element can have same id 
- link id tag to label tag 

label tag 
- tells user what to type into input field 
- link id tag to label tag 
- for attribute 
  - what input field is this label for 
  - for attribute inside label links to the id attribute inside input field 
  - associate label with input field via for attribute in label and id attribute in input field 
  - 

``` html
<form>
    <label for="username" > content </label>
    <!-- for attribute - what input field is this label for -->
    <input type="text" id="username" name="username"> 
    
    <label for="email"> enter email: </label>
    <input type="email" id="email" name="email"> 

    <label for="password"> enter password: </label>
    <input type="password" id="password" name="password">

</form>
```
input type email
- web browser interpret field as emial 
- web browser checks if valid email 

input type password
- hide what user types into field 

name attribute 
- like id attribute 
- used for server-side processing 
- <strong> web server get value from input field </strong>
- good idea to include name attribute for backend developer 
- give id same value as name attribute 
- <strong> also group different parts of web forms together ie: radio button</strong>
``` html
<label for> </label>
<>
```
radio button
- allows user to click only one of several options 
- when user clicks radio button, it becomes checked, and all other radio buttons with equal name become unchecked. 
- <strong> name attribute important when grouping together radio button name fields </strong>
- value tag 
  - so server can see value submitted user selected, unlike input type="" where user species type 
``` html
<form action="">
<input type="radio" name="gender" value="male" > Male <br>

<input type="radio" name="gender" value="female" > Female <br>
<input type="radio" name="gender" value="other" > Other <br>

<!-- name tag in radio buttons all set to same value  -->
</form>
```


