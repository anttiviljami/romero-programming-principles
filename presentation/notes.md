# How John Romero’s principles apply to modern web coding

Why I’m interested in this:

- ID software was amazingly productive during the early 90’s
- They released 13 games within two years. One of those games was the classic Wolfenstein 3D.
    - Captain Keen, Shadow Knights, Rescue Rover, Hovertank 3D, Wolfenstein 3D
- Coding wisdom from 25 years ago ! Romero still does this talk

## 1. No prototypes

Prototyping is a difficult subject. How many times honestly does a prototype end up in production?

Of course prototyping is a good thing, but they should really be prototypes and not shitty versions of the product.

How many times honestly does a prototype end up in production?

## 2. Fallbacks on load failure

This is a generally good programming tip. In web development for example, a nice error message shown to the user is always better than a white screen of death or a generic 500 null pointer exception coming from your api.

Use stupid lorem ipsums, placeholder images (make sure they look like placeholders!) instead of crashing your application when content is missing.

## 3. Simplify

This doesn’t mean code as few lines as possible. This means code as readable code as possible. Simple code is simple for the programmer to read, not simple in terms of clever lines of code hard to understand.

## 4. Tools

I think the web development crowd has taken this advice into heart. There’s no lack of good libraries and frameworks for web dev. Learn them and use them! :)

## 5. Testing

Test often by actually using the software. Fix stuff as you find it. Don’t give broken shit to people who test.

## 6. Fix bugs immediately

Please do this!!

## 7. Target less powerful systems

You probably have a better machine than your users do. That’s a good thing because it allows you to develop faster and do things slower systems can’t do. Actually test your stuff with low powered machines!

## 8. Don’t write code for the future

This I actually disagree with mostly. When you feel like you’ve coded some valuable thing as part of your code, you should definitely separate it into a module or a library and share with others (at least your team)!

This principle probably came before GitHub and NPM etc.

The general principle of not overengineering things when it’s really not needed however should be applied.

## 9. Write modular code

Quite a basic piece of advice. :) But this helps everyone understand your code and enables unit testing. Also a lot easier to refactor when you can do it in small pieces.

## 10. Transparent coding

Transparency! This is an awesome piece of advice :) Talk to other developers in your team. Review your pull requests together. Get feedback and advice from others. Make sure you know what other people in your team are doing.

## 11. Embrace differences in programmers !!!

Everyone solves problems differently. Uniform code style is important, but don’t get tied up with the solution. Love the problem!


