# Throw Away

> Notes by Amanpreet

The line above is equivalent to an <h1>Throw Away</h1> HTML markup.

The ides of markdown files is to make it easier to write text that you want to have *some* sort of **richness** to it, but don't want to get hung up on the details of markup (HTML) or having to reset to more "binary" representation such as in MS WOrd.

MArkdown can produce lists, just like this:

- A list item can start with either a dash or an asterix
 - It's a good idea to be consistent
 - This line, and the one above are "intented" in the lists
- Besides unordered lists, you can do "ordered" lists. For an ordered list, use the number 1 followed by a dot (as seen below)

## Other Examples

The line above is equivalent to an '<h2>' element. (Note the two pound symbols - you can have up to six!)

For your homework:

1. Learn about the different stylings for markdown. Specifically, how to do
	1. Readings
	2. Lists (ordered/unordered)
	3. Code snippets (like '<h1>code</h1>')
	4. Code blocks (multiple lines of code)
	5. **Bold** and *Italic*
	6. Tables
	7. Hyperlinks (e.g.: [Google Home Page] (www.google.ca))
	8. Images
	9. Other interesting things
Answer the question, "What is the difference between **Github Flavored MArkdown** (GFM) and regular markdown?"
Find out how to do a checkbox in a list item using GFM.

## Code Blocks

You can do code block in Markdown, and even have it highlighted in the right colors for the appropriate kind of code. Eg. here's some HTML.

```html
<h1> Hello World </h1>
<p> YOu should really get into learning about CSS Grid and Flexbox!</p>
```

Here is an example of C# code
```csharp
public class Greeter
{
	private string _Greeting = "Hello World";
	private string _GoodBye;
	
	public Greeter(string greeting, string goodbye)
	{
		_Greeting = greeting;
		_GoodBye = goodbye;
	}
	
	public string SayHello()
	{
		return _Greeting;
	}
}