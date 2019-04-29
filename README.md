# Keeping Sites Accessible

## Checklists

- Way to keep track of progress
- However, **not** the actual guidelines

[WebAim checklist](https://webaim.org/standards/wcag/checklist)

> The following is NOT the Web Content Accessibility Guidelines (WCAG) 2. It is a checklist that presents our recommendations for implementing accessibility principles and techniques for those seeking WCAG conformance. The language used here significantly simplifies and condenses the official WCAG 2.1 specification and supporting materials to make it easier to implement and verify for web pages.

## Automated Checks

- You can only catch 20-40% of checks
- [AxE from Deque - AxE Plugin](https://www.deque.com/axe/)
- [Accessibility Insights](https://accessibilityinsights.io/). Has a great "manual" mode.

You can get these in CI:
- https://github.com/fpapado/accessible-pipeline

...what does "in CI" mean, though?

- Testing vs. Monitoring; building a backlog

## Audits

- Audits are a great way to find issues, keep a holistic overview, as well as learn things
- Evaluation by pattern vs. by principle

## Processes / Ways of Working

> A shared pain is half the pain, a shared joy is twice the joy

- Always write things down
- Agree that it's the focus
- Ask questions
- Knowing what / who to ask, is more important than how to solve it

### Descriptive Issues / PRs

(Internal links)

### Code Reviews

- PR templates
- Walk through with someone

## Things to watch for

> As you incorporate accessibility into your workflow, you develop an intuition for these things

- Semantic HTML
- Color contrast
- Labels
- Click handlers on non-buttons
- Document hierarchy (h1-h6)
- Identifying roles/widgets
- Visual/source order mismatch (absolute positioning, flex order etc.)
- Routing

## You will be wrong, and that's fine :)

From the HTML Design Principles:
> In case of conflict, consider users over authors over implementors over specifiers over theoretical purity

## References

### Specs and Principles
[ARIA Authoring Practices](https://www.w3.org/TR/wai-aria-practices-1.1/) How to work with ARIA, how to implement speicfic patterns. For example, a combobox, a modal, a carousel. Also, illustrate how much semantic HTML gives you by default.

[Inclusive Design Principles](https://inclusivedesignprinciples.org/). Series of principles that are meant to promote good practices. Great to print out and have as a reminder, and to help establish a common ground.

[HTML Design Principles](https://www.w3.org/TR/html-design-principles/).

[HTML Accessibility API Mappings](https://www.w3.org/TR/html-aam-1.0/). Ever wonder why we say "semantic HTML is better for accessibility"? This document establishes what role, label, and state each semantic HTML element exposes by default!

### Reading
[Inclusive Components](https://inclusive-components.design). A "blog aiming to be a pattern library", great breakdown of custom widgets and considerations. Also as an ebook.

[Accessibility For Everyone](https://abookapart.com/products/accessibility-for-everyone). Great insight into the reasons, processes and implementation of accessibility.

[Form Design Patterns](https://www.smashingmagazine.com/printed-books/form-design-patterns/).

[Testing with Screen Readers](https://webaim.org/articles/screenreader_testing/).

### Watch
[How A Screen Reader User Accesses The Web: A Smashing Video](https://www.smashingmagazine.com/2019/02/accessibility-webinar/). Léonie Watson goes over how she browses, and various modes in screen readers.

### Courses

[Udemy: Web Accessibility, by Google](https://eu.udacity.com/course/web-accessibility--ud891). Short, fairly comprehensive insight into practical accessibility. Give this a watch!

[Deque University](https://dequeuniversity.com/). Longer-form, self-paced courses. Intended to develop expertise and prepare for certification. Useful to have someone with that knowledge on the team.

### Audits

I think one of the best ways to learn, is to read audits. They show how accessibility is an ongoing process. One I like in particular is the [Bulb Inclusive Design Audit](https://bulbenergy.github.io/bulb-audit/).

### People I follow (and that you might want to as well)

Entirely not comprehensive list:
- [Marcy Sutton](https://twitter.com/marcysutton)
- [Heydon Pickering](https://twitter.com/heydonworks)
- [Léonie Watson](https://twitter.com/leoniewatson)
- [Scott O'Hara](https://twitter.com/scottohara)
- [Adrian Roselli](https://twitter.com/aardrian)

