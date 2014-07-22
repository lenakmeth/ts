Title:        TEI - Mini Quidelines for thinking
Subtitle:     elements, attributes, snippets, and conventions we (will) use
Editors:      trianta, eAnagnostis, indvstry
Status:       in progress - *don't edit if not one of editors mentioned above!*


<!-- notation legend -->
  <<some.class>>
  <element>
  `@attribute`
  \\`attribute value`
  <el.at="va"> ? -- maybe use this
  x-> is an example
  n-> is a note
  ###### sn1pp3ts
  [UseCase][description]
  ![important][phrase]
<!-- ...... -->


<!-- MarkdownTOC depth=4 -->

- Διαδικασία, στόχοι, ιδέες, κανόνες, etc
  - 1.1 encoding στόχοι και tasks
    - 1.1.1 1st pass
  - 1.2 Encoding and Feature Ideas for consideration
- Our TEI Guidelines and Snippets
  - 3.1 Paragraphs
  - 3.3 Highlighting and Quotation
    - 3.3.1 What Is Highlighting?
    - 3.3.2 Emphasis, Foreign Words, and Unusual Language
      - 3.3.2.1 Foreign Words or Expressions
      - 3.3.2.2 Emphatic Words and Phrases
      - 3.3.2.3 Other Linguistically Distinct Material
    - 3.3.3 Quotation
    - 3.3.4 Terms, Glosses, Equivalents, and Descriptions
    - 3.3.5 Some Further Examples
  - 3.4 Simple Editorial Changes
    - 3.4.1 Apparent Errors
    - 3.4.2 Regularization and Normalization
  - 3.5 Names, Numbers, Dates, Abbreviations, and Addresses
    - [3.5.2 Addresses](#)
    - 3.5.3 Numbers and Measures
    - 3.5.4 Dates and Times
    - 3.5.5 Abbreviations and Their Expansions
  - 3.6 Simple Links and Cross-References
  - 3.7 Lists
  - 3.8 Notes, Annotation, and Indexing
    - 3.8.1 Notes and Simple Annotation
    - 3.8.2 Index Entries
  - 3.10 Reference Systems
- 4 Default Text Structure
  - 4.1 Divisions of the Body
    - 4.1.1 Un-numbered Divisions
    - 4.1.2 Numbered Divisions
    - 4.1.3 Numbered or Un-numbered?
    - 4.1.4 Partial and Composite Divisions
  - 4.2 Elements Common to All Divisions
    - 4.2.1 Headings and Trailers
    - 4.2.2 Openers and Closers
    - 4.2.3 Arguments, Epigraphs, and Postscripts
  - 4.3 Grouped and Floating Texts
    - 4.3.1 Grouped Texts
    - 4.3.2 Floating Texts
  - 4.4 Virtual Divisions
  - 4.5 Front Matter
  - 4.6 Title Pages
  - 4.7 Back Matter
- 13. Names, Dates, People, and Places
  - 13.1 Attribute Classes Defined by this Module
    - 13.1.1 Linking Names and their Referents
      - General Use Cases and Snippets
    - 13.1.2 Dating Attributes
      - General Use Cases and Snippets
  - 13.2 Names
    - 13.2.0 (was 3.5.1 Referring Strings)
    - 13.2.1 Personal Names
      - 13.2.2 Organizational Names
      - 13.2.3 Place Names
  - 13.3 Biographical and Prosopographical Data
    - 13.3.1 Basic Principles
    - 13.3.2 The Person Element
      - 13.3.2.1 Personal Characteristics
      - 13.3.2.2 Personal Events
      - 13.3.2.3 Personal Relationships
- 14 Tables, Formulæ, Graphics and Notated Music
  - 14.1 Tables
  - 14.2 Formulæ and Mathematical Expressions
  - [14.4 Specific Elements for Graphic Images](#)
    - General Use Cases and Snippets
      - Encode internally divided figure(s)
      - Maintain two versions of an image
      - Associate part(s) of image with textual element (or other)
  - 16.1 Links
    - 16.1.1 Pointers and Links
    - 16.1.3 Groups of Links
  - 16.2 Pointing Mechanisms
    - 16.2.3 Using Abbreviated Pointers
    - 16.2.5 TEI XPointer Schemes
      - 16.2.5.2 xpath1(Expr)
      - 16.2.5.4 range()
    - 16.2.6 Canonical References
    - 16.3 Blocks, Segments, and Anchors
    - 16.4.2 Alignment of Parallel Texts
  - 16.5
    - 16.5.1 Aligning Synchronous Events
    - 16.5.2 Placing Synchronous Events in Time
  - 16.7 Aggregation
  - 16.8 Alternation
  - 16.9 Stand-off Markup
    - 16.9.1 Introduction
    - 16.9.2 Overview of XInclude
  - 17.2 Global Attributes for Simple Analyses
  - 17.3 Spans and Interpretations
  - 17.4 Linguistic Annotation
  - 18.2 Elementary Feature Structures and the Binary Feature Value
  - 20.3 Fragmentation and Reconstitution of Virtual Elements
  - 23.3 Personalization and Customization
    - 23.3.1 Kinds of Modification
      - 23.3.1.1 Deletion of Elements
      - 23.3.1.2 Renaming of Elements
      - 23.3.1.3 Modification of Content Models
      - 23.3.1.4 Modification of Attribute and Attribute Value Lists
      - [](#23.3.1.5 Class Modification)
      - [](#23.3.1.6 Addition of New Elements)

<!-- /MarkdownTOC -->

# Διαδικασία, στόχοι, ιδέες, κανόνες, etc

## 1.1 encoding στόχοι και tasks
- chunk files into chapter parts
- schedule around calendar
- με συγκεκριμένες αρμοδιότητες

### 1.1.1 1st pass
* να περάσουμε τις σκηνές
  - δες _"sn1pp3ts - scenes and their info"_
  - μετά να δώσουμε <head> + (later) <abstract>  
* ιδιαίτερες λέξεις και φράσεις (πχ αργκό, ιδιωματικές, ξένες, όροι, κ.α.)
  - δες _"sn1pp3ts - words needing an extra layer of info"_ 
* λίστα προσώπων και encoding εμφανίσεων τους στο κείμενο
  - δες _"sn1pp3ts - people and appearances"_
* λίστα τόπων, κτιρίων και παρόμοιων, και encoding εμφανίσεων τους στο κείμενο
  - δες _"sn1pp3ts - places, buildings, etc. and appearances"_
* διάλογοι, μονόλογοι και σκέψεις των χαρακτήρων στο βιβλίο
  - δες ... <said who="#Tom.Sawyer" aloud="false">
* encoding (σχετικών πάντα) ημερομηνιών και χρόνων μέσα στο κείμενο
  - δες _"sn1pp3ts - dates and times within text"_
* encoding αριθμών και μετρήσεων (βάρους, κ.λπ.) μέσα στο κείμενο
  - δες _"sn1pp3ts - numbers and measures within text"_
* annotation κομματιών που παρουσιάζουν ενδιαφέρον για επόμενη φάση encoding
  - δες _"sn1pp3ts - notes for 1st pass (mostly)"_
* ενσωμάτωση, §στο βασικό αρχείο, τελικών στοιχείων που θα μπουν στο "about"
  - να φτιάξουμε στο <back>(matter) ένα <div type="about"> που θα περιέχει το τελικό υλικό και τις αναφορές του που θα μπουν στα σχετικά τμήματα του tom sawyer site (οργανωμένα σε <div subtype="theAuthor">, <div subtype="theBook">, <div subtype="theEra">, κ.λπ.)
* να περάσουμε τα αντικείμενα
* να περάσουμε fauna + flora

## 1.2 Encoding and Feature Ideas for consideration
- _Tom trading (and work)_ -- great for "play"
- superstitions and religion
- techniques and arts (bad boys cub scout stuff)
- legal and crime
- racism ...
- weather etc.

# Our TEI Guidelines and Snippets

## 3.1 Paragraphs

**element types:**
- *phrase-level* must be contained within a paragraph (emphasized or quoted phrases, names, dates, etc.)
- *chunks* can appear between, but not within, paragraphs (bibliographic citations, notes, lists, etc.)
- *inter-level* can appear within a paragraph or between paragraphs (paragraph, anonymous block, and other)

-------

\<p> (paragraph) marks paragraphs in prose.

- for internal subdivision of paragraphs <s> (sentence type) or <seg> (segment) elements may be used
- usually paragraphs have no firm internal structure, but contain *prose* encoded as a mix of characters, entity references, phrases marked as described in this chapter, and *embedded elements* like lists, figures, or tables.

[UseCase][use <s> to mark any sentence we want to refer to]
[UseCase][use <seg> to mark any segment we want to refer to]



x-> single \<p>:

......
  <body>
    <p>I fully appreciate Gen. Pope's splendid achievements with their invaluable results; but you must know that Major Generalships in the Regular Army, are not as plenty as blackberries.</p>
  </body>
......

x-> short journalistic paragraphs:

......
  <head>SARAJEVO, Bosnia and Herzegovina, April 19</head>
    <p>Serbs seized more territory in this struggling new country today as the United States Air Force ended a two-day airlift of humanitarian aid into the capital, Sarajevo.</p>
    <p>International relief workers called on European Community nations to step up their humanitarian aid to the former Yugoslav republic, in conjunction with new American aid flights if necessary.</p>
    <p>A special envoy from the European Community, Colin Doyle, harshly condemned the decision by Serbs to shell Sarajevo on Saturday night during a visit to the Bosnian capital by a senior American official, Deputy Assistant Secretary of State Ralph R. Johnson.</p>
    <p>...</p>
......

x-> how other phrase level elements (ie <q>) may be nested:

......
  <p>A fly built a castle, a tall and mighty castle.
  There came to the castle the Crawling Louse. <q>Who,
  who's in the castle? Who, who's in your house?</q>
  said the Crawling Louse. <q>I, I, the Languishing Fly.
  And who art thou?</q>
  <q>I'm the Crawling Louse.</q>
  </p>
  <p>Then came to the castle the Leaping Flea. <q>Who,
  who's in the castle?</q> said the Leaping Flea. <q>I,
  I, the Languishing Fly, and I, the Crawling Louse. And
  who art thou?</q>
  <q>I'm the Leaping Flea.</q>
  </p>
  <p>Then came to the castle the Mischievous Mosquito.
  <q>Who, who's in the castle?</q> said the Mischievous
  Mosquito. <q>I, I, the Languishing Fly, and I, the
  Crawling Louse, and I, the Leaping Flea. And who art
  thou?</q>
  <q>I'm the Mischievous Mosquito.</q>
  </p>
......

## 3.3 Highlighting and Quotation

This section deals with [...] such features as underlining, italic fonts, or quotation marks, collectively referred to here as highlighting:
  - emphasis, foreign words and other linguistically distinct uses of highlighting
  - representation of speech and thought, quotation, etc.
  - technical terms, glosses, etc.


### 3.3.1 What Is Highlighting?

the use of any combination of typographic features (font, size, hue, etc.) in a printed or written text in order to distinguish some passage of a text from its surroundings [with] the purpose to generally draw reader's attention to some feature or characteristic of the passage highlighted. 

Highlighting is employed to identify words or phrases are one or more of following:

- *distinct* in some way—as foreign, dialectal, archaic, technical, etc.
- *emphatic* and which would for example be stressed when spoken
- *not part of the body of the text* (ie cross-ref, titles, headings, labels, etc.)
- identified with *distinct narrative stream* (ie internal monologue or commentary.)
- *attributed by the narrator to some other agency* (ie direct speech or quotation.)
- *set apart from text in some other way* (ie proverbs, editorial corrections, etc)

  
> Guidelines distinguish encoding of _rendering_ and of _underlying feature_

- Rendering may be encoded by using `rend`, `rendition`, or `style`. 
- Function can be encoded by selecting element described here or elsewhere in.
- Both rendering and feature/function can be encoded


[a] If encoder wishes to offer no interpretation of feature <hi> may be used

<hi> (highlighted) marks a word or phrase as graphically distinct from the surrounding text, for reasons concerning which no claim is made
  `rend` possible values are not formally defined in Guidelines (may be used to document the way given segment was rendered in the original source text)
  `style` (by contrast) defines the way the source text was rendered using a formally defined style language (such as W3C CSS)
  `rendition` (attribute) is used to point to fragments expressed using such a language predefined in TEI header using <rendition> (element

[b] Recommended that *feature* highlighted *be encoded* for the following reasons:
  - same kind of highlighting may be used for different purposes in other contexts
  - same textual function may be highlighted in different ways in different contexts
  - for analytic purposes (useful to know function than simply that it is distinct)


Distinction between <<model.emphLike>> and <<model.hiLike>> classes is typified by <hi> (typographically distinct) and <emph> (linguistically emphasized)


### 3.3.2 Emphasis, Foreign Words, and Unusual Language

This subsection discusses the following elements:
  <foreign> marks word/phrase as belonging to another language (than of text)
  <emph> marks words/phrases emphasized for linguistic or rhetorical effect
  <distinct> marks word/phrase regarded as linguistically distinct (ie archaic, technical, dialectal, non-preferred, etc.)

> These elements are all members of the model.emphLike class.


#### 3.3.2.1 Foreign Words or Expressions

**!!** 
Where there is no other applicable element, <foreign> may be used to provide a peg onto which the `xml:lang` may be attached.

......
  <q>Aren't you confusing <foreign xml:lang="la">post hoc</foreign> with <foreign xml:lang="la">propter hoc</foreign>?</q> said the Bee Master.
  <q>Wax-moth only succeed when weak bees let them in.</q>
......

<foreign> **should'nt be used** for foreign words mentioned or glossed within text (use elements from 3.3.4). Compare the following example sentences:

......
  - John eats a <foreign xml:lang="fr">croissant</foreign> every morning.
  - <mentioned xml:lang="fr">Croissant</mentioned> is difficult to pronounce with your mouth full.
  - A <term xml:lang="fr">croissant</term> is a crescent-shaped piece of light, buttery, pastry that is usually eaten for breakfast, especially in France.
......


n-> Elements which do not state language of their content by `xml:lang` inherit a value for it from their parent element. It is _recommended to supply default_ value for xml:lang on the root TEI or text element

> [UseCase][mark foreign words, language they belong to, and offer translation]

#### 3.3.2.2 Emphatic Words and Phrases

<emph> marks words / phrases which are linguistically emphatic or stressed (if only typographically ‘emphasized’ may be tagged with <hi>)
  `rend`, `rendition`, or `style` may describe examples which deviate from norm



x-> [a] If TEI header has default rendering for <emph> element:
  ......
  <q>Sex, sir, is <emph>purely</emph> a question
  of appetite!</q> Tarr exclaimed.
  <!-- no need to define styling info for <emph> -->
  ......

x-> [b] If no default defined for element, we may specify using `rend`: 
  ......
  <q>What does Chris <emph rend="italic">do in the morning?</emph></q>
  ......


x-> [c] If we wish to express rendition using -ie- CSS, then use the `style`:
  ......
  <q>What does Chris<emph style="font-style: italic">do in the morning?</emph></q>
  ......

x-> [d] More convenient to provide default value using <rendition> in header. 
  ......
    <!-- in the header we define <rendition> element... -->
  <rendition xml:id="italic" scheme="css">font-style: italic</rendition>
    <!-- in text somewhere we refer to <rendition> using @rendition ... -->
  <l>Here, great <name rendition="#italic">Anna</name>! whom Realms obey,</l>
  <l>Doth Counsel take — and sometimes <emph rendition="#italic">Tea</emph>.</l>
  ......

> [UseCase][define <rendition> styles in <teiHeader>, point to external "style names" table, and  use `@rendition` for elements]


-
  <hi> marks words / phrases highlighted, but for which identification of the intended distinction is difficult, controversial, or impossible. It allows  recording and possibly describing it by `rend`, `style`, or `rendition`, as discussed above, without taking a position about function of highlighting. 

  This may also be useful if the text is to be processed in two stages: representing simply typographic distinctions during a first pass, and then replacing the hi elements with more specific elements in a second pass.

> [UseCase][use to highlight words or phrases that will be encoded on 2nd pass]

x-> Some simple examples:
  <hi rend="gothic">And this Indenture further witnesseth</hi> that the said <hi rend="italic">Walter Shandy</hi>, merchant, in consideration of the said intended marriage ...
    n-> first <_hi_> uses gothic print to mimic legal document, and italic to mark Walter Shandy as a name. In _a second pass_, <head> or <label> might be appropriate for the first use, and <name> for the second
  <!-- 2nd example -->
  They often <hi rend="quoted">came down</hi> handsomely, and Scrooge did'nt
    n-> "came down" uses inverted commas to indicate a play on words. In a 2nd pass, the <soCalled> can be used to show that narrator is distancing himself from usage



#### 3.3.2.3 Other Linguistically Distinct Material

--
When we want to encode linguistic distinctiveness with more delicacy than allowed by <foreign>, we can use <distinct>
  
Its attributes allow linguistic distinction to be made in two ways: 
  - `@type` assigns user-defined code to word/phrase which assigns it to some register, sub-language, etc.
  - remaining three attributes are used to _place word / phrase on 3D scale_:
    - `@time` places word in time (archaic, old-fashioned, contemporary, futuristic, etc.)
    - `@space` places word diatopically (regional, international, etc)
    - `@social` places word diastatically (technical, polite, restricted, etc)

Examples:
......
  Next morning a boy in that dormitory confided to his bosom friend, a <distinct type="psSlang">fag</distinct> of Macrea's, that there was trouble in their midst which King <distinct type="archaic">would fain</distinct> keep secret.
<!-- using @type on previous example, and 3d scale on next example -->
  Next morning a boy in that dormitory confided to his bosom friend, a <distinct time="1900" space="GB" social="publicschool">fag</distinct> of Macrea's, that there was trouble in their midst which King <distinct time="archaic">would fain</distinct> keep secret.
......

> [UseCase][mark words / phrases that have cultural or similar interest to reader or other user]

### 3.3.3 Quotation

Section discusses the following elements, all of which are often rendered by the use of quotation marks:

<q> (quoted) contains material distinguished using quotation marks or similar method (ie - direct speech or thought, technical terms or jargon, authorial distance, quotations from elsewhere, and passages mentioned but not used.)

<said> indicates passages thought or spoken aloud, whether explicitly indicated in the source or not, whether directly or indirectly reported, whether by real people or fictional characters (words or phrases represented as being spoken or thought by people or characters within the current work).
  `@direct` used to indicate if quoted matter is direct or indirect speech
  `@aloud` used to indicate if quoted matter is vocalized or signed

<quote> (quotation) contains a phrase or passage attributed by the narrator or author to some agency external to the text (may be used for written passages cited from other works)
  `@source` provides a pointer to bibliographical source

<cit> (cited quotation) contains a quotation from some other document, together with a bibliographic reference to its source. In a dictionary it may contain an example text with at least one occurrence of the word form, used in the sense being described, or a translation of the headword, or an example.

<mentioned> marks words or phrases mentioned, not used (where a word or phrase is being discussed in the body of a text rather than forming part of the text directly).

<soCalled> contains a word or phrase for which the author or narrator indicates a disclaiming of responsibility, for example by the use of scare quotes or italics (for cases where the author or narrator distances him or herself from the words in question without however attributing them to any other voice in particular).


<said> and <q> share the following attribute:
  `@who` indicates person, or group of people, to whom content is ascribed

x-> example of `@who` within <said> elements:
  Adolphe se tourna vers lui:
  <said who="#Adolphe">— Alors, Albert,
   quoi de neuf?</said>
  <said who="#Albert">— Pas grand-chose.</said>
  <said who="#Robert">— Il fait beau,</said>
   dit Robert.
    <!-- ... elsewhere in the document -->
  <list type="speakers">
   <item xml:id="Adolphe"/>
   <item xml:id="Albert"/>
   <item xml:id="Robert"/>
  </list>

`@who` may be supplied whether or not an indication of the speaker is given explicitly in the text
  - It may take the form (as above) of a normalized form of the speaker's name, but its role is to act as a pointer to a location elsewhere in the text, or another document, where data about each speaker may be supplied. 
  - While `@who` can point to any source of info about speaker (available by a URI), most appropriate place is in <particDesc> (in TEI header). Otherwise we can use a simple list of speakers.
  - although terms speaker or participant are used, the same mechanisms may be used to characterize fictional personæ or ‘voices’ in a text

> [UseCase][use to mark, monologue, dialogue and thought, and assign each such segment to characters]

> [UseCase][list characters as <person> in <particDesc> -include <sex>, <age>, <trait>, <listEvent>, <figure>, <birth>, etc.]


x-> `@aloud` may also be used to distinguish speech from thought:

......
  <said aloud="true">Oh yes,</said> said Henry, 
  <said aloud="false">I mean Gordon Macrae, for example…</said>
  <said aloud="false">Jungian Analyst with Winebox! That's what you called him, you callous bastard, didn't you? Eh? Eh?</said>
......


Quotes may be embedded within quotes (ie one speaker quotes another):
......
  <said who="#Wilson">Spaulding, he came down into the office just this day eight weeks with this very paper in his hand, and he says:— <said who="#WilsonSpaulding">I wish to the Lord, Mr. Wilson, that I was a red-headed man.</said> </said> 
  <!-- ... -->
  <list type="speakers">
  <item xml:id="Wilson">Wilson</item>
  <item xml:id="WilsonSpaulding">Spaulding reported by Wilson</item>
  <!-- ...-->
  </list>
......


x-> <cit> can group quotation *and* bibliographic reference, for example:
  <div xml:id="mm01" type="chapter">
    <head>Chapter 1</head>
    <epigraph>
      <cit>
        <quote>
          <l>Since I can do no good because a woman</l>
          <l>Reach constantly at something that is near it.</l>
         </quote>
        <bibl>
          <title>The Maid's Tragedy</title>
          <author>Beaumont and Fletcher</author>
        </bibl>
      </cit>
    </epigraph>
    <p>Miss Brooke had that kind of beauty which seems to be thrown into relief by poor dress...</p>
   </div>

x-> <cit> in an example where simple cross-ref is provided:
  Lexicography has shown little sign of being affected by the work of followers of J.R. Firth, best summarized in his slogan, <cit> <quote>You shall know a word by the company it keeps.</quote> <ref>(Firth, 1957)</ref> </cit>

> [UseCase][use <cit> to mark passages or references from other sources -ie- from the "Good Book" in Tom Sawyer]


<soCalled> is provided for all cases in which quotation marks are used to distance the quoted text from the narrator or speaker (ie ‘scare’ quotes found in newspaper headlines and advertising copy where the effect is to cast doubts on the veracity of an assertion):

x-> examples (cast doubts, irony)
  <!-- cast doubts -->
  <head>PM dodges <soCalled>election threat</soCalled> in interview</head>
  <!-- irony -->
  He hated <soCalled>good</soCalled> books
  <!-- irony -->
  <soCalled>Croissants</soCalled> indeed! toast not good enough for you?
  <!-- irony -->
  Although Chomsky's decision that all NL sentences are finite objects was never justified by arguments from the attested properties of NLs, it did have a certain <soCalled>social</soCalled> justification. It was commonly assumed in works on logic until fairly recently that the notion <mentioned>language</mentioned> is necessarily restricted to finite strings.

> [UseCase][use <soCalled> to mark sarcasm, scare quotes, or other "distancing" from the narrator]


### 3.3.4 Terms, Glosses, Equivalents, and Descriptions

to provide gloss, other identification, or description of something. Terms are (often) italic or bold (on first mention); a gloss is sometimes given in quotation marks

<term> contains a single-word, multi-word, or symbolic designation which is regarded as a technical term (may appear with or without gloss)

<gloss> marks a phrase / word used to provide a gloss or definition for some other word or phrase (usually <term> or <mentioned>). It is linked to <term> via `@target` (term needs to have `@xml:id`):

x-> examples of <term> and <gloss>: 
  We may define <term xml:id="TDPv" rend="sc">discoursal point of view</term> as <gloss target="#TDPv">the relationship, expressed through discourse structure, between the implied author or some other addresser, and the fiction.</gloss>
  <!-- next example -->
  <gloss rend="unmarked" target="#PRSR">A computational device that infers structure from grammatical strings of words</gloss> is known as a <term xml:id="PRSR">parser</term>, and much of the history of NLP over the last 20 years has been occupied with the design of parsers.

> [UseCase][can use <term> + <gloss> where we want to explain / describe more of a technical word or phrase]


<mentioned> better used where words or phrases are simply being cited, discussed, or glossed in a text, as in the following example:
  There is thus a striking accentual difference between a verbal form like <mentioned xml:id="cw234" xml:lang="grc">eluthemen</mentioned> <gloss target="#cw234">we were released,</gloss> accented on the second syllable of the word, and its participial derivative <mentioned xml:id="cw235" xml:lang="grc">lutheis</mentioned> <gloss target="#cw235">released,</gloss> accented on the last.

> [UseCase][better use <mentioned> + <gloss> where we want to describe not necessarily technical words or phrases]


### 3.3.5 Some Further Examples

As a simple example of the elements discussed here, consider the following sentence:

    On the one hand the Nibelungenlied is associated with the new rise of romance of twelfth-century France, the romans d'antiquité, the romances of Chrétien de Troyes, and the German adaptations of these works by Heinrich van Veldeke, Hartmann von Aue, and Wolfram von Eschenbach.

1st approximation might be to record highlighted phrases:

......
  On the one hand the <hi rend="italic">Nibelungenlied</hi> is associated with the new rise of romance of twelfth-century France, the <hi xml:lang="fr" rend="italic">romans d'antiquité</hi>, the romances of Chrétien de Troyes, ...

  > This way we would lose distinction between italicized title and foreign phrase, so a retrieval program seeking to identify foreign terms (for example) would not be able to produce reliable results by simply looking for italicized words. 
......


2nd approximation would be to encode function _and_ appearance:

......
  On the one hand the <title rend="italic">Nibelungenlied</title> is associated with the new rise of romance of twelfth-century France, the <foreign rend="italic">romans d'antiquité</foreign>, the romances of Chrétien de Troyes, ...


As a less straightforward example, consider the use of italic font in the following passage:
  
.
  A pretty common case, I believe; in all *vehement* debatings. She says I am *too witty*; Anglicé, *too pert*; I, that she is too wise; that is to say, being likewise put into English, *not so young as she has been*: in short, she is grown so much into a *mother*, that she had forgotten she ever was a *daughter*. ...

- "vehement" is *emphasized*
- "not so young as she has been" is *proverbial*
- also provides an *ironic gloss* for the words "too wise", in the same way as "too pert" *glosses* "too witty"
- "mother" and "daughter" are italic to *oppose* them in the sentence
- "Anglicé" is not italic though not generally considered an English word

so, passage could be encoded as follows:

......
  A pretty common case, I believe; in all <emph>vehement</emph> debatings. She says I am <q rend="italic">too witty</q>; <foreign xml:lang="la" rend="roman">Anglicé</foreign>, <gloss rend="italic">too pert</gloss>; I, that she is <q rend="italic"> too wise</q>; that is to say, being likewise put into English, <gloss rend="italic">not so young as she has been</gloss>: in short, she is grown so much into a <hi rend="italic">mother</hi>, that she had forgotten she ever was a <hi rend="italic">daughter</hi>.

## 3.4 Simple Editorial Changes

The tags described in this section may be used to record editorial interventions, whether made by the encoder, by the editor of a printed edition used as a copy text, by earlier editors, or by the copyists of manuscripts.

...


Pairs or other groupings of elements can be wrapped within <choice>:

<choice> groups a number of alternative encodings for same point in a text. It enables representing -ie- a text in its ‘original’ unaltered form, alongside same text in one or more ‘edited’ forms. This permits switching between one ‘view’ of a text and another.

Elements which can be combined are <sic>, <corr>, <reg>, <orig>, <unclear>, <abbr>, <expan>, <ex>, <am> and <seg>


x-> conditional <choice> using and <seg>:
  …pressing 
  <choice>
    <seg type="platform" subtype="Mac">option</seg>
    <seg type="platform" subtype="PC">alt</seg>
  </choice>
  -f will …

> [UseCase][we can make generic choices using alternative <seg>]


Three categories of editorial intervention are discussed:

- indication / correction of apparent errors [3.4.1]
- indication of variant, irregular, non-standard, eccentric forms [3.4.2]
- editorial additions, suppressions, and omissions [3.4.3]

### 3.4.1 Apparent Errors

When copy text is manifestly faulty, an encoder may [a] elect simply to correct it without comment, although for scholarly purposes it will often be more generally useful to [b] record both the correction and the original state of the text.

(more -obviously- in full guidelines)


### 3.4.2 Regularization and Normalization

When the source text makes extensive use of variant forms or non-standard spellings, we may want to regularize it (give ‘standard’ or ‘regularized’ forms equivalent to non-standard forms)

Applications include *production of editions intended for student or lay readers*, linguistic research in which spelling or usage variation is not the main question at issue, *production of spelling dictionaries*, etc.

.
  <reg> (regularization) contains a reading which has been regularized or normalized in some sense.
  <orig> (original form) contains a reading which is marked as following the original, rather than being normalized or corrected.
  <choice> groups a number of alternative encodings for the same point in a text.

x-> Consider this 16th-century text:
  how godly a dede it is to overthrowe so wicked a race the world may judge: for my part I thinke there canot be a greater sacryfice to God.
......
[keep original spelling, but flag as nonstandard with __orig__:][]
  <p>...how godly a <orig>dede</orig> it is to <orig>overthrowe</orig> so wicked a race the world may judge: for my part I <orig>thinke</orig> there <orig>canot</orig> be a greater <orig>sacryfice</orig> to God</p>

[indicate that certain words have been modernized using __reg__:][]
  <p>...how godly a <reg>deed</reg> it is to <reg>overthrow</reg> so wicked a race the world may judge: for my part I <reg>think</reg> there <reg>cannot</reg> be a greater <reg>sacrifice</reg> to God.</p> 

[we may elect to record both old and new spellings][]
  <p>...how godly a <choice> <orig>dede</orig> <reg>deed</reg> </choice> it is to <choice> <orig>overthrowe</orig> <reg>overthrow</reg> </choice> so wicked a race the world may judge: for my part I <choice> <orig>thinke</orig> <reg>think</reg> </choice> there <choice> <orig>canot</orig> <reg>cannot</reg> </choice> be a greater <choice> <orig>sacryfice</orig> <reg>sacrifice</reg> </choice> to God.</p>
......

> [UseCase][keep original word, phrase or spelling, but also provide a more correct or understandable alternative]


`@resp` may be used to specify agency responsible for regularization


###### sn1pp3ts - words needing an extra layer of info
Process for marking slang, idiomatic, foreign, strange, term, abbreviated, incorrectly spelled, and such, words and phrases:
  
  --- 1st Pass ---
  1. Encoder would encode all such words & phrases using <orig resp="ed.Lena"> αρνάκι άσπορο και παχύ</orig> in first pass
  2. others encoders doing same work would have to do it [a] on different portions of text, [b] asynchronously, in own time slot, or [c] relying on git diff'ing and merging (along with other encoders). And would have to add own `@resp` (ie <orig resp="ed.Mao">)
  3. annotations and explanations can be added using 
    <orig resp"ed.EncoderName"><note type="temp" subtype="...">
  --- 2nd Pass ---
  4. Editor(s) working through 2nd pass can -depending on case- then choose one of following ---
    - if <orig> is what was meant, then insert <reg> and regularized value, and wrap the two (<orig> and <reg> in <choice>), with <reg> always **after** <orig>
    - if <orig> is not relevant, and <choice> can be used [a] choose the right replacement (ie <abbr>, <unclear>, <seg>, etc.), [b] insert the correct pair element (<expan>, <corr>, <seg>) **after** existing marked-up text, and [c] wrap within <choice>
    - some words or phrases marked with <orig> are done so as a convention ( keep 1st pass simple and quick). These are cases that should have been marked <term>, <foreign>, <distinct> (and perhaps other similar), and should be encoded correctly in 2nd pass. 
      > **Dependencies** may exist, and should be marked or -preferably- inserted for completeness / integrity. Most obvious example is that of the pair <term> + <gloss>. 
    - finally, some words or phrases marked as <orig> may actually have no particular reason to be so after closer inspection (ie "hookey" might be marked as older spelling but may still hold)
  --- Next Pass(es) ---
  5. depending on elements, element combinations, and values, we could help add more value to end user(s) by adding more content (ie notes) and/or context (ie attributes / links) 
    _\\further thought needed\\_



## 3.5 Names, Numbers, Dates, Abbreviations, and Addresses

> treatment of features here isn't exhaustive (see _chapter 13 Names, Dates, People, & Places_, & section _11.3.1.2 Abbreviation & Expansion_)




### 3.5.2 Addresses[](check some day -- now incomplete)


### 3.5.3 Numbers and Measures

elements provided for encoding of numbers and measurements:

<num> (number) contains a number, written in any form.
  `@type`  of value (1.cardinal; 2.ordinal; 3.fraction; 4.percentage)
  `@value` supplies the value of the number in standard form
  `@atLeast` gives minimum estimated value for approximate measurement
  `@atMost`  gives maximum estimated value for approximate measurement
<measure> contains word / phrase referring to some quantity of object or commodity (usually number, unit, and commodity name)
  `@type`  specifies the type of measurement in any convenient typology.
<measureGrp> contains a group of dimensional specifications which relate to the same object (ie height and width of a manuscript page)


Numbers can occur anywhere in a text and are special in that 
- they can be written with letters or digits (twenty-one, xxi, and 21)
- presentation is language-dependent (5th vs 5.; 3,456.78 vs 3.456,78)

x-> examples:
  <num value="33">xxxiii</num>
  <num type="cardinal" value="21">twenty-one</num>
  <num type="percentage" value="10">ten percent</num>
  <num type="percentage" value="10">10%</num>
  <num type="ordinal" value="5">5th</num>
  <num type="fraction" value="0.5">one half</num>
  <num type="fraction" value="0.5">1/2</num>

> [UseCase][normalize and/or extract numbers / values from text to use in tests, games, recipes, etc.]

_Sometimes_ we want to mark something as numerical which cannot be accurately normalized (ie "dozens"). To help in such situations, <num> may also bear either or both of `@atLeast` and `@atMost`

> [UseCase][get approximate calculations and use for various applications such as generated virtual maps]


<measure> can have number (`@quantity`), phrase expressing units of measure (`@unit`), and phrase expressing commodity (`@commodity`) being measured (not all components need be present).

we distinguish measures from surrounding text for two reasons: 
1. notation or system of abbreviations which we do not wish to regard as lexical
2. for quantitative application to distinguish and perform calculations on content

x-> example of 1st case (list of Celia's charms, not normalized):
......
  <div n="2">
    <list type="gloss">
      <!-- ... -->
      <label>Features</label>
      <item>Mobile</item>
      <label>Neck</label>
      <item>
        <measure>13¾"</measure>
      </item>
      <label>Upper arm</label>
      <item>
        <measure>11"</measure>
      </item>
    <!--...-->
    </list>
  <!-- ... -->
  </div>


example (mark representations of currency which may be misinterpreted as lexical):
  <p>...the sum of <measure type="currency">12s 6d</measure>...</p>


Normalization of measure requires specification of one or more of its three parts:
  `@quantity` gives number of specified units that comprise measurement
  `@unit`  indicates units used for measurement (usually standard symbol for units
    Suggested values: 1] m; 2] kg; 3] s; 4] Hz; 5] Pa; 6] Ω; 7] L; 8] t; 9] ha; 10] Å; 11] mL; 12] cm; 13] dB; 14] kbit; 15] Kibit; 16] kB; 17] KiB; 18] MB; 19] MiB
  `@commodity` indicates substance being measured

examples:
  <!-- list of Celia's charms, in normalized form -->
  <measure quantity="13.75" unit="in">13¾"</measure>
  <!-- representing historical data such as inventories: -->
  <list>
   <item>
    <measure
      type="volume"
      quantity="2"
      unit="bag"
      commodity="hops">ii bags hops</measure>
   </item>
   <item>
    <measure
      type="volume"
      quantity="6"
      unit="truss"
      commodity="cloth">six trusses Woolen and linen goods</measure>
   </item>
  </list>


<measureGrp> is provided as means of grouping related measurements together, either because measurement involves several dimensions (for example height and width) or to avoid the need to repeat all the normalizing attributes:
......
  <measureGrp type="volume" unit="in">
   <measure type="height" quantity="14">xiv</measure>
   <measure type="width" quantity="5">v</measure>
   <measure type="depth" quantity="10">x</measure>
  </measureGrp>


###### sn1pp3ts - numbers and measures within text

<number>
<measure>

- build / borrow a list of words and abbreviations to use in searching for possible numbers and measurements lurking in text (ie inch - in, foot - ft, yard - yd, furlong - fur, mile - mi, pint - pt, quart - qt, gallon - gal, ounces - oz, pound - lb, ton - tn, millimeter - mm, centimeter - cm, etc.)



### 3.5.4 Dates and Times

<date> contains a date in any format.
<time> contains a phrase defining a time of day in any format.

`@when`  supplies value of date or time in a standard form, e.g. yyyy-mm-dd
`@calendar` indicates system or calendar to which date of this element belongs


- _Partial dates or times_ (e.g. 1990, Sep. 1990, twelvish) can be expressed in `@when` by simply omitting part of value supplied. 
- _Imprecise dates or times_ (e.g. early August, some time after ten and before twelve) may be expressed as date or time ranges.

> [UseCase][great for marking and extracting normalized dates and times to be used in applications such as timelines, etc.]


n-> \\more about dates and times in "13 Names, Dates, People, and Places"\\
n-> \\where certainty (i.e. reliability) of date or time is in question, we should record using  mechanisms discussed in "21 Certainty, Precision, and Responsibility"\\

`@when` is useful way of normalizing or disambiguating dates and times which can appear in many formats, as the following examples show:
.......
  <date when="1980-02-12">12/2/1980</date>
  <!-- in prose -->
  <p>Given on the <date when="1977-06-12">Twelfth Day of June in the Year of Our Lord One Thousand Nine Hundred and Seventy-seven of the Republic the Two Hundredth and first and of the University the Eighty-Sixth.</date></p>
  <!-- more examples -->
  <date when="2001">The year 2001</date>
  <date when="2001-09">September 2001</date>
  <date when="2001-09-11">11 Sept 01</date>
  <date when="--09-11">9/11</date>
  <date when="--09">September</date>
  <date when="---11">Eleventh of the month</date>
  <time when="08:48:00">8:48</time>
  <date when="2001-09-11T12:48:00">Sept 11th, 12 minutes before 9 am</date>
    n-> \\last example could equally be tagged using <time> (with `@when`)\\
  <!-- example demonstrating <date> to mark a period of time -->
  <p>Those five years — <date from="1918" to="1923">1918 to 1923</date> — had been, he suspected, somehow very important.</p>
  <!-- another example demonstrating <date> to mark a period of time -->
  <p>The Eddic poems are preserved in a unique manuscript (Codex Regius 2365) from <date notBefore="1250" notAfter="1300">the second half of the thirteenth century</date>, and <title>Hervarar saga</title> dates from <date when="1300">around 1300</date>.</p>

###### sn1pp3ts - dates and times within text
- mark all temporal values on 1st pass with <date> or <time> regardless if they are dates or times
- then create tom sawyer calendar (later related to Adventures of Huck Finn)
- and -2nd pass- assign more precise dates and times

_later:_
evaluate attributes
`@n` | `@calendar` | `@when-iso` | `@notBefore-iso` | `@notAfter-iso` | `@from-iso` | `@to-iso` | `@unit` | `@quantity` | `@precision`| `@type` | `@subtype`

evaluate <offset> (marks that part of a relative temporal or spatial expression which indicates the direction of the offset between the two place names, dates, or times involved in the expression)

full and partial values (for `@when` and similar):
Date:                           2014-07-19
Combined date and time in UTC:  2014-07-19T23:05:09+00:00
                                2014-07-19T23:05:09Z
Week:                           2014-W29
Date with week number:          2014-W29-6
Ordinal date:                   2014-200
  _also_

<date when="1980-02-12">12/2/1980</date>
  <!-- in prose -->
  
"2001" -                            The year 2001
"2001-09"-                          September 2001
"2001-09-11" -                      11 Sept 01
"--09-11" -                         9/11
"--09" -                            September
"---11" -                           Eleventh of the month</date>
"08:48:00" -                        8:48
"2001-09-11T12:48:00" -             Sept 11th, 12 minutes before 9 am</date>
        
from="1918" to="1923" -             1918 to 1923
notBefore="1250" notAfter="1300" -  the second half of the thirteenth century
when="1300" -                       around 1300





### 3.5.5 Abbreviations and Their Expansions

<abbr> (abbreviation) contains an abbreviation of any sort.
<expan> (expansion) contains the expansion of an abbreviation.

x-> <abbr> distinguishing semi-lexical items such as acronyms or jargon:
.......
  We can sum up the above discussion as follows: the identity of a <abbr>CC</abbr> is defined by that calibration of values which motivates the elements of its <abbr>GSP</abbr>; ...
.......
  Every manufacturer of <abbr>3GL</abbr> or <abbr>4GL</abbr> languages is currently nailing on <abbr>OOP</abbr> extensions.


x-> `@type` attribute distinguishing <abbr> by function:
  <abbr type="title">Dr.</abbr>
  <abbr type="initial">M.</abbr> Deegan is the Director of the <abbr type="acronym">CTI</abbr> Centre for Textual Studies.

x-> Abbreviations such as Dr. M. above may be treated as two abbreviations, as above, or as one:
  <abbr>Dr. M.</abbr> Deegan is the Director of the <abbr>CTI</abbr> Centre for Textual Studies.

x-> using <expan> to record that abbreviation has been expanded by encoder, and combined with <abbr> inside <choice> to record both:
.......
  the <choice><expan>World Wide Web Consortium</expan><abbr>W3C</abbr></choice>
  <!-- Nested abbreviations may also be handled in this way: -->
  <choice>
   <abbr>RELAXNG</abbr>
   <expan>regular
     language for <choice>
     <abbr>XML</abbr>
     <expan>extensible markup
         language</expan>
    </choice>, next
     generation</expan>
  </choice>

n-> \\A more detailed set of recommendations is discussed in 11.3.1 Altered, Corrected, and Erroneous Texts, which includes additional elements made available for the purpose by the transcr module.\\

> [UseCase][useful for marking abbreviations -by type moreover- and their full expanded forms]

## 3.6 Simple Links and Cross-References

Cross-references or links between a location in document and one or more other locations, either in the same or different XML documents, may be encoded using <ptr> and <ref>. These elements both ‘point’ _from_ the place that the element itself appears, _to_ another or several, specified by means of `@target`:

`@target` specifies destination of reference by supplying one or more URI References


n-> \\Linkages of other kinds can be further examined in "16 Linking, Segmentation, and Alignment"\\

value of `@target` provides a way of pointing to another element using the XPointer mechanism (standardized by W3C). This permits from simple (reference to value of target xml:id attribute) to the complex (full URI with embedded XPointers).

For example, the source of the following paragraph looks something like this:
......
  <p>...
    The complete XPointer specification is managed by the W3C
      <note place="foot">
        <ptr target="http://www.w3.org/TR/xptr-framework/"/>,
        <ptr target="http://www.w3.org/TR/xptr-element/"/>,
        <ptr target="http://www.w3.org/TR/xptr-xmlns/"/>, and
        <ptr target="http://www.w3.org/TR/xptr-xpointer/#xpointer(id('chum'))"/>
      </note>;
      for a discussion of TEI schemes for XPointer, see
      <ptr target="#eSATS"/>.
  </p>
  <!--... -->
  <div xml:id="eSATS">
  <!--... -->
  </div>

If no explicit link is to be encoded <ref> may be used _without_ `@target`

> [UseCase][use <ref> with no explicit link to mark words or phrases of further interest, that may be touched upon again at a later stage]


__For an introduction__ to the use of links in general, see 16 Linking, Segmentation, and Alignment.

<ptr/> (pointer) defines pointer to another location (<ptr/> is empty)
<ref> (reference) to another location, usually has additional text or comment

typical attributes:
`@target` specifies destination of reference by one or more URI References
`@evaluate` specifies intended meaning when target of pointer is also pointer

`@cRef` specifies destination of pointer by supplying _canonical reference_ expressed using scheme defined in <refsDecl> in TEI header. It is an **error** to supply both <cRef> and <target>

`@type` characterizes element using any classification scheme or typology
`@subtype` provides a sub-categorization of the element, if needed

`@mimeType` (MIME media type) specifies MIME media type

<ref> may contain phrases specifying or describing the target of a cross-reference, and since its content is human-readable, it need not (necessarily)identify its target in any other way. 

x-> examples without and with `@target`, both <ref> and <ptr/>:
  See <ref>section 12 on page 34</ref>.
  See <ref target="#SEC12">section 12 on page 34</ref>
  See in particular <ptr target="#SEC12"/>
  <!-- ... -->
  <div1 xml:id="SEC12">
  <!-- ... -->
  </div1>

When `@target` is used, cross ref may point to many locations simultaneously, by giving more than one identifier, such as in following (indexing) example:
.......
  <list>
    <item>Saints aid rejected in mel. <ptr target="#p299"/> </item>
    <item>Sallets censured <ptr target="#p143 #p144"/> </item>
    <item>Sanguine mel. signs <ptr target="#p263"/> </item>
    <item>Scilla or sea onyon, a purger of mel. <ptr target="#p442"/> </item>
  </list>
  <!-- targets (page breaks) -->
  <pb xml:id="p143"/>
   ...
  <pb xml:id="p144"/>
   ...
  <pb xml:id="p263"/>
   ...
  <pb xml:id="p299"/>
   ...
  <pb xml:id="p442"/>
   ...

> [UseCase][using `@target` we can point to multiple references instead of just one]

x-> example with <ref> of sigla:
  annotated text <ref target="#a51" type="noteAnchor">⁵¹</ref>
  <!-- ... -->
  <note xml:id="a51" type="footnote">text of annotation</note>

> [UseCase][define different types and/or "positions" of notes depending on `@type` of <ref>, ie footnotes, endnotes, margin notes, bibl, etc]

x-> example using `@type` to categorize cross-reference:
......
  Similar forms, often called rewriting systems, have a long history among mathematicians, but the specific form of <ptr target="#fig22"/> was first studied extensively by Chomsky <ptr type="bibliog" target="#chom59"/>.
  <!-- ... -->
  <figure xml:id="fig22">
   <graphic url="fig22.jpg"/>
  </figure>
  <!-- elsewhere, in the bibliography -->
  <bibl xml:id="chom59">
  <!-- citation for the book referenced above -->
  </bibl>
  .....
  n-> "bibliog" for `@type` on 2nd <ptr> indicates that object referenced is bibliographic entry rather than cross-ref to illustration, as in 1st <ptr>



<ptr> and <ref> have many applications in conjunction with analytic tools discussed in chapters 16, 17, and 18. They may be used to link analyses of a text to their object, combine corresponding segments of text, or align segments of a text with a temporal or other axis or with each other.

When `@target` points to external resource available on network, `@mimeType` may be used as this may be important for appropriate processing.

x-> example of `@mimeType`:
  <p>The current version of the TEI Guidelines source code is available in the TEI Sourceforge Repository; <ref target="http://sourceforge.net/p/tei/code/HEAD/tree/trunk/P5/Source/guidelines-en.xml" mimeType="application/tei+xml">guidelines-en.xml</ref> is the root document used to create the English version of the Guidelines.</p>

> [UseCase][help applications prepare correct type of processing / handling for different `@mimeType`]


## 3.7 Lists

<list> (list) contains any sequence of items organized as a list.
<item> contains one component of a list.
<label> for identifying part of text, typically (not only) in list or glossary
<head> contains heading, (ie title of section, heading of list, glossary, etc)
<headLabel> contains heading for label or term column in gloss or similar list
<headItem> contains heading for item or gloss column in a gloss or similar list


<list> should be used to mark any kind of list: numbered, lettered, bulleted, or unmarked, and lists given as run-on text.

If an enumerator is retained in text, it may be done by using `@n` on <item>, _or_ by using <label>. 

x->The following examples are thus equivalent:
  <!-- using <label> -->
  I will add two facts, which have seldom occurred in the composition of six, or even five quartos.
  <list rend="runon" type="ordered">
    <label>(1)</label>
    <item>My first rough manuscript, without any intermediate copy, has been sent to the press.</item>
    <label>(2)</label>
    <item>Not a sheet has been seen by any human eyes, excepting those of the author and the printer: the faults and the merits are exclusively my own.</item>
  </list>
  <!-- using @n -->
  I will add two facts, which have seldom occurred in the composition of six, or even five quartos.
  <list rend="runon" type="ordered">
    <item n="1">My first rough manuscript, without any intermediate copy, has been sent to the press.</item>
    <item n="2">Not a sheet has been seen by any human eyes, excepting those of the author and the printer: the faults and the merits are exclusively my own.</item>
  </list>
  n-> The two styles may not be mixed in the same list


x-> a list not in list format (simply printed as a single paragraph):
  <p>On those remote pages it is written that animals are divided into 
    <list>
      <item n="a">those that belong to the Emperor, </item>
      <item n="b">embalmed ones, </item>
      <item n="c">those that are trained, </item>
      <item n="d">suckling pigs, </item>
      <item n="e">mermaids, </item>
      <item n="f">fabulous ones, </item>
      <item n="g">stray dogs, </item>
      <item n="h">those that are included in this classification, </item>
      <item n="i">those that tremble as if they were mad, </item>
      <item n="j">innumerable ones, </item>
      <item n="k">those drawn with a very fine camel's-hair brush, </item>
      <item n="l">others, </item>
      <item n="m">those that have just broken a flower vase, </item>
      <item n="n">those that resemble flies from a distance. </item>
    </list>
  </p>

x-> list with <head> and use of <label> to mark tabular (glossary) list:
  <list type="gloss">
  <head>Report of the conduct and progress of Ernest Pontifex. Upper Vth form — half term ending Midsummer 1851</head>
    <label>Classics</label>
    <item>Idle listless and unimproving</item>
    <label>Mathematics</label>
    <item>ditto</item>
    <label>Divinity</label>
    <item>ditto</item>
    <label>Conduct in house</label>
    <item>Orderly</item>
    <label>General conduct</label>
    <item>Not satisfactory, on account of his great unpunctuality and inattention to duties</item>
  </list>
  n-> In such a list, the individual items have internal structure. 

In complex cases, where list items contain many components, the list is better treated as a table (14 Tables, Formulæ, Graphics and Notated Music)

An important two-column table is ‘glossary list’, marked as <list type="gloss">(semantic error for it not to have labels). For example:
<list type="gloss">
  <head>Unit Three — Vocabulary</head>
    <label xml:lang="la">acerbus, -a, -um </label>
    <item>bitter, harsh</item>
    <label xml:lang="la">ager, agrī, M. </label>
    <item>field</item>
    <label xml:lang="la">audiō, īre,
    īvī, ītus </label>
    <item>hear, listen (to)</item>
    <label xml:lang="la">bellum, -ī, N. </label>
    <item>war</item>
    <label xml:lang="la">bonus, -a, -um </label>
    <item>good</item>
</list>

Additionally, <term> and <gloss> may be used to make explicit the role that each column in the glossary list has, as follows:
  <list type="gloss">
    <head>Unit Three — Vocabulary</head>
      <label>
        <term xml:lang="la">acerbus, -a, -um</term>
      </label>
      <item>
        <gloss>bitter, harsh</gloss>
      </item>
      <label>
        <term xml:lang="la">ager, agrī, M. </term>
      </label>
      <item>
        <gloss>field</gloss>
      </item>
      <label>
        <term xml:lang="la">audiō, -īre, -īvī, -ītus</term>
      </label>
      <item>
        <gloss>hear, listen (to)</gloss>
      </item>
      <label>
        <term xml:lang="la">bellum, -ī, N. </term>
      </label>
      <item>
        <gloss>war</gloss>
      </item>
      <label>
        <term xml:lang="la">bonus, -a, -um</term>
      </label>
      <item>
        <gloss>good</gloss>
      </item>
  </list>
  n-> in above examples `@xml:lang` specifies language of <label> or <term>


In addition to <head> used as title for whole list, headings for two columns of a glossary-style list may be given via <headLabel> and <headItem>:
  <p>
    The simple, straightforward statement of an idea is preferable to the use of a worn-out expression.
    <list type="gloss">
      <headLabel>TRITE</headLabel>
        <headItem>SIMPLE, STRAIGHTFORWARD</headItem>
          <label>bury the hatchet </label>
          <item>stop fighting, make peace</item>
          <label>at loose ends </label>
          <item>disorganized</item>
          <label>on speaking terms </label>
          <item>friendly</item>
          <label>fair and square </label>
          <item>completely honest</item>
          <label>at death's door </label>
          <item>near death</item>
    </list>
  </p>

<label>, <head>, <headLabel>, and <headItem> may contain **only** phrase-level elements. The <item> element **however** may contain paragraphs or other ‘chunks’, including other lists.
......
  x-> glossary list with two items, each of which is itself a simple list:
  <list type="gloss">
    <label>EVIL</label>
    <item>
      <list type="simple">
        <item>I am cast upon a horrible desolate island, void of all hope of recovery.</item>
        <item>I am singled out and separated as it were from all the world to be miserable.</item>
        <item>I am divided from mankind — a solitaire; one banished from human society.</item>
      </list>
    </item>
    <label>GOOD</label>
    <item>
      <list type="simple">
        <item>But I am alive; and not drowned, as all my ship's company were.</item>
        <item>But I am singled out, too, from all the ship's crew, to be spared from death...</item>
        <item>But I am not starved, and perishing on a barren place, affording no sustenances....</item>
      </list>
    </item>
  </list>
  n-> Lists of different types may be nested to arbitrary depths in this way.

----

## 3.8 Notes, Annotation, and Indexing 

### 3.8.1 Notes and Simple Annotation

<note> contains any additional comment found in a text, marked in some way as being out of the main textual stream [...] whether they appear as block notes in the main text area, at the foot of the page, at the end of the chapter or volume, in the margin, or in some other place.
  n-> \\point of attachment: where (if) note is attached to specific point or span within a text\\

For ease of processing, it may be adequate to:
- position marginal notes before the relevant paragraph or other element
- group notes at foot of page on which points of attachment are (not generally recommended since pagination is unlikely to be of structural significance)
- may be desirable to transcribe notes at point of appearance, (ie end of volume, end of chapter). The `@target` of <note> indicates point of attachment 
- also possible to encode the point of attachment itself, using the <ptr/> or <ref> element, pointing from that to the body of the <note> placed elsewhere.

In cases where the note is applied not to a point but to a span of text, not itself represented as a TEI element, the target attribute may use an appropriate pointer expression, for example using the _range()_ function to specify the span of attachment.


example: <note> is attached to <l>

<l>The self-same moment I could pray</l>
<l>And from my neck so free</l>
<l>The albatross fell off, and sank</l>
<l>Like lead into the sea. 
  <note type="gloss" place="margin">The spell begins to break</note>
</l>

example: __note__ is attached to __lg__

<lg>
  <l>The self-same moment I could pray</l>
  <l>And from my neck so free</l>
  <l>The albatross fell off, and sank</l>
  <l>Like lead into the sea.</l>
    <note type="gloss" place="margin">The spell begins to break</note>
</lg>

in previous example we could also use __label__, if it really is some sort of heading or descriptive label

example: a note which appears at the foot of the page in the printed source is given at its point of attachment within the text. 
_@n_ is used to indicate the note number:

<foo>
  Collections are ensembles of distinct entities or objects of any sort.
    <note n="1" place="bottom">We explain below why we use the uncommon term collection instead of the expected set.</note> 
  The elements ..
</foo>


__Transcribing vs adding own notes:__

advisable to distinguish two categories, either using _type_ (authorial, editorial, etc.), and/or _resp_ (definition of person or other agency responsible for the content of the note)

###### sn1pp3ts - notes for 1st pass (mostly)
>(check if Oxygen offers snippets or triggers - or kbmaestro?)

0. probably use `@ana` with tags list in header or in some arbitrary <list>
1. <element>here appears some sort of content <note place="foot | margin | endOfChap | endOfBook | adjacent"> this is a note </note> </element>
2. <element>here appears some sort of content <note type="" @subtype=""> this is a note of type and suptype --- good to build a nice typo-subtypo-logy of notes</note> </element>
3. <element>here appears some sort of content <note rendition="bubbleCloud | emphStrong | ... "> this is a note </note>  </element>
  n-> \\ `@place`, `@type` and `@subtype`, `@rendition` can be used for slicing and dicing notes along different axes
4. <element>here appears some sort content <note resp="#authorA | #editorA | #editorB | ..."> good way to mark the "creator" of any note, regardless if it is an author, an editor -of any type-, or an individual in the future  </note> </element>
  n-> \\ new @resp (at least for notes) could be populated automatically via script depending on who commits to git. *Or* by snippet with default `@resp` and it's value
5. <element>here appears some sort of content <note xml:id="wtf"> this is a note with a unique (xml) id </note> </element>
6. <note> can -naturally- use `@n`, `@corresp`, `@next`, `@prev`, `@source`, `@ana`, `@target`, and a few more
7. <note> can -naturally- combine attributes
8. <note> can contain <note>nested note</note> within it</note>





### 3.8.2 Index Entries

role of index is to _provide access via keywords and phrases_ which are not necessarily present in the text itself, but must be added by indexer

> we only look at created by us (ie not ready made) indices

example: single headword is supplied by <term> contained by an <index>:

<ab>
  The students understand procedures for Arabic lemmatisation 
    <index><term>Lemmatization, Arabic</term></index>
  and are beginning to build parsers.
</ab>

- The effect of this is to document index entry for term ‘Lemmatization, Arabic’, which when processed could reference location of original __index__ element



## 3.10 Reference Systems

system by which names or references are associated with particular passages of a text (e.g. Ps. 23:3 or Amores 2.10.7 for Ovid's Amores, book 2, poem 10, line 7)


Such names make it possible to mark a place within a text and enable other readers to find it again. 

System may be based on 
- _(a)_ structural (chapters, paragraphs, sentences; stanza and verse), 
- _(b)_ typographic units (page and line numbers), or 
- _(c)_ divisions created specifically (chapter and verse in Biblical texts)

_Reference systems may be recorded in any of the following ways:_

- system exists, and based on same logical structure as that of the text's markup, reference for passage may be recorded as _xml:id_ or _n_, or may be constructed by combining attribute values from several levels of tags

- no pre-existing system, _xml:id_ or _n_ may be used to construct one (e.g. collections and corpora created in electronic form)

- system exists, but not based on same logical structure as that of the text's markup (described in chapter 20).

- system exists, but does not correspond to particular logical structure, or where the logical structure concerned is of no interest to encoder, then references may be encoded by means of <milestone/> elements
  `@unit` has following enumerated values by default: 1] page; 2] column; 3] line; 4] book; 5] poem; 6] canto; 7] speaker; 8] stanza; 9] act; 10] _scene_; 11] section; 12] absent; 13] unnumbered

When text has no pre-existing system, we _recommend that at least the page boundaries_ of the source text be marked using one of the above methods


###### sn1pp3ts - scenes and their info

1. every scene beginning (incl. 1st scene for each chapter), will be marked with <milestone/>, rather than contained in <div> elements
2. the <milestone/> (empty) element has attribute `@unit` with enumerated values, one of which is "scene". So <milestone unit="scene"/> is a default
3. we can assign a title to the scene using `@n`, like in the following example: <milestone n="Tom gets his tooth pulled out" unit="scene"/>. It is probably best to place `@n` as first attribute in order to see it's value in outline view of Oxygen
4. `@type` and `@subtype` can be used as attributes, but it is probably easier to employ just the latter, filling in the value that best characterizes the scene (or chapter, act, etc. for that matter). Values could be "transition", "revelation", and more (check "Scene Typology" below).
  - it is *not* necessary to classify scene (sub)type during 1st pass
5. each scene (beggining) should be arbitrarily addressable, so it's important that it has a unique `@xml:id` for example <milestone xml:id="ch17sc2"/>
6. So, a *full* marking of a scene beggining should be something like this: 
  <milestone n="Tom runs away" subtype="escape" xml:id="ch6sc3" unit="scene"/>


**Scene Typology** (ie from [the script lab][http://thescriptlab.com/screenwriting/structure/the-scene/16-types-of-scenes]):
    1. Setting - Where are we?
    2. Atmosphere/Mood - What is it like there?
    3. Introduction - Who is it we are dealing with here?
    4. Exposition - Necessary information. Quick and Clever. 
    5. Transition - getting from one place to another. Fast.
    6. Preparation - What will it take to prepare for the task at hand?
    7. Aftermath - How does the character feel about what just happened?
    8. Investigation - Gathering information.
    9. Revelation - The reader/audience finds out something important.
    10. Recognition - The character finds out something important.
    11. The Gift - Using a prop with emotional investment and turning it into a weapon, emotional or otherwise. 
    12. Escape - The character is trying to get away, avoid, or hide.
    13. Pursuit - The character is trying to follow, capture, or secure.
    14. Seduction - Someone must convince someone else.
    15. Opposites - Two characters from seemingly opposite poles are forced together.
    16. Reversal of Expectations - A character expects a certain, very clear outcome, but another character surprises him, influencing him to reverse his intention and do something else - practically the opposite of what he planned to do.
    17. Unexpected Visitor - Someone unexpected shows up. Problems arise.




# 4 Default Text Structure

default high-level structure for (single) TEI document (in <TEI>):
- metadata describing it, represented by <teiHeader>
- the document itself, represented by <text>

<teiCorpus> consists of one or more complete <TEI>, each with <teiHeader> and <text> which itself carries <teiHeader>. This permits us to distinguish metadata for whole collection of texts, from that of each <TEI> within corpus. 

elements available for representation of outermost structure of TEI document:

<TEI> (TEI document) contains a single TEI-conformant document
<teiCorpus> contains the whole of a TEI encoded corpus
<teiHeader> supplies descriptive and declarative info (see chapter 2)
<text> contains single text (unitary, composite, poem or drama, collection of essays, a novel, a dictionary, or a corpus sample)

TEI document may also contain elements such as a collection of facsimile images, or a feature system declaration

[Use Case][include images from original book, including pages themselves]


Structure of <text>, unitary or composite, is defined by following elements:

<front> (front matter) prefatory matter (headers, title page, prefaces, dedications, etc.) found at the start of a document, before the main body.
<body> (text body) whole body of single unitary text, excluding front or back
<group> body of _composite_ text, grouping together sequence of distinct texts (or groups of such texts) which are regarded as a unit for some purpose, for example the collected works of an author, a sequence of prose essays, etc.
<back> (back matter) appendixes, etc. following the main part of a text

x-> structure of unitary text:
<TEI xmlns="http://www.tei-c.org/ns/1.0">
  <teiHeader>
  <!-- .... -->
  </teiHeader>
  <text>
    <front>
    <!-- front matter of copy text, if any, goes here -->
    </front>
    <body>
    <!-- body of copy text goes here -->
    </body>
    <back>
    <!-- back matter of copy text, if any, goes here -->
    </back>
  </text>
</TEI>

x-> structure of composite text made up of two unitary texts:
<TEI xmlns="http://www.tei-c.org/ns/1.0">
  <teiHeader>
  <!-- .... -->
  </teiHeader>
  <text>
    <front>
    <!-- front matter for composite text -->
    </front>
      <group>
        <text>
          <front>
          <!-- front matter of first unitary text, if any -->
          </front>
          <body>
          <!-- body of first unitary text -->
          </body>
          <back>
          <!-- back matter of first unitary text, if any -->
          </back>
        </text>
        <text>
          <body>
          <!-- body of second unitary text -->
          </body>
        </text>
      </group>
    <back>
    <!-- back matter for composite text, if any -->
    </back>
  </text>
</TEI>

<floatingText> is for cases where a text is embedded within another, but does not contribute to its hierarchical organization, ie because it interrupts it, or is quoted within it (ie ‘play within a play’ or narrative interrupted by other multiple narratives).

## 4.1 Divisions of the Body

In some cases, <body> contains _simple sequence_ of low-level structural items (components or component-level elements such as paragraphs or lists, speeches and stage directions, dictionary entries etc).

In other cases _sequences of such elements are grouped hierarchically_ into textual divisions and subdivisions, such as chapters or sections. Names used for such subdivisions vary (ie 'book' in Bible, ‘part’ or ‘section’ in a report, 'chapter' in a novel, 'acts' and 'scenes' in play, etc.)

Guidelines propose that such divisions be organized using same neutrally named elements, and `@type` used to categorize them independently of hierarchic level

Two styles are provided for marking neutral divisions:
- __Numbered divisions__ -  named <div1>, <div2>, etc., where number indicates depth of particular division within hierarchy
- __Un-numbered divisions__ named <div> are nested recursively and indicate their hierarchic depth

n-> The two styles cannot be combined within single <front>, <body>, or <back>


### 4.1.1 Un-numbered Divisions

<div>..</div> contains subdivision of <front>, <body>, or <back> of <text>

`@type` characterizes element using any convenient scheme or typology
`@subtype` provides a sub-categorization of the element, if needed

x-> <body> of <text> containing two parts, each composed of two chapters:
  <body>
    <div type="part" n="1">
      <div type="chapter" n="1">
      <!-- text of part 1, chapter 1 -->
      </div>
      <div type="chapter" n="2">
      <!-- text of part 1, chapter 2 -->
      </div>
    </div>
    <div type="part" n="2">
      <div n="1" type="chapter">
      <!-- text of part 2, chapter 1 -->
      </div>
      <div n="2" type="chapter">
      <!-- text of part 2, chapter 2 -->
      </div>
    </div>
  </body>

### 4.1.2 Numbered Divisions

**not going to use these**


### 4.1.3 Numbered or Un-numbered?

Whichever style is used, `@n` and `@xml:id` attributes may be used to provide reference strings or labels for each division of a text, where appropriate. 

Also `@type` and `@subtype` may be used to provide name or description for the division (ie ‘book’, ‘chapter’, ‘section’, ‘part’, ‘canto’, ‘stanza’, ‘act’, ‘scene’, etc.). 

As an alternative or complement to using `@type` to characterize neutrally named <div>, the modification mechanisms ("23.3 Personalization and Customization") may be used to define new elements (ie <chapter>, <part>, etc.) 
x-> customization with new element <diaryEntry> added to model.divLike class:
<body>
  <my:diaryEntry type="entry" n="1">
    <my:diaryEntry type="morning" n="1.1">
      <p>....</p>
    </my:diaryEntry>
    <my:diaryEntry type="afternoon" n="1.2">
      <p>....</p>
    </my:diaryEntry>
  </my:diaryEntry>
  <my:diaryEntry type="entry" n="1">
    <my:diaryEntry type="morning" n="1.1">
      <p>....</p>
    </my:diaryEntry>
    <my:diaryEntry type="afternoon" n="1.2">
      <p>....</p>
    </my:diaryEntry>
  </my:diaryEntry>
  <!-- ...-->
</body>

### 4.1.4 Partial and Composite Divisions

**not going to use this**

## 4.2 Elements Common to All Divisions

TEI defines following elements (in five classes):

<opener> groups <dateline>, <byline>, <salutation>, etc. and similar phrases appearing as preliminary group at start of a division, especially of a letter.
<signed> (signature) contains closing salutation, etc., appended to foreword, dedicatory epistle, or other division of a text.

<closer> groups salutations, datelines, and similar phrases appearing as a final group at the end of a division, especially of a letter.
<postscript> contains a postscript, e.g. to a letter.
<signed> (signature) contains closing salutation, etc., appended to foreword, dedicatory epistle, or other division of a text.
<trailer> contains closing title or footer appearing at end of division of text

<argument> contains list or prose description of topics in subdivision of text
<byline> contains primary statement of responsibility given for a work on its title page or at the head or end of the work.
<dateline> contains brief description of place, date, time, etc. of production (ie letter, newspaper story, etc.), prefixed or suffixed to it as a kind of heading or trailer.
<docAuthor> (document author) contains the name of the author of the document, as given on the title page (often but not always contained in a byline).
<docDate> (document date) contains the date of a document, as given on a title page or in a dateline.
<epigraph> contains a quotation, anonymous or attributed, appearing at the start or end of a section or on a title page.
<meeting> contains formalized descriptive title for meeting or conference, for use in bibl for an item derived from such a meeting
<salute> contains salutation prefixed to a foreword, dedicatory epistle, or other division of a text, or salutation in closing of a letter, preface, etc.

### 4.2.1 Headings and Trailers

<head> is used to identify a heading prefixed to the start of any textual division, at any level. 

x-> A given division may contain more than one such element:
<div1 n="Etym">
  <head>Etymology</head>
  <head>(Supplied by a late consumptive usher to a grammar school)</head>
  <p>The pale Usher — threadbare in coat, heart, body and brain; I see him now. He was ever dusting his old lexicons and grammars, ...</p>
</div1>

Unlike other markup schemes, TEI does not require that headings attached to subdivisions at different levels have different identifiers:
- all kinds of heading are marked identically using <head>
- type or level is implied by parent of <head> (ie <div2>, <div>, or any member of the <<model.listLike>> class)

x-> lead story and headlines as <div> with <<model.divTop>> elements attached:
  <div type="story">
    <head rend="underlined" type="sub">President pledges safeguards for 2,400 British troops in Bosnia</head>
    <head rend="scream" type="main">Major agrees to enforced no-fly zone</head>
    <byline>By George Jones, Political Editor, in Washington</byline>
    <p>Greater Western intervention in the conflict in former Yugoslavia was pledged by President Bush ...</p>
  </div>
 
x-> <trailer> marks any heading-like feature and appears only at end of div:
<div type="book" n="I">
  <!-- ... -->
  <div>
    <head>In the name of Christ here begins Book I of the history.</head>
    <p>Proposing as I do ...</p>
    <p>From the Passion of our Lord until the death of Saint Martin four hundred and twelve years passed.</p>
    <trailer>Here ends the first Book, which covers five thousand, five hundred and ninety-six years from the beginning of the world down to the death of Saint Martin.</trailer>
  </div>
</div>

### 4.2.2 Openers and Closers

**will not use for the time being**


### 4.2.3 Arguments, Epigraphs, and Postscripts

<argument> may be used to encode prefatory list or paragraph of topics 

x-> encoding the same <argument>:
  <div type="chap" n="6">
    <argument>
      <p>Kingston — Instructive remarks on early English history
      — Instructive observations on carved oak and life in general
      — Sad case of Stivvings, junior 
      — Musings on antiquity
      — I forget that I am steering 
      — Interesting result
      — Hampton Court Maze 
      — Harris as a guide.</p>
    </argument>
    <p>It was a glorious morning, late spring or early summer, as you care to take it ...</p>
  </div>
<!-- list + item -->
  <div type="chap" n="6">
    <argument>
      <list type="inline">
        <item>Kingston</item>
        <item>Instructive remarks on early English history</item>
        <item>Instructive observations on carved oak and life in general</item>
        <item>Sad case of Stivvings, junior</item>
        <item>Musings on antiquity</item>
        <item>I forget that I am steering</item>
        <item>Interesting result</item>
        <item>Hampton Court Maze</item>
        <item>Harris as a guide.</item>
      </list>
    </argument>
    <p>It was a glorious morning, late spring or early summer, as you care to take it ...</p>
  </div>


<epigraph> is a quotation from some other work, a saying, or a motto, appearing on a title page, or at the start of a division:
  <titlePage>
    <docAuthor>E. M. Forster</docAuthor>
    <docTitle>
      <titlePart>Howards End</titlePart>
    </docTitle>
    <epigraph>
      <q>Only connect...</q>
    </epigraph>
  </titlePage>
  <!-- <epigraph> with <quote> -->
  <div n="19" type="chap">
    <head>Chapter 19</head>
    <epigraph>
      <cit>
        <quote>I pity the man who can travel from Dan to Beersheba, and say <q>'Tis all barren;</q> and so is all the world to him who will not cultivate the fruits it offers. </quote>
        <bibl>Sterne: Sentimental Journey.</bibl>
      </cit>
    </epigraph>
    <p>To say that Deronda was romantic would be to misrepresent him: but under his calm and somewhat self-repressed exterior ...</p>
  </div>


<postscript> is a passage added after the signature of a letter or, less frequently, the main portion of the body of a book, article, or essay:
  <div type="letter">
    <opener>
    <!--  -->
    </opener>
      <p>...</p>
    <closer>
    <!--  -->
    </closer>
    <postscript>
      <label>P.S.</label>
      <p>I have Mollases, Sugar,
      <lb/>Coffee &amp; Rum, which
      <lb/>will Exchange with you
      <lb/>for Candles or Oyl</p>
    </postscript>
  </div>

## 4.3 Grouped and Floating Texts

<group> contains body of composite text, grouping a sequence of distinct texts regarded as a unit, (ie works of an author, sequence of prose essays, etc.)
<floatingText> used to represent an independent text which interrupts the text containing it at any point but after which the surrounding text resumes

### 4.3.1 Grouped Texts

**not going to use for time being**

### 4.3.2 Floating Texts

Unitary or composite text have an internal structure that can be decomposed hierarchically into subparts, each of which is a properly nested subtree. 

While this is undoubtedly true of a large number of documents, it is not true of all (ie if text A is contained by text B in such a way that part of B precedes A and part follows it, we cannot tesselate the whole of B. In such a case, we say that text A is a ‘floating’ text.)

For example, texts such as the Decameron or the Arabian Nights might be regarded as containing many floating texts embedded within another single text, the framing narrative, rather than as groups of discrete texts in which the fragments of framing narrative are regarded as front or back matter.

<floatingText> is a member of <<model.divPart>> and can appear within any division level element in the same way as a paragraph

.........
x-> 
  Consider "The Lining to the Patch-Work Screen", by Jane Barker (1726). It contains nearly a hundred distinct ‘tales’ embedded in a single patchwork. It begins by introducing Galecia, but within a few pages launches into a distinct narrative, the story of Captain Manly:
  ......
  <p>Galecia one Evening setting alone in her Chamber by a clear Fire, and a clean Hearth ... reflected on the Providence of our All-wise and Gracious Creator....</p>
  <p>She was thus ruminating, when a Gentleman enter'd the Room, the Door being a jar... calling for a Candle, she beg'd a thousand Pardons, engaged him to sit down, and let her know, what had so long conceal'd him from her Correspondence.</p>
  <pb n="5"/>
  <floatingText>
    <body>
    <head>The Story of <hi>Captain Manly</hi>
    </head>
      <p>Dear Galecia, said he, though you partly know the loose, or rather lewd Life that I led in my Youth; yet I can't forbear relating part of it to you by way of Abhorrence...
      <!-- Captain Manly's story here -->
      I had lost and spent all I had in the World; in which I verified the Old Proverb, That a Rolling Stone never gathers Moss, </p>
      </body>
  </floatingText>
  <pb n="37"/>
  ......
  Following conclusion of Captain Manly's tale, we return to Galecia, and almost immediately after that into two further stories. However, Galecia narrative returns between each of the texts, which is why we choose to represent them as floatingTexts:
  ......
  <p>The Gentleman having finish'd his Story, Galecia waited on him to the Stairs-head; and at her return, casting her Eyes on the Table, she saw lying there an old dirty rumpled Book, and found in it the following story: </p>
  <floatingText>
    <body>
      <p> IN the time of the Holy War when Christians from all parts went into the Holy Land to oppose the Turks; Amongst these there was a certain English Knight...</p>
      <!-- rest of story here -->
      <p>The King graciously pardoned the Knight; Richard was kindly receiv'd into his Convent, and all things went on in good order: But from hence came the Proverb, We must not strike <hi>Robert</hi> for <hi>Richard.</hi> </p>
    </body>
  </floatingText>
  <pb n="43"/>
  <p>By this time Galecia's Maid brought up her Supper; after which she cast her Eyes again on the foresaid little Book, where she found the following Story, which she read through before she went to bed. </p>
  <floatingText>
    <body>
    <head>The Cause of the Moors Overrunning <hi>Spain</hi> </head>
      <p>King ———— of Spain at his Death, committed the Government of his Kingdom to his Brother Don ——— till his little Son should come of Age ...</p>
      <p>Thus the little Story ended, without telling what Misery befel the King and Kingdom, by the Moors, who over ran the Country for many Years after. To which, we may well apply the Proverb, 
        <quote>
          <l>Who drives the Devil's Stages,</l>
          <l>Deserves the Devil's Wages</l>
        </quote>
      </p>
    </body>
  </floatingText>
  <p>The reading this Trifle of a Story detained Galecia from her Rest beyond her usual Hour; for she slept so sound the next Morning, that she did not rise, till a Lady's Footman came to tell her, that his Lady and another or two were coming to breakfast with her... </p>
.........

- Distinguish between <quote> (its semantics suggest content that derives from source external to current text) and <floatingText> (has no such implication)
- For a text with rich internal structure, quoted at length, <floatingText> might be used within <quote>


## 4.4 Virtual Divisions

<divGen> (automatically generated text division) indicates where a textual division generated automatically by a text-processing application is to appear It may appear wherever a div or div1 (div2, etc.) element may appear.

x-> example for TOC:
  <divGen type="toc"/>

x-> transcription, translation and aligned version three distinct divisions:
  <div>
    <!-- transcript here-->
  </div>
  <div>
    <!-- translation here -->
  </div>
  <divGen type="alignment"/>

## 4.5 Front Matter

Front matter of a text should not be confused with TEI header, which is kind of a front matter for the file, not the text it encodes. *Ignore* front matter in text, if original presentation of work is of no interest. 

Suggested values for `@type` (for front matter divisions):
\\`preface`: foreword for reader (explains content, purpose, or origin of text)
\\`ack`: formal acknowledgment by author
\\`dedication`: to one or more persons or institutions by the author
\\`abstract`: summary of the content of a text as continuous prose
\\`contents`: TOC, specifying structure + constituents (<list> should be used)
\\`frontispiece`: pictorial frontispiece, possibly including some text

x-> example demonstrates how various parts of front matter may be encoded:
  <div type="dedication">
    <p>To my parents, Ida and Max Fish</p>
  </div>
  <div type="preface">
    <head>Preface</head>
    <p>The answer this book gives to its title question is <q>there is and there isn't</q>.</p>
    <p>Chapters 1–12 have been previously published in the following journals and collections:
      <list>
        <item>chapters 1 and 3 in <title>New literary History</title> </item>
        <item>chapter 10 in <title>Boundary II</title> (1980)</item>
      </list>.
    I am grateful for permission to reprint.</p>
    <signed>S.F.</signed>
  </div>

## 4.6 Title Pages

Detailed analysis of the title page and other preliminaries of older printed books and manuscripts is of major importance in descriptive bibliography and the cataloguing of printed books

<titlePage> (title page) contains the title page of a text, appearing within the front or back matter.
<docTitle> (document title) contains the title of a document, including all its constituents, as given on a title page.
<titlePart> contains a subsection or division of the title of a work, as indicated on a title page.
  `@type`  specifies the role of this subdivision of the title. Suggested values include: 1] main; 2] sub; 3] alt; 4] short; 5] desc
<argument> contains a formal list or prose description of the topics addressed by a subdivision of a text.
<byline> contains the primary statement of responsibility given for a work on its title page or at the head or end of the work.
<docAuthor> (document author) contains the name of the author of the document, as given on the title page (often but not always contained in a byline).
<epigraph> contains a quotation, anonymous or attributed, appearing at the start or end of a section or on a title page.
<imprimatur> contains a formal statement authorizing the publication of a work, sometimes required to appear on a title page or its verso.
<docEdition> (document edition) contains an edition statement as presented on a title page of a document.
<docImprint> (document imprint) contains the imprint statement (place and date of publication, publisher name), as given (usually) at the foot of a title page
<docDate> (document date) contains the date of a document, as given on a title page or in a dateline.
<graphic> indicates the location of an inline graphic, illustration, or figure.

Together with <figure> these elements constitute `model.titlepagePart`

x-> title page of the work discussed earlier in this section
  <front>
   <titlePage>
    <docTitle>
     <titlePart type="main">Is There a Text in This Class?</titlePart>
     <titlePart type="sub">Authority of Interpretive Communities</titlePart>
    </docTitle>
    <docAuthor>Stanley Fish</docAuthor>
    <docImprint>
     <publisher>Harvard University Press</publisher>
     <pubPlace>Cambridge, Massachusetts</pubPlace>
     <pubPlace>London, England</pubPlace>
    </docImprint>
   </titlePage>
  </front>

x-> verbose 17th century example:
  <titlePage>
   <docTitle>
    <titlePart type="main">THE
    <lb/>Pilgrim's Progress
    <lb/>FROM
    <lb/>THIS WORLD,
    <lb/>TO
    <lb/>That which is to come:
    </titlePart>
    <titlePart type="sub">Delivered under the Similitude of a
    <lb/>DREAM</titlePart>
    <titlePart type="desc">Wherein is Discovered,
    <lb/>The manner of his setting out,
    <lb/>His Dangerous Journey; And safe
    <lb/>Arrival at the Desired Countrey.</titlePart>
   </docTitle>
   <epigraph>
    <cit>
     <quote>I have used Similitudes,</quote>
     <bibl>Hos. 12.10</bibl>
    </cit>
   </epigraph>
   <byline>By <docAuthor>John Bunyan</docAuthor>.</byline>
   <imprimatur>Licensed and Entred according to Order.</imprimatur>
   <docImprint>
    <pubPlace>LONDON,</pubPlace>
     Printed for <name>Nath. Ponder</name>
    <lb/>at the <name>Peacock</name> in the <name>Poultrey</name>
    <lb/>near <name>Cornhil</name>, <docDate>1678</docDate>.
   </docImprint>
  </titlePage>

## 4.7 Back Matter

**Content model for back and front elements are identical**

The following suggested values may be used for `@type` (for back-matter divs):

\\`appendix`: ancillary self-contained section of a work, often providing additional but in some sense extra-canonical text
\\`glossary`: A list of terms associated with definition texts (‘glosses’): this should be encoded as a <list type="gloss"> (see section 3.7 Lists).
\\`notes`: section where textual or other kinds of notes are gathered together.
\\`bibliogr`: A list of bibliographic citations: this should be encoded as a listBibl (see section 3.11 Bibliographic Citations and References).
\\`index`: Any form of index to the work.
\\`colophon`: A statement appearing at the end of a book describing the conditions of its physical production.

x-> an index (where printed index is interesting enough to transcribe):
  <back>
   <div type="index">
    <head>Index</head>
    <list type="index">
     <item>Actors, public, paid for the contempt attending
         their profession, <ref>263</ref>
     </item>
     <item>Africa, cause assigned for the barbarous state of
         the interior parts of that continent, <ref>125</ref>
     </item>
     <item>Agriculture
     <list type="indexentry">
       <item>ancient policy of Europe unfavourable to, <ref>371</ref>
       </item>
       <item>artificers necessary to carry it on, <ref>481</ref>
       </item>
       <item>cattle and tillage mutually improve each other, <ref>325</ref>
       </item>
       <item>wealth arising from more solid than that which proceeds
             from commerce <ref>520</ref>
       </item>
      </list>
     </item>
     <item>Alehouses, not the efficient cause of drunkenness, <ref>461</ref>
     </item>
    </list>
   </div>
  </back>

x-> back-matter division in epistolary form:
  <back>
   <div type="letter">
    <head>A letter written to his wife, founde with this booke
       after his death.</head>
    <p>The remembrance of the many wrongs offred thee, and thy
       unreproued vertues, adde greater sorrow to my miserable state,
       than I can utter or thou conceiue. ...
       ... yet trust I in the world to come to find mercie, by the
       merites of my Saiuour to whom I commend thee, and commit
       my soule.</p>
    <signed>Thy repentant husband for his disloyaltie,
    <name>Robert Greene.</name>
    </signed>
    <epigraph xml:lang="la">
     <p>Faelicem fuisse infaustum</p>
    </epigraph>
    <trailer>FINIS</trailer>
   </div>
  </back>

x-> list of corrigenda and addenda with pseudo-epistolary features:
  <back>
   <div type="corrigenda">
    <head>Addenda</head>
    <salute xml:lang="la">M. Scriblerus Lectori</salute>
    <p>Once more, gentle reader I appeal unto thee, from the shameful
       ignorance of the Editor, by whom Our own Specimen of
    <name>Virgil</name> hath been mangled in such miserable manner, that
       scarce without tears can we behold it. At the very entrance, Instead
       of <q xml:lang="grc">προλεγομενα</q>, lo!
    <q xml:lang="grc">προλεγωμενα</q> with an Omega!
       and in the same line <q xml:lang="la">consulâs</q> with a circumflex!
       In the next page thou findest <q xml:lang="la">leviter perlabere</q>,
       which his ignorance took to be the infinitive mood of
    <q xml:lang="la">perlabor</q> but ought to be
    <q xml:lang="la">perlabi</q> ... Wipe away all these
       monsters, Reader, with thy quill.</p>
   </div>
  </back>

----
  
# 13. Names, Dates, People, and Places

[UseCase][great for exposing info, delineating borders, and such for fan fiction, and such]


## 13.1 Attribute Classes Defined by this Module

> where the core module allows one simply to represent that a given piece of text is a name, this module allows one _further to represent_ a __personal name__, to represent the __person being named__, and to represent the __canonical name__ being used. A _similar range is provided for names of places and organizations_. The main intended applications for this module are in biographical, historical, or geographical data systems such as gazetteers and biographical databases, where these are to be integrated with encoded texts.

### 13.1.1 Linking Names and their Referents

__key__	provides an externally-defined means of identifying the entity (or entities) being named, using a coded value of some kind.

__ref__	(reference) provides an explicit means of locating a full definition for the entity being named by means of one or more URIs.

__role__ may be used to specify further information about the entity referenced by this name, for example _occupation_ of a person, or the _status_ of a place.


#### General Use Cases and Snippets

- one basic example:

That silly man <name role="politician" type="person">David Paul Brown</name> has suffered ...

[UseCase][maybe good for capturing transient roles a person may hold within different parts of a document]


__@ref__ attribute should be used to supply a direct link such as a URI to indicate the location of canonical information about the referent.

That silly man <name ref="#DPB1" type="person">David Paul Brown</name> has suffered ...

this means there exists a <person> with identifier _#DPB1_ and info (marked up using the elements discussed in 13.3)

same element might be provided by some other document:

That silly man <name ref="http://www.example.com/personography.xml#DPB1" type="person">David Paul Brown</name> has suffered ...


### 13.1.2 Dating Attributes

Members of the att.datable class share the following attributes:

__period__ supplies a pointer to some location defining a named period of time within which the datable item is understood to have occurred.

> datable events using the W3C datatypes:

__when__ supplies value of date or time in a standard form, e.g. yyyy-mm-dd.

__notBefore__ specifies earliest possible date for event in standard form, e.g. yyyy-mm-dd.

__notAfter__ specifies latest possible date for event in standard form, e.g. yyyy-mm-dd.

__from__ indicates starting point of the period in standard form, e.g. yyyy-mm-dd.

__to__ indicates ending point of the period in standard form, e.g. yyyy-mm-dd.


#### General Use Cases and Snippets

[Use Case][normalize any date]

__@when__ can normalize any temporal expression, independently of how it is represented in the text:

<date when="1807-06-09">June 9th</date> The period is approaching which will terminate my present copartnership. On the <date when="1808-01-01">1st Jan.</date> next, it expires by its own limitation.

[Use Case][associate any datable element with -fictional or real- "named periods"]

__@period__ can associate event or date with a named period. Periods [can be defined] in __taxonomy__ element (in TEI Header --> encodingDesc\classDecl)


[Use Case][specify temporal (before, after, during) info in normalized form]

<birth when="1857-03-15">15 March 1857.</birth>

<birth notBefore="1857-03-01" notAfter="1857-04-30">March or April of 1857</birth>

<residence from="1857-03-01" to="1857-04-30">March and April of 1857</residence>

<residence from="1857-03-01" notAfter="1857-04-30">From the 1st of March to some time in April of 1857.</residence>

## 13.2 Names

### 13.2.0 (was 3.5.1 Referring Strings)

A referring string is a phrase which refers to some person, place, object, etc. Two elements are provided to mark such strings:

<rs> (referencing string) contains a general purpose name or referring string
<name> (name, proper noun) contains *only* proper noun or noun phrase
  
`@type`  characterizes element in some sense
  `@subtype` provides a sub-categorization of the element


x-> Examples for <rs>:
......
  <!-- <rs> with @type "person" and "place" -->
  <p><q>My dear <rs type="person">Mr. Bennet</rs> </q>, said his lady to him one day, <q>have you heard that <rs type="place">Netherfield Park</rs> is let at last?</q></p>
  <!-- <rs> with @type "org" -->
  <p>Collectors of water-rents were appointed by the <rs type="org">Watering Committee</rs>. They were paid a commission not exceeding four per cent, and gave bond.</p>
  <!-- <rs> with @type "person" and "org" -->
  <p>It being one of the principles of the <rs type="org">Circumlocution Office</rs> never, on any account whatsoever, to give a straightforward answer, <rs type="person">Mr Barnacle</rs> said, <q>Possibly.</q> </p>
  <!-- <rs> refering to proper name (noun) *and* just ... reference -->
  <p><q>My dear <rs type="person">Mr. Bennet</rs> </q>, said <rs type="person">his lady</rs> to him one day ... </p>


<name> is for referencing strings which are only *proper nouns* (may be used synonymously with the rs element, or nested within it if a referring string contains a mixture of common and proper nouns).

x-> alternative way of encoding sentence from Pride and Prejudice:
......  
  <p><q>My dear <name type="person">Mr. Bennet</name>,</q> said <rs type="person">his lady</rs> to him one day, <q>have you heard that <name type="place">Netherfield Park</name> is let at last?</q> </p>
  
x-> proper <name> nested within a referring string (<rs>):
  <rs>His Excellency the Life President, <name>Ngwazi Dr H. Banda</name></rs>

-----

**Two issues arise:**
- *firstly*, may need to encode regularized form of a name, distinct from the actual form in the source --- So, use <reg>

- *secondly*, may need to identify particular person, place, etc. referred to by the name, irrespective of whether the name itself is normalized or not. --- Use `@key` or `@ref`
  `@key` provides an externally-defined means of identifying the entity (or entities) being named, using a coded value of some kind.
  `@ref` (reference) provides an explicit means of locating a full definition for the entity being named by means of one or more URIs.

x-> Useful for getting all refs to same person / location in document:
  <p><q>My dear <rs key="BENM1" type="person"> Mr. Bennet</rs>,</q> said <rs key="BENM2" type="person">his lady</rs> to him, <q>have you heard that <rs key="NETP1" type="place">Netherfield Park</rs> is let at last?</q> </p>
  <!-- one more example -->
  <p> <name key="VOM1" type="person">Mme. de Volanges</name> marie <rs key="VOM2">sa fille</rs>: c'est encore un secret; mais elle m'en a fait part hier. </p>
  <!-- example with externally defined code -->
  <p>
    <name key="LHR" type="airport">Heathrow</name>
  </p>
  n-> \\reference source should be documented with <taxonomy> in TEI header\\
......

> [UseCase][use <rs> to get all references of a person, object, org, etc. in a text]


`@ref` can point directly resource providing more info about entity named (ie authority record in a database, encylopaedia entry, another element in the same or a different document etc).

......
  <p>
    <name ref="http://en.wikipedia.org/wiki/Heathrow_airport"type="airport">Heathrow</name>
  </p>

n-> \\Be _extra careful_ with external dependencies (ie authority refs, etc)\\

This use should be distinguished from the use of nested <reg> to provide standard form of a referring string, as in this example:

......
  <p>My personal life during the administration of <rs key="POJA1" type="person">Col. Polk (<reg>Polk, James K.</reg>)</rs> has but poorly compensated me for the suspended enjoyments and pursuits of private and professional spheres</p>

`@key` is not recommended in data interchange (there's no way of ensuring that values used by one project are distinct from another). 

x-> Preferable approach for tokens is to use `@ref` whose value is a **tag URI** as defined in RFC 4151, for example:
......
  <p><name ref="tag:projectname.org,2012:VOM1" type="person">Mme. de Volanges</name> marie <rs ref="tag:theworksoflaclos.org,2012:VOM2">sa fille</rs>: c'est encore un secret; mais elle m'en a fait part hier.</p>
  > inclusion of domain name ("theworksoflaclos.org"), as specified in RFC 4151, helps ensure uniqueness of magic token values across TEI docs


x-> <choice> used if we want to record normalized and original form name:
......
  <p><name ref="tag:projectname.org,2012:WADLM1" type="person"> <choice><orig>Walter de la Mare</orig> <reg>de la Mare, Walter</reg> </choice> </name> was born at <name ref="tag:projectname.org,2012:Ch1" type="place">Charlton</name>, in <name ref="tag:projectname.org,2012:KT1" type="county">Kent</name>, in 1873.</p>


Although adequate for many simple cases, these methods are not efficient when name occurs many times. So, _check chapter_ "13 Names, Dates, People, and Places" for more demanding applications such as [onomastics](relating to persons or places named rather than the name itself), or wherever a detailed analysis of component parts of a name is needed


### 13.2.1 Personal Names

<rs> and <name> elements can distinguish names in a text but cannot mark internal components or structure (ie for creating alphabetically sorted list of personal names we need family name, a forename, honorary title, etc.). To conduct nominal record linkage or even to create an alphabetically sorted list of personal names, it is important to distinguish between a family name, a forename and an honorary title.


> _Hence_ the need for following elements and attributes:

<persName> (personal name) possibly including forenames, surnames, honorifics, added names, etc. (and is synonymous with <name type="person:">)
	- it is more powerful than <rs> and <name> because distinctive name components occurring within it can be marked as such
	- it can contain the following:

__surname__ contains family (inherited) name

__forename__ contains a forename, given or baptismal name.

__roleName__ contains a name component such as an official title or rank.

__addName__ (additional name) such as nickname, epithet, or alias

__nameLink__ (name link) such as van der or of

__genName__ (generational component) distinguish names on basis of relative ages

__@full__ indicates if name component is given in full, abbreviation or initial

__@sort__ specifies sort order of name component in relation to others within name

[UseCase][keep full name / nickname info about character / person record]
[UseCase][encode character appearances in text, and keep this info in one source]


###### sn1pp3ts - people and appearances

- enter and organize all persons (characters -fictional and not-, authors, editors, etc) into _one_ <listPerson>, like this:
  <teiHeader>
    .....
    <profileDesc>
      <particDesc>
        <listPerson>
          <person xml:id="...">
- must decide <xml:id> conventions for <person> (ie actor.TomSawyer, editor.Trianta, etc.)
- *required*: marked scenes with <milestone type="scene">
- mark first reference for each person / character within scene, most probably with <persName ref="#act.Tom.Sawyer" role="in.Scene"> (particular characteristics and other info are catalogued gradually in parent <person>)
  - we'll use <persName> in unorthodox way for marking all references to a person (ie even for pet-names or diminutive, such as "blue-eyed creature")
- **also** mark each *new* variation or form of character name (proper, diminutive, pet-name, etc.)

__later__ (pass 2 etc.)
- distinguish if person is acting in scene or referred to by others or narrator using `@role`
- organize persons into discrete lists (ie actors, etc.), and perhaps move editors and such to another place in <teiHeader>
- describe relations and links between characters (and places, organizations, objects, etc.) <listRelation> .. <relation> **OR** <linkGrp> with <link>
- mark <said>, <rs type="..." subtype="event | state | ..."> or <seg ...> 
  ... in order to capture traits, events, states, and similar info about someone "in-situ"
     <persName ref="#Becky" role="referredTo"><rs type="trait" ref="#Becky">blue eyed</rs> creature</persName>

> do we want to mark *all* occurences of name or reference to a person (or place, object for that matter) in a scene? -- at a later time
> Maybe we want to chart / graph intensity of appearances for each character
> count the fact that dialogues are de facto person.Actor occurences
> on the other hand variations of how a character is referred to (ie Tom, Thomas, "Sheriff of Whatever", etc.) should probably be marked


#### 13.2.2 Organizational Names
* <rs> can also be used

any named collection of people regarded as a single unit (‘Harvard College’, ‘the BBC’, ‘Apple’, ‘Google’ but also ‘the Scythians’, ‘the Militant Tendency’, etc.). Organizational names can be marked up as __rs__ or __name__, but __orgName__ is used where it is desired to distinguish organizational names more explicitly.

__orgName__ (organization name) contains an organizational name.

[UseCase][keep full name / nickname info about organization record]
[UseCase][encode organization appearances in text, and keep info in one source]
[UseCase][relate people, places, dates, etc to an organization / group]

#### 13.2.3 Place Names
* <rs> can also be used

Like other proper nouns or noun phrases used as names, place names can simply be marked up with the rs element, or with the name element

three ways of referring to places

- __placeName__ element) may consist of one or more names for hierarchically-organized geo-political or administrative units. Contains an absolute or relative place name. May be regarded as an abbreviation for elements <name type="place"> or <rs type="place">. 

	can be further analysed:

	_district_ any kind of subdivision of settlement (parish, ward, etc.)

	_settlement_ contains name of settlement (city, town, or village)

	_region_ name of admin unit (state, province, county) larger than settlement, but smaller than a country
	
	_country_ (country) contains the name of a geo-political unit, such as a nation, country, colony, or commonwealth, larger than or administratively superior to a region and smaller than a bloc.

	_bloc_ (bloc) contains the name of a geo-political unit consisting of two or more nation states or countries.

These elements are all members of the model.placeNamePart class, members of which may be used anywhere that text is permitted, including within each other as in the following examples:
<placeName>
 <settlement type="city">Rochester</settlement>,
<region type="state">New York</region>
</placeName>
<placeName ref="tag:projectname.org,2012:LSEA1">
 <country type="nation">Laos</country>,
<bloc type="sub-continent">Southeast Asia</bloc>
</placeName>
<placeName>
 <district type="arondissement">6ème</district>
 <settlement type="city">Paris, </settlement>
 <country>France</country>
</placeName>



- __geogName__ for names in terms of geographical features such as mountains or rivers element

- phrases expressing spatial or other kinds of relationship between other kinds of named place may be regarded as reference to a place

##### 13.2.3.3 Relative Place Names

A place may be specified in terms of its relationship to another place, for example ‘10 miles northeast of Paris’ or ‘near the top of Mount Sinai’. It can contain:
	- place name which acts as a referent (e.g. ‘Paris’ and ‘Mount Sinai’)
	- phrase indicating position of place related to referent (‘top of’, ‘north of’)
	- distance (possibly vague) between referent and place

Relative place names may be encoded using the following elements (in combination with either a __placeName__ or a __geogName__ element):

_offset_ marks direction offset between place names, dates, or times

_measure_ contains phrase referring to quantity (number, unit, and commodity name)


Some examples of relative place names are:
<placeName ref="tag:projectname.org,2012:NRPA1">
 <offset>near the top of</offset>
 <geogName>
  <geogFeat>Mount</geogFeat>
  <name>Sinai</name>
 </geogName>
</placeName>
<placeName>
 <measure>20 km</measure>
 <offset>north of</offset>
 <settlement type="city">Paris</settlement>
</placeName>

Distance specified may be normalized using unit and quantity attributes of measure:

<placeName ref="tag:projectname.org,2012:Duncan">
 <measure unit="km" quantity="17.7">11 miles</measure>
 <offset>Northwest of</offset>
 <settlement type="city">Providence</settlement>, <region type="state">RI</region>
</placeName>


[UseCase][encode relative directions / positions + play with them on maps]
[UseCase][think of gamification ideas!!!]


###### sn1pp3ts - places, buildings, etc. and appearances
- mark places, buildings, and such in the book using <placeName>
- *prerequisite*: all scenes must be marked with <milestone> 
- create <div n="Places, Bulidings, Etc."> in <back>(matter) and position a (temporary) <listPlace> with all <place> values that are found in the text
- 

- tagged with <placeName>, <geogName>, and maybe <location> + <note>)
- mark places in the text




## 13.3 Biographical and Prosopographical Data

> elements to markup _biographical_, _historical_, and _prosopographical_ data



### 13.3.1 Basic Principles

Info about people, places, and organizations relating to:

- characteristics or traits which do not change over time
- characteristics or states which hold true only at a specific time
- events / incidents which may lead to change of state or trait

__‘Characteristics’__ or __‘traits’__ are typically _independent_ of an individual's volition or action (physical, such as sex or hair and eye colour, or cultural, such as ethnicity, caste, or faith)

__‘States’__ (ie marital status, place of residence, position or occupation) have duration (beginning and end and are typically consequence of own action or that of others)

__‘Changes in state’__ are events such as birth, marriage, or appointment to office; such events will normally have specific date or a fairly narrow date-range. They can also cause or be caused by changes in characteristics.


Generic elements for state, trait, and event are also defined:

<state> description of some status or quality attributed to a person, place, or organization often at some specific time or for a specific date range.

<trait> description of some status or quality attributed to a person, place, or organization typically independent of the volition or action of the holder (usually not at specific time or for specific date range)

<event> contains data relating to any kind of significant event associated with a person, place, or organization.
	`@where`	indicates the location of an event by pointing to a place element

<listEvent> (list of events) contains a list of descriptions, each of which provides information about an identifiable event.


### 13.3.2 The Person Element

Information about person (not references to a person, for example by name) is grouped together within a __person__ element. 

Information about a group of people regarded as a single entity (for example ‘the audience’ of a performance) may be encoded using the __personGrp__ element (info about a group of people with distinct identity, ie a named theatrical troupe, should be recorded using __org__ element

These elements appear only within __listPerson__, which _groups descriptions_ together, and optionally _describes relationships_ amongst people listed.

__listPerson__ contains list of descriptions (which provide info about an identifiable person or a group of people)

__listRelation__ provides info about relationships amongst people, places, and organizations (informally as prose or as formally expressed relation links)

> listPerson elements may _(a)_ be supplied within the __particDesc__ element (in profileDesc of TEI header), but _(b)_ can also appear within the body of a text when the module defined by this chapter is included in a schema

The _type_ attribute may be used to distinguish lists of people of different kinds where this is considered convenient:

<profileDesc>
 <particDesc>
  <listPerson type="historical">
   <person xml:id="ART1">
    <persName>Arthur</persName>
   </person>
   <person xml:id="BERT1">
    <persName>Bertrand</persName>
   </person>
<!-- ... -->
  </listPerson>
  <listPerson type="mythological">
   <person xml:id="ART2">
    <persName>Arthur</persName>
   </person>
   <person xml:id="BERT2">
    <persName>Bertrand</persName>
   </person>
<!-- ... -->
  </listPerson>
 </particDesc>
</profileDesc>

The __person__ element carries several attributes. 

In addition, a small number of very commonly used personal properties may be recorded using attributes specific to person and personGrp:

_role_	specifies a primary role or classification for the person.
_sex_	specifies the sex of the person.
_age_	specifies an age group for the person.

These _attributes_ are intended for use where only a small amount of data is to be encoded ... When however a more detailed encoding is required it will be more appropriate to use the _elements_ age, sex and others


__person__ may contain many sub-elements. For convenience they are grouped into three classes (_traits_, _states_, and _events_). All elements in these three classes have following attributes:

_when_	supplies value of date or time (standard form, e.g. yyyy-mm-dd)
_notBefore_	specifies earliest date for event (standard form, e.g. yyyy-mm-dd)
_notAfter_	specifies latest possible date for event in standard form
_from_	indicates the starting point of the period in standard form
_to_	indicates the ending point of the period in standard form


---

#### 13.3.2.1 Personal Characteristics

__faith__ specifies the faith, religion, or belief set of a person.

__langKnowledge__ summarizes person's linguistic knowledge (prose or list)

__nationality__ description of present / past nationality or citizenship

__sex__ specifies the sex of a person.

__age__ (age) specifies the age of a person.

__socecStatus__ description of a person's perceived social or economic status

__persName__ proper noun or proper-noun phrase referring to a person, possibly including one or more of the person's forenames, surnames, honorifics, added names, etc.

__occupation__ description of a person's trade, profession or occupation

__residence__ describes a person's present or past places of residence.

__affiliation__ description of person's present or past affiliation with some organization, for example an employer or sponsor.

__education__ contains a description of the educational experience of a person.

__floruit__ contains information about a person's period of activity



> If elements above will not do, choose between __trait__ (for characteristics generally considered unchanging) and __state__ (for characteristics that are generally perceived to be transient)

__state__ contains description of some status or quality attributed to person, place, or organization at some specific time or for a specific date range. 

__trait__ describes some status or quality attributed to person, place, or organization _typically_, but not necessarily, independent of volition or action of holder (usually not at some specific time or specific date range)


can be used to extend the range of info about personal characteristics:

<trait type="ethnicity" key="alb">
 <label>Ethnicity</label>
 <desc>Ethnic Albanian.</desc>
</trait>

can also extend set of descriptive features available in standardized way

<trait type="physical">
 <label>eye colour</label>
 <desc>blue</desc>
</trait>
<trait type="physical">
 <label>hair colour</label>
 <desc>brown</desc>
</trait>


__state__ or __trait__ may be used instead of specific elements listed above:

<state type="nationality" notBefore="2002-01-15">
 <label>Nationality</label>
 <desc>American citizen from 15 January 2002.</desc>
</state>

is the same as:

<nationality notBefore="2002-01-15">American citizen from 15 January 2002.</nationality>

or even:

<nationality notBefore="2002-01-15" key="US"/>


----

#### 13.3.2.2 Personal Events

> elements describing specific events in a person's history (example birth, marriage, etc) -- not characteristics of an individual, but often cause an individual to gain such characteristics, or to enter a new state

__birth__ (birth) contains information about a person's birth, such as its date and place.
__death__ (death) contains information about a person's death, such as its date and place.

__event__ (generic element) is similar to state and trait, chief difference is it can include __placeName__ element (name of place where event occurred.). Is used to describe any event in the life of an individual or organization.

__EXAMPLE:__ summary of wedding (Jane Burden to William Morris) encoded _(a)_ as _event_ embedded within _person_ (data about Morris). We could have _(b)_ embedded _event_ within the _person_ (for Burden), or _(c)_ have it as freestanding event independent of either person element:

<person xml:id="WM">
<!-- ... -->
 <event type="marriage" when="1859-04-26">
  <label>Marriage</label>
  <desc>
     <name type="person" ref="#WM">William Morris</name> and <name
       type="person"
       ref="http://en.wikipedia.org/wiki/Jane_Burden">Jane Burden</name> were
       married at <name type="place">St Michael's Church, Ship Street, Oxford</name> on <date when="1859-04-26">26 April 1859</date>. The wedding was conducted by Morris's friend <name type="person" ref="#RWD">R. W. Dixon</name> with <name type="person" ref="#CBF">Charles Faulkner</name> as the best man. The bride was given away by her father, <name type="person" ref="#RB">Robert Burden</name>. According to the account that <name
       type="person" ref="http://en.wikipedia.org/wiki/Edward_Burne-Jones">Burne-Jones</name> gave <name type="person" ref="#JWM">Mackail</name> <quote>M. said to Dixon beforehand <said>Mind you don't call her Mary</said> but he did</quote>.        
  </desc>
  <bibl>J. W. Mackail, <title>The Life of William Morris</title>, 1899.</bibl>
 </event>
</person>


a __relation__ element may then be used to link them in a more meaningful way:

<relation name="spouse" mutual="#WM #JBM"/>
<relation name="friend" mutual="#WM #RWD"/>
<relation name="parent" active="#RB" passive="#JBM"/>

all these elements can be limited in terms of time, for example:

<person xml:id="DB">
 <persName notAfter="1966">David Jones</persName>
 <persName notBefore="1966">David Bowie</persName>
</person>

also available are attributes: 
  _cert_ for degree of certainty
  _resp_ for agency responsible, 
  _evidence_ for nature of the evidence used, 
  _source_ pointer to a resource from which the information derives

<event type="birth" resp="#XYZ" cert="high">
 <p>Born in <name type="place">Brixton</name> on 8 January 1947.</p>
</event>
<event type="birth" resp="#ABC" cert="low">
 <p>Born in <name type="place">Berkhamsted</name> on 9 January 1947.</p>
</event>

----

#### 13.3.2.3 Personal Relationships

the following two elements may be used to document relationships amongst the persons, places, or organizations identified:

__listRelation__ gives info about relationships identified amongst people, places, and organizations, either informally as prose or as formally expressed relation links.

__relation__ (relationship) describes any kind of relationship or linkage amongst a specified group of places, events, persons, objects or other items.
  _name_  for kind of relationship of which this is an instance
  _active_  identifies ‘active’ participants in a non-mutual relationship, or all the participants in a mutual one.
  _mutual_  supplies a list of participants amongst all of whom the relationship holds equally.
  _passive_ identifies the ‘passive’ participants in a non-mutual relationship.



for persons a relationship might be _social_ (such as employer/employee), _personal_ (such as sibling, spouse, etc.) or _something less precise_ (such as ‘possessing shared knowledge’). 

relationships may be _mutual_ (ie ‘sibling’) or non-mutual (ie ‘employer’). For non-mutual relationships use _active_ and _passive_ (chosen to reflect the fact that non-mutual relations are directed)

example:
<listRelation>
 <relation name="parent" active="#P1 #P2" passive="#P3 #P4"/>
 <relation name="spouse" mutual="#P1 #P2"/>
 <relation
   type="social"
   name="employer"
   active="#P1"
   passive="#P3 #P4"/>
</listRelation>


----



# 14 Tables, Formulæ, Graphics and Notated Music

The module defined by this chapter defines special purpose ‘container’ elements that can be used to encapsulate occurrences of such data within a TEI-conformant document in a portable way. 

## 14.1 Tables

A table is the least ‘graphic’ of the elements discussed in this chapter. Almost any text structure can be presented as a series of rows and columns: one might, for example, choose to show a glossary or other form of list in tabular form, without necessarily regarding it as a table.

we can use TEI table (simplest) all the way to CALS (most comprehensive), but most probably will use the _XHTML table model_ 

It supports arrangement of arbitrary data into rows and columns of cells. Table rows and columns may be grouped to convey additional structural information and may be rendered by user agents in ways that emphasize this structure. Support for incremental rendering of tables and for rendering on ‘non-visual’ user agents is also available. 

Special elements and attributes are provided to associate metadata with tables. They indicate the table's purpose, or are for the benefit of people using speech or Braille-based user agents.

## 14.2 Formulæ and Mathematical Expressions

As with tables, in all the XML solutions a tension exists between the need to encode the way a formula is written (its appearance) and the need to represent its semantics. 

If the object of the encoding is purely to act as an interchange format among different formatting programs, then there is no need to represent the mathematical meaning of an expression. 

If however the object is to use the encoding as input to an algebraic manipulation system (such as Mathematica or Maple) or a database system, clearly simply representing superscripts and subscripts will be inadequate.

__formula__ should be used to encode any formula, no matter what notation is employed:

__formula__ contains a mathematical or other formula.
	_notation_	names the notation used for the content of the element.

By default, a formula is assumed to contain character data which is not validated in any way:

<formula notation="TeX">$e=mc^2$</formula>

The character data must still be well-formed, of course, which means that < and & must be escaped with entity references or numeric character references, e.g.

<formula notation="TeX">$\matrix{0 &amp;amp; 1\cr&amp;lt;0&amp;amp;>1}$</formula>

## 14.4 Specific Elements for Graphic Images [](collect from this point)

The following special purpose elements are used to indicate the presence of graphic images within a document:

__figure__ groups elements representing or containing graphic information such as an illustration, formula, or figure.

__graphic__ indicates the location of an _inline_ graphic, illustration, or figure.

__binaryObject__ provides encoded binary data representing an inline graphic, audio, video or other object.

__figDesc__ (description of figure) contains a brief prose description of the appearance or content of a graphic figure, for use when documenting an image without displaying it.


The figure element is used to contain images, captions, and textual descriptions of the pictures. The images themselves are specified using the graphic element, whose url attribute provides the location of an image. For example:

<figure>
	<graphic url="Fig1.pdf"/>
</figure>


> These kinds of content may be supplied inside a figure element:

- __head__ used to supply a descriptive heading or title for graphic
- __p__ or __ab__ one or more for caption or extended notes on figure
- __graphic__ which is about the graphic or __binaryObject__ which can be graphic, audio, video or other object
- __figDesc__ brief description of the appearance or content of a graphic figure, for use when documenting image _without_ displaying it .. *NOT going to use probably*

### General Use Cases and Snippets

#### Encode internally divided figure(s)

A figure which is _internally divided_, or contains _sub-figures_, may be encoded with nested figure elements, as in the following example.

<figure n="6.45">
	<figure n="a">
		<graphic url="./figs/6.45a.png"/>
		<ab type="caption">Parallel</ab>
	</figure>
	<figure n="b">
		<graphic url="./figs/6.45b.png"/>
		<ab type="caption">Perspective</ab>
	</figure>
	<ab type="caption">The two canonical view volumes, for the (a) parallel and (b) perspective projections. Note that -z is to the right.</ab> 
</figure>

[Use Case][interesting for comics and similar caret based genres]
[Use Case][possibly interesting for maps (ie sequential reveals)]

---

#### Maintain two versions of an image

_maintain two versions of an image_ in an electronic file: one a low resolution or ‘thumbnail’ version which, when selected by the user, causes the other, high resolution, version to be accessed. In TEI terms, the thumbnail image acts as a reference to the other:

<ref target="#IM1">Click here <graphic url="fig1th.png"/> for enlightenment </ref>
...
<figure xml:id="IM1">
	<graphic url="fig1.jpg"/>
</figure>

[Use Case][small -inline- icons pointing to full image/graphic]

---

#### Associate part(s) of image with textual element (or other)
_associate part of an image with a textual element_ not necessarily contiguous to it in the text (ie callout). Following example assumes that we wish to associate one portion of the image held as ‘fig1’ with chapter two of some text, and another portion of it with chapter three.

_first:_ some way of identifying and pointing to sub-parts of a graphic, ie:

<ptr xml:id="PD1" target="Fig1.svg#object1"/>
<ptr xml:id="PD2" target="Fig1.svg#object2"/>

these ptr elements point at elements inside Fig1.svg below:

<svg xmlns="http://www.w3.org/2000/svg" width="8cm" height="3cm" viewBox="2 1 8 3">
	<g id="object1">
		<ellipse
		style="fill: #ffffff"
		cx="3.875"
		cy="3.025"
		rx="1.175"
		ry="1.175"/>
	</g>
	<g id="object2">
		<rect
		style="fill: #a81616"
		x="7.8"
		y="1.9"
		width="2.17581"
		height="2.24833"/>
	</g>
</svg>

_second:_ identify parts of document to which a link is to be made, ie:

<div1 type="chapter" xml:id="CHAP1">
<!-- ... -->
</div1>
<div1 type="chapter" xml:id="CHAP2">
<!-- ... -->
</div1>

_finally:_ link these areas to relevant chapters with a linkGrp: 

<linkGrp type="callout">
	<link target="#CHAP1 #PD1"/>
	<link target="#CHAP2 #PD2"/>
</linkGrp>

[Use Case][interesting for comics and similar caret based genres]
[Use Case][reveal only part of a map or other image info to reader]

## 16.1 Links

We say that one element points to others if the first has an attribute whose value is a reference to the others: such an element is called a pointer element, or simply a __pointer__ (note, ref, and ptr). These elements all indicate an association between one place in the document (the location of the pointer itself) and one or more others (the elements whose identifiers are specified by the pointer's target attribute). 

The module described in this chapter introduces a _variation_ on this basic kind of pointer, known as a __link__, which specifies both ‘ends’ of an association.

### 16.1.1 Pointers and Links

the __link__ element, which represents an association between two (or more) locations by specifying each location explicitly. Its own location is irrelevant to the intended linkage.

---

The __ptr__ and __ref__ elements point, conceptually, at a _single target_, even if that target _may be discontinuous_ in the document. The link element specifies at least two targets and represents an association between them, independent of its own location.

---

_Double connection among elements_ could also be expressed by a combination of pointer elements, for example, two ptr elements, or one ptr element and one note element. 

Thus, in the following encoding:

<ptr xml:id="sa-p1" target="#sa-p2"/>
<ptr xml:id="sa-p2" target="#sa-p1"/>

sa-p1 points to sa-p2, and sa-p2 points to sa-p1. This is logically equivalent to the more compact encoding:

<link target="#sa-p1 #sa-p2"/>

What the link element accomplishes is the handling of double connection by means of a single element. 

---

footnotes can be encoded using the __note__ element without a target attribute, _placed adjacent to the passage_ to which the note refers

<l>(Diff'rent our parties, but with equal grace</l>
<l>The Goddess smiles on Whig and Tory race,</l>
<l>
 <note type="imitation" place="bottom" anchored="false">
  <bibl>Virg. Æn. 10.</bibl>
  <quote>
   <l>Tros Rutulusve fuat; nullo discrimine habebo.</l>
   <l>—— Rex Jupiter omnibus idem.</l>
  </quote>
 </note>'Tis the same rope at sev'ral ends they twist,
</l>
<l>To Dulness, Ridpath is as dear as Mist)</l>

- This use of the note element can be called _implicit pointing (or implicit linking)_ -- relies on the juxtaposition of the note to the text being commented on for the connection to be understood.


### 16.1.3 Groups of Links

The element __linkGrp__ may be used to group links of a particular type together in a single part of the document; such a collection may be used to represent what is sometimes referred to in the literature of Hypertext as a web, a term introduced by the Brown University FRESS project in 1969, and not to be confused with the World Wide Web.

It provides a convenient way of establishing a default for the type attribute on a group of links of the same type

<linkGrp type="imitation">
 <link target="#n2.79 #L2.79"/>
 <link target="#n2.88 #L2.88"/>
 <link target="#n3.284 #L3.284"/>
</linkGrp>

(all __link__ @type are "imitation")


	> Typical software might hide a web entirely from the user, but use it as a source of information about links, which are displayed independently at their referenced locations. Alternatively, software might provide a direct view of the link collection, along with added functions for manipulating the collection, as by filtering, sorting, and so on. 

## 16.2 Pointing Mechanisms

the TEI provides methods of pointing:

- into documents other than the current doc
- to element in another doc, using its xml:id;
- to element (in current doc or not), using its - position in XML tree
- at arbitrary content in any XML doc using TEI-defined XPointer schemes

### 16.2.3 Using Abbreviated Pointers

xml:base is less convenient when your text contain many references to a variety of different sources in different locations. 

To deal with this problem, the TEI provides a useful method of using abbreviated pointers and documenting a way to dereference them automatically.

Imagine a project which has a large collection of XML documents organized like this:

anthology
	poetry
		poem.xml
	prose
		novel.xml
references
	people
		personography.xml

If you want to link a name in the novel.xml file to a person in the personography.xml file, the link will look like this:

<name ref="../../references/people/personography.xml#fred">Fred</name>

If there are many names to tag in a single paragraph, the XML encoding will be congested, and such lengthy links are prone to typographical error. In addition, if the project organization is changed, every relative link will have to be found and altered.

An alternative is to use a private URI scheme, a method of constructing a simple, key-like token which functions as a data.pointer, and can be used as the value of any attribute which has that datatype, such as ref and target. You might, for example, use the prefix psn (for "person"), and structure your name tags like this:

<name ref="psn:fred">Fred</name>

TEI provides a structured method of dereferencing it (turning it into a computable path, such as ../../references/people/personography.xml#fred) by means of a declaration inside encodingDesc in the TEI header, using the elements and attributes for prefix declaration

This is how you might document a private URI scheme using the psn: prefix:
<listPrefixDef>
 <prefixDef
   ident="psn"
   matchPattern="([a-z]+)"
   replacementPattern="../../references/people/personography.xml#$1">
  <p> In the context of this project, private URIs with the prefix
     "psn" point to <gi>person</gi> elements in the project's
     personography.xml file.
  </p>
 </prefixDef>
</listPrefixDef>


Any number of prefixDef elements may be provided for the same prefix. A processor may decide to process one or all of them; if it processes only one, it should choose the first one with the correct ident value, so the primary or most important prefixDef for any given prefix should appear first in its parent listPrefixDef.


### 16.2.5 TEI XPointer Schemes


#### 16.2.5.2 xpath1(Expr)

The __xpath1() scheme__ locates a node or node set in an XML Information Set. For example, the following example selects the first paragraph of the <ftnote> element with id of fn6 of a paper that discusses XPointers.

<ptr
  target="http://tinyurl.com/267z62/xml/2004/Thompson01/EML2004Thompson01.xml#xpath1(//ftnote[@id='fn6']/para[1])"/>

This pointer scheme allows easy, direct use of the most widely-implemented XML query method. It is probably the most robust pointing mechanism for the common situation of selecting an XML element or its contents where an xml:id is not present.


#### 16.2.5.4 range()

The __range() scheme__ locates a range between two points in an XML information set. The two fragment identifier arguments to range() locate the boundaries of the range. The possibilities for range() pointer schemes are as follows:

_A Node:_ When the first argument resolves to a node, the starting point of the range is the point immediately preceding the node. When the second argument resolves to a node, the ending point of the range is the point immediately following the node. It is an error if the ending point precedes the starting point of a range.
_A range:_ When the first argument resolves to a range R, the starting point of the result range is the same as the starting point of R. When the second argument resolves to a range R, the ending point of the result range is the ending point of R.
_A Point:_ When the first argument resolves to a point, that point is the start of the range. When the second argument resolves to a point, that point is the end of the range.


### 16.2.6 Canonical References

By ‘canonical’ reference we mean any _means of pointing into documents, specific to a community or corpus_. For example, biblical scholars might understand ‘Matt 5:7’ to mean ‘the book called Matthew, chapter 5, verse 7.


### 16.3 Blocks, Segments, and Anchors

three general purposes elements which may be used to mark and categorize both a span of text and a point within one. These elements have several uses, most notably to provide _elements which can be given identifiers for use when aligning or linking to parts of a document_, as discussed elsewhere in this chapter. 

They also provide a _convenient way of extending the semantics of the TEI markup scheme in a theory-neutral manner_, by providing for two neutral or ‘anonymous’ elements to which the encoder can add any meaning not supplied by other TEI defined elements.

__anchor/__ (anchor point) attaches an identifier to a point within a text, whether or not it corresponds with a textual element.
> it may be thought of as an empty __seg__ enabling an identifier to be attached to any position in a text. [it] is primarily intended to mark an arbitrary point used for alignment, or as the target of a spanning element [...] rather than as a means of marking segment boundaries for some arbitrary segmentation of a text.


__ab__ (anonymous block) contains any arbitrary component-level unit of text, acting as an anonymous container for phrase or inter level elements analogous to, but without the semantic baggage of, a paragraph.

__seg__ (arbitrary segment) represents any segmentation of text below the ‘chunk’ level.

n-> it may be used to mark almost any segment of interest for processing. One use of the element is to mark text features for which no appropriate markup is otherwise defined, i.e. as a simple extension mechanism. Another use is to provide an identifier for some segment which is to be pointed at by some other element, i.e. to provide a target

For example:
- as a means of marking segments significant in a metrical or rhyming analysis (see section 6.3 Rhyme and Metrical Analysis)
- as a means of marking typographic lines in drama (see section 7.2 The Body of a Performance Text) or title pages (see section 4.6 Title Pages)



### 16.4.2 Alignment of Parallel Texts

One very important application area for the alignment of parallel texts is multilingual corpora. 

We present a passage using the linkGrp mechanism and marking explicitly the segments which have been aligned:
<div xml:id="div-e" xml:lang="en" type="subsection">
  <p>
    <seg xml:id="e_1">According to our survey, 1988 sales of mineral water and soft drinks were much higher than in 1987, reflecting the growing popularity of these products. Cola drink manufacturers in particular achieved above-average growth rates.</seg>
    <seg xml:id="e_2">The higher turnover was largely due to an increase in the sales volume.</seg>
  </p>
</div>
<div xml:id="div-f" xml:lang="fr" type="subsection">
  <p>
    <seg xml:id="f_1">Quant aux eaux minérales et aux limonades, elles rencontrent toujours plus d'adeptes. En effet, notre sondage fait ressortir des ventes nettement supérieures à celles de 1987, pour les boissons à base de cola notamment.</seg>
    <seg xml:id="f_2">La progression des chiffres d'affaires résulte en grande partie de l'accroissement du volume des ventes.</seg>
  </p>
</div>

<linkGrp type="alignment" domains="#div-e #div-f">
 <link target="#e_1 #f_1"/>
 <link target="#e_2 #f_2"/>
</linkGrp>


## 16.5

### 16.5.1 Aligning Synchronous Events

Provided that explicit elements are available to represent the parts or places to be synchronized, then the global linking attribute __synch__ may be used to encode such synchronization, once it has been identified.

### 16.5.2 Placing Synchronous Events in Time

A synchronous alignment specifies which points in a spoken text occur at the same time, and the order in which they occur, but does not say at what time those points actually occur.

## 16.7 Aggregation

Because of the strict hierarchical organization of elements, or for other reasons, it may not always be possible or desirable to include all the parts of a possibly fragmented text segment within a single element.

- the __link__ element may be used to aggregate such segments, 
- the __join__ element, which is a special-purpose linking element specifically for representing the aggregation of parts, and __joinGrp__ for grouping join elements. 

The join element is equivalent to a link element of @type="join".

Double linking of two s-units (in the available exmple) is equivalent to specifying a link element:

<link type="join" target="#qs3 #qs4"/>

Such a link element must carry a type attribute with a value of join to specify that the link is to be understood as joining its targets into a single aggregate.

we now use a join element to represent the virtual sentence formed by the aggregation of s1 and s2:

<join target="#qs3 #qs4" result="s"/>

----

Suppose now that xml:id attributes, for whatever reasons, are not available. Then ptr elements may be created using any of the methods described in sections 16.2.4 W3C element() Scheme or 16.2.5 TEI XPointer Schemes. The xml:id attributes of these elements may now be specified by the target attribute on the join elements.

<text>
 <body>
<!-- five div1 elements -->
  <div1>
   <p>Zui-Gan called out to himself every day, <q>Master.</q>
   </p>
   <p>Then he answered himself, <q>Yes, sir.</q>
   </p>
   <p>And then he added, <q>Become sober.</q>
   </p>
   <p>Again he answered, <q>Yes, sir.</q>
   </p>
   <p>
    <q>And after that,</q> he continued, <q>do not be deceived by others.</q>
   </p>
   <p>
    <q>Yes, sir; yes, sir,</q> he replied.</p>
   <ab type="aggregation">
    <ptr xml:id="rzuiq1" target="./#xpath1(//div1[6]/p[1]/q[1])"/>
    <ptr xml:id="rzuiq2" target="./#xpath1(//div1[6]/p[2]/q[1])"/>
    <ptr xml:id="rzuiq3" target="./#xpath1(//div1[6]/p[3]/q[1])"/>
    <ptr xml:id="rzuiq4" target="./#xpath1(//div1[6]/p[4]/q[1])"/>
    <ptr xml:id="rzuiq5" target="./#xpath1(//div1[6]/p[5]/q[1])"/>
    <ptr xml:id="rzuiq6" target="./#xpath1(//div1[6]/p[5]/q[2])"/>
    <ptr xml:id="rzuiq7" target="./#xpath1(//div1[6]/p[6]/q[1])"/>
    <joinGrp evaluate="one" result="q">
     <join target="#rzuiq1 #rzuiq2 #rzuiq4 #rzuiq7">
      <desc>what Zui-Gan said</desc>
     </join>
     <join target="#rzuiq3 #rzuiq5 #rzuiq6">
      <desc>what Master said</desc>
     </join>
    </joinGrp>
   </ab>
  </div1>
 </body>
</text>

The extended pointer with identifier rzuiq2, for example, may be read as ‘the first q in the first p, within the sixth div1 element of the current document.’

## 16.8 Alternation

elements are in _exclusive_ alternation if any of those elements could be present in a text, but one and only one of them is; in addition, we say that those elements are mutually exclusive. 

elements are in _inclusive_ alternation if at least one (and possibly more) of them is present. The elements that are in alternation may also be called alternants.

One way to mark an exclusive alternation is to use the linking attribute _@exclude_. 

A more general way to mark alternation (for exclusive and inclusive) is to use the linking element __alt__. 

__alt/__ (alternation) identifies an alternation or a set of choices among elements or passages.
	_@weights_	If _@mode_ is excl, each weight states the probability that the corresponding alternative occurs. If _@mode_ is incl each weight states the probability that the corresponding alternative occurs given that at least one of the other alternatives occurs.
__altGrp__ (alternation group) groups a collection of alt elements and possibly pointers.

> example possible uses: 
	- word games with choices and different paths
	- multiple choice questions, quizzes, etc

## 16.9 Stand-off Markup

### 16.9.1 Introduction

In stand-off markup encoding does not directly contain any part of the text, but instead includes it by reference. One specific mechanism recommended by these Guidelines for this purpose is the standard XInclude mechanism defined by the W3C; another is to use pointers as demonstrated elsewhere in this chapter.

There are _many reasons for using stand-off markup_: 
- source text might be read-only so that additional markup cannot be added
- text may need to be marked up by hierarchically incompatible schemes
- a single scheme may need to accommodate multiple hierarchical ambiguities, so that a single markup tree is not the most faithful representation of the source material

This section describes a generic mechanism for expressing all kinds of markup externally as stand-off tags, for use whenever it is appropriate.

### 16.9.2 Overview of XInclude

XInclude is a W3C recommendation which specifies a syntax for the inclusion within an XML document of data fragments placed in different resources. Included resources can be either plain text or XML.

> XInclude defines a namespace (associated with the prefix xi:, and two elements, <xi:include> and <xi:fallback>).

The __<xi:include>__ element uses the _@href_ attribute to specify the location of the resource to be included; its value is an URI containing, if necessary, an XPointer. 

XInclude currently requires support for one XPointer scheme, called element(), which can use either _a bare name_ (element with specific xml:id) or _a child sequence_ (a path in the XML tree) to specify its target. 

The xpointer() scheme and the TEI schemes (see 16.2.5 TEI XPointer Schemes) add the concepts of points and ranges, which can be used to specify sub-node fragments (e.g., a few words within a longer text node) or trans-node fragments (e.g., a segment of text that spans across different branches of the overall XML tree).

<!-- still editing -->
## 17.2 Global Attributes for Simple Analyses

_ana_ (analysis) indicates one or more elements containing interpretations of the element on which the ana attribute appears (when the module described by this chapter is selected). It may be specified for any element and it associates it with one or more others (as an analysis or interpretation)


## 17.3 Spans and Interpretations

simplest mechanisms for attaching analytic notes to particular passages of text are provided by __span__, __interp__, __spanGrp__ and __interpGrp__

__span__ associates interpretative annotation directly with a span of text
__spanGrp__ (span group) collects together span tags.
__interp__ summarizes interpretative annotation which is linked to a span of text§
__interpGrp__ collects set of __interp__ which share _resp_ or _type_ or other


These elements share (among others) the following attributes:

> via att.interpLike --
  _type_  indicates what kind of phenomenon is being noted in the passage. Sample values include: 1] image; 2] character; 3] theme; 4] allusion
  _inst_  (instances) points to instances of the analysis or interpretation represented by the current element.

> via att.responsibility --
  _cert_  (certainty) signifies the degree of certainty associated with the intervention or interpretation.
  _resp_  (responsible party) indicates the agency responsible for the intervention or interpretation, for example an editor or transcriber.

> _type_ (for __span__ and __interp__) can indicate that annotations are -ie- thematic or structural. Annotation itself is content of __span__ or __interp__

> for __span__ the span of text being annotated is indicated by values of the from, to or target attributes, used in combination as follows. 
  - if only _from_ is given, span is coterminous with element indicated by its value
  - if _from_ and _to_ are given, span runs from start of element indicated by the _from_ attribute up to the end of the element indicated by _to_; 
  - if _target_ is used, span is defined by aggregating the contents of the (possibly non-contiguous) elements pointed to by its values

> it is an error to supply only _to_ attribute, or more than one value for _to_ or _from_ attributes; or to supply either in conjunction with the __target__


examples of __span__ "range" attributes (_from_, _to_, and _target_):
.
--> _from_ & _to_
  <span from="#mk01" to="#up01">phrasal verb "make up"</span>

--> _target_:
  <span target="#mk02 #up02">phrasal verb "make up"</span>

--> _target_ for non-consecutive values:
  <span target="#mk03 #up03">phrasal verb "make up"</span>

--> _resp_ attribute indicates the annotator responsible for this annotation.


__span__ example in narratological analysis:
.
  <p xml:id="MaQp1s2p114">
    <s xml:id="MaQp1s2p114s1">There was [...] point at which the thing began.</s>
    <s xml:id="MaQp1s2p114s2">It was not [...] it away.</s>
    <s xml:id="MaQp1s2p114s3">There was a slow integration [...] atoms.</s>
    <s xml:id="MaQp1s2p114s4">She felt [...] the sun.</s>
    <s xml:id="MaQp1s2p114s5">Not for one [...] afterwards.</s>
      <span from="#MaQp1s2p114s3" to="#MaQp1s2p114s5">the moment</span>
    <s xml:id="MaQp1s2p114s6">For during [...] unimportance of humanity.</s>
  </p>


__span__ may be placed near the text it is associated with or elsewhere in same or different document

when __span__ or __interp__ elements share attributes we can group them within a spanGrp or interpGrp element as follows:

<spanGrp resp="#DTL">
  <span from="#MaQp1s2p114s3" to="#MaQp1s2p114s5">the moment</span>
  <!-- other spans identified by DTL here -->
</spanGrp>


structural analysis of a text (narrative units in pattern shared with other texts):
.
  <p xml:id="P1">
    <s xml:id="S1">Sigmund ... was a king in Frankish country.</s>
    <s xml:id="S2">Sinfiotli was the eldest of his sons.</s>
    <s xml:id="S3">Borghild, Sigmund's wife, had a brother ...</s>
    <s xml:id="S4A">But Sinfiotli ... wooed the same woman</s>
    <s xml:id="S4B">and Sinfiotli killed him over it.</s>
    <s xml:id="S5">when he came home .. she was obliged to accept it</s>
    <s xml:id="S6">At the funeral feast Borghild was serving beer.</s>
    <s xml:id="S7">She took poison ... and brought it to Sinfiotli.</s>
    <s xml:id="S17">Sinfiotli drank it off and at once fell dead.</s>
    <anchor xml:id="EOS17"/>
  </p>
  <p xml:id="P2">Sigmund carried him a long way in his arms ... </p>
  <p xml:id="P3">King Sigmund lived a long time in Denmark ... </p>
  <p xml:id="P4">Sigmund and all his sons were tall ... </p>
  ********
  <spanGrp resp="#TMA" type="narrative-structure">
    <span from="#S1" to="#S3">introduction</span>
    <span from="#S4A">conflict</span>
    <span from="#S4B">climax</span>
    <span from="#S5" to="#S17">revenge</span>
    <span from="#EOS17">reconciliation</span>
    <span from="#P2" to="#P4">aftermath</span>
  </spanGrp>

Note use of empty __anchor__ to provide target for ‘reconciliation’ unit normally part of narrative pattern but not realized in this text


The second example above can be recoded using interp and interpGrp tags in a similar manner. The interpretation itself can be expressed in an interpGrp element, which would replace the spanGrp in the example shown above:


Any of these interp elements may be linked to the text either by means of the ana attribute, or by means of link elements. Using the ana attribute (on seg elements introduced specifically for this purpose), the text would be encoded as follows:
  <p xml:id="PP1">
   <seg xml:id="SS1-SS3" ana="#INTRO">
    <s xml:id="SS1">Sigmund ... was a king in Frankish country.</s>
    <s xml:id="SS2">Sinfiotli was the eldest of his sons.</s>
    <s xml:id="SS3">Borghild, Sigmund's wife, had a brother ... </s>
   </seg>
   <s xml:id="SS4A" ana="#CONFLICT">But Sinfiotli ... wooed the same woman</s>
   <s xml:id="SS4B" ana="#CLIMAX">and Sinfiotli killed him over it.</s>
   <seg xml:id="SS5-SS17" ana="#REVENGE">
    <s xml:id="SS5">And when he came home, ... she was obliged to accept it.</s>
    <s xml:id="SS6">At the funeral feast Borghild was serving beer.</s>
    <s xml:id="SS17">Sinfiotli drank it off and at once fell dead.</s>
   </seg>
  </p>
  <anchor xml:id="NIL1" ana="#RECONCIL"/>
  <p xml:id="PP2">Sigmund carried him a long way in his arms ... </p>
  <p xml:id="PP3">King Sigmund lived a long time in Denmark ... </p>
  <p xml:id="PP4">Sigmund and all his sons were tall ... </p>
  <join xml:id="PP2-PP4" target="#PP2 #PP3 #PP4" ana="#AFTERM"/>
  ********
  <interpGrp resp="#TMA" type="structuralUnit">
    <interp xml:id="INTRO">introduction</interp>
    <interp xml:id="CONFLICT">conflict</interp>
    <interp xml:id="CLIMAX">climax</interp>
    <interp xml:id="REVENGE">revenge</interp>
    <interp xml:id="RECONCIL">reconciliation</interp>
    <interp xml:id="AFTERM">aftermath</interp>
  </interpGrp>
  ......
  <linkGrp targFunc="interpretation text">
   <link target="#INTRO    #SS1-SS3"/>
   <link target="#CONFLICT #SS4A"/>
   <link target="#CLIMAX   #SS4B"/>
   <link target="#REVENGE  #SS5-SS17"/>
   <link target="#RECONCIL #NIL1"/>
   <link target="#AFTERM   #PP2-PP4"/>
  </linkGrp>


The linkage may also be accomplished using a linkGrp element, whose content is a set of link elements which point to each interpretive element and its corresponding text unit. This method does not require the use of the ana attribute on the text units.


![important][advantage of using] __interp__ rather than __span__ is that it can be reused for marking up other texts in the same document, whereas __span__cannot. On the other hand, the use of interp elements may require the creation of special text elements not otherwise needed (e.g. the seg and the join in the revised encoding of the text), whereas the use of span elements does not.


## 17.4 Linguistic Annotation
[etc](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/AI.html#AILA)


> annotation determined by an analysis of linguistic features of the text (such as a word-class or part-of-speech code, relationships such as cohesion)

example of such analysis (for "The victim's friends told police that Kruger drove into the quarry and never surfaced."):
  .......
  <s>
    <w ana="#AT0">The </w>
    <w ana="#NN1">victim</w>
    <w ana="#POS">'s</w>
    <w ana="#NN2">friends </w>
    <w ana="#VVD">told </w>
    <w ana="#NN2">police </w>
    <w ana="#CJT">that </w>
    <w ana="#NP0">Kruger </w>
    <w ana="#VVD">drove </w>
    <w ana="#PRP">into </w>
    <w ana="#AT0">the </w>
    <w ana="#NN1">quarry </w>
    <w ana="#CJC">and </w>
    <w ana="#AV0">never </w>
    <w ana="#VVD">surfaced</w>
  </s>
  .......
  <interpGrp type="POS">
    <interp xml:id="AT0">Definite article</interp>
    <interp xml:id="AV0">Adverb</interp>
    <interp xml:id="CJC">Conjunction</interp>
    <interp xml:id="CJT">Relative that</interp>
    <interp xml:id="NN1">Noun singular</interp>
    <interp xml:id="NN2">Noun plural</interp>
    <interp xml:id="NP0">Proper noun</interp>
    <interp xml:id="POS">Genitive marker</interp>
    <interp xml:id="PRP">Preposition</interp>
    <interp xml:id="VVD">Verb past tense</interp>
  </interpGrp>
  .......

-------

## 18.2 Elementary Feature Structures and the Binary Feature Value
[more](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/FS.html#FSBI)


Fundamental elements used to represent feature structure analysis are:
  __f__ (for feature), which represents a feature-value pair (has a *required* _name_ attribute and an associated value)
  __fs__ (for feature structure), which represents a structure made up of such feature-value pairs (has an optional _type_ attribute which may be used to represent typed feature structures)

> An fs element containing f elements with binary values can be straightforwardly used to encode the matrices of feature-value specifications for phonetic segments, such as the following for the English segment [s]. This representation may be encoded in XML as follows:

......
  <fs type="phonological_segments">
   <f name="consonantal">
    <binary value="true"/>
   </f>
   <f name="vocalic">
    <binary value="false"/>
   </f>
   <f name="voiced">
    <binary value="false"/>
   </f>
   <f name="anterior">
    <binary value="true"/>
   </f>
   <f name="coronal">
    <binary value="true"/>
   </f>
   <f name="continuant">
    <binary value="true"/>
   </f>
   <f name="strident">
    <binary value="true"/>
   </f>
  </fs>
......

  > **restriction of specific features** to specific types of values (e.g. restriction to a binary value) requires additional validation (at document level -using special purpose processing-, at schema level -additional validation rules-, or at declarative level, using an additional mechanism such as the feature-system declaration discussed in 18.11 Feature System Declaration.



## 20.3 Fragmentation and Reconstitution of Virtual Elements

A third method involves breaking what might be considered a single logical (but non-nesting) element into multiple smaller structural elements that fit within the dominant hierarchy but can be reconstituted virtually. For example, if a passage of direct discourse begins in the middle of one paragraph and continues for several more paragraphs, one could encode the passage as a series of said elements, each fitting within a p element. The resulting encoding is valid XML, but the text in each said element represents only a portion of the complete passage of direct discourse. For this reason these elements are sometimes called ‘partial elements’.

In the case of our selection from Pinsky's poem, for example, the second passage of direct quotation, which crosses a line boundary and is broken up by a She said in the narrator's voice, can be made to fit within the hierarchy established by the metrical lineation by using two said elements:

<lg>
 <l>Catholic woman of twenty-seven with five children</l>
 <l>And a first-rate body—pointed her finger</l>
 <l>at the back of one certain man and asked me,</l>
 <l>
  <said n="quotation1">Is that guy a psychiatrist?</said> and by god he was!
 <said n="quotation2">Yes,</said>
 </l>
 <l>She said, <said n="quotation2">He <emph>looks</emph> like a
     psychiatrist.</said>
 </l>
 <l>Grown quiet, I looked at his pink back, and thought.</l>
</lg>

## 23.3 Personalization and Customization
[more](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/USE.html#MD)

> The recommended way of implementing and documenting all such modifications is by means of the ODD system described in chapter 22 Documentation Elements

### 23.3.1 Kinds of Modification

- deletion of elements;
- renaming of elements;
- modification of content models;
- modification of attribute and attribute-value lists;
- modification of class membership;
- addition of new elements.

#### 23.3.1.1 Deletion of Elements

done by setting _mode_ attribute to 'delete' on elementSpec for element concerned

example (suppressing __note__) :

......
  <schemaSpec ident="mySchema">
    <moduleRef key="core"/>
    <!-- other modules used by this schema -->
    <elementSpec ident="note" module="core" mode="delete"/>
  </schemaSpec>
......


> some elements in TEI have mandatory children (ie __fileDesc__ must contain both a titleStmt and a sourceDesc), so check further what to do

#### 23.3.1.2 Renaming of Elements

Every element in TEI scheme has a canonical name (usually in English, provided as a value of _ident_  on __elementSpec__, __attDef__, __classSpec__, or __macroSpec__ used to define it)

We can have many alternative identifiers for the same markup (ODD processor may choose which of them to use). Alternative names are supplied by __altIdent__  within specification element concerned:

......
  <elementSpec ident="note" module="core" mode="change">
    <altIdent>annotation</altIdent>
    <!-- "note" also named "annotation" -->
  </elementSpec>

> The content of the altIdent element will be used in place of the canonical ident value in the schema generated.
> Renaming in this way is always a reversible modification.
......

#### 23.3.1.3 Modification of Content Models

The content model for an element in the TEI scheme is defined by means of a content element within the elementSpec which specifies it. As shown elsewhere in these Guidelines, the content model is defined using RELAX NG syntax, whether the resulting schema is expressed in RELAX NG or in some other schema language.

For example, the specification for the element term provided by the Guidelines contains a content element like the following:
......
  <content>
    <rng:ref name="macro.phraseSeq"/>
  </content>
......

This indicates that the content model contains declarations taken from the RELAX NG namespace, and that it consists of a reference to a pattern called macro.phraseSeq. 

Pattern "macro.phraseSeq" expands to an optional [...] three classes (model.gLike, model.phrase, or model.global). If it is -ie- preferable to insist that __term__ should only contain plain text we can do this thus:
......
  <elementSpec ident="term" module="core" mode="change">
    <content>
      <rng:text/> <!-- replace broader "rng:ref" with "rng:text" for term-->
    </content>
  </elementSpec>

> This is a clean modification which does not change the meaning of a TEI element
> Note: content models are generally defined in terms of references to model classes, rather than to explicit elements. It is not (in general) good practice to replace class references by explicit element references.


......



#### 23.3.1.4 Modification of Attribute and Attribute Value Lists

Attributes applicable to an element may be specified in two ways:
- may be given explicitly, by __attList__ element within corresponding elementSpec
- may be inherited from an attribute class, as specified in the classes element

To _add a new attribute_, first check to see whether it is already defined by an existing attribute class. If it is, the simplest method of adding it will be to make the element in question a member of that class. If this is not possible, then a new __attDef__ must be added to existing __attList__ for element in question


> *‘content’ of an attribute* is defined by means of the datatype, valList, or valDesc elements within the attDef element. So we can also replace or extend the valList supplied as part of any attribute in the TEI scheme.


#### [23.3.1.5 Class Modification][forget it]


#### [23.3.1.6 Addition of New Elements][maybe consider]

To add a completely new element into a schema involves providing a complete element specification for it, the classes element of which includes a reference to at least one TEI model class. Without such a reference, the new element will not be referenced by the content model of any other TEI element, and will therefore be inaccessible within a TEI document.
