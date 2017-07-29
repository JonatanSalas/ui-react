# Preface {#Preface}

Frontend development has undergone a major transformation with modern frontend technologies, such as React, Angular, Vue, and so forth. This is largely due to the wide adoption of component-based architecture provided by these wildly successful technologies.

You can find many books covering how to use these different technologies, however, they are either heavily tied to the technology or do not take into account real world scenarios. This book aims to not only guide readers from the foundational building blocks of creating well architected interfaces but also provide an exhaustive list of different philosophies for creating modular, extendable and scalable **U**&**I** --- i.e. UI intended for all developers, like **you** and **I**.



## Topics

Even though the concepts in this book are taught via React, all of the concepts are transferrable to other frontend technologies. I chose React as our base, due to the simplicity, wide adoption and undeniable power that it provides.




### [Chapter 1: Introduction](#Chapter-1)

Explains a brief history of web development and the rise of component-based architecture.




### [Chapter 2: What is U&I?](#Chapter-2)

Provides an in depth view of U&I and the criteria for building them.




### [Chapter 3: Getting Started](#Chapter-3)

Outlines some of the base technologies we'll be using and then walks us through setting up a boilerplate codebase.




### [Chapter 4: Building our App](#Chapter-4)

Guides us through building the foundation for our application.




### [Chapter 5: Using U&I Concepts](#Chapter-5)

Covers some best practices and guides us on refactoring our application with some important best practices.




### [Chapter 6: Exploring CSS Preprocessors](#Chapter-6)

Explains CSS preprocessors and guides us on how to refactor our interface to be able to leverage the power of Sass.




### [Chapter 7: Exploring CSS Modules](#Chapter-7)

Introduces CSS modules and guides us on refactoring our interface using CSS modules.




### [Chapter 8: Exploring Inline Styles](#Chapter-8)

Takes us on a journey through inline styles and guides us on refactoring our application using this dated philosophy in a modern setting.




### [Chapter 9: Adding Real Time Capabilities](#Chapter-9)

Introduces an entirely new perspective of looking at interactive interfaces and guides us bringing our application to life with real time capabilities.




### [Chapter 10: Showcasing](#Chapter-10)

Guides us on how we can build, document and showcase our components in an isolated environment.




### [Chapter 11: Looking Ahead](#Chapter-11)

Compares and contrasts the the various methodologies covered throughout this book with a glimpse into the future of UI development.




## Requirements

The following is recommended for maximum productivity:

- Any modern computer with Linux, Mac OS, or Windows.
- Node
- NPM
- Git *(optional)*

I> All software mentioned in this book are free of charge and can be downloaded from the Internet. You can find the source code hosted on GitHub: [https://github.com/FarhadG/ui-react](https://github.com/FarhadG/ui-react).



## Audience

This book is ideal for developers who are familiar with React and are looking for a comprehensive guide for building modular, extendable and scalable UI interfaces. Even though this book is intended for intermediate to advanced React developers, anyone new to React can easily follow along given the progressive format of this book where each chapter builds on the chapters before. 

I> The ideas covered in this book are not tied to React and are transferable to other frontend technologies.



## Conventions

In this book, you will a find number of text formats that conveys different types of information. Here are some examples for illustration:

A block of code:

```js
function greet(name) {
  return 'Hello, ' + name;
}
```

When blocks of code are redundant from previous examples, you will see an ellipsis signifying that they have been omitted to be able to draw your attention to the appropriate blocks of code:

```js
function greet(name) {
  ...
}
```

To signify added blocks of code, they will be highlighted in **bold**:

```js
function greet(name) {
  ...
}

# leanpub-start-insert
greet('rock star developer!');
# leanpub-end-insert
```

To help locate the files we're working with, you will see titles at the top of code blocks describing the path to the file:

{title=src/util/greet.js}
```js
function greet(name) {
  ...
}
  
...
```

It is often useful to provide inline comments within code examples, as you can see here:

{title=src/util/greet.js}
```js
function greet(name) {
  // if name does not exist, it's set to a default value
  name = name || 'World';
  ...
}
```

Any command-line input or output is written as follows:

{line-numbers=off}
```bash
$ npm install --save react
$ npm install --save-dev webpack
$ npm install --save-dev style-loader
```

The `$` signifies a new command-line input. This does not need to be included with your commands as it only serves to distinguish new command-line lines and inputs.

Lastly, if there are any auxiliary information or useful tips, you can find them in the following format:

I> Webpack has many powerful and useful loaders listed on their website that you can leverage for your application needs.



## Example Code

You can download the example code for each of the chapters in this book by going to the GitHub repository, [https://github.com/FarhadG/ui-react](https://github.com/FarhadG/ui-react). There are several ways for downloading the code examples:

- **GIT:** You can clone the repo and go through the various chapters by navigating the different directories.
- **Zip download**: You can directly download the codebase from GitHub via their zip option.

I> The contents of this book can be found under the `manuscript` directory and the source code has been broken down by each chapter under the `code` directory. If you'd like to run the source code, you can do so by installing the chapter's dependencies and running to appropriate `npm` scripts.



## Feedback

I'd love to hear your feedback. Your feedback is very important to me, so please don't hesitate to reach out to let me know what you like or dislike about this book. You can find my contact details in the [**Profile**](#Profile) section.



## Errata

Although I have taken every care to ensure the accuracy of the content presented in this book, mistakes do happen. If you spot any mistakes in the book or the code examples, please contact me or use the GitHub issues page to report the issue. By reporting these mistakes, you will help improve the quality of the book for yourself and other readers in the future. Once your errata are verified, your submission will be accepted and the errata will be resolved. You can find my contact details in the [**Profile**](#Profile) section.



## Piracy

Although I'm very supportive of open source, piracy of copyrighted material is a major problem. If you come across any illegal copies of this book, please contact me. You can find my contact details in the [**Profile**](#Profile) section.



## Contributions

Given that all of the contents of this book are open source and intentionally provided on GitHub, contributions are welcome and encouraged. You can find all of the necessary information on [GitHub](https://github.com/FarhadG/ui-react).



## Questions

If you have any questions, concerns or suggestions, please contact me directly. You can find my contact details in the [**Profile**](#Profile) section.



{pagebreak}

**What are we waiting for? Lets get started...**