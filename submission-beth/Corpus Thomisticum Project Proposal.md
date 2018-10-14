# Corpus Thomisticum Project Proposal

This proposal outlines a design for a readable, easy to use and creative user interface for the works of Thomas Aquinas, that uses data visualisation to allow users to draw connections, and to read in detail without losing perspective of the larger context of St Thomas' works. I achieve this by representing the structure of the text as a tree, allowing easy navigation and visual representation of search results.

A 2 minute video summary of the proposal can be found here: https://www.youtube.com/watch?v=rcOv7RC3tLY&feature=youtu.be



## Structure

Thomas Aquinas' works are highly structured arguments. For example, here is a quote from the Summa Theologica:

>Because the chief aim of sacred doctrine is to teach the knowledge of God, not only as He is in Himself, but also as He is the beginning of things and their last end, and especially of rational creatures, as is clear from what has been already said, therefore, in our endeavor to expound this science, we shall treat: (1) Of God; (2) Of the rational creature's advance towards God; (3) Of Christ, Who as man, is our way to God.
In treating of God there will be a threefold division, for we shall consider: (1) Whatever concerns the Divine Essence; (2) Whatever concerns the distinctions of Persons; (3) Whatever concerns the procession of creatures from Him.
Concerning the Divine Essence, we must consider: (1) Whether God exists? (2) The manner of His existence, or, rather, what is NOT the manner of His existence; (3) Whatever concerns His operations---namely, His knowledge, will, power.
Concerning the first, there are three points of inquiry:
(1) Whether the proposition "God exists" is self-evident?
(2) Whether it is demonstrable?
(3) Whether God exists?

This section introduces the structure of the entire book, but is difficult to keep track of when reading through the rest of the text. A visual representation is much easier to comprehend, as shown by the simple diagram below.

Although not every one of Thomas Aquinas' works has such a clear internal structure, they are all logical arguments which can be split into subsections in a similar way.

In many of the works, the text is set out in articles, and each article has its own structure. St Thomas starts by listing arguments from the opposing viewpoint as robustly as possible, stating his position, expanding on his position, and then replying to each of the objections in turn. 

![Summa](https://github.com/1mwtt-soc1/corpus-thomisticum-hackathon-beth/blob/submission-beth/SummaTree.png)

**Figure 1:** Structure of the Summa Theologica showing the first 13 questions, demonstrating the branching of the sections. *Inset:* the cyclical structure of the whole text (copied from ref [1](https://en.wikipedia.org/wiki/Summa_Theologica)).



## Visual representation of structure

The above image looks something like a tree. There are many examples <sup>([2](http://www.scottbot.net/HIAL/index.html@p=39166.html)) </sup> of knowledge being represented as a tree in medieval texts, some of which are pictured below. Splitting knowledge into categories which build on each other was widely used as a technique for learning and memorisation.
<sup>([3](http://csis.pace.edu/~marchese/Papers/IV13/Marchese_Virtues_and_Vices.pdf),
[4](http://blog.wellcomelibrary.org/2016/04/spotlight-a-medieval-tree-of-knowledge/))</sup>

<img src="https://upload.wikimedia.org/wikipedia/commons/c/c0/Virtues_Speculum_Virginum_W72_26r.jpg" alt="Tree of Virtues" height="400">    <img src="https://upload.wikimedia.org/wikipedia/commons/c/c9/Arbor-scientiae.png" alt="Arbor Scientiae" height="400">

**Figure 2:** Tree of virtues (Specullum Virginum) and Tree of science (Ramon Lull)
	
The tree is thus a fitting representation of the works of Thomas Aquinas, since it both accurately fits the argument structure, and was also in common use at the time. It would also enhance the visual appeal of the text, being reminiscent of the way in which medieval texts were illuminated with beautiful images and diagrams.

Figure 3 shows a representation of the Summa Theologica as a tree. The first branch (God -> Divine essence) is drawn accurately but the rest is simplified. The questions are represented by the leaves on the tree, and the branches show how they relate to each other.

![Summa Tree](https://github.com/1mwtt-soc1/corpus-thomisticum-hackathon-beth/blob/submission-beth/MyTreeUpdate3.jpg)
	
**Figure 3:** Drawing of a tree, representing the Summa Theologica (simplified)
	
In addition, the Summa Theologica has a cyclical structure, whereby the arguments move from one to the next logically, and come full circle to God where the argument started (see inset to Figure 1). This is also represented nicely by the tree, since the questions are in order clockwise around the tree in a circle.

## User interface

The current digital text of the Corpus Thomisticum is functional but difficult to use, and can be frustrating to navigate. The aim of this project is to design an easy to use and visually appealing interface for reading these valuable texts. As well as improving the experience of people who already read these works, it is likely to open them up to a wider audience by increasing their accessibility and usability, which will allow the public to access, enjoy and benefit from these works. The interface should be kept as intuitive as possible, with a simple uncluttered design that can be displayed on smaller screen sizes (eg. iPad).

The tree representation would be central to the website, adding aesthetic appeal, allowing easy navigation and highlighting where the reader is in the text as a whole. This helps the user to keep a sense of perspective of how articles are related to each other. It can also be used to highlight searchable keywords or themes and give an instant visual representation of where they appear in the text. This will help in drawing connections and patterns between different parts of the text.

Representing multiple works as one tree is likely to make the image overcrowded and therefore lose functionality. My suggestion would be that each book, or collection of shorter works, is visualised as one tree. The collection of books can then be represented as a virtual book shelf, so that any work is easily accessible. Even if the website began with only one work, this would allow room for expansion as more works are added.


### Landing page

Landing pages today are designed to be as simple as possible to direct the user straight to where they want to go <sup>([5](https://www.forbes.com/sites/johnrampton/2016/07/21/10-examples-of-amazing-landing-pages/#6fceff077b08))</sup>. For this project the landing page would allow you to click on a work and start reading in the 'Reader view', or search for a keyword, which would take you to the 'Search view'.

![Landing page](https://github.com/1mwtt-soc1/corpus-thomisticum-hackathon-beth/blob/submission-beth/LandingPage%20copy.jpg)

**Figure 4:** Landing page for the Corpus Thomisticum website

As shown in Figure 4, the texts are represented as books on a bookshelf, with clearly labelled spines. The size of the book should correspond to the length of the text, allowing the user to identify the major works at a glance. When a book is clicked, the corresponding tree opens up. Clicking on the trunk takes the user to the first page of the text in the 'Reader view'. Clicking on a branch takes the user to the first page of that section or subsection. Clicking on a leaf would take you to the smallest division of the text, which in the case of the Summa Theologica would be a question (there are too many articles to view these as separate leaves).

The book and tree images used are placeholders for artwork designed specifically for the purpose. In reality the tree would have its leaves around the outside of the tree, and it would therefore be clearer to see which of the main branches the leaves belong to.

The tree image is actually an 18th century family tree in the public domain, sourced from [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Naryshkin_family_tree.jpg).
The bookshelf image is free for commercial and non-commercial use from [Pexels](https://www.pexels.com)


### Reader view

![Reader view](https://github.com/1mwtt-soc1/corpus-thomisticum-hackathon-beth/blob/submission-beth/ReadingPage_search.jpg)

**Figure 5:** Reader view, with a highlighted search word

The reader view consists of a large pane for reading the text, a search pane, and an image of the tree showing where the text you are viewing is located in the whole. The reading pane has the section and subsections marked at the top. The user can navigate to different sections of the text by clicking on the subsection header they want to change, or by selecting a different part of the tree. The tree can be expanded by clicking the expansion button at the bottom right corner of the tree.

The reading pane can be split into two parts for reading in two different languages, or comparing two sections of a text in the same language. When using two languages, the texts will both navigate to the same section if one is changed, and scroll together. This could be indicated by a padlock symbol between the panes, which the user can unclick if they prefer.

Clicking on a word in the text brings up the definition and a list of occurrences in the search pane. It also highlights which other parts of the text this word is found in on the tree, and on the spines of the books on the bookshelf. Clicking on one of these occurrences, either in the search pane or on the tree, loads that section in the reading pane.

To start reading a different book, the reader can select one off the bookshelf, which is always at the top of the screen.


### Search view

![Search view](https://github.com/1mwtt-soc1/corpus-thomisticum-hackathon-beth/blob/submission-beth/SearchPage%20copy.jpg)

**Figure 6:** Search view, with a highlighted search word

The search view can be accessed either from the landing page, or by clicking 'search all' after making a search in the reader view. This view allows all the works to be searched and compared. The texts with the most occurrences of the search word are shown as trees, with the location of the words highlighted on the leaves. These books are shown missing from the bookshelf, since they are 'open'. Other texts have words highlighted on the spines of the corresponding book on the bookshelf. The user may close open books (trees) and open others from the bookshelf to explore further. They may also expand a tree for an enlarged view. Clicking on a section of the tree would open this portion of the text in the reader view, as before. The user may return to the text they last viewed by clicking on an icon of the reader view located at the top of the screen. The 'back' button in the browser would offer the same function. This will help the user not to get lost.


## Feasibility

There are two main considerations for determining the feasibility of this project. Firstly, whether this idea will work with such a large volume of text, and secondly what resources are needed.

### Scale

The texts we are looking at are very large. It is important to determine whether this representation will be feasible or whether the layout will be too crowded and unreadable.

There are a total of 431 questions in the Summa Theologica, which is the largest of the texts. This number of leaves should be possible to fit onto the tree. The layout of the tree should be neat and orderly, and the branches of the tree should be clearly labelled. It will not be possible to fit legible labels onto all of the leaves so the number of the question could appear but not its name. However it will be clear from the branches what the approximate topic of the question is. The questions in the Summa Theological and other works already have a conventional numbering system, so this would make navigating easy for those acquainted with the works.

If the thumbnail in the reader view is too small to make the tree diagram helpful, the thumbnail could show the branch for the relevant part of the text, rather than the whole tree. The beauty of using a tree representation is that a branch of the tree has the same look as the whole tree (since it is somewhat fractal-like), so the concept can work at any scale (see Figure 7).

![Zoomed tree](https://github.com/1mwtt-soc1/corpus-thomisticum-hackathon-beth/blob/submission-beth/TreeThumbnail2.jpg)

**Figure 7:** Zoomed in tree, showing how the reader view thumbnail could show a part of the text whilst keeping the same concept.


### Resources
This user interface can be implemented using standard features of modern web development languages.
The search functionality may be able to incorporate existing resources, such as Perseus <sup>([6](http://www.perseus.tufts.edu))</sup>, which is already included on the existing corpusthomisticum website <sup>([7](http://www.corpusthomisticum.org))</sup>.
The project would require a collaboration between 
- a web developer, 
- a graphic designer who can design the tree images,
- an expert in the works of Thomas Aquinas who can make sure the text is appropriately sectioned and suggest functionality improvements.

It may also be possible to automate the process of sectioning the text and making the tree. This would make adding additional works easier. Sectioning the text would likely require some knowledge of natural language processing.


## Additional Functionality

Additional functionality is optional and could be added at a later stage by adding buttons that open up options for more advanced users. This should be done in a way that does not detract from the experience of the uninitiated user by overcrowding the screen.

### Zooming in

An additional function would be to allow the user to zoom in and see a higher resolution image. For example, when the leaves (questions) are expanded, they could resolve into a branch of multiple leaves (articles). Further zooming in on an individual leaf could reveal the argument structure (objections and responses) as the veins on the leaf. This would also mean that the search function could pinpoint words with increasing accuracy as the user zooms in - for books on the a section is highlighted on the spine, for an expanded tree a question is highlighted (whole leaf), for a zoomed in tree an article, or even a line in an article is highlighted (see Figure 8).

![Zoomed Branch](https://github.com/1mwtt-soc1/corpus-thomisticum-hackathon-beth/blob/submission-beth/BranchZoom.jpg)

**Figure 8:** Zooming in to reveal more detailed structure - question to article to argument.

### Personal account

The 'log in' button should allow users to register with an email address. Once they have logged in, buttons would appear to allow the user to highlight or annotate text, and to save a favourite article or search term. The 'log in' button would be replaced with their account name. Clicking here would open a side panel with a number of features such as access to saved pages, saved searches and the user's own annotations. Adding an annotation would add an icon next to that section of the text. Clicking on the icon would bring up the annotation text in the 'search pane' alongside the text. Alternatively it could expand in the screen when the user hovers over it.

As a further extension, searches could be saved for a particular book and could appear as roots on the tree in the search view, which when clicked would highlight the relevant branches.

### References to other texts

The works that Thomas Aquinas cites are often available online, as ebooks <sup>([8](https://ebooks.adelaide.edu.au/a/aristotle/a8poa/book1.html),[9](http://www.ccel.org/ccel/schaff/npnf209.iii.iv.i.i.html))</sup> or (in the case of the Bible) an advanced digital humanities project <sup>([10](https://www.stepbible.org))</sup>. Where St Thomas cites other works, clicking the reference should display the relevant quotation in the 'Search pane'. This can be collected from other online digital texts, whatever their current state of readability. There could be a 'see more' button at the bottom of the box which would open the relevant website to display the source text in a new tab. A further addition could be to allow the user to view these texts in the second reader pane, alongside St Thomas' work.

Alternatively, there is already a plugin available to view Bible quotes when you hover over a reference with the mouse (available from ref [11](https://biblia.com)).

### Commentaries on the works of St Thomas Aquinas

The second reading pane could give an option to view a commentary on the section of text currently being viewed.


### Multiple reader panes

The screen could be further split (e.g. into 4) by pressing a '+' button (see ref [10](https://www.stepbible.org) for a working example). This would allow for multiple translations and/or secondary texts to be viewed simultaneously.

### Number of books

This layout will work best with a limited collection of books such that the user can visually see them all collected on a bookshelf at the top of the screen. Before undertaking this project, the traffic of the corpusthomistum website could be analysed to determine which are the most used works. Additional works that are not part of the main canon (e.g. those of dubious authorship), could perhaps be included as one volume on the shelf. Signed in users could have an option to 'favourite' some volumes, which would reorder their position on the shelf.

## Accessibility

Options for viewing the website with larger text and compatibility with screen-readers (text to voice software) should be included. I have also chosen the colour scheme such that the colours should still be distinguishable to people who are colour blind, checked using a colour blindness simulator <sup>([12](https://www.color-blindness.com/coblis-color-blindness-simulator))</sup>.


## References

Accessed October 2018

1. https://en.wikipedia.org/wiki/Summa_Theologica
2. www.scottbot.net/HIAL/index.html@p=39166.html
3. http://csis.pace.edu/~marchese/Papers/IV13/Marchese_Virtues_and_Vices.pdf
4. http://blog.wellcomelibrary.org/2016/04/spotlight-a-medieval-tree-of-knowledge/ 
5. www.forbes.com/sites/johnrampton/2016/07/21/10-examples-of-amazing-landing-pages/#6fceff077b08
6. www.perseus.tufts.edu
7. www.corpusthomisticum.org
8. https://ebooks.adelaide.edu.au/a/aristotle/a8poa/book1.html
9. http://www.ccel.org/ccel/schaff/npnf209.iii.iv.i.i.html
10. https://www.stepbible.org
11. https://biblia.com
12. https://www.color-blindness.com/coblis-color-blindness-simulator
