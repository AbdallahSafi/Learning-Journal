# What is JavaScript?

It is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else. (Okay, not everything, but it is amazing what you can achieve with a few lines of JavaScript code.)It consider high level programing language and it is intrepted language which mean it excuted line by line.

 It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the .js extension.

If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created.

# Basic javascript inctrutions

## Variables
A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.

### How I can declare a variable ?

You should use key word Var and then type the name of the variable and you can assign value to it as the following figure
![variables](https://www.bookofnetwork.com/images/javascript-images/1.png)

### There is some rules of how we can name the variable:
- Variable names cannot contain spaces.
- Variable names must begin with a letter, an underscore (_) or a dollar sign ($).
- Variable names can only contain letters, numbers, underscores, or dollar signs.
- Variable names are case-sensitive.
- Certain words may not be used as variable names, because they have other meanings within JavaScript.

## Datatype in Javascript ?
### there is three main primitive data type to be considered now 
- Boolean — true or false
- Number — integers, floats, etc
- String — an array of characters i.e words

## javascript comments
When writing code you may have some complex logic that is confusing, this is a perfect opportunity to include some comments in the code that will explain what is going on. Not only will this help you remember it later on, but if you someone else views your code, they will also be able to understand the code (hopefully)!

### creating single line comments
To create a single line comment in JavaScript, you place two slashes "//" in front of the code or text you wish to have the JavaScript interpreter ignore. When you place these two slashes, all text to the right of them will be ignored, until the next line.

```javscript
<script type="text/javascript">
<!--
// This is a single line JavaScript comment

document.write("I have comments in my JavaScript code!");
//document.write("You can't see this!");
//-->
</script>
```
### creating multi-line comments
Although a single line comment is quite useful, it can sometimes be burdensome to use when disabling long segments of code or inserting long-winded comments. For this large comments you can use JavaScript's multi-line comment that begins with /* and ends with */.

```javascript
<script type="text/javascript">
<!--
document.write("I have multi-line comments!");
/*document.write("You can't see this!");
document.write("You can't see this!");
document.write("You can't see this!");
document.write("You can't see this!");
document.write("You can't see this!");
document.write("You can't see this!");
document.write("You can't see this!");*/
//-->
</script>
```