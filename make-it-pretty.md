# Make it Pretty!

## Why is it Important to Have a Pretty Portfolio?

Your portfolio projects are the first impression that a company has of you. Imagine you are non-technical person looking to hire a developer to build your website.
Would you hire someone who's site looked incredibly janky and poorly styled, even if 'the functionality works perfectly'? If you wouldn't hire yourself based on your
portfolio why should anyone else? Non-technical people will be looking at your projects before engineers and they don't know the amount of work it takes to get a backend
up and running, all they see are poorly styled components, so unless you take care of your frontend you'll never even get the chance to talk about the backend work you did.

**Learning Objectives**

- You will be able to identify the items recruiters are most interested in from a list of what makes for a fuctional good looking industry standard website.
- You will identify the attributes of a good looking website.
- Given two sites, one good and one bad, you can correctly choose the good one and identify 2 factors that make it superior.

## What Recruiters Are Looking For

Recruiters expect professionalism & good design (we'll discuss more about what good design means below). A good litmus test is: if you were to stumble upon your portfolio sight unexpectedly, would you be able to tell that
this wasn't done by a professional dev? In other words, does your website look on par with the millions of other production sites that exist on the internet?

## Attributes of Great Looking Websites

- The first thing to pay attention to is padding and margin. Every element should have padding so that it's inner contents are not butting up against its edges and margin so that the element itself is not
  butting up against any other elements. In general sibling elements should NOT touch or overlap.
- Pay attention to whitespace when laying out your elements and adding margin/padding. If you have 20px of whitespace to the left of the element you should probably have 20px to the right as well. Make sure
  things are centered correctly (horizontally and vertically) and be consistent! I.E. If you have a row of buttons in the header they should all be aligned vertically with consistent margin and padding.
- Use a [color palette](https://99designs.com/blog/tips/the-7-step-guide-to-understanding-color-theory/) to determine your website's themes and avoid color clashes. You should have a primary color, a secondary color, and 1 or 2 accent colors. Your primary color is going to be the most abundant on the site followed by
  your secondary color. The accent color is used for things like buttons and other areas that you want to draw the user's eye to.
- [Use Google Font Pairing](https://fonts.google.com/) recommendations to find good fonts. In general you should not have more that 2 fonts in a web app and you should avoid mixing Serif and Sans-serif fonts.
- Pay attention to font-size and weight! You should use [textual hierarchies](https://blog.designcrowd.com/article/867/understanding-the-hierarchy-of-text) to break up your text and make it easier to read. Prefer multiple short lines to fewer long lines of text
  when displaying info to the user. Your headers should be large and paragraphs should be slightly smaller font size. Having widely varying and inconsistent font sizes is one of the surest signs that a website was designed by a beginner.
- Most modern websites slightly round the corners of buttons and background cards/modals. [You should too](https://developer.mozilla.org/en-US/docs/Web/CSS/border-radius).
- Take advantage of advanced CSS features like transitions and shadows to make your site pop.
- Make sure you let your user know what parts of the site are alive through [affordances](https://uxplanet.org/ux-design-glossary-how-to-use-affordances-in-user-interfaces-393c8e9686e4).

## Additional Requirements

In addition to the above recommendations, App Academy also expects your projects to include the following:

- **Seed Data:** Make sure your seeds are plentiful and appropriate. Even an excellently designed site will fail to impress if you don't have a good seed data.
- **Favicon:** Make sure your website has a [favicon](https://www.abeautifulsite.net/what-are-favicons).
- **Demo Login:** Make sure your website has a demo login. Most recruiters will not sign up for your website with their own email address as the chance for misuse of said email address is too high.
- Be sure that your **console is free of logs and error messages.** Nothing screams amatuer more than seeing a ton of console.logs when visiting a potential candidate's website.
- **Personal Links:** Any links to your GitHub, LinkedIn, or Angellist should open in a new tab.
- **Scorecard:** When you go to turn in your project on InterviewDB, be sure to include the [scorecard](https://docs.google.com/spreadsheets/d/1mpc1eArqplVtNakIcgSFHGGEKbFCiRTnOc7d2QUGwW0/edit?usp=sharing) so that your advisor can grade your work. Note that you'll need to make your own copy and save it to your google drive before adding the link to InterviewDB.

### For Your JavaScript Project

- Be sure to include clear directions on how to play your game or read your data vizualization. Follow the tips above and don't just slap them on the page somewhere. One good way to include instructions is to put a button labeled 'instructions' that pops up a modal with them when clicked.
- If making a visualization be sure that your data is clearly labeled and that the display makes logical sense. It doesn't matter how nice your D3 transtions are or how cool your bubble chart looks if the data within makes no sense.

## What To Avoid

- Avoid fonts that look like handwriting.
- Avoid over using accent colors.
- Avoid themes that relate to specific holidays (ie. don't make a Christmas themed app).
- Dead Links. If you didn't implement a feature then don't put a link to it. If you do then you're forcing recruiters to find the needle of implemented features in a haystack of unimplemented features.
- Avoid linking to the actual site that you are cloning.
- Avoid neon and crazy colors and avoid having too many different colors in your app.
- Avoid putting [affordances](https://uxplanet.org/ux-design-glossary-how-to-use-affordances-in-user-interfaces-393c8e9686e4) on things that can't be clicked or interacted with.
- Avoid blinking, spinning or flashing images
- Avoid busy tiled background images with any color text
- Avoid having everything centered
- Avoid too many images or huge images
- Avoid long lists of links
- Avoid too many headlines or blinking text

## Exercises

Take a look at the apps below. Each set has a link to a good example and a bad example. Identify which of the two is the good example and list two reasons why it is superior to it's counterpart.

### Set 1

[TriviaLand](https://trivialand-app.herokuapp.com/#/)

[ShakeItUp](http://shake-it-up-aa.herokuapp.com/#/)

### Set 2

[AerBnB](https://aerbnb.herokuapp.com/#/)

[PineappleBeaches](https://pineapple-beaches.herokuapp.com/#/)

### Set 3

[Instatute](https://udemy-clone.herokuapp.com/#/)

[TwixterTube](https://twixtertube.herokuapp.com/#/)

Check out this link for some [Additonal Practice](https://www.toptal.com/designers/web/interview-questions)
