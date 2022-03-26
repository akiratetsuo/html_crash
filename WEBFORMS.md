# WEB FORMS

web forms

- capture user information
- normally composed input fields so user can input information

```html
<input type=" " />
```

## Form Tag

- inside form tag is where all input field go

```html
<form action=" TELLS WEB BROWSER WHAT TO DO WHEN FORM IS SUBMITTED"></form>
```

- Action Attribute

  - has to do with PHP and server-side data

- type attribute = text
  - single line of text

```html
<form>
  <input type="text" />
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

```html
<form>
  <label for="username" placeholder=""> content </label>
  <!-- for attribute - what input field is this label for -->
  <input type="text" id="username" name="username" />

  <label for="email" placeholder=""> enter email: </label>
  <input type="email" id="email" name="email" />

  <label for="password" placeholder=""> enter password </label>
  <input type="password" id="password" name="password" />
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

```html
<label for> </label> <>
```

radio button

- allows user to click only one of several options
- when user clicks radio button, it becomes checked, and all other radio buttons with equal name become unchecked.
- <strong> name attribute important when grouping together radio button name fields </strong>
- value tag
  - so server can see value submitted user selected, unlike input type="" where user species type

```html
<form action="">
  <input type="radio" name="gender" value="male" /> Male <br />

  <input type="radio" name="gender" value="female" /> Female <br />
  <input type="radio" name="gender" value="other" /> Other <br />

  <!-- name tag in radio buttons all set to same value  -->
</form>
```

Select Box

- user select and takes on the the value of whatever user selects
- when user submits, form sent value to server to do something
- drop down box is the same thing as select box
- each option inside its own option tag
- not an input

```html
<label for="question"> Security question: </label>
<select name="question" id="question">
  <option value="q1">What color are you favorite pair of cucumbers?</option>
  <option value="q2">
    If you could be a vegetable, what fruit would it be?
  </option>
  <option value="q3">
    What is the answer to your favorite security question
  </option>
</select>
```

text area

- not an input
- when you need more than one line of text
- cols
- rows
- placeholder attribute or default content that disapears when user types placeholder=""
- with textarea, user can grab corner and resize it

```html
<label for="bio"> Your bio:</label>
<textarea name="bio" id="bio" cols="30" rows="10" placeholder="about you...boo">
 Default Place holder content that appears inside textarea </textarea
>
```

submit button

- user clicks button, when ready to submit form
- all the data you submit will be inside the url bar

```HTML
<input type="submit" value="submit the form"  >
```

required attribute

- make input required
- gives you an error message if you try to submit without input

