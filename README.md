# SASS-Light-Dark-theme
This is an example of how to create a Light/Dark theme project in SASS using @if SASS directive.

## How it works

First of all use your console inside the project. Type
```
sass main.scss:main.css --watch
```

now SASS will be looking for changes!

Inside the main.scss file you will find a key variable named "$theme". This variable only allows 2 values: dark, light.
Depending in which one you use, the color variables will change to display a 'Light mode' or a 'Dark mode'.

## The @if directive in SASS

You can use this directive for any purpose you have in mind. I used it to build this easy-and-fast project of a Dark/Light theme. It usually depends in the value of a variable. It is **a must** to define the allowed values of the variables you'll be using in the @if directive condition.

>For example, as I defined it in my project:
```scss
// Theme variable. Allowed values: 'dark', 'light'. Light by default.
$theme: light;
```

Keep in mind that this is a fast way to show your clients a live light/dark mode demonstration of their product.

### You will find me also in
[Twitter](https://twitter.com/helleworld_) [Behance](https://www.behance.net/desiremcarmona)
