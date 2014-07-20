# CSS Comments snippets

<img src="https://raw.githubusercontent.com/visualstudio-code-snippets/css-comments-visualstudio-snippets/gh-assets/css-comments-visualstudio-snippets.png" alt="CSS Comments Visual Studio snippets" align="right" />

CSS comments snippets for [Visual Studio](http://www.visualstudio.com/) 2012/2013.

Well commented code is extremely important. Take time to describe components, how they work, their limitations, and the way they are constructed. Don't leave others in the team guessing as to the purpose of uncommon or non-obvious code.

> Comment style should be simple and consistent within a single code base.

To install through Package Control, search for [**CSS Comments**](https://sublime.wbond.net/packages/CSS%20Comments). If you still don't have Package Control in Sublime Text, [go get it](http://wbond.net/sublime_packages/package_control/installation). If you insist to not install it, you can download the package and put it manually inside your Pacakages directory. It should work but will not update automatically.

## Snippets

To trigger a comment just put a **c-** followed by it's name, like so:

![image snippets](https://raw.githubusercontent.com/visualstudio-code-snippets/css-comments-visualstudio-snippets/gh-assets/snippets.gif)

## Basic Comment

**trigger:** c-basic⇥

```css
/* Basic comment */
```

## Long Comment

**trigger:** c-long⇥

```css
/*
 * Long comment
 */
```

## Section Comment

**trigger:** c-section⇥

```css
/* ==========================================================================
   Section comment block
   ========================================================================== */
```

## Sub-section Comment

**trigger:** c-subsection⇥

```css
/* Sub-section comment block
   ========================================================================== */
```

## Multiple Comment with TODO

**trigger:** c-multi⇥

```css
/**
 * Short description using Doxygen-style comment format
 *
 * The first sentence of the long description starts here and continues on this
 * line for a while finally concluding here at the end of this paragraph.
 *
 * The long description is ideal for more detailed explanations and
 * documentation. It can include example HTML, URLs, or any other information
 * that is deemed necessary or useful.
 *
 * @tag This is a tag named 'tag'
 *
 * TODO: This is a todo statement that describes an atomic task to be completed
 *   at a later date. It wraps after 80 characters and following lines are
 *   indented by 2 spaces.
 */
```

## Summary Comment

**trigger:** c-summary⇥

```css
/**
 * Description: Short description.
 * Version: 1.0.0
 * Last update: YYYY/MM/DD
 * Author: User Name <username@gmail.com>
 *
 * Summary:
 *
 *	0. ELEMENT
 *		- 0.1. TYPE ELEMENT
 *		- 0.2. TYPE ELEMENT
 *	1. ELEMENT
 *		- 1.1. TYPE ELEMENT
 *		- 1.2. TYPE ELEMENT
 */

/* ==========================================================================
   0. ELEMENT
   ========================================================================== */

/* 0.1. TYPE ELEMENT
   ========================================================================== */

/* 0.2. TYPE ELEMENT
   ========================================================================== */
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m "Add some feature"`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request  :)

English is the universal language nowadays, so please don't create or comment on issues using another language.

## History

For detailed changelog, see [Releases](https://github.com/visualstudio-code-snippets/css-comments-visualstudio-snippets/releases).

## Credits

Comment format based on [Idiomatic CSS](https://github.com/necolas/idiomatic-css) by [Nicolas Gallagher](https://github.com/necolas).

## License

[MIT License](http://brenopolanski.mit-license.org/) © Breno Polanski
