# Schedule

- [Week 1](#week-1)
- [Week 2](#week-2)
- [Week 3](#week-3)
- [Week 4](#week-4)
- [Week 5](#week-5)
- [Week 6](#week-6)
- [Week 7](#week-7)
- [Week 8](#week-8)
- [Week 9](#week-9)
- [Week 10](#week-10)
- [Week 11](#week-11)
- [Week 12](#week-12)
- [Week 13](#week-13)
- [Week 14](#week-14)
- [Week 15](#week-15)

## Week 1

Initial week focusing on the process of Fisk and the process of designing with a content first and mobile first approach.

> Design is the synthesis of form and content; without content there is no form; and without form there is no content.
>
> —[Paul Rand](http://www.paul-rand.com)

> Content precedes design. Design in the absence of content is not design, it's decoration.
>
> —[Jeffrey Zeldman](https://www.zeldman.com/about/)

### Wednesday, August 29

#### Goals

1. Introductions and team assignments
2. Markup basic internal page navigation (list) and sections (headings, paragraphs, lists, and links)
3. Develop basic typographic styles for body text and link, lists, and headings (and images [figures/captions] if resources are available)

#### In Class

- Team building, skill survey
- Introduction to Content First, Mobile First
- Markdown as a content first approach to structure essential page content
- Style tiles as a first step in developing a style guide
- Review syllabus (and Week 1 schedule)

#### Tasks

1. Our Process Page

  - Review content
  - Markup content first with Markdown (content source)

    - Always keep Markdown as clean as possible, with minimal use of [inline HTML text semantics](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Inline_text_semantics) *only* when necessary

      - For example, the use of `<i>` and `<b>` instead of markdown `*` (`<em>`) and `**` (`<strong>`)
      - See [The i, b, em, and strong elements](http://html5doctor.com/i-b-em-strong-element/)

    - Focus on content flow (user experience), hierarchy, and structure

      - Define content types (headings, subheadings, paragraphs, lists, etc.) and content chunks (navigation, sections, etc.)
      - Consider content flow: jump to section (local) navigation, instead of separate pages; back to top links per section to jump back to local navigation; etc.
      - Test user experience on mobile (small screen) devices

    - See [`markdown-tmpl.md`](handouts/week-1/markdown-tmpl.md) for starter Markdown page template

2. Branding Style Guide (Style Tile)

  - Review existing print-based styles

    - [Style Guide Assets](https://) (Work from previous semester.) <mark>`todo`</mark>

    - Fisk brochure/catalog (printed matter)

  - Discuss font pairing, web fonts (performance), color contrast (accessibility), etc.

    - Recommendation: Use a web font for headings/subheadings and a web-safe font for body text

        - Didot has [~93% support on iOS/Mac and 0% support on Android/Win](https://www.cssfontstack.com/Didot)
        - Use Didot for headings, with a web font as a fallback (e.g. [GFS Didot](https://fontlibrary.org/en/font/gfs-didot))

          - [Compare](http://webfont-test.com) Didot and GFS Didot (et al.) side by side and overlaid for size and line length comparison

        - Consider Optima (roman weight is potentially too thin), Gill Sans or Trebuchet MS ([widely supported](http://fontfamily.io/trebuchet_ms)) for body text, with a web font fallback (e.g. [Cabin](https://fonts.google.com/specimen/Cabin))

          - [Compare](http://webfont-test.com) Optima, Gill Sans, and Cabin (et al.) side by side and overlaid for size and line length comparison

  - Develop basic style tile in HTML/CSS

    - Typography (fonts, sizes, spacing, etc.)

      - Headings, body text and links
      - Navigation and navigation links for local navigation (*not* global/primary navigation)

    - Colors (texts and backgrounds)

    - Images (figure/caption)

#### Homework

- Read [About Us](http://www.cbfisk.com/company/about) and entire [Our Process](http://www.cbfisk.com/process) section (including all subsections: Request for Information, Request for Proposal, etc.)
- Enroll in the free online course <cite>[Defeating Busy](https://thegymnasium.com/courses/GYM/001/0/about)</cite>

  - Complete the course (about 1 hour of video content)
  - Take the final exam and earn a badge
  - Share badge with class for homework credit; Share on LinkedIn (optional)
  - Create a takeaways list, for defeating busy, in markdown (for daily personal use)

#### Lectures

- [Paul Rand Retrospective](https://vimeo.com/8930131) Form and content; content and form. `video`
- [Content First by Jeffrey Zeldman](https://aneventapart.com/news/post/aea-video-jeffrey-zeldman-designing-with-web-standards-content-first) `video`

#### Readings

##### Content First

- [Content First Web Design: What It's About and How to Get Started](https://blogs.adobe.com/creativecloud/content-first-web-design-what-its-about-and-how-to-get-started/)
- [Content-First Design](https://alistapart.com/blog/post/content-first-design)
- [Content First — Design Last](https://www.smashingmagazine.com/2015/02/design-last/)
- [How Chunking Helps Content Processing](https://www.nngroup.com/articles/chunking/)
- [Designing For Micro-Moments](https://www.smashingmagazine.com/2018/08/designing-for-micro-moments/)

##### Style Tiles & Guides

- [Style Tiles and How They Work](https://alistapart.com/article/style-tiles-and-how-they-work)
- [Creating Style Guides](https://alistapart.com/article/creating-style-guides)

##### Type

- [What is Typesetting?](https://alistapart.com/article/flexible-typesetting)
- [How Typography Determines Readability: Serif vs. Sans Serif, and How To Combine Fonts](https://medium.freecodecamp.org/how-typography-determines-readability-serif-vs-sans-serif-and-how-to-combine-fonts-629a51ad8cce)
- [The Typographic Scale](http://spencermortensen.com/articles/typographic-scale/)
- [Type in History: The Didones](https://www.sessions.edu/notes-on-design/type-in-history-the-didones/)
- [Web Typography & Layout: Past, Present, and Future](https://alistapart.com/event/web-typography-layout-past-present-future) `video`

##### Color

- [Designing for Accessibility, Step 1: Color Contrast](https://uxdesign.cc/the-easiest-part-about-designing-accessible-websites-76cd6b9a7ae4)
- [Color Accessibility Workflows](https://alistapart.com/article/color-accessibility-workflows)

##### Markdown & HTML

- [Writing with Markdown for Better Content & HTML: Why & How To](https://moz.com/blog/markdown)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [The i, b, em, and strong elements](http://html5doctor.com/i-b-em-strong-element/)

##### GitHub

- [The Art of the Commit](https://alistapart.com/article/the-art-of-the-commit)
- [Useful Tips for writing better Git commit messages](https://code.likeagirl.io/useful-tips-for-writing-better-git-commit-messages-808770609503)

#### Tools

##### Fonts

- [Font Family Reunion](http://fontfamily.io)
- [Webfont Test](http://webfont-test.com) Test and analyze your favorite web fonts.

##### Typographic Scale

- [Type Scale](http://type-scale.com) — A visual calculator.

##### Color

- [Accessible Colors](http://accessible-colors.com)
- [Accessible Color Palette Builder](https://toolness.github.io/accessible-color-matrix/)
- [Scale](https://hihayk.github.io/scale/) Color scale generator.
- [ColorHexa](https://www.colorhexa.com)
- [HTML Color Codes](https://htmlcolorcodes.com)

### Monday, September 3

- **No Class** (Labor Day)

### Tuesday, September 4

- [Harvard Organ Recital](https://memorialchurch.harvard.edu/event/organ-recital) at 7:30–8:45 p.m.

  - At least one member from each team should attend

#### Directions

- [Driving](https://memorialchurch.harvard.edu/directions)
- [Via MBTA](https://www.harvard.edu/on-campus/visit-harvard/directions)

  1. Depart 5:46 p.m. Beverly Depot; Arrive 6:21 p.m. Boston
  2. Take any Green Line train inbound to Park Street; Red Line Northbound (Alewife) to Harvard (Square) stop

### Wednesday, September 5

#### Goals

1. Markup basic internal page navigation (list) and sections (headings, paragraphs, lists, and links)
2. Develop basic typographic styles for body text and link, lists, and headings (and images [figures/captions] if resources are available)

#### In Class

- Review Our Process page prototype using [Device Mode](https://developers.google.com/web/tools/chrome-devtools/device-mode/emulate-mobile-viewports) in Chrome DevTools.
- Prep and handoff Our Process page to Style Title team

  - Convert MD to HTML
  - [Validate HTML](https://validator.w3.org/nu/)
  - Handoff both MD and HTML files

- Style Tile team

  - Meeting with Justin Gagne from 4–5 p.m.

    - Update Our Process page HTML with necessary sectioning elements (see MD for reference)
    - Build basic HTML/CSS style title template based on research and tests conducted by the team
    - Apply basic styles to Our Process page

## Week 2

A deeper dive into content and the concerns of modern front-end web development.

### Monday, September 10

#### Goals

1. Introduction to front-end web development
2. Familiarization with client content

#### In Class

- Review Homework

  - Our Process page prototype
  - Font style prototypes
  - Discuss <cite>[Defeating Busy](https://thegymnasium.com/courses/GYM/001/0/about)</cite>
    - Post badges on Slack

- Lecture: front-end web development
- Assess and map current [Fisk website](http://www.cbfisk.com)

  - Discuss proposed sitemap and new content
  - Review work from previous semester

##### Known Fisk Competitors

- [Taylor and Boody](https://www.taylorandboody.com)
- [Richards, Fowkes & Co.](http://www.richardsfowkes.com)
- [Dobson](http://www.dobsonorgan.com)

#### Homework

- Research Fisk competitors and be prepared to present your findings and evaluation of their websites
- Revise prototypes taking into account feedback from class

### Wednesday, September 12

#### Goals

1. Introduction to Accessibility
2. Introduction to Prototyping

  - Review, discuss, and prototype information architecture of site navigation
  - Review [Navigation Summary](https://www.youtube.com/watch?v=SpJFavEB18Y) report in Google Analytics

#### Tasks

1. Prototype primary navigation for small (mobile) and wide (tablet/laptop/desktop) screens

  - Existing primary, header navigation:

    - The Process
    - Our Company
    - Instruments

  - Existing secondary, footer navigation:

    - Concert Calendar
    - Discography
    - Newsletter
    - Contact Us
    - Facebook

#### Homework

- Prototype Primary Navigation for small (mobile) and wide (tablet/laptop/desktop) screens (on paper and/or in text [Markdown])

#### Readings

##### Accessibility

- [To Make Your Product Accessible, Consider Accessibility at Each Stage of the Design Process](https://medium.com/@jessicaivins/to-make-your-product-accessible-consider-accessibility-at-each-stage-of-the-design-process-5b09fc188c9e)

##### Navigation Patterns

- [The Hamburger Menu Doesn't Work](http://jamesarcher.me/hamburger-menu)
- [3 Good Reasons Why You Might Want to Remove that Hamburger Menu from Your Product](https://medium.muz.li/3-good-reason-why-you-might-want-to-remove-that-hamburger-menu-from-your-product-69b9499ba7e2)
- [Hamburger Menu Alternatives for Mobile Navigation](https://medium.com/@kollinz/hamburger-menu-alternatives-for-mobile-navigation-a3a3beb555b8)

##### Progressive Enhancement

- [The Web I Want](https://dev.to/quii/the-web-i-want-43o)
- [The Power of Progressive Enhancement](https://medium.com/no-divide/the-power-of-progressive-enhancement-98738766b009)

##### Prototyping

- [Paper Prototyping](https://alistapart.com/article/paperprototyping)

#### Tools

##### Accessibility

- [WAVE](https://wave.webaim.org) (web accessibility evaluation tool)
- [Accessible Colors](http://accessible-colors.com)
- [Accessible Color Palette Builder](https://toolness.github.io/accessible-color-matrix/)

##### Prototyping

- [Printable Grids for Design Wireframing](http://sneakpeekit.com)
- [HTML Builder Prototype](http://dev.artequalswork.com/builder/) (web-based)

## Week 3

### Monday, September 17

#### Goals

1. Develop primary navigation

#### In Class

- Review, discuss, and prototype primary navigation

 - Compare competitors
 - Exposure menu without dropdown (hamburger)
 - Simply and clarify menu labels

#### Homework

- Prototype Revised Navigation for small (mobile) and wide (tablet/laptop/desktop) screens

#### Readings

##### Navigation Guidelines

- [Menu Design: Checklist of 15 UX Guidelines to Help Users](https://www.nngroup.com/articles/menu-design/)

##### Writing Guidelines

- [Plain Language Is for Everyone, Even Experts](https://www.nngroup.com/articles/plain-language-experts/) (Apply to navigation.)

### Wednesday, September 19

#### Goals

1. Develop responsive branding for Fisk header (web and print [spec data sheets])
2. Develop Our Process page

#### In Class

- Review, discuss, and prototype branding: Logotype, slogan, favicon, etc.
- Review, discuss, and prototype Our Process page

#### Homework

- Design new Fisk favicon

 - lo-fi `16px × 16px` version (consider using graph paper)
 - hi-fi `256px × 256px` version (design as vector using [Adobe XD](https://www.adobe.com/products/xd.html) [free for Mac/PC])

#### Readings

##### Favicon

- [How We Got the Favicon](https://thehistoryoftheweb.com/how-we-got-the-favicon/)
- [How to Make a Favicon](http://blog.teamtreehouse.com/how-to-make-a-favicon)

##### Responsive Branding

- [Responsive Logos](http://responsivelogos.co.uk)
- [Centered Logos Hurt Website Navigation](https://www.nngroup.com/articles/centered-logos/)

#### Tutorials

##### Adobe XD

- [How To Create Icons In Adobe XD](https://www.smashingmagazine.com/2016/07/how-to-create-icons-adobe-xd/)

## Week 4

### Monday, September 24

#### Goals

1. Prepare for Fisk visit

#### In Class

- Review, and discuss favicon designs
- Revise Our Process page
- Practice presentation

  - Discuss presentation tips and strategies
  - Divide content and develop draft presentation
  - Practice presentation as a group

#### Homework

- Practice presentation
- Complete revisions to Our Process, Navigation

#### Readings

- [Ten Tips for Improving Your Public Speaking Skills](https://www.extension.harvard.edu/professional-development/blog/10-tips-improving-your-public-speaking-skills)
- [Five Basic Public Speaking Tips](https://youtu.be/AykYRO5d_lI) `video`

### Wednesday, September 26

#### Goals

1. Present Progress to Fisk employees
2. Tour the shop, meet the staff, learn the context behind the Content

#### In Class

- Meet at the checkerboard of the Hardie Building, the bus will leave at 3:30pm
