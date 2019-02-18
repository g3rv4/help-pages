Title: established user
Subtitle: You've been around for a while; see vote counts

###What are Established Users?

Established users are those who have been participating on the site for a fair amount of time. They gain the following privileges.

 - They may view the vote counts on posts
 - An expanded usercard will show additional profile information

### How do I view vote counts?

Voting *scores*, as displayed, are the sum of the up and down votes on a post. Vote *counts* are the individual up and down votes that make up the score.

You can view the vote counts by clicking on the score of a post. This will break the score into upvotes and downvotes, like so:

![vote count click][1]

The upvotes have a plus sign next to them and are displayed as the top number, in green. The downvotes have a negative sign next to them and are displayed as the bottom number, in red.

### How do people see an expanded usercard?

When anyone is viewing your usercard on a question, an answer, or on the users list, they may hover over your avatar to produce an expanded usercard that contains extra information. This is also known as a *hover card*.

![Comparison of normal usercard and expanded usercard][2]

An expanded usercard is only available if there are at least 28 characters in the "About Me" section of your profile. When your profile is long enough to show an expanded usercard a drop shadow effect will be shown on your avatar.

![Image of drop shadow versus normal][4]

### What information is shown on the expanded usercard?

Your expanded usercard will show the following information:

 - A larger resolution of your **avatar**
 - Your **display name** linked to your profile
 - Your **reputation and badges**
 - Your **Location**, if you have entered one on your profile
 - A **link to your Website**, if you have entered one on your profile
 - Your **About Me** section. Up to the first 298 characters will be displayed as the meat of your expanded usercard. HTML links and linebreaks/paragraphs will be rendered, but not formatting such as bold.
 - Any **additional HTML links** will be displayed and linked at the bottom of the expanded usercard. This does not repeat any links that are already shown in the previous part.

If you don't want the exact text of your About Me section there (such as it is too long and gets cut off, or because the formatting is weird), then you may use a summary comment using the following syntax:

    <!-- summary: [your text here] -->

Replace `[your text here]` with your desired summary (of at least 28 characters), and that will be placed on your expanded usercard in place of your About Me section. Note that because it is an HTML comment, you cannot use any HTML such as for links. The spaces before and after `summary:` and before the closing `-->` are required to use a summary.

### What if I don't want an expanded usercard to show?

If you have a long profile About Me, but don't want there to be an expanded usercard for any reason, you can use the summary comment with an insufficiently long passage to render your profile as "too short" for display. For example, the following will be considered too short.

    <!-- summary: &nbsp; -->


  [1]: http://i.stack.imgur.com/yi9X8.png
  [2]: http://i.stack.imgur.com/j9wxl.png
  [3]: http://i.stack.imgur.com/fSPak.png
  [4]: http://i.stack.imgur.com/CF03C.png
