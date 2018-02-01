# Markdown Styleguide
For writing technical instructions

**Contents**
1. [Project organization](README.md#01-project-organization)
1. [Headlines](README.md#02-headlines)
1. [Screenshots](README.md#03-screenshots)
1. [Code, Buttons or Files](README.md#04-code-buttons-or-files)
1. [Hints and warnings](README.md#05-hints-and-warnings)
1. [Example](README.md#06-Example)


## 01 Project organization

- Separate your instructions into modules
- Give each module a name including order number and name
  - Example: **03 Adding Documentation**
- Add a `README.md` to each module folder for the content
- Add a `Resources` folder to a module for screenshots etc if needed

## 02 Headlines

Add one single H1 headline with the title of the module at the beginning of the file and describe briefly what to expect in this module. Point out what the module is about and why we are doing it.

For every step, add a H2 numbered headline and add H3 headlines if you need to structure substeps.


> # Adding documentation
> In this module, we will add documentation to the project. Not only this increases...
> 
> ## 1. Documentation root
> ### 1.1 Create a new Markdown file
> Let's start with a new file which defines you root. To create a new markdown file, click the ***New*** button at the top left corner...

###### Markdown

```
# Adding Documentation
In this module, we will add documentation to...

## 1. Documentation root
### 1.1 Create a new Markdown file
Let's start with a new file which defines you root. To create a new markdown file, click the ***New*** button at the top left corner... 
```

## 03 Screenshots

Add screenshots where ever it makes sense and add as much as possible. Please make sure, to capture in a wide landscape format to make the screenshot as narrow as possible to increase readability.

Also, let all screenshots link to the original images in case readers need a larger view.

![New Xamarin.Forms project in Visual Studio Screenshot](https://raw.githubusercontent.com/robinmanuelthiel/xamarinworkshop/master/Misc/vsnewxamarinformsproject.png)

###### Markdown

```
![Describe Screenshot](Resources/screenshot.png)
```

## 04 Code, Buttons or Files

Whenever providing code, make sure to wrap it into a dedicated coding block. Even if it is just a single line. Do never write any code inline!

Make sure to specify the language to get proper syntax highlighting which increases readability.

```csharp
// Add comments to your code
var code = "This is a C# string";
```

You will come to a point where you mention a class name, method or variable in your documentation

- Clickable elements like buttons and menu items are ***Bold and italic***
- Code as classnames and methods are `marked as code`
- Filenames are also `Marked.text`

###### Markdown

<pre><code>***Bold and italic*** for buttons

`marked as code`

```csharp
// Add comments to your code
var code = "This is a C# string";
```</code></pre>

## 05 Hints and warnings

Use quotes to highlight hints and warnings in your documentation whenever you feel the need to highlight an important side note. Use a bold "**Warning:**" or "**Hint:**" to introduce.

>**Warning:** This is a warning!

>**Hint:** This is a hint!

###### Markdown

```
>**Warning:** This is a warning!

>**Hint:** This is a hint!
```

## 06 Example
https://github.com/robinmanuelthiel/xamarinworkshop/tree/master/07%20Platform%20Specifics
