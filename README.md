# FlexBox(https://www.theodinproject.com/lessons/foundations-introduction-to-flexbox)
Introduction to Flexbox with basic example.
Content and example is taken(copied) form TheOdinProject.com. Except code
This example explain the basic and introductory overview of Flexbox with code.
# Introduction
As you’ll learn, there are many ways to move elements around on a web page. Over the years, new methods have been developed, and older things have fallen out of style. Flexbox is a relatively new way of manipulating elements in CSS, and when introduced, it was revolutionary.

Because it is somewhat new as a technology, many resources put it near the end of their curriculum. But at this point, it has become the default way of positioning elements for many developers. Flexbox will be one of the most used tools in your toolbox, so why not learn it first?

# Before We Get Started
Flexbox layouts can get a little complicated. In a previous lesson, you learned how to inspect and debug things using your browser’s developer tools. Those tools will be crucial for you in the following lessons. If something isn’t behaving the way you expect, inspecting it in the developer tools should be your first step every time.

# Let’s Flex!
Flexbox is a way to arrange items into rows or columns. These items will flex (i.e. grow or shrink) based on some simple rules that you can define. To get started, let’s look at a simple example(code)in yourbrowser. Take your time to inspect the code and really understand what’s going on. In fact, playing with the code yourself will make it much easier to retain this information.

# Flex Containers and Flex Items
As you’ve seen, flexbox is not just a single CSS property but a whole toolbox of properties that you can use to put things where you need them. Some of these properties belong on the flex container, while some go on the flex items. This is a simple yet important concept.

A flex container is any element that has display: flex on it. A flex item is any element that lives directly inside of a flex container.

# Container-vs-child

Somewhat confusingly, any element can be both a flex container and a flex item. Said another way, you can also put display: flex on a flex item and then use flexbox to arrange its children.

# Nesting Flex Containers
Creating and nesting multiple flex containers and items is the primary way we will be building up complex layouts. The following image was achieved using only flexbox to arrange, size, and place the various elements. Flexbox is a very powerful tool.
