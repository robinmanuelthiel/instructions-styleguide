# Styleguide for writing technical instructions in Markdown

[01 Project organization](README.md#01-project-organization)
[02 Headlines](README.md#02-headlines)


## 01 Project organization

- Separate your instructions into modules
- Give each module a name including order number and name
  - Example: `03 Adding Documentation`
- Add a `README.md` to each module folder for the content
- Add a `Resources` folder to a module for screenshots etc if needed

## 02 Headlines

Add one single H1 headline with the title of the module at the beginning and describe briefly what to expect in this module. Point out what the module is about and why we are doing it.

For every step, add a H2 numbered headline and add H2 headlines if you need to structure sub steps.


> &nbsp;
> # 03 Adding documentation
> In this module, we will add documentation to the project. Not only this increases...
> 
> ## 1. Documentation root
> ### 1.1 Create a new Markdown file
> Let's start with a new file which defines you root. To create a new markdown file, click the ***New*** button at the top left corner...
> 
> &nbsp;

###### Markdown

```
# 03 Adding Documentation

In this module, we will add documentation to...

## 1. Documentation root

### 1.1 Create a new Markdown file

Let's start with a new file which defines you root. To create a new markdown file, click the ***New*** button at the top left corner... 
```

## Screenshots

Add screenshots where ever it makes sense and add as much as possible. Please make sure, to capture in a wide landscape format to make the screenshot as narrow as possible to increase readability.

Also let all Screenshots link to the original images in case readers need a larger view.

![New Xamarin.Forms project in Visual Studio Screenshot](https://raw.githubusercontent.com/robinmanuelthiel/xamarinworkshop/master/Misc/vsnewxamarinformsproject.png)

###### Markdown

```
![New Xamarin.Forms project in Visual Studio Screenshot](Resources/vsnewxamarinformsproject.png)
```

## Code, Buttons or Files

Whenever providing code, make sure to wrap it into a dedicated coding block. Even if it is just a single line. Do never write any code inline!

Make sure to sepcify the language to get proper syntax highlighting which increases readability.

```csharp
// Add comments to your code
var code = "This is a C# string";
```

You will come to a point where you mention a class name, method or variable in your documentation

- Clickable Elements are ***Bold and italic***
- Code as classnames and methods are `marked as code`
- Filenames are also `Marked.text`

###### Markdown

<pre><code>***Bold and italic*** for buttons

`marked as code`

```csharp
// Add comments to your code
var code = "This is a C# string";
```</code></pre>

## Hints and warnings

Use quotes to highlight hints and warnings in your documentation whenever you feel the need to highlight an important sidenote. Use a bold "**Warning:**" or "**Hint:**" to introduce.

>**Warning:** This is a warning!

>**Hint:** This is a hint!

###### Markdown

```
>**Warning:** This is a warning!

>**Hint:** This is a hint!
```

## Example
https://github.com/robinmanuelthiel/xamarinworkshop/tree/master/07%20Platform%20Specifics
