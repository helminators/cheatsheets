<!-- comment -->

<!-- headings -->
# Heading 1 (h1)
## Heading 2 (h2)
### Heading 3 (h3)
#### Heading 4 (h4)
##### Heading 5 (h5)
###### Heading 6 (h6)

<!-- italics -->
*This text* is italic.
_This text_ is italic.

<!-- bold -->
**This text** is bold.
__This text__ is bold.

<!-- escape characters -->
\*This text\* is not italic.
\__This text\__ is not bold.

<!-- strikethrough -->
~~This text~~ is strikethrough.

<!-- horizontal rule -->
---
Something...
___

<!-- blockquote -->
>You quote someone using '>' character.
>
>...
>
>You can do it on multiple lines, too!

<!-- links -->
[Title of link](https://www.google.com/ "Tooltip of link")
[Link without tooltip](https://www.google.com/)
https://www.google.com/

<!-- unordered list -->
List of unordered items:
* item 1
* item 2
    * item 2.1
    * item 2.2
        * item 2.2.1

<!-- ordered list -->
1. item
1. another item
1. some other item

<!-- block of code -->
`<p>This is a paragraph.</p>`

<!-- images -->
![Markdown Logo](https://markdown-here.com/img/icon256.png)

<!-- github specific things -->
<!-- block of code -->
```
$ echo "generic block of code"
```

```c
float Q_rsqrt( float number )
{
	long i;
	float x2, y;
	const float threehalfs = 1.5F;

	x2 = number * 0.5F;
	y  = number;
	i  = * ( long * ) &y;                       // evil floating point bit level hacking
	i  = 0x5f3759df - ( i >> 1 );               // what the fuck? 
	y  = * ( float * ) &i;
	y  = y * ( threehalfs - ( x2 * y * y ) );   // 1st iteration
//	y  = y * ( threehalfs - ( x2 * y * y ) );   // 2nd iteration, this can be removed

	return y;
}
```

<!-- tables -->
|Name|E-mail|
|-|-|
|John Doe|john.doe@mail.com|
|Alice Smith|alice.smith@mail.com|

<!-- task list -->
* [x] complete task 1
* [x] complete task 2
* [ ] incomplete task