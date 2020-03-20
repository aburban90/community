# Writing Style Guide

The MakerDAO Community Writing Style Guide summarizes the standards and best practices Writers should follow when contributing to Community Development resources.

- Errors are sometimes overlooked. If something in a document does not adhere to the Writing Style Guide, edit accordingly.
- In addition to this guide, Writers are encouraged to study the [Quickstart Guide](https://docs.google.com/document/d/1DvpA7EdhoK2a_bepfAzP3mAz_QsDvRKFBfI_qaHiGTQ/edit?usp=sharing), [Reviewer Guide](https://hackmd.io/PxQDuZ6mRvOUD8x7Q24YkQ?both), and [Contributor Tools](https://hackmd.io/JKv26kagS5eTGnpgMpBxUA?both) before starting work on Maker Community Development projects.

---

## <a id="tocmain"></a> Table of Contents

<!-- TOC -->

### Intent and Tone

- [Overview](#writing-intent-and-tone)

### Writing Guidelines

- [General Rules](#writing-guide1)
- [Cases](#cases)
- [Naming Conventions](#naming-conventions)
- [Numbers](#numbers)
- [Currencies](#currencies)
- [Acronyms & Decades](#acronyms-and-decades)
- [Lists](#lists)
- [Links](#links)
- [Table of Contents](#toc1)

### Markdown Guidelines

- [Markdown](#markdown)
- [Guidelines](#guidelines)

### Best Practices

- [Overview](#writer-best-practices)
- [Writing Tools](#helpful-writing-tools)
- [Review Community Guides](#review-community-guides)
- [Collaborate](#collaborate)
- [Track Progress](#track-progress)
- [Submitting Final Drafts](#final-drafts-and-submissions)

<!-- /TOC -->

---

## Writing Intent and Tone

MakerDAO Community Development materials should cater to readers who are unfamiliar with the Maker system. Writers should also assume that their readers have tight schedules and short attention spans.

As such, Writers should focus on communicating concepts as clearly and succinctly as possible.

- Use simple language.
- Use short, concise sentences.
- Avoid unnecessary words.
- Remain open and objective.
- Provide examples when possible.
- Provide examples to help explain concepts, but avoid overcomplicating them.
    - Use math when necessary, but keep it simple.
- Link to basic terms if necessary.

## <a id="writing-guide1"></a> Writing Guidelines

### General Rules

**Use:**

- [Oxford commas](https://en.wikipedia.org/wiki/Serial_comma).
- [Pluralized, gender-neutral pronouns](https://en.wikipedia.org/wiki/Singular_they). 
    - Use “they/their” instead of “he/she/his/hers.”
    - **Examples:** “When they…” or “If users choose to X, then their…”
- The `%` symbol. Do not spell out "percent."
    - **Correct:** 15%
    - **Incorrect:** 15 percent
- Double quotes `" "` for phrases, quotes, etc.
    - Do not use single `' '` quotes.

**Avoid:**

- [First-person language](https://en.wikipedia.org/wiki/Grammatical_person).
    - **Examples:** I, we, our, etc.
-  [Second-person language](https://en.wikipedia.org/wiki/Grammatical_person).
    - **Examples:** "You then..." or "Now you should..."
- Exclamation points.
- Footnotes.
- References to [Purple Paper](https://makerdao.com/purple/) names.
    - **Examples:** Flip, Flap, Flop, etc.

***Note:** Run all drafts through [Grammarly](https://app.grammarly.com/) before submission. Grammarly will catch most spelling and grammatical errors.*

### Cases

- **Capitalize**
  - Names and proper nouns.
  - Cities, countries, nationalities, and languages.
  - Terms with definitions provided by MakerDAO.
    - Vist the [Glossary of Terms](community/faqs/glossary.md) for the official list.
  - Comm-Dev role titles.
      - **Examples:** Lead, Approver, Advisor, etc.
- **Title Case**
  - Capitalize the first word and all nouns, proper nouns, verbs, and adjectives.
  - Lowercase all:
      - **Articles:** a, an, the, etc.
      - **Conjunctions:** and, but, etc.
      - **Prepositions:** on, it, before, etc.

### Naming Conventions

#### Cryptocurrencies

- When directly referring to the creation, destruction, or manipulation of a token (particularly as it relates to tooling):
    - Use the capitalized TLA version: `DAI`.
    - **Example:** “Draw DAI against ETH from a Vault.”
- Similarly, when referring to exchange pairs: 
    - Use: `ETH/DAI`.
- When referencing the token as a currency, in an instructional or conversational setting, or as a conceptual product of the Foundation or its systems:
    - Use: `Dai`.
    - **Example:** “Dai is a price-stable asset that can be used as money.”

#### MakerDAO

- When referring to MakerDAO as a smart contract system, use "The Maker Protocol."
    - **Example:** “The Maker Protocol facilitates DAI generation."
- When referring to MakerDAO as a body of MKR voters and the general stakeholder community, use "Maker Community" or "MakerDAO."
    - **Example:** "MakerDAO passed a vote to increase the Stability Fee."
    - **Example:** "The Maker Community passed a vote to increase the Stability Fee."
- Use "Maker" for casual references to MakerDAO and the Maker Protocol as a whole.
- Always distinguish the Maker Foundation from MakerDAO.

#### Community Development

- Use "Comm-Dev" as the shortened version of "Community Development."

### Numbers

- Spell out numbers below 10.
    - **Examples:** one, two, three, etc.
- Use numerals for numbers above 10, unless starting a sentence.
- For numbers with million, billion, or trillion, use figures in all except casual cases.
    - **Standard:** "The nation has 1 million citizens."
    - **Casual:** "I'd like to make a billion dollars."

### Currencies

The examples below use dollars, but the same rules apply to all global currencies.

- Use lowercase except when writing "US Dollar.”
- Use figures and the \"$" sign in all except casual references, or amounts without a figure.
    - **Standard:** "The book costs \$4."
    - **Casual:** "Please give me a dollar."
- For amounts under \$1 million, follow this format:
    - **Correct:** \$4, \$25, \$500, \$1,000, \$650,000.
- For amounts over \$1 million, use the word, not numerals. 
    - **Correct:** "He is worth \$4 million."
    - **Incorrect:** "He is worth \$4,000,000."

### Acronyms and Decades

Do not use apostrophes to pluralize acronyms or indicate decades. Add an "s" at the end.

**Acronyms**
- To make an acronym plural:
    - **Correct:** SCDs
    - **Incorrect:** SCD's

**Decades**
- To indicate a decade:
    - **Correct:** 1990s
    - **Incorrect:** 1990's

### Lists

When bulleted and numbered lists contain complete sentences, capitalize the first word, and follow each with a period. If list items are phrases, no capitalization or punctuation is required.

- Use [parallel construction](https://en.wikipedia.org/wiki/Parallelism_\(grammar\)) for each item in a list.
- Start with the same [part of speech](https://en.wikipedia.org/wiki/Part_of_speech) for each item (in this case, a verb).
- Use the same verb [tense](https://en.wikipedia.org/wiki/Grammatical_tense#English) for each item.
- Use the same [voice](https://en.wikipedia.org/wiki/Voice_\(grammar\)) for each item.
- Use the same sentence type (statement, question, exclamation) for each item.
- List items that include definitions should look like this:
    - **Team:** Core team and Advisors are critical to MakerDAO's success.
    - **Community**: Sentiment analysis is invaluable.
- Use dashes rather than asterisks for unordered lists.
    - **Correct:** `-` 
    - **Incorrect:** `*`
- Alphabetize lists of names unless there is a clear priority at work.
- Do not use ordered (numbered) lists unless order matters.
- Ordered list items should use the `#1` repeated.
    -  Markdown will automatically generate numbers.
  ```markdown
  1. Item 1
  1. Item 2
  1. Item 3
     1. Item 3a
     1. Item 3b
  ```
  
### Links

- Use [relative links](https://docs.microsoft.com/en-us/contribute/markdown-reference#links).
- Use [anchor IDs](#anchor-id).
- Create descriptive hyperlinks and avoid generic language.
    - **Descriptive:** Learn more at [Awesome-MakerDAO](link).
    - **Generic:** Learn more [here](link).
- When creating links for parallel translated documents, make sure to update relative links to reflect the correct heading.
  ```text
  en: faqs/cdp.md#what-are-collateralized-debt-positions
  es: faqs/es/cdp.md#qué-son-las-posiciones-de-deuda-colateralizadascdp
  ko: faqs/ko/cdp.md#부채-담보부-포지션collateralized-debt-positions-cdp이란-무엇인가요```

### <a id="toc1"></a>Table of Contents

- For documents that span several pages and multiple sections, include a table of contents.
- Use the raw Markdown from the [Table of Contents](#tocmain) above as a starting point.
    - Be sure to include the line breaks `---` as well to keep formatting consistent.
- The table of contents should list important sections for easy navigation.

## Markdown

MakerDAO documents posted on Github are written in Markdown.

- Consider using Visual Studio Code and install the extensions below:
    - `Markdown Preview Enhanced`
    - `Markdown Linter`
    - `Code Spell Checker`
    - `GitLens`
    - `Prettier`
      - Prettier will auto-correct most Markdown mistakes.

### Guidelines

- Include line breaks above and below headings.
- Use top-level headers `#` only once per document.
    - Do not make multiple top-level headings.
- Avoid repeat headings without anchors.
    - They will break auto-generated navigation.
- <a id="anchor-id"></a> To link to a repeated heading, create an anchor ID.
    - **Anchor ID:** `### <a id="section_id"></a> Section One`
    - **Link:** `[Section One](#section_id)`
- Avoid trailing spaces.
- Do not use:
    - Em or en [dashes](https://en.wikipedia.org/wiki/Wikipedia:Hyphens_and_dashes): `—`.
    - Ampersands `&` in titles and headers.
    - Pipes `|` in titles and headers.
    - Curly quotes. Use the plaintext version.
        - **Correct:** `"`
        - **Incorrect:** `“`
    - Escaping parentheses. Use normal parentheses.
        - **Correct:** `(SOMETHING)`
        - **Incorrect:** `\(SOMETHING\)`
- Ensure there is a single hard return at the end of a .md file.

## Writer Best Practices

Writers and Contributors familiar with MakerDAO and cryptocurrency basics will have a better sense of where to apply their skills best. 
- Spend some time learning about MakerDAO's function, history, and any latest events before contributing.
- In-depth knowledge is appreciated but not required.

### Helpful Writing Tools

Make use of any writing tools that help improve workflow and writing quality. See the list below for some recommendations.

#### Text Editors

- [Grammarly](https://app.grammarly.com/): Mistake-free writing editor.
- [HemingwayApp](http://www.hemingwayapp.com/): Make writing bold and clear.

#### Word Choice

- [Thesaurus](https://www.thesaurus.com/): Synonyms.
- [Powerthesaurus](https://www.powerthesaurus.org/): Synonyms and phrase suggestions.
- [WordHippo](https://www.wordhippo.com/): Synonyms and phrase suggestions.

### Review Community Guides

Review all contributor guides before starting any work on Maker Community Development projects.
- Community contributor guides outline writing standards and help simplify the writing process. 

#### Contributor Quickstart Guide

- Refer to the [Contributor Quickstart Guide](link) for an introduction to contributing to MakerDAO's Community Development resources.

#### Document-Specific Maintenance Guides

- Check for an associated maintenance guide before starting work on a given document.
- A document maintenance guide outlines standards to help Reviewers and contributors when maintaining a given resource.
    - The rules described within a document-specific maintenance guide supersede other guides.
    - If a discrepancy is glaring or unreasonable, bring the issue to an Advisor in [#community-development](https://chat.makerdao.com/channel/community-development) on MakerDAO's chat.
    
#### Contributor Tools

- The [Contributor Tools](https://hackmd.io/JKv26kagS5eTGnpgMpBxUA?both) guide introduces the tools regularly used by Community Development.

### Express Interest

- Join the [#community-development](https://chat.makerdao.com/channel/community-development) channel on MakerDAO's chat and reach out to a Community Lead or Advisor.
- Community team members and senior contributors help onboard new contributors.
    - Leads and Advisors consider a contributor’s strengths and abilities to help assign appropriate projects or tasks.
- Discuss personal interests and relevant skills to help determine a well-suited project.
- Provide relevant examples of past projects, work, and experience.
    - Demonstrate a reliable work ethic and offer quality work that speaks for itself.
    - Stand out by suggesting projects and adding insight to public discussions.

### Collaborate

- When accepting an assignment, be sure to collaborate early and often.
- Visit [#community-development](https://chat.makerdao.com/channel/community-development) regularly.
- Coordinate with other members.
    - Ask as many questions as necessary
    - Ask for feedback when stuck.
    - Provide frequent progress updates.
- Develop a plan that defines an approach for an assignment.
    - Produce a project outline.
    - Set achievable deadlines.
    - Assign and divide tasks with other contributors. 
        - Multiple contributors should not start work on similar projects individually.


#### Track Progress

- Track projects and progress with [GitHub issues.](https://github.com/makerdao/community/projects/2)
    - Keep GitHub issues updated with comments and feedback.
- Take advantage of version history when working in HackMD or Google Docs.

#### Final Drafts and Submissions

- Let an Advisor know when a project is ready for final review.
- Transfer approved final drafts from Google Docs to HackMD.
- Submit completed projects for approval as [Pull Requests](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) on GitHub.
    - Update any relevant issues and the project board on GitHub.
