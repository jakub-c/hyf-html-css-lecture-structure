# Week 02

## Timetable

to be discussed

### Live coding 01 - forms

* types:

  * text
  * email
  * password
  * textarea
  * select
  * button

* attributes:
  * name
  * value
  * placeholder
  * maxlength

#### Semantic and UX friendly use of `for`

```html
<form action="#">
  <label for="email">Email:</label>
  <input type="email" id="email" placeholder="email@adress.com" />
  <button>Send</button>
</form>
```

* placeholder is not a label and vice versa

### Asignment 01 - form

specs:

* background: #3b81c8
* foreground: #23252f
* signup: #e35141
* twitter: #47a1ec
* facebook: #405a93
* fonts:
  * Arial for sans-serif
  * https://fonts.google.com/specimen/Merienda+One - for serif
* font-sizes:
  * heading: 2.5rem;
  * label: 1rem;
  * form-text: 1rem;
* don't focus on the icons - if you can't find any svg skip it

[source](https://w3layouts.com/preview/?l=/flat-open-account-form-responsive-widget-template/)

### Live coding 01 - animation

```html
<button>Hello world</button>
```

```css
body {
  text-align: center;
}

button {
  background: #fff;
  border: solid 1px #000;
  font-size: 1.5rem;
  font-weight: bold;
  line-height: 1;
  padding: 0.7rem 2.2rem;
  text-transform: uppercase;

  transition-property: all;
  transition-duration: 1s;
}

button:hover {
  background: #b9b9b9;
  transform: scale(1.2);

  transition-property: all;
  transition-duration: 1s;
  transition-delay: 0s;
}
```

### Final assignment:

#### Live coding - how to add JS into HTML

tabbed naviagion:
https://github.com/bkapke/simple-tabs/

#### assignment:

* start with a desktop version
* designer forgot creating labels for the all form fields - fix it
* placeholder values are wrong - fix them
* create all 4 tabs and make them work with JavaScript
* once the desktop version is ready - try to make it responsive

#### specs:

* body bg: https://hdwallsource.com/img/2014/9/beautiful-sea-foam-wallpaper-39428-40337-hd-wallpapers.jpg
* button: #f37100
* button-hover: #975a39
* button-submit: #7b96d1
* font: Arial
* font-size: 1.6rem

[source](https://w3layouts.com/xtreme-travel-guide-flat-bootstrap-responsive-web-template/)
