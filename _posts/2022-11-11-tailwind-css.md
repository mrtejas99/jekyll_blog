---
layout: post
title: "Tailwind CSS"
date: 2022-11-11T11:04:44+05:30
categories: tutorial
---

Tailwind CSS is basically a Utility first CSS framework for building rapid custom UI. It is a highly customizable, low-level CSS framework that gives you all of the building blocks that you need. Also, it is a cool way to write inline styling and achieve an awesome interface without writing a single line of your own CSS.

### Why Tailwind CSS ?

As we know there are many CSS frameworks but people always choose the fast and easy framework to learn and use in the project. Tailwind has come with inbuilt a lot of features and styles for users to choose from and is also used to reduce the tendency of writing CSS code and create a beautiful custom UI. It will help you to overcome the complicated task. Tailwind CSS creates small utilities with a defined set of options enabling easy integration of existing classes directly into the HTML code.

### Tailwind CSS CDN Link:
```html
<link href=”https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css” rel=”stylesheet”>
```
Note: There are some limitations when CDN is used. Some of them are:

-  Customize Tailwind’s default theme can’t be used
- Directives like `@apply`, `@variants`, etc can’t be used
- Can’t install third-party plugins

### Installation of Tailwind CSS:

#### Through npm:
Basically Tailwind is available on npm and you can install it using the following command:

    npm install tailwindcss

After that create ad Tailwind configuration file using the following command:

    npm tailwind init {name of file}

#### Through yarn:

You can install tailwind by using the yarn command:

    yarn add tailwindcss
    
After that create a Tailwind configuration file using the following command:

    yarn tailwind init {name of file}
	
**Example:** It is a basic example of Tailwind CSS that describes how to change the background color on mouse hover.
```html
<!DOCTYPE html>
<html lang="en">
 
<head>
    <meta charset="UTF-8">
    <!-- Tailwind CSS CDN link -->
    <link href=
"https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css"
          rel="stylesheet">
</head>
 
<body>
    <div class="h-full border-2 border-gray-200
                border-opacity-60 rounded-lg
                overflow-hidden">
 
        <div class="p-6 hover:bg-green-600
                    hover:text-white transition
                    duration-300 ease-in">
 
            <h1 class="text-2xl font-semibold mb-3">
                Hover
            </h1>
        </div>
    </div>
</body>
 
</html>
```

### Advantages:
* Highly Customizable.
* Enables building complex responsive layout.
* Responsive and development is easy.
* Components creation is easy.

### Disadvantages:
* There are missing headers, and navigation components.
* It takes time to learn how to implement inbuilt classes.