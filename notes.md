# Cancer case study
- Good pathway to focus on: **mevalonate pathway** (Rohrig and Schulze)
  - It is essential for producing isoprenoids that act as building blocks for many compounds including steroids and cholesterol
  - Is it already in WikiPathways?
    - Not for homo sapiens but for yeast [here](http://www.wikipathways.org/index.php/Pathway:WP483)
    - The statin pathway is available for homo-sapiens [here](http://www.wikipathways.org/index.php/Pathway:WP430)
  - the pathway is highly druggable

# Notes/Ideas
- UI - "story flow"
  - On top of green links
  - Make the PVJS diagram static on page
  - As user scrolls, the diagram updates (highlights?) the section that is being described
- How can make annotations machine readable? Should it be done?
  - I.e. the content that the editor highlights with green links being machine readable. So know that one bit of a pathway is associated with one bit of text
  - PVJS provides an opportunity to create a **standardised widget/plugin** that all pathway databases can use

# Questions
- How should cancer be integrated?
  - Into the project. I assume to just use it as a case study like above.
  - BTW: I made the GPML of the mevalonate pathway but the upload tool is currently broken on WikiPathways. Johnathon is on it.
- Testing? Test new interface on users
  - If manage to actually get an interface up and running. Can I test it on others? Get feedback
- **UI Story flow** (see notes/ideas)
- Improved research question (see below)
- **Machine readability** (see above).
  - Would be nice if any annotations I add are machine readable too. So, somehow in GMPL include an anchor to that section of text on WP. Or include the text itself as meta info
  - So how are the descriptions stored on WP?
- RE: **Timeline**
  - What tasks need doing?
  - Something like:
    - Get a rudimentary page up and running with latest PVJS (end of feb)
    - Figure out how to highlight parts of the diagram, zoom in etc.
    - Preliminary green links interface testing
    - Implement some kind of Framework/library (Angular/React) to display text alongside diagram with green links and/or story UI
    - Final green links interface testing
    - Implement storage mechanism of green links in Framework
    - Implement green links into WP editor
    - Test editing
    - Into WP
  - *Note: I realise a portion of this won't come into fruition during my thesis*
- **Not for now (probably) but idea that came up:**
  - PVJS gives the possibility to create a shareable widget for pathway visualisation. Think Youtube embed.
  - People can copy the code from WikiPathways or (as they could already but docs are outdated) natively embed it with jQuery in there own site using own GPML.
  - Would be nice to see other pathway DBs use pvjs to display their pathways if the community moves onto GPML (or other standard)
  - Maybe you already thought about this but the possibility for a standard diagram across many platforms seems exciting. Javascript is used everywhere!

# Research Question
"Are pathways in GPML and pvjs of sufficient quality to interactively
explain in a educational webpage how cancer metabolism deviates from the
normal cell metabolism?"

## Improve to:
Are pathways in GPML and pvjs of sufficient quality to interactively
explain in a educational webpage how certain metabolic pathways function? Here, using the example of cancer metabolism and how it deviates from normal cell metabolism. (maybe some better wording)
