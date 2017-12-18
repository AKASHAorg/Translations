## Translation requirements
 - Must preserve the file name and directory structure;
 - Must translate only `defaultMessage` key;
 - Must preserve the quotation marks ( `""` );
 - Must preserve commas ( `,` );
 - Must preserve curly braces and the words inside curly braces (eg. `Write a reply to {name}` -> `{name}` must not be translated);
 - Exception from above rule is a special notation like:
    - `{words, number} {words, plural, one {word} few {words} many {words} other {words}}`
    - `{count, number} new {count, plural, one {comment} few {comments} many {comments} other {comments}}`
    - In this cases only the words inside curly braces belonging to `one`, `few`, `many` and `other`, must be translated. In the example above the word `comment` must be translated with all his plural forms. (eg. `{count, number} new {count, plural, one {comentariu} few {comentarii} many {comentarii} other {comentarii}}`). In some languages the plural of form for `few` is different than the plural form of `many`.


## FAQ

 - Q: I\`m not familiar with the word `excerpt`. Is `excerpt` like an abstract?
 - A: Yes. Excerpt is a brief summary (abstract) of an article.


