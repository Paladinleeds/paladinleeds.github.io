# Homepage

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Annotation examples

### Codeblocks

`Inline code` can be used here.

### Plain codeblock

A plain codeblock

```
using System;
try
{
    Console.WriteLine("This is a plain codeblock!");
}
```

#### Code for a specific language

Some more code marked with `cs` at the start:

``` cs
public static void Highlight()
{
    Console.WriteLine("I am syntax highlighted!");
}
```

#### With a title

``` cs title="TryCatch.cs"
try
{
    int RanNumber = 69;
    Console.WriteLine(RanNumber.ToString());
}
catch (Exception e)
{
    Console.WriteLine("Function failed!");
}
```

#### With line numbers

``` cs linenums="1"
try
{
    int RanNumber = 69;
    Console.WriteLine(RanNumber.ToString());
}
catch (Exception e)
{
    Console.WriteLine("Function failed!");
}
```

#### Highlighting lines

``` cs hl_lines="3 4"
try
{
    int RanNumber = 69;
    Console.WriteLine(RanNumber.ToString());
}
catch (Exception e)
{
    Console.WriteLine("Function failed!");
}
```