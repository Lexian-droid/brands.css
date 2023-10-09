# BRANDS.CSS
BRANDS.CSS is a custom theme for the CSS framework W3.CSS. It is intended to add easy integration for popular brands, colors, and otherwise.
It comes with many already existing brands, with the data continuously expanding as time goes on.

# Features
- Free to use
- Easy to Use and Integrate
- 100% open source

# How to get started
In order to get started using BRANDS.CSS all you have to do is link the <a href="https://cdn.jsdelivr.net/gh/lexian-droid/brands.css@latest/brands.min.css">CSS File</a> in your ``<head>`` element.

Here is an example:

```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/lexian-droid/brands.css@latest/brands.min.css">
```

Now, how do you use it? That's simple too.

In any element, simply add the following class: ``w3-brand-brandName`` of course, replacing **brandName** with your desired brand. This will change the element
to follow the same design style of the brand specified.

This theme also includes the ability to use "Hover" options as well, you can do hovering theme with the following class: ``w3-brand-hover-brandName`` of course, still replacing **brandName** with your desired brand.

And that's all you need to get started.

# How to create Custom Brands
In order to create a custom brand, simply follow these steps.
1. Create a file, called "additional-brands.css"
2. Open "additional-brands.css" in your preferred code editing software
3. Add a new line, and enter the following: ``.w3-brand-brandName, .w3-brand-hover-brandName:hover{}`` and replace **brandName** with your desired brand.
4. in the ``{}`` simply add a Newline.
```css
.w3-brand-brandName, .w3-brand-hover-brandName:hover {

}
```
6. Now, add the next two lines: (***Please read the comments***)
```css
.w3-brand-brandName, .w3-brand-hover-brandName:hover {
  color: #HEX !important; /* Replace #HEX with your desired brand text color */
  background-color: #BGHEX !important; /* Replace #BGHEX with your desired brand background color */
}
```
6. Now that you have styled your class, your code should look something like this:
```css
.w3-brand-google, .w3-brand-hover-google:hover {
  color: #FFFFFF !important;
  background-color: #F4B400 !important;
}
```
Now, all you have to do is add the newly created class to your element, you can do so by simply navigating
to your HTML and adding a class called ``w3-brand-brandName`` of course, replacing **brandName** with your newly created brand.

# Contribute
We accept contributions from all over the world - If you want to contribute to BRANDS.CSS, by adding more brands, optimizing or changing existing brands, you are more then welcomed to do so! You are free to edit the repository and make as many pull requests as you see fit.

In addition, by forking brands.css, you can create your own version! and you're completely free to do so, please however, remember to follow the open source license, because your own forks can help us all improve. :)

# Thank You!
Thank you for checking out BRANDS.CSS, we hope you enjoy our project.

<a href="https://www.buymeacoffee.com/timewisely" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
