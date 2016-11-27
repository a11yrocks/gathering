# Checklist
This is the checklist we use when analysing websites. You can use it in order to make sure your website has the bare minimum to be **perceivable**, **operable**, **understandable** and **robust** to all people.

## Media
- Images have equivalent alternative text
- Text transcripts are provided where needed
- Images of text are not used

## Forms
- If an input error is detected, the error is identified and described in text
- Input suggestions and instructions are provided for helping the user

## Text
- Text is no more than 80 characters wide
- Text is not fully justified
- Text have adequate line spacing and paragraph spacing
- Text can be resized to 200% without loss of content or function
- Links have a focus state
- Links are distinguishable from surrounding text and recognizable
- Abbreviations and strange words are explained

## Colors
- Foreground and background colors have sufficient (1) contrast
- Colors are tested for different types of color blindness (2)
-	Don’t use presentation that relies solely on colour

## Web Semantics
- Language attributes (`<html lang="en">`, `<blockquote lang="en">`) are used where needed
- ARIA Landmark Roles (3) are used to identify regions of a page
- Heading tags (`h1`, `h2`) are used for titles
- Emphasized or special text tags (`<strong>`, `<code>`, `<abbr>`, `<blockquote>`) are used where needed
- List tags (`ol` and `ul`) are used where needed

## Tables
- Row and column headers are recognizable and distinguishable

## Usability
- Event handlers are input device-independent
- A "Skip to Content" (4) link is provided
- Content does not blink, flashes or move for more than 3 seconds or more than 3 times per second
- Page functionality is available using a keyboard
- Users are not interrupted while browsing
- Focus events follow a logical order
- Instructions do not rely upon shape, size, or visual location ("right", "left")

# References

1: Contrast ratio between text and background is at least 4.5:1.

2: Test for Deuteranopia, Protanopia and Tritanopia.

3: Read [HTML 5 and ARIA Landmarks](https://dequeuniversity.com/assets/html/jquery-summit/html5/slides/landmarks.html) for more information on roles.

4: See [Skip Navigation technique](http://webaim.org/techniques/skipnav/).
