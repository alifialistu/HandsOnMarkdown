# Hands-On Markdown

__Topic : Learning Basic Markdown__
__Date : May 31st, 2022__

This activity was organized by the Technical Writer Squad PT. Warung Pintar Sekali as a "Learning New Things" material that is held every two months on a regular basis.

***

## 1. Headings

> To create a heading, add number signs (#) in front of a word or phrase. The number of number signs you use should correspond to the heading level. For example, to create a heading level three (`<h3>`), use three number signs (e.g., ### My Header).

# H1 

## H2

### H3

| Do This | Don't Do This |
| ----------- | ----------- |
| # Here's a Heading | #Here's a Heading |

***

## 2. Paragraphs

> To create paragraphs, use a blank line to separate one or more lines of text.

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

__NOTES__ : Unless the paragraph is in a list, don’t indent paragraphs with spaces or tabs.

***

## 3. Bold

> To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

I just love **bold text**.

I just love __bold text__.

Love**is**bold

| Do This | Don't Do This |
| ----------- | ----------- |
| Love**is**bold | Love__is__bold |

***

## 4. Italic

> To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.

Italicized text is the *cat's meow*.

Italicized text is the _cat's meow_.

A*cat*meow

| Do This | Don't Do This |
| ----------- | ----------- |
| A*cat*meow | A_cat_meow |

***

## 5. Blockquotes

> To create a blockquote, add a > in front of a paragraph.

__Nested Blockquotes__

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

***

## 6. Ordered Lists

> To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

1. First item
2. Second item
    1. Indented item
    2. Indented item
3. Third item
4. Fourth item

***

## 7. Unordered Lists

> To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items. Indent one or more items to create a nested list.

- First item
- Second item
    - Indented item
    - Indented item
- Third item
- Fourth item

__Starting Unordered List Items With Numbers__

- 1968\. A great year!
- I think 1969 was second best.

***
## 8. Code

> To denote a word or phrase as code, enclose it in backticks (`).

At the command prompt, type `nano`.

***

## 9. Code Blocks

> Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.

1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.

***

## 10. Horizontal Rules

> To create a horizontal rule, use three or more asterisks (***), dashes (---), or underscores (___) on a line by themselves.

***

---

_________________

## 11. Links

> To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) and then follow it immediately with the URL in parentheses (e.g., (https://duckduckgo.com)).

My Favorite website is [warungpintar.co.id](https://www.warungpintar.co.ic)

__Adding Titles__

My Favorite website is [warungpintar.co.id](https://www.warungpintar.co.ic "Warung Pintar")

***

## 12. Images

> To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title in quotation marks after the path or URL.

![Warung Pintar](https://asset.kompas.com/crops/HujzAhIc0pbzHdILe4A3Mnpqx24=/54x36:1000x667/750x500/data/photo/2018/01/23/43549314.jpg "Warung Pintar Image")

***

## 13. Linking Images

> To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.

[![Warung Pintar](https://asset.kompas.com/crops/HujzAhIc0pbzHdILe4A3Mnpqx24=/54x36:1000x667/750x500/data/photo/2018/01/23/43549314.jpg "Warung Pintar Image")](https://warungpintar.co.id/)
