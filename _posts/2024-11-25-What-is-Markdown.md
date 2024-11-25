---
title: What is Markdown?
author: alpa28980
date: Mon, 25 Nov 2024 05:02:49 GMT
categories: ["Development Language"]
tags: ["Markdown"]
comment: true
---
Introduction.


Markdown is a simple markup language that makes it easy and fast to write documents on the web. Created by Jon Gruber in 2004, Markdown provides a lightweight syntax that allows you to write readable documents without the need for complex tags.

The main features of Markdown include

1. Simple syntax: It allows you to write documents without the need for additional complex tags \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)).
2. Versatile: In addition to the basic grammar, it has an extended grammar to support a variety of features such as tables, code blocks, and automatic links.
3. web-friendly: Documents written in Markdown can be easily converted to HTML and published on the web.
4. Open source: It is an open source project that can be used for free.

These features make Markdown easy to create and share documents for developers as well as general users. Many web services, including GitHub, Reddit, and Stackoverflow, officially support Markdown, making it a popular choice for writing web content, such as technical documentation and blog posts. Markdown's simplicity and compatibility facilitates collaboration and knowledge sharing, making it an important part of the development community.

How to use headings
------

In Markdown, headings are used to structure the document and separate content. There are six different levels of headings, each represented by a number of # (hash symbols). For example

Highest heading (H1)
============

Second largest heading (H2)
---------------

### Third largest heading (H3)

#### Fourth largest heading (H4)

##### Fifth largest heading (H5)

###### Smallest heading (H6)

In general, headings in a document use the H1 level, headings in large sections use the H2 level, and headings in subsections use the H3 level. Lower levels can be used to separate details.

Heading text cannot be followed by a space or other Markdown element, otherwise it will not be recognized as a heading. For example, you cannot use

### is incorrect.

There must also be a space between each # and the heading text, for example:

#Correct usage

Because headings are so important for creating a table of contents and structure for your document, \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/), it's a good idea to choose the right level of headings.

Paragraph breaks
-----

Separating paragraphs in Markdown is very simple. To start a new paragraph, simply insert a blank line. For example:

This is the first paragraph. This is the content of the first paragraph.

This is the second paragraph. We put the blank line above to start a new paragraph.

Inserting blank lines like this makes the document more readable and structured \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)). This simplicity of Markdown makes it easy for anyone to write documents.

Writing a citation
------

Creating a quote in Markdown is very simple. Simply precede a sentence with a > and that sentence will appear as a quote. For example

> This is an example of a quote.

Quotes are separated by paragraphs, and consecutive quotes are automatically recognized as a single block of quotes. For example:

> This is the first quote.
>
> This is the second quote.
>
> These consecutive sentences appear as a single block of quotes \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)).

You can also use other Markdown elements (headings, lists, emphasis, etc.) inside a quote. This simple syntax of Markdown makes it easy to write quotes.

Bold, italics, strikethrough
------------

You can apply different styles to text in Markdown. You can bold, italicize, or strike through text, for example. Varying the style of your text in this way makes your document more readable and structured \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)).

The first way is to bold text. You can do this by placing two asterisks (\*\*) or an underbar (\_) before or after a word or phrase. For example:

**When surrounded by asterisks like this, it will be bold:** _When surrounded by underbars like this, it will be bold:_.

Next is how to slant text. You can do this by placing a single asterisk (\*) or underbar (\_) before or after a word or phrase. For example:

_When surrounded by an asterisk like this, it will be italicized._ _When surrounded by an underbar like this, it will be italicized._.

Finally, you can add strikethroughs. Simply add two tildes (~~) before and after a word or phrase. For example:

Surrounding it with tildes like this creates a strikethrough.

This simple syntax of Markdown allows you to apply different styles to your text. This makes your documents more readable and structured, helping you communicate your content effectively.

Create a hyperlink
--------

Creating a hyperlink in Markdown is very simple. Simply enclose the text you want to link to in square brackets (\[\]), followed by the actual URL in parentheses (()). For example

[Google link](https://www.google.com)

This will hyperlink the text "Google link" to the address [https://www.google.com](https://www.google.com) \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)).

You can also use the referenced link style. This style separates the link from the URL, which is useful when using the same link in multiple places. Enclose the link text in square brackets, and write the referrer name in square brackets separately from the link URL, followed by a colon (:) and the URL. For example

[Google](https://www.google.com) [Naver](https://www.naver.com)

This will link the text "Google" and "Naver" to the Google and Naver sites, respectively \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)).

Hyperlinks increase the usability of your document by making it easy to link to other sites or pages in your Markdown document.

Inserting an image
------

Inserting images in Markdown is very simple. Simply enclose the image description in square brackets (\[\]) where you want the image to appear, followed by the image URL in parentheses (()). For example

![example image](https://example.com/image.jpg)

This inserts the image [https://example.com/image.jpg](https://example.com/image.jpg) with the description "Example image" \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)). The image description is used as alt text that is displayed in place of the image in environments where the image cannot be viewed.

The image URL is the path to the image file on the web. You can also use a local image file. In this case, you can enter a relative or absolute path.

Inserting images like this can make your document more readable and understandable, helping to convey your \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/) content effectively. The simple syntax of Markdown makes it easy to add images, which is a big plus.

Ordered and unordered lists
------------------

In Markdown, you can create two types of lists: Ordered lists and unordered lists.

An ordered list is a numbered list, which lists items with numbers and periods (.). For example

1. first item
2. the second item
3. third item

An ordered list is useful when listing procedures or processes \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)).

An unordered list, on the other hand, lists items with symbols without numbers. The most commonly used symbols are the asterisk (\*) and hyphen (-). For example:

* apples
* bananas
* orange

* Football
* Basketball
* baseball

Unordered lists are useful for listing or summarizing \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)). You can also put another list within a list, which allows for structure.

A list within a list
--------

In Markdown, you can structure by putting another list inside a list. This makes it easy to represent hierarchical information \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)).

For example, you can put an ordered list inside an unordered list like this

* Fruits
    1. apples
    2. bananas
    3. oranges
* Vegetables
    1. carrots
    2. broccoli
    3. potatoes

Or, conversely, you can put an unordered list inside an ordered list:

1. first list.
    * Sub-item 1
    * Sub-item 2
2. second list.
    * Sub-item 1
    * Sub-item 2

When creating nested lists like this, you need to pay attention to indentation \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)). There should be at least three spaces or tabs between the parent list item and the child list item. This will help break up the structure of your document nicely.

Checkbox list
-------

Creating a checkbox list in Markdown is very simple. First, you write a dash (-) followed by a space, then square brackets (\[\]), and then a space or an X inside the checkboxes. For example

* Unchecked.
* Checked

This creates a list of checkboxes. You can create a checklist by adding content before the checkboxes:

* View chapter
* Clean
* Study

Checkbox lists can be useful for creating to-do lists or checklists \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)). They can be used to check the progress of a project, for example, or to check off a meeting agenda. They can also help you structure your documentation.

Inline code and code blocks
-------------

In Markdown, you can represent code in two ways: inline code and code blocks.

Inline code is a way to put small snippets of code inside a sentence. You do this by wrapping the snippet in backticks (\`\`). For example, `print("Hello, World!")`. Inline code is most commonly used to indicate variable names, function names, file names, and so on.

A code block, on the other hand, is a way to represent multiple lines of code separated into separate blocks. To create a code block, you can put three backticks (\`\`\`) before and after the code, or at least four spaces before each line. For example, you might use

python

    # Example Python code
    def hello():
        print("Hello, World!")
    
    hello()
    

Code blocks like this are useful for displaying actual program code or showing multiple lines of code snippets \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)). Utilizing this code representation feature of Markdown can be very helpful when writing technical documentation or tutorials.

Specifying code block language
-----------

Specifying a programming language for a code block in Markdown enables syntax highlighting, which makes your code more readable. To do this, simply write the name of the programming language after the first backtick (\`\`\`) in the code block. For example, for Python code, you might write something like this

python

    def hello():
        print("Hello, World!")
    
    hello()
    

where `python` is the name of the programming language. This will apply the appropriate syntax highlighting for Python code.

Other programming languages can be specified similarly. For example, you can write `javascript` for JavaScript, `cpp` for C++, and `java` for Java, such as \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)). Be careful if you name the language incorrectly, as syntax highlighting will not work properly.

Specifying the programming language for code blocks in Markdown like this helps you express your code more clearly, making your documentation more readable and understandable.

Example code block usage
-----------

Markdown's code block feature is very useful when you want to include code examples from different programming languages in your documentation. For example, if it's Python code, you could write something like this

python

    # Example Python function
    def factorial(n):
        if n == 0:
            return 1
        else:
            return n * factorial(n-1)
    
    print(factorial(5)) # output: 120
    

For javascript code:
```
javascript

    // Example of a JavaScript function
    function greet(name) {
      console.log(`Hello, ${name}!`);
    }
    
    greet('John'); // Output: Hello, John!
 ```

In addition, the Java code can also be expressed as follows

java
```
    // Example Java class
    public class HelloWorld {
        public static void main(String[] args) {
            System.out.println("Hello, World!");
        }
    }
```

Like this, Markdown's code block feature allows you to include code examples from different programming languages in your documentation \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)). Specifying a programming language also makes your code more readable by applying syntax highlighting. This is a great help when writing technical documentation or tutorials.

Creating a table
-----

Here's how to create a table in Markdown: first, separate each column in the table with a pipe (`|`), write the column headings on the second line, and specify how each column is sorted on the line below. The sorting method is determined by the position of the colon (`:`). For example:

Title1

title2

Title3

内容1

内容2

内容3

内容4

内容5

内容6

This creates a table where heading 1 is left-aligned, heading 2 is centered, and heading 3 is right-aligned. You can also use other elements of Markdown (links, emphasis, code blocks, etc.) inside the table \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/). Using tables in this way can help you structure your data effectively and make your document more readable.

Sorting columns
----

In Markdown, the way a table's columns are aligned is determined by the position of the colon (:). Placing the colon to the left results in left alignment, placing it to the right results in right alignment, and placing it on either side results in center alignment.

For example, writing the following creates a left-aligned table

Title1

Subject2

Title3

内容1

内容2

内容3

内容4

内容5

内容6

To center align, you can put a colon on either side, like this

Title1

title2

Title3

内容1

内容2

内容3

内容4

内容5

内容6

Finally, for right alignment, we write

Title1

Subject2

Title3

内容1

内容2

内容3

内容4

内容5

内容6

As you can see, Markdown allows you to specify the column alignment of a table with a simple syntax. This allows you to align your data nicely to make your document more readable \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)).

Formatting text in a table
----------

Markdown allows you to apply different formatting to text, even inside tables. This allows you to improve the readability of your tables and emphasize important information \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)). Formatting text within a table is as simple as using Markdown's normal text-style syntax.

First, to make text bold, you can wrap it in asterisks (\*\*) or underbars (\_). For example:

Title.

Description.

**emphasis added

This text is bolded.

_emphasized

This text is also bolded.

Next, to italicize text, you just need to wrap it once with an asterisk (\*) or an underbar (\_). Example:

Title

Description.

Tilt

This text is italicized.

Italicized

This text is also italicized.

If you want to include strikethrough, you can wrap it in a tilde (~~):

Title.

Description.

Strikethrough

This text is strikethrough.

You can also wrap it in backticks (\`\`) to apply a code style:

Title

Description.

`code`

This text is the code style.

This basic syntax of Markdown allows you to format text differently, even within a table \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)). This makes the table more readable and structured, which improves its ability to convey information.

Conclusion.
--.

Markdown is a markup language with a simple syntax and a wide range of features that make it easy and fast to create documents on the web. The key advantage of Markdown is its simplicity. You can include a variety of elements in your documents, such as headings, bodies, lists, tables, code blocks, and more, without the need for complicated tags \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)). It's also web-friendly, making it easy to convert Markdown documents to HTML. Because of this simplicity and compatibility, Markdown is widely used for writing technical documentation and blog posts.

Markdown also plays a big role in collaboration and knowledge sharing. Services like GitHub, Reddit, and Stackoverflow officially support Markdown, making it easy for developers to create and share documentation. Markdown's extended syntax allows you to add tables, code blocks, formulas, and more, making it an important part of the \[[1](https://www.google.com)\]([https://www.markdownguide.org/](https://www.markdownguide.org/)) development community.

Markdown is a free and open-source project and is constantly evolving. As new features are added and the support landscape expands, Markdown is expected to become even more useful, especially as recent advances in artificial intelligence make it possible to automatically generate or convert Markdown documents.
---
---

<iframe src="https://ads-partners.coupang.com/widgets.html?id=807239&template=carousel&trackingCode=AF3190673&subId=&width=680&height=140&tsource=" width="680" height="140" frameborder="0" scrolling="no" referrerpolicy="unsafe-url" browsingtopics></iframe>
해당 링크를 통해 제품 구매가 이루어진 경우 쿠팡 파트너스 활동 일환으로 인해 일정 수수료가 블로거에게 제공되고 있습니다

