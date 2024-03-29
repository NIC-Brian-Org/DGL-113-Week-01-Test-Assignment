# DGL 113 Week 01 Test Assignment

This is basically the same as this repository:

https://github.com/NIC-Brian-Org/DGL-113-Week-01-Demo

The main difference is that this is a private template
configured to work with GitHub Classrooms and
autograding.

This is just for students to get familiar with
GitHub Classroms and autograding. It is not actually
going to be graded.

Here are instructions from the original repository
for your reference:

This repository is a starter for basic client side JavaScript development.

It is configured for automated testing using GitHub actions and Jest.

The automated tests check for an `alert()`, some JavaScript variables,
and some content injected into the HTML using `document.write()`.

If you want to pass the tests, add the script with the `alert()` just
inside the opening `<head>` tag.

```html
<script>
    alert( "Check out our amazing prices!" );
</script>
```
In the above script, add statements to set up the pricing variables.

```javascript
const proPrice = 99;
const enterprisePrice = 2 * proPrice;
```

In the HTML body, replace the Pro pricing of `15` with a call to
`document.write()`.

```HTML
<script>document.write( proPrice );</script>
```

Do the same for the Enterprise pricing.

```HTML
<script>document.write( enterprisePrice );</script>
```

This post describes how to <a 
href="https://www.koehler.ca/2023/01/08/client-side-javascript-development-github"
target="_blank">
set up your local development
environment</a>.
