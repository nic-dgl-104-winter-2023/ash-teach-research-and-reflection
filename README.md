# Ashley's research and reflection journal

This is my research and reflection journal for [DGL 104 - Application Development Foundations](https://ash-teach.github.io/dgl-104/). I'll use this repo to record the results of my research and reflection activities throughout the semester. 

If you're using this repository as a template to model your own research and reflection journal, feel free to include whatever information or content you wish, but remember to use proper markdown formatting to ensure your journal is readable! Read on to see additional examples of markdown headings, links, images, and code snippets.
## Week 1
### Course goals

The goal of week 1 is primarily to orient all students towards the intentions, expectations and goals of DGL 104. As part of this process each student should begin to develop their own personalized goals for the course (i.e. the [course goals assignment](https://ash-teach.github.io/dgl-104/#/dgl104-2023wi/assignments?id=course-goals)). Each student should have a clear statement of their course goals completed by the end of class in week 2, although I stress that this statement need not be the *final* form that the course goals will take: there will be multiple opportunities to check-in and revise course goals throughout the semester.

**ACTION:** In preparation for week 2 class (the week of Jan. 16th) you should ideally complete the first **five steps** specified in the course goals assignment [what you're going to do](https://ash-teach.github.io/dgl-104/#/dgl104-2023wi/assignments?id=what-youre-going-to-do) section. 

Feel free to go further and complete step six, if you like, although we'll work on this collectively in class in week 2.

You might be left wondering what you could possibly write as a goal. I'll encourage you to be brave at this stage and think big about possible goals. Likely, we'll have to scale back, but that's ok! It's better to start big and then narrow focus than it is to think too small. Some potential ideas that you might consider:
- To learn a particular *aspect* of your chosen programming language (e.g. perhaps how to use some advanced features of your programming language)
- To learn a particular *application* of your chosen programming language (e.g. you might be interested in data analysis)
- To learn a specific *framework* or *library* associated with your programming language (e.g. Python and JavaScript both have huge ecosystems and libraries that support all sorts of activities)
- To learn the use of a specific cross-platform development tool for a specific development task (e.g. such as Unity for games development)
- Or even to learn a wholly new programming language!

Whatever you choose, keep in mind that your goals will be scaled appropriately to your background and capacity. If you choose to learn a new programming language, for example, I *wouldn't* expect that by the end of the semester you would be a completely fluent programmer in that new language, but you should be pretty comfortable in some aspects of it and in the basic syntax. These are things we'll discuss as you further refine your goals.

Make sure to record your course goals in your research and reflection journal / repository!

### A few additional markdown tips

If you need to write a code snippet enclose the code in triple backticks. So the markdown in your .md file might look like this:
<pre>
```
let x = 10
let y = 20
let z = x + y
```
</pre>

which will render like this when displayed on GitHub:

```
let x = 10
let y = 20
let z = x + y
```

But a much better way is to also include a language annotation after the opening triple backtick, which also provides proper syntax highlighting. So this (note the 'javascript'):
<pre>
```javascript
let x = 10
let y = 20
let z = x + y
```
</pre>

will render like this on GitHub (notice the colour difference from the example above):
```javascript
let x = 10
let y = 20
let z = x + y
```

If you want to write some code within some text (we call this 'in-line'), rather than in a block on its own, then use **single backticks** to wrap your code statement. So this:
<pre>
`let x = 10`
</pre>
would render as:

`let x = 10`

but, ideally, since this is in-line code you would embed it in a sentence like this: `let x = 10`. Notice that in this case the code is always written monospace and highlighted in grey - there is no option to add a specific language annotation as with `javascript` in the code block example above.

Finally, you'll likely want to add links and images to your README.md file at different times. The syntax for each is very similar. For a link provide the link text in square brackets immediately followed by the url in rounded parentheses. So the following:
<pre>
[Google](https://www.google.com)
</pre>

renders as:

[Google](https://www.google.com)

For images, use the same syntax with the alt text in the square brackets and the relative url in the rounded parentheses (note the image below is stored in the repository `assets` directory). Prepend the entire statement with an exclamation mark (also known as a bang, in programmer-speak). So this:

<pre>
![A screenshot of some code](assets/Code-1076536.jpg) 
</pre>

renders as:

![A screenshot of some code](assets/Code-1076536.jpg) 

*Image CC0, courtesy of [Wikimedia Commons](https://pixabay.com/en/users/JOSBORNE_-1640589/)*
