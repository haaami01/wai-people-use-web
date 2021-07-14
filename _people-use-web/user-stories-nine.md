---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:".

title: "Yun | How People with Disabilities Use the Web"
nav_title: "Yun"
parent_in_h1:
  - ref: /people-use-web/user-stories/
    name: nav_title
  - ref: /people-use-web/
    name: nav_title

lang: en   # Change "en" to the translated-language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2021-@@-@@   # Put the date of this translation YYYY-MM-DD (with month in the middle)

# translators:    # remove from the beginning of this line and the lines below: "# " (the hash sign and the space)
# - name: "Jan Doe"   # Replace Jan Doe with translator name
# - name: "Jan Doe"   # Replace Jan Doe with name, or delete this line if not multiple translators
# contributors:
# - name: "Jan Doe"   # Replace Jan Doe with contributor name, or delete this line if none
# - name: "Jan Doe"   # Replace Jan Doe with name, or delete this line if not multiple contributors

github:
  repository: w3c/wai-people-use-web
  path: people-use-web/user-stories-nine.md    # Add the language shortcode to the middle of the filename, for example: people-use-web/user-stories-nine.fr.md
permalink: /people-use-web/user-stories-nine/   # Add the language shortcode to the end, with no slash at end, for example: /people-use-web/user-stories-nine/fr

navigation:
  previous: /people-use-web/user-stories-eight/
  next: /people-use-web/user-stories/

ref: /people-use-web/user-stories-nine/      # Translators, do not change this
changelog: /people-use-web/changelog/
acknowledgements: /people-use-web/user-stories/acknowledgements/

description: add @@ - @@possibly create separate social images later
image: /content-images/wai-people-use-web/social.png

# In the footer below:
# Do not translate or change CHANGELOG or ACKNOWLEDGEMENTS.
# Translate the other words below, including "Date:" and "Editor:"
# Translate the Working Group name. Leave the Working Group acronym in English.
# Do not change the dates in the footer below.
footer: >
   <p><strong>Date: Draft in progress.</strong> Updated @@ Month 2021. First published Month 20@@. CHANGELOG.</p>
   <p><strong>Editors:</strong> Kevin White, Mark Palmer, Jane Schurick, and <a href="https://www.w3.org/People/shadi/">Shadi Abou_Zahra</a>.  <strong>Contributors:</strong> @@name, @@name, and <a href="https://www.w3.org/groups/wg/eowg/participants">participants of EOWG</a>. ACKNOWLEDGEMENTS lists past editors and additional contributors.</p>
   <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Previously developed with the <a href="https://www.w3.org/WAI/EO/2008/wai-age-tf">WAI-AGE Task Force</a>, with support of the <a href="https://www.w3.org/WAI/WAI-AGE/">WAI-AGE Project</a>.</p>

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

Introduction about Yun

**Note:** The following scenarios are not real people. They do not address every kind of disability.

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::options toc_levels="2..3" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Yun, retiree with low vision, hand tremor, and mild short-term memory loss

> I love all this new technology. It is great to be see my grandchildren. It takes me a bit to find all the controls and sometimes they are a bit of the small side, but I get there in the end

Yun had a long and successful career as an architect. He delayed retirement until he was in his 70's because work challenged him and as the senior architect in his firm, he was often sought after to mentor the new hires and guest lecture at local universities. Yun always wore glasses but over time, the demands of the close-up work necessary to render architectural drawings strained his eyes to the point that he could only work a couple of hours at a time. The final straw was when he developed a mild hand tremor and found it difficult to maintain the precision required in his line of work.

Currently, at age 85 Yun's vision has continued to deteriorate, his hand tremors have gotten worse, and his family has started to notice some short term memory loss. Even so, yun maintains an active interest in the history of architecture and is part of a small group of people who share his passion and write about it online. His blog has an active following and helps him feel like he can still contribute to the field. 

Like many older people, Yun has difficulty reading small text. He stopped buying physical newspapers and now subscribes to an online version now because he is able to increase the size of the text to something he finds easier to read. However, he has had trouble on some sites where this doesn't work so well because either the text gets cut off or the larger text doesn't flow to the next line and he has to scroll horizontally. With his tremor, it's difficult to scroll across in a straight line. Still, however, it's easier than managing the large pages of a print newspaper.

For all of the benefits of using the computer to read the news and stay active in his field, Yun finds CAPTCHAs particularly difficult. These are common when he is signing up to new websites. If the CAPTCHA uses distorted text, he has trouble making it out and if it requires him to select certain images, the pictures are usually not clearly rendered. He's tried using the sound CAPTCHAs but finds them even more difficult even though he has no hearing loss. Yun prefers sites that send him a code that he needs to enter.

### Assistive technologies and adaptive strategies used

* [Screen magnification (Presentation)](https://www.w3.org/WAI/people-use-web/tools-techniques/#presentation)
* [Alternative keyboard and mouse (Input)](https://www.w3.org/WAI/people-use-web/tools-techniques/#input)
* [Keyboard and mouse filters (Input)](https://www.w3.org/WAI/people-use-web/tools-techniques/#input)
* [Mouse customization (Input)](https://www.w3.org/WAI/people-use-web/tools-techniques/#input)
* [Bookmarks and history (Interaction)](https://www.w3.org/WAI/people-use-web/tools-techniques/#interaction)
* [Consistency and predictability (Interaction)](https://www.w3.org/WAI/people-use-web/tools-techniques/#interaction)
* [Descriptive titles, headings, and labels (Interaction)](https://www.w3.org/WAI/people-use-web/tools-techniques/#interaction)
* [Helpful error and success messages (Interaction)](https://www.w3.org/WAI/people-use-web/tools-techniques/#interaction)

### Barrier examples

Inaccessible CAPTCHA
: **Problem**: When I login to my online banking I need to complete a CAPTCHA but I can't really read it well.
: **Works well**: My banking login sends me a text to with a code to confirm it is me.

Text doesn't reflow
: **Problem**: When I resize a website using my browser some of the text disappears or is cut short and sometimes I have to scroll across the screen as well as down.
: **Works well**: When I resize a website using my browser the text is all still available and is presented in a longer thinner column that doesn't need to be scrolled sideways.

Distracting animations
: **Problem:** When my screen is magnified, animations are very distracting because I don't get the full context of what is going on.
: **Works well:** Allow me to stop any animation on the screen so I can concentrate on what I'm looking at.

Tables don't zoom well
: **Problem:** Online tables sometimes have a lot of space between the columns and when I'm zoomed it, I have scroll from left to right to see all of the content and I often miss the association from one column to the next.
: **Works well:** Make tables to be compact so I can see the information in multiple columns at once without have to scroll horizontally.

### Related resources

TBD

### Related principles

* [Text alternatives for non-text content (Perceivable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#alternatives)
* [Content can be presented in different ways (Perceivable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#adaptable)
* [Content is easier to see and hear (Perceivable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#distinguishable)
* [Users have enough time to read and use the content (Operable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#time)
* [Users can easily navigate, find content, and determine where they are (Operable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#navigable)
* [Content is readable and understandable (Understandable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#readable)
* [Content appears and operates in predictable ways (Understandable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#predictable)
* [Users are helped to avoid and correct mistakes (Understandable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#tolerant)
* [Content is compatible with current and future user tools (Robust)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#compatible)