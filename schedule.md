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

### Goals

1. Markup basic internal page navigation (list) and sections (headings, paragraphs, lists, and links)
2. Develop basic typographic styles for body text and link, lists, and headings (and images [figures/captions] if resources are available)

#### In Class

- Introduction to Content First, Mobile First
- Markdown as a content first approach to structure essential page content
- Style tiles as a first step in developing a style guide
- Review syllabus (and Week 1 schedule)

#### Tasks

1. Our Process Section

  - Review content
  - Markup content first with Markdown (content source)

    - Always keep Markdown as clean as possible, with minimal use of [inline HTML text semantics](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Inline_text_semantics) *only* when necessary

      - For example, the use of `<i>` and `<b>` instead of markdown `*` (`<em>`) and `**` (`<strong>`)
      - See [The i, b, em, and strong elements](http://html5doctor.com/i-b-em-strong-element/)

    - Focus on content flow (user experience), hierarchy, and structure

      - Define content types (headings, subheadings, paragraphs, lists, etc.) and content chunks (navigation, sections, etc.)
      - Consider content flow: jump to section (local) navigation, instead of separate pages; back to top links per section to jump back to local navigation; etc.
      - Test user experience on mobile (small screen) devices

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

##### Type & Color

- [Style Tiles and How They Work](https://alistapart.com/article/style-tiles-and-how-they-work)
- [What is Typesetting?](https://alistapart.com/article/flexible-typesetting)
- [Color Accessibility Workflows](https://alistapart.com/article/color-accessibility-workflows)
- [Type in History: The Didones](https://www.sessions.edu/notes-on-design/type-in-history-the-didones/)
- [How Typography Determines Readability: Serif vs. Sans Serif, and How To Combine Fonts](https://medium.freecodecamp.org/how-typography-determines-readability-serif-vs-sans-serif-and-how-to-combine-fonts-629a51ad8cce)
- [Web Typography & Layout: Past, Present, and Future](https://alistapart.com/event/web-typography-layout-past-present-future) `video`

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

##### Color

- [Accessbile Colors](http://accessible-colors.com)
- [Accessible Color Palette Builder](https://toolness.github.io/accessible-color-matrix/)
- [Scale](https://hihayk.github.io/scale/) Color scale generator.
- [ColorHexa](https://www.colorhexa.com)

#### Homework

- Read [About Us](http://www.cbfisk.com/company/about) and entire [Our Process](http://www.cbfisk.com/process) section (including all subsections: Request for Information, Request for Proposal, etc.)
- Enroll in the free online course <cite>[Defeating Busy](https://thegymnasium.com/courses/GYM/001/0/about)</cite>

  - Complete the course (about 1 hour of video content)
  - Take the final exam and earn a badge
  - Share badge with class for homework credit; Share on LinkedIn (optional)
  - Create a takeaways list, for defeating busy, in markdown (for daily personal use)

### Monday, September 3

- **No Class** (Labor Day)

### Tuesday, September 4

- [Harvard Organ Recital](https://memorialchurch.harvard.edu/event/organ-recital) at 7:30–8:45 p.m.

  - (Optional/required? [add note])

#### Directions

- [Driving](https://memorialchurch.harvard.edu/directions)
- [Via MBTA](https://www.harvard.edu/on-campus/visit-harvard/directions)

  1. Depart 5:46 p.m. Beverly Depot; Arrive 6:21 p.m. Boston
  2. Take any Green Line train inbound to Park Street; Red Line Northbound (Alewife) to Harvard (Square) stop

### Wednesday, September 5

### Goals

1. Markup basic internal page navigation (list) and sections (headings, paragraphs, lists, and links)
2. Develop basic typographic styles for body text and link, lists, and headings (and images [figures/captions] if resources are available)

#### In Class

- Review Our Process section prototype using [Device Mode](https://developers.google.com/web/tools/chrome-devtools/device-mode/emulate-mobile-viewports) in Chrome DevTools.
- Prep and handoff Our Process section to Style Title team

  - Convert MD as HTML
  - [Validate HTML](https://validator.w3.org/nu/)

- Style Tile team

  - Meeting with Justin Gagne from 4–5 p.m.

    - Build basic HTML/CSS style title template based on research and tests conducted by the team
    - Apply basic style guide to Our Process section

## Week 2

### Monday, September 10

#### Goals

1. Structure [Our Company](http://www.cbfisk.com/company/about) (About Us/Our People) Section
2. Structure and style header (brand) and primary navigation (menu)
