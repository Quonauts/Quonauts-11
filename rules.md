# Quonauts 11: NEVER SETTLE — Rules

## Table of contents

* [**1. Meta rules**](#meta-rules)
    * [**1.1. Glossary**](#glossary)
    * [**1.2. Accurcay**](#accuracy)
    * [**1.3. Precedence**](#precedence)
    * [**1.4. Forbidden actions**](#forbidden-actions)
    * [**1.5. Timezones**](#timezones)
    * [**1.6. Bots**](#bots)
    * [**1.7. Rule content**](#rule-content)
    * [**1.8. Style conventions**](#style-conventions)
        * [**1.8.1. Content**](#content)
        * [**1.8.2. Headers and tags**](#headers-and-tags)
        * [**1.8.3. Lists**](#lists)
        * [**1.8.4. Formatting**](#formatting)
* [**2. Channels**](#channels)
    * [**2.1. #general**](#general)
    * [**2.2. #proposals**](#proposals)
        * [**2.2.1. Proposal content**](#proposal-content)
            * [**2.2.1.1. Conflict resolution**](#conflict-resolution)

## <a name='meta-rules'/> Meta rules

This section details how the rules are to be applied to the game.

### <a name='glossary'/> Glossary

The definitions for terms listed here take precedence over their normal English meanings, however any terms defined in a specific section of the rules override these in the section in which they are defined and its subsections. A section may also define terms for use in the whole document.

* **The Game**: The instance of Nomic governed by these rules.
* **Game Channel**: Any text or voice channel listed under the "Game Channels" category of the Discord server.
* **Game Action**: Any modification of the game state.
* **Game State**: Every current rule; every non-deleted proposal and any votes on it; every poll and any votes on it; and every message or reaction in any game channel.
* **The Rules**: The rules of the game, which are described by this document.
* **Section**: A part of the rules contained under one header. Unless otherwise specified, this does not include its subsections.
* **Subsection**: A section contained within another another section.
* **Clause**: A single statement in the rules.
* **Player**: Any participant of the game.
* **Active Player**: Any player who has performed a game action in the preceding 72 hours, and is a member of the Discord server.
* **Inactive Player**: Any player who is not an active player.

### <a name='accuracy'/> Accurcay

This document is not guaranteed to always be up-to-date as the game rules are modified, however it is the duty of all players to keep this document accurate as game rules are modified. Where this document disagrees with the game rules, players must follow the game rules as they are, rather than their description in this document.

### <a name='precedence'/> Precedence

In the case of a contradiction between clauses, the following criteria are to be considered in turn until a clear determination can be made as to which clause takes precedence:

* If and only if precedence is specified in the relevant rules and is non-contradictory, follow the instructed precedence.
* The clause which appears last in the rules takes precedence.

### <a name='forbidden-actions'/> Forbidden actions

Unless explicitly stated in the rules, all game actions are forbidden.

Any game action that is forbidden (a "rule violation") is considered void and does not modify the game state; the action and its consequences are to be reverted.

### <a name='timezones'/> Timezones

Unless otherwise specified, all times and dates are specified with respect to UTC.

### <a name='bots'/> Bots

Certain game functions may be performed automatically by automated "bots"; the behaviour of such bots is not governed by the rules, and any function that bots may perform should be feasible, even if inconvenient, to do manually.

Bots are not players.

### <a name='rule-content'/> Rule content

Rules must not refer to individual players, except by using a Discord mention.

### <a name='style-conventions'/> Style conventions

This section and its subsections describe grammatical and stylistic conventions used throughout this ruleset.

Any player may edit the rules to conform to these style conventions. Edits made this way must otherwise be minimal; i.e. they may not change wording or meaning. Note that the meaning of other, linked rule sections must not be changed by such an edit.

#### <a name='content'/> Content

* All rules should be written in English using proper English grammar and spelling. American and British English spelling are both acceptable.
* Where applicable, rules should be written using gender-neutral language, with "they/them/their" as a third-person pronoun, both singular and plural.
* Sentences should be separated by a single space.
* Paragraphs should be separated by a blank line.
* Each paragraph or list element must be shorter than 1000 characters.
* Rules may not contain invisible characters besides newlines, normal spaces, and (in special cases) tabs. Non-ASCII characters should be used sparingly.
* Double quotes should be preferred instead of single quotes. ASCII-compatible straight quotes should be used instead of "smart" quotes.

#### <a name='headers-and-tags'/> Headers and tags

* Each section must have a header and a tag.
* Headers must use [sentence case](https://en.wiktionary.org/wiki/sentence_case), and must be a short, succinct word or phrase (not a complete sentence) describing the section.
* A section tag must be a string of text begin with a lowercase letter, end with either a lowercase letter or a number, and may contain only lowercase letters `a`-`z`, digits `0`-`9`, and hyphens `-`.
* A rule's tag should resemble its header.
* Tags must be unique; no two rule sections may have the same tag.

#### <a name='lists'/> Lists

* Unordered lists should use a single asterisk followed by a space (`* `) before each list element.
* Ordered lists should use a single number followed by a period and a space (`1. `) before each list element.
* The numbers of a ordered list should start at `1` and increase by `1` for each element.
* Lists should not be nested.
* Lists should be separated by the paragraphs above and below by a blank line.
* Two lists of the same type can not be adjacent. (This is treated as one list when converted to Markdown.)

Within a given list, all elements should have the same style, chosen from the following:

* Elements are words or phrases, and do not end with a period.
* Elements are clauses ending in a period (or other punctuation), and optionally followed by complete sentences.
* Elements are complete sentences ending in a period, and optionally followed by more complete sentences.

#### <a name='formatting'/> Formatting

From [GitHub's "Mastering Markdown" document](https://guides.github.com/features/mastering-markdown/), the following may be used:

* Emphasis (italics and bold, not including double underscore `__`)
* Unordered and ordered lists (not nested)
* Links
* Inline code
* Automatic linking for URLs
* Strikethrough

Additionally, square brackets `[]` containing a tag will be converted into links to another rule section; e.g. `[%rule-tag]`. Discord mentions (@username, @role, and #channel) may be used, however they are not readable in GitHub-flavored markdown.

## <a name='channels'/> Channels

Each subsection of this rule section corresponds to a game channel; as the subsections are created, removed, renamed, or reordered, game channels must be created/removed/renamed/reordered accordingly.

### <a name='general'/> #general

Players may talk freely in the <#758947554162769921> channel.

### <a name='proposals'/> #proposals

Proposals can be made by posting them to the <#758947579235926056> game channel.

The first proposal is numbered #1 and each subsequent proposal's number is increased by 1. Deleted proposals retain their number.

A proposal is either open or closed. When it is first submitted a proposal is open. A closed proposal is either passed or failed.

#### <a name='proposal-content'/> Proposal content

A proposal must describe one or more actions that make changes to the game rules or otherwise alter the game state.

A proposal must not reference information outside of the game state, or propose a rule that does so.

If a proposal describes a modification to the rules, it must unambiguously specify the rule section(s) to be modified and how they will be modified.

If a proposal describes the creation of a new rule section, it must specify its title, its content, and should specify its location in relation to an existing rule; if and only if it does not specify a location, then it will be assumed that its location is below all other currently existing rules (this does not apply after the proposal has been enacted).

Any open proposal that does not comply to these rules may be closed as failed at any time.

##### <a name='conflict-resolution'/> Conflict resolution

If multiple proposals describe the modification or addition of sections, paragraphs, or sentences to the same part of the rules, conflicts should be resolved based on the age of the proposal, such that the newer proposal's effect overrides the older one's. For example, if proposal #10 adds a new section "A" to the bottom of the rules, and proposal #11 adds a new section "B" to the bottom of the rules, and both proposals pass, then regardless of which proposal passed first, section "B" will appear below section "A" in the rules.

