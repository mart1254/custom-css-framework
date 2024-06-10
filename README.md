# Companion Framework

**Companion Framework** is a custom CSS framework built with Sass, designed to help you with your web development with pre-defined styles for headings, lists, buttons, forms, inputs, tables, and more. It offers a flexible and customizable foundation, allowing developers to create consistent and responsive designs. By leveraging Sass partials and variables, the framework ensures ease of maintenance and scalability for any web project.

## Installation of Companion Framework
Companion Framework can be installed through the use of npm via console:\
`npm i companion-framework`\
Where you can edit the example index.html or link your current file to the main.css

Companion Framework can also be cloned from GitHub:\
`https://github.com/mart1254/custom-css-framework.git`

## How to use
**Companion Framework** can be used by adding the corrosponding classes to your HTML elements throughout your project.
Simply add the name of the Companion Framework class like so:\
Before:\
`<a href="#" class="">This is a primary button</a>`\
After:\
`<a href="#" class="btn btn-primary">This is a primary button</a>`\
Some classes can be found below:

### HTML Element Classes
#### Basic Classes
- `padding-xsm`
- `padding-sm`
- `padding-md`
- `padding-lg`
- `list-disc`
- `list-decimal`
- `list-alpha`
- `list-roman`
- `color-black`
- `color-white`
- `color-yellow`
- `color-blue`
- `color-red`
- `bg-primary`
- `bg-danger`
- `bg-success`
- `bg-info`
- `img-responsive`
- `img-shadow`
#### Typography Classes
- `font-xsm`
- `font-sm`
- `font-md`
- `font-lg`
- `font-lg1`
- `font-lg2`
- `font-lg3`
- `font-lg4`
- `font-lg5`
- `font-weight-light`
- `font-weight-normal`
- `font-weight-medium`
- `font-weight-semi-bold`
- `font-weight-bold`
- `txt-center`
- `txt-left`
- `txt-right`
- `txt-justify`
#### Utility Classes
- `btn`
- `btn-primary`
- `btn-danger`
- `btn-success`
- `btn-info`
- `img`
- `form`
- `label`
- `table`
- `caption`
#### Layout Classes
- `container-xsm`
- `container-sm`
- `container-md`
- `container-lg`
- `row`
- `col`
- `col-[1-12]`

## Customization
In order to customize the framework you can overide the default **Companion Framework** classes, create new classes using the default ones, or edit the classes and variables directly by going into .scss partial files `_variables.scss`.

Create new classes using the default:

`.user-class {`\
    `font-size: $font-lg;`\
    `color: red;`\
`}`\
Edit the classes and variables directly:

`$red: orange;`
