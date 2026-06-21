The Seybold Report on Publishing Systems\
Volume 20, Number 3\
October 8, 1990

# Interleaf 5: A Complete Overhaul of TPS

*This article presents an overview of Interleaf’s announcement of its new Interleaf 5 technology October 3 at the Seybold Computer Publishing Conference. Although it looks much like TPS, Interleaf 5 is a radical departure for the company. Rather than merely add features to TPS, Interleaf has taken it apart and constructed a set of programmable modules that may be tied together in a variety of ways and may be accessed by users or other vendors. A central component of all of the modules is the ability to tailor any aspect of the system—even to program a document to do certain things without operator intervention, what Interleaf calls “active documents.” In addition, several key changes to the underlying composition engine will enable Interleaf to bring its software into alignment with contemporary operating environments. To publish the information in a timely fashion, we prepared this story in advance, based on visits to Interleaf.*

INTERLEAF’S Technical Publishing Software (TPS) has been the leading publishing software for Unix workstations for several years, but in the past year or so the company’s stature has diminished. Its desktop programs—Interleaf Publisher for PCs and Macintoshes—have both sold sluggishly and did not establish Interleaf in the mass market the way it had hoped. At the same time, the company has been undergoing a rough transition from selling the turnkey systems that were once its core business to selling just software and services, such as consulting, training and support.

Interleaf faced several problems. First, its unique combination of a fast WYSIWYG text editor and superior graphics editors were no longer sufficient differentiators in the market. Its workstation software sales remained strong, but the competition in the PC and Mac markets foreshadowed rising competition on the Unix front. As FrameMaker, Ventura and other competitors advanced from the low end, Interleaf needed a product that was immediately recognizable as more advanced than its competition. At the same time, its advanced features had to be valuable to customers.

Another issue Interleaf faced was its user interface. The desktop it created in the early 1980s—before graphical user interfaces were generally available for computers—has become a liability in the general software marketplace, where applications are now expected to follow the graphical user interface supplied by the computer manufacturer. Thus, at the same time that Interleaf needed sophistication, it needed a product that was consistent, from users’ standpoints, with other applications they might run on their computer desktops.

Interleaf’s answer was to peel apart much of its TPS product and create a toolkit from which software applications may be built. The toolkit fits Interleaf’s view of its role in the industry—it must broaden its services at the same time that it focuses on solving specific industry and customer problems. The toolkit also will enable Interleaf to offer a consistent base level of software across all of its platforms and, starting next year, to offer products that comply with other graphical user interfaces.

------------------------------------------------------------------------

![](/img/seybold-1990-3-000.jpg)

**Interleaf 5 In OpenWindows environment.** Interleaf’s new software looks much like TPS, but key changes were made beneath the surface. Here it is running inside Sun’s X-based windowing technology, OpenWindows, although it does not yet make use of the Open Look user interface.

------------------------------------------------------------------------

One of Interleaf 5’s distinguishing traits is its support for “active documents.” In rebuilding its software, Interleaf has made every component of a document, both text and graphics, an object that may have programmable attributes. We wrote about Interleaf’s active documents concept when it was introduced at the Seybold Seminars last March *(see Vol. 19, No. 14).* With the introduction of Interleaf 5, this feature is now realized in a product.

In one sense, Interleaf 5 is Interleaf’s seventh major release to TPS in eight years. From that point of view, Interleaf 5 is TPS 5.0—TPS as we know it with the addition of some programming extensions.

At first glance, there is little in Interleaf 5 to differentiate it from TPS 4.0. But a closer examination reveals fundamental, underlying differences in the new code. According to Steve Pelletier, Interleaf’s chief technical officer, the guts of TPS were overhauled more in this release than in any other. There are three main areas in which the overhaul is significant:

- **Modular architecture.** Interleaf is calling Interleaf 5 an open architecture, but “open” means many different things to different people. In Interleaf 5, the architecture is a modular system that is programmable at every level, allowing it to run on a variety of hardware and software platforms and to be tightly coupled with many application programs. It is the first publishing product that was designed for integrating publishing-specific functions with other applications all driven from a document model. And it is one of the few on the market that offer a built-in language and interpreter for attaching scripts to objects within a document or documents as a whole. Other programs are extendible, but few, if any, offer the breadth of programmability found in Interleaf 5.
- **Font architecture.** Interleaf has scrapped its bitmapped font approach in favor of an outline-based technology that will be part of all Interleaf 5-based products. Initially, it is relying on Bitstream’s Speedo, but it has made provisions for supporting other font outlining technology. The outlining allows arbitrary sizing of fonts and their display on the screen.
- **Windowing/user interface.** The user interface rewrite is perhaps the most difficult of all, which is why it was not finished in time for the show. Interleaf has always relied on its own windowing manager—even when running within another graphical windowing environment. Now it is cutting the cord between engine and display, relying as much as possible on external system software for window functions. In its initial release, Interleaf 5 is an X application, running on top of X Window with the TPS interface. By next year, Interleaf will have made it possible to invoke one of several user interfaces from the same engine, enabling it to introduce Motif, Open Look and Macintosh interface products in 1991, with Presentation Manager a possibility for 1992.

From a hardware perspective, the Interleaf 5 engine is being offered on Sun, DEC, IBM, Apollo and HP Unix workstations, IBM-compatible PCs under MS-DOS and the Apple Macintosh. However, the LISP extensions that tweak the engine and documents to user requirements need only be written once because the LISP interpreter supplied as part of the engine is the same across all of the platforms.

----

> [!NOTE]
> Interleaf's engine is composed of discrete objects that may be pieced together—and extended—through LISP.

----

**Entering new territory.** The major overhauls in these areas result in a fundamentally new product for Interleaf—hence its new name. But Interleaf 5 has close ties to TPS 4.0, which is why Interleaf stayed with the number 5. After looking at it, we see Interleaf 5 as one of a new class of publishing products. Part engine, part development environment, part end-user packages—in total, we can only describe it as the active document environment from which a family of products are being developed to meet general horizontal applications and specific vertical market solutions.

Yes, Interleaf can still offer a shrink-wrapped product targeted at a mass audience. And it is introducing several such packages at the Conference. But we think it far more likely that initial demand for the product will come from high-volume corporate publishers looking for systems that do more than put text and graphics on pages. Eventually, as VARs and even end users grow accustomed to creating active documents and

personalized publishing software, Interleaf could penetrate the mass market with an Interleaf 5-based product. The look and functionality of its PC and Macintosh versions, not due out until next year, will be critical to its success in the mass market.

For now, we view Interleaf 5 as a general-purpose toolkit from which Interleaf, other developers, VARs and sophisticated end users will build information management tools. It is almost like a database manager in that the vendor provides basic software to end users from which other applications may be derived, then offers as a service custom-built solutions.

Unlike most publishing software, Interleaf 5 has the potential to interact closely with other applications. By this we mean more than just filters that allow cutting and pasting between documents, or live links that dynamically bring in information. The recent trend at the high end of the market is to develop publishing tools that interact directly with a database, which opens new dimensions to the term electronic publishing.

If Interleaf were new to the market, we would probably begin by describing the core engine of Interleaf 5. But we now presume that most of our readers have at least a passing acquaintance with Interleaf TPS. Basically, the engine has all of the TPS functional code; now it’s just constructed differently. We’ll discuss in detail its new underlying construction, followed by an overview of the new features, a glimpse of what it may look like to an end user and a discussion of how it is being packaged, marketed and sold.

## **Interleaf 5's construction**

**Modular architecture.** At Interleaf 5’s core is an engine of modules programmed in C. As with previous Interleaf products, these modules are optimized as much as possible for performance without being tied to specific operating systems or hardware. But unlike previous versions, Interleaf 5’s engine is composed of discrete objects that may be pieced together—and extended—through Interleaf’s LISP-based programming language. Whereas the code for activating and displaying the engine functions (h&j, pagination, graphics, etc.) was formerly also written in C and intertwined with the engine, in Interleaf 5, the code that activates the engine is LISP. Essentially, all of the engine components that were previously very different have been unified into programmable objects. Each engine component (object) has its own class and may have unique behaviors, but the fact that all are subsets of the master object class makes it possible to program actions that affect all layers of the system.

In fact, all engine objects are now viewed as LISP objects. Interleaf supplies a LISP interpreter as part of every Interleaf 5-based product. The critical difference between what Interleaf has done with Interleaf 5 and what Quark did with Xpress is that extensions written to Interleaf 5 do not become wed to the source code. LISP extensions act on objects within the system without knowing what the underlying code is at all.

The engine components—h&j, pagination, several graphics editors, font resource, translators, etc.—are functionally not that different from what is available in TPS 4.0, although there are new features. Interleaf has solved most of the problems of combining text and graphics on the page, and it has done so in a way that is extremely fast and flexible. Thus, all of the compound document editor features that it is known for are still present.

But by breaking the engine into *accessible* modules, Interleaf now makes it possible to insert external code that executes on the way into or out of one of these modules.

For example, one third-party developer is working on a hyphenation module for Interleaf 5. It will plug into the system at the engine level, so that the user will see no difference in the way the system behaves, but the composition might make better breaks in the new module, which uses ranked preferential hyphenation points.

Other extensions could be written to create a customer- configured editor—whether it be a structured editor that keeps an author within the bounds of a predetermined outline and style, a full compound document editor with a user’s favorite keyboard mappings or a form processor, in which a document is used as the interface for accessing a database.

**Great! But—LISP?** While the ability to extend a system and define new object attributes by writing your own code is a powerful feature, we wonder how many end users will feel comfortable with LISP. The language has a rather peculiar syntax with which relatively few programmers (and even fewer non-programmers) are familiar. It stands in sharp contrast to the scripting languages, such as those in HyperCard or Excel, that were designed for end-user programming. (Some cynics have even wondered if Interleaf's real purpose in picking LISP was to assure itself of lots of custom-programming business.) We suspect that users will experience some frustration in getting up to speed with the new functionality.

**Font resource.** All previous versions of Interleaf software were based on a raster-font model that provided extremely fast display but imposed a burden in disk space and limited most of its versions to discrete point sizes. With Interleaf 5, Interleaf has moved to outline-based technology that adds new functionality and decreases the program’s footprint on the disk.

Initially, Bitstream’s Speedo will be built into all versions of Interleaf 5. The LaserWriter Plus set of PostScript fonts is the standard font set for all Interleaf 5 products, but all will also support any additional Bitstream fonts the user might purchase.

The software supports arbitrary sizing of fonts to tenths of a point in sizes ranging from 4 to 400 points. In addition, the display of any document may be enlarged or reduced in single percentages ranging from 25% to 1,600% of its original size.

For the first time, Interleaf will be offering display of facing pages. If you scale the page small enough, you get as many as eight pages on the screen at one time in slightly larger than thumbnail size. No matter what size, the document is still fully editable, and text is never greeked, even when its size makes it virtually illegible.

------------------------------------------------------------------------

**Two-page display.** Using Bitstream’s Speedo technology, Interleaf 5 scales the page display to arbitrary sizes.

![](/img/seybold-1990-3-001.jpg)

------------------------------------------------------------------------

In page demonstrations we saw, zooming in or out incurred quite a performance hit as the font was rasterized. Once the font was in RAM, use of that size was quite fast.

One disappointment is that because its display technology cannot show more than two pages in a horizontal row, the thumbnail view places all of the pages in the left side of the window, leasing part of the right side empty. If Interleaf were able to display more pages horizontally, the thumbnail view could show up to 16 pages at a time.

Another limitation is that the pages must be contiguous. There is no way to display pages 1 and 16 side by side, for example.

Significantly, Interleaf has planned to make use of the font resources of operating environments that handle fonts. Thus, it plans support for Adobe Type Manager, and it could support other outline technologies (TrueType, Folio) that might become significant in the market.

Why not rely on font resource managers in X Window and other Unix environments available today? Interleaf decided that rather than offer different font capabilities on different platforms, it would offer a consistent font capability across all of its Interleaf 5-based products. The use of Speedo on all platforms will enable it to provide drivers for PostScript, Impress, IBM AFP, LeafScript and PCL 4 that permit Interleaf 5 users to print to any device that supports one of those page description languages—with full confidence that what was created on the screen will be rendered on paper or film. Assuming the printer supports downloadable fonts, the user also need not worry if the fonts chosen are resident within the printer.

Interleaf is not abandoning customers that drive devices that do not support downloadable fonts. Support for Triple-I, Compugraphic 8000 series and Monotype typesetters is still offered with Interleaf 5.

**The display and user interface.** Ever since its first product (remember OPS?), Interleaf’s trademark has been its iconic desktop and popup cascading menus. Introduced in 1983, this approach followed the Xerox Star but predated the Apple Macintosh and the new graphical user interfaces: Windows, Open Look and Motif. When it introduced its Macintosh and PC Publisher products in 1987, Interleaf made a conscious decision to offer its customer base desktop products that were consistent in look and feel with its Unix-based products.

Today the marketplace has changed. It is now an accepted fact that graphical user interfaces will be part of the standard operating system, although in the Unix world there are still at least two major interfaces to contend with (Motif and Open Look). Developers in all computer applications are being forced to adapt their programs to these graphical interfaces or face rejection in the market. For developers who are increasingly offering their products on multiple computers, the burden of adapting the interface to each environment is not trivial—unless it is planned for in the underlying code.

Interleaf’s answer will be to separate the window drawing and user interface aspects of its code completely from its underlying engine components. We say will, because this work will not be complete until 1991. In the first release, Interleaf 5 will make use of X Window for displaying windows, but it will not offer alternative user interfaces. For example, it demonstrated Interleaf 5 at the Conference running on Sun’s new OpenWindows, but it did not show support for Open Look, which is promised for 1991. This is a good example of how, on the surface, Interleaf 5 looks much like TPS, but underneath there have been significant changes.

By next year, Interleaf will be making use of the interface toolkits provided by hardware vendors. The Sun Open Look and OSF/Motif versions of Interleaf 5 will utilize those toolkits and the Mac version will make use of Apple’s Macintosh Toolbox. In so doing, Interleaf has made it possible for itself to develop an Interleaf 5-based product that conforms to whatever graphical user interface is required.

That much is not that different from what Frame did several years ago. But Interleaf is taking it one step further. Because Interleaf 5’s interface layer is a set of programmable objects, it is possible to write LISP scripts that interact with the user interface *independent of the underlying engine code.* A VAR or sophisticated user can actually tailor the user interface of an Interleaf 5 product without a source license, much as users can create database query forms with today’s database management products. To our knowledge, Interleaf is the first vendor to introduce such a user-configurable interface for a publishing product.

(Admittedly, it is more likely that Interleaf, a VAR or a customer system administrator would do this customization for end users, rather than the end users doing it themselves. This is, after all, programming in LISP, not HyperCard. But in the academic environment it is not unreasonable to expect that clever end users will indeed make such modifications themselves.)

------------------------------------------------------------------------

**Revision tracking.** Now a standard engine feature, revision tracking traces edits to text and graphics; it tracks who made the edits, when and in what version of the document. *Top:* The attributes in the component’s property sheet. *Bottom:* The style of edit tracing is set in the property sheet of the document version.

![](/img/seybold-1990-3-002.jpg)

![](/img/seybold-1990-3-003.jpg)

------------------------------------------------------------------------

One question that remains is how LISP routines written for one environment will act in another (the Mac Toolbox has different functions from the Open Look toolkit). Interleaf is exploring that interaction, but not until next year will we know how that issue is addressed. Until then, one option is to put some of the user interface right into the document. For example, Interleaf hot buttons—in-document icons that initiate actions (comparable to HyperCard buttons)—are portable across all of Interleaf 5’s platforms without any additional programming.

## **Interleaf 5 features**

In addition to the fundamental changes described above, Interleaf has added a new set of publishing features to its core software. We’ll describe first the most dramatic changes, followed by a list of other noteworthy improvements.

**Revision control.** In TPS 4.0, it is possible to initiate edit trace to track different versions of a document, but the information that is tracked must be custom-designed by the end user or Interleaf. In Interleaf 5, revision control is a basic engine component that, when part of the package, appears in the menu bar at the top of the document with a complete dialog box listing all of the possible items to be tracked.

Through the property sheet, the user establishes the style for tracing different types of edits—strike-through, underlines, different colors or revision bars, for example. It is possible to have multiple editing sessions within a single version—each of which may have different styles—which allows different people to edit the same version and differentiate among each other’s edits.

The system automatically tracks edits to text *and* graphics (additions and deletions), who made the change, when, on what system and at what time.

When edits are approved, a new version is saved, using a hierarchical numbering scheme. The popup menu allows the user to access any version, current or previous, at any time.

Using the Relational Document Manager (RDM), an Interleaf product based on Oracle, it would be possible to add further controls, such as restricting access depending on revision level. Interleaf does not offer Context’s feature of arbitrary display of different editing sessions *(eg.,* Sarah’s edits but not Bob’s) unless they are recorded as separate versions, but, like Context, it does maintain all of the revisions as iterations of the same document, rather than storing them all as separate documents. Storing multiple versions as iterations of the same document makes it easier to trace the history of changes and also saves disk space.

In general, Interleaf’s new revision control is among the best, if not *the* best, in the market. A key difference between the revision tracking of Interleaf 5 and that of Context, which prides itself on this feature, is that Context stores the revision information *inside the document.* In complex applications, Interleaf tracks revisions in RDM *(outside the document in an Oracle database).* Context’s approach is tightly integrated with its standard product, but it only supports certain data types. Interleaf’s standard revision control may offer less than Context’s, but through RDM it offers more, in that it extends the basic package to include other applications and other data types created by products from other vendors. Interleaf also tracks edits inside tables and graphics, rather than just storing different versions.

**Graphic object masters.** Another welcome improvement is the addition of a property sheet for all graphic objects created inside frames. In TPS 4.0, only the frame itself had a property sheet. In Interleaf 5, every diagramming object may be named, and every object, or group of objects, within a frame has its own property sheet. The naming of objects brings Interleaf’s graphics into its text model, where each paragraph has a name (what Interleaf calls components, or what is commonly known as a tag). By naming objects, Interleaf is able to apply the style sheet approach to graphics as well as text.

For example, a drawing may be created in which one element is repeated numerous times. Later, when a change is made to one of those elements, it is now possible to update all of the others automatically to reflect the change, yet still maintain transforms such as stretch, shear or rotate *(see photo).* The change may be one of style (fills, colors, etc.), or it may be content (position, rotation, addition or deletion of objects, etc.). This feature is a powerful addition to an already-strong illustration system.

------------------------------------------------------------------------

**Graphic property sheets.** Diagramming objects may now be named, and they have associated property sheets, shown in the three dialog boxes below. By sharing contents with another graphic of the same name, the content\*\* *and* style of objects may be controlled through the property sheets of master objects.

![](/img/seybold-1990-3-004.jpg)

![](/img/seybold-1990-3-005.jpg)

![](/img/seybold-1990-3-006.jpg)

------------------------------------------------------------------------

----

> [!NOTE]
> The real power of Interleaf 5 is that LISP code may be attached to objects as an attribute.

----

As if that weren’t enough, there is one additional aspect to the named objects, one that is shared by all objects (text, frames, pages and documents). TPS 4.0 supported the use of “extensible objects”—those that were of an unknown data type—but it was not a feature available at the user interface level. This feature made it possible, for example, to include graphics in Interleaf documents for which Interleaf had no filter, or to attach security levels to documents, but it did not let you attach scripts to objects. In Interleaf 5, the program doesn’t care if attributes are data or LISP code, and Interleaf has brought the object attributes out to the user interface.

For the user, the ability to create attributes easily can be quite handy. An obvious application is assigning levels of security to objects and then selectively displaying or suppressing elements according to their security level. But, in another example, an educator might create a test that had questions of different degrees of difficulty, with answers that are also given attributes. The instructor could use one document to produce several different tests, with or without the answers shown. Other programs allow the use of conditional variables, but few offer such a fluid interface for invoking the feature.

But the real power of Interleaf 5 is that LISP code may be attached to objects as an attribute. For example. Interleaf is now able to create and activate hypenext links within a document, as attributes. (In its Optical Publishing Software, introduced in 1989, it creates hypertext links from tokens embedded in an output file.) The attribute of a link to another document actually contains a LISP script for opening that document and scrolling to the link destination. ArborText has done this in a similar fashion in its current version of The Publisher, and it is quite attractive for those that create a library of electronic documents.

**Interactive equation editor.** The command-driven equation editor of TPS 4.0 has been upgraded to an “interactive editor” in which special characters are keyed from the keyboard or pulled off popup menus. Although it is possible to map any keyboard character to any special or math character, Interleaf is not supplying a default mapping for math, a feature we’d like to sec added. In our brief look at Interleaf 5, it appears that this package is not as slick as the equation editors of FrameMaker and The Publisher, but without question it will make Interleaf 5 a more attractive authoring tool for those who write a lot of math.

**Other features.** The other new features may be more subtle, but some are significant:

- *“Computed components.”* Interleaf 5 will generate content within components based on other components. For example, it could extract the content of heads in body text into running heads or feet.
- *Illustrator’s palette.* Some Interleaf 5 packages will sport a new palette of drawing tools that eliminate the need to use popup, cascading menus to create and manipulate objects. Even though Interleaf built intelligence into its menus so that the popup cascades across to the item it anticipates you will want to pick, the palette is much faster and more in keeping with the interfaces of other illustration products. Like most aspects of Interleaf 5, the palette may be customized by adding your own graphics to it.
- *Repeating column headers.* Running heads and feet may now be different for columns as well as facing pages.
- *Multiple page-numbering streams.* Developed specifically for the pharmaceutical market, this feature allows a single document to have more than one set of folios.
- *PostScript color output.* The spot color facility of TPS 4.0, which created spot color separations, has been extended to allow the printing of all, or some, layers on PostScript color printers, such as the QMS ColorScript.
- *External references to images.* Images may now be included by reference without pasting them into the document, a feature that saves disk space and is useful when images are created by someone other than the author.
- *Extended search and replace.* The search and replace is now case sensitive and has a robust set of wildcards.
- *Authoring support.* The keyboard is completely user-modifiable in all Interleaf 5-based products, so you can map your favorite actions to whatever key you like. The macro facility of Interleaf 5 enables authors to not only save keystrokes and mouse clicks to keyboard combinations but also to attach scripts to keys. XyWrite has a similar capability, and we find it an invaluable time-saver.
- *Improved hyphenation control.* You can now specify the number of letters that may precede or follow a hyphen. The minimum number of letters in a hyphenated word remains fixed at 5.
- *Improved leading control.* Leading may be specified as baseline to baseline, and you may enter negative leading values. As before, leading is in hundredths of a point.

**Compatibility with other versions.** Every software vendor offers some sort of migration path for converting documents created in old versions into new versions of their software, but oftentimes they neglect to offer a downward translation. We are glad to see Interleaf has included a “convert to previous” feature that converts Interleaf 5 documents to TPS 4.0 or Interleaf Publisher (for Mac or PC) format. In addition, when converting documents from older versions to the new, the user has the option of freezing composition so that when opened in Interleaf 5, the document will retain exactly the same line endings and pagination.

## **Packaging a product**

Unlike past Interleaf products, Interleaf 5 is not a single product. The core technology may be packaged in a variety of ways to fit different requirements. Interleaf secs three types of end-user products: horizontal applications, which are aimed at a broad class of users much like TPS or Interleaf Publisher; vertical-market applications, which are general packages tailored to specific industries and applications; and customerspecific ones, such as developed for Grumman. Horizontal applications will be sold primarily by the direct sales force, with help from deals with hardware manufacturers. The vertical market packages will be offered by VARs and by select Interleaf sales people trained in that application. The customerspecific products are sold and developed by Interleaf’s system integration division, which is currently the fastest-growing portion of the company. Where applicable, Interleaf develops vertical-market products as offshoots of custom work.

------------------------------------------------------------------------

**Vertical-market products.** This is the Professional Writer software configured for creating Aircraft Maintenance Manuals. The writer’s menus are preconfigured with components appropriate to the application.

![](/img/seybold-1990-3-007.jpg)

------------------------------------------------------------------------

**Horizontal applications.** At the Conference, Interleaf showcased six general-purpose packages built from Interleaf 5. All rely on the core TPS engine, but with different capabilities that reflect their primary purposes:

- *Passport.* A general-purpose compound document editor designed for everyday use in the office, Passport is much like TPS but with the addition of the active-document technology and without some of the advanced features (tables, equations, gray-scale editing, revision control, etc.). Initially, it will be offered with Interleaf’s user interface. Broader success may be more likely next year, when Interleaf introduces Open Look and Motif versions, pitting this Interleaf 5 product against FrameMaker, which is now available on more than 20 different Unix workstations. Passport will lack some of the features of FrameMaker, but it may offer some that Frame lacks, such as Interleaf’s graphics and charting facilities.
- *Interleaf Engineer.* Similar to Passport, this package adds the table and equation editors and the Methods Toolkit *(described below).*
- *Professional Writer.* In addition to the features of Passport, this package offers revision tracking, the optional Houghton Mifflin Writer’s Helper *(described below),* hypertext links, live links to Lotus 1-2-3 and other applications and configurable keyboards for emulating other word processors.

------------------------------------------------------------------------

**Automated task cards.** This is another example of active document technology married to Interleaf’s Relational Datatbase Manager. In the foreground is the attribute list of a component of the job instruction card—a list of instructions for maintaining an aircraft. Much of the card is filled in automatically by linking it to a database of product information.

![](/img/seybold-1990-3-008.jpg)

------------------------------------------------------------------------

- *Interleaf Illustrator.* Interleaf’s graphics editors are no substitute for Auto-trol or InterCAP systems, but they are better suited to creating nontechnical drawings, such as flow-charts, viewgraphs and diagrams. Adobe has ported Illustrator to DEC workstations, but as yet the market for Unix general-purpose illustration tools is wide open. Interleaf’s Illustrator is Passport plus all of Interleaf’s graphics capabilities—drawing, gray-scale and line-art image manipulation, graphic text, the new graphic style sheets and a palette interface as an alternative to the popup cascading menus.
- *Interleaf Production.* This is the full-blown package that includes all of Interleaf 5’s functionality. As with the other packages, it may be extended and tailored through the use of LISP scripts.
- *Interleaf Academic.* Containing all of Interleaf Production, plus the Methods Toolkit, this package is available free to accredited colleges and universities in the U.S. and Canada.

All of these products may be extended by LISP scripts. Those customers who buy a product with a toolkit will have complete access to all of the software’s components. Those who buy a subset of the engine may upgrade to receive more functionality.

Interleaf expects all of these packages to be available by the end of the year. When we prepared this article, Interleaf was still finalizing the pricing. We expect it to range from about \$2,400 to \$16,000, but we will report the actual numbers as they are made available.

----

**Active documents at work.** This engineering change order is an Interleaf document, but its fields are linked to a database. Checking the approval box automatically brings in the digitized signature and date. Accepting with conditions prompts the user to enter the condition notes.

![](/img/seybold-1990-3-009.jpg)

----

**Vertical market applications.** Interleaf 5 also makes possible the building of a special product for niche markets, and Interleaf has already developed ones for aerospace and for Amoco, which will be used in petroleum engineering. (We described its work with Amoco in our coverage from Seybold Seminars, Vol. 19, No. 14.) In addition to these markets, Interleaf announced its intention to develop vertical applications for pharmaceuticals, computer-aided software engineering (CASE) and automobile manufacturers.

Of these, the aerospace market is getting the most attention. Interleaf has set up a business unit, led by Larry Bohn, specifically to address contracts that demand compliance with the guidelines of the Air Transport Association (ATA, the airlines) and the Aerospace Industry Association (AIA, the manufacturers). The unit has mushroomed to 22 people in just six months, and not just in anticipation of orders. Interleaf has already won contracts with America West, Eastern and, most recently, TWA. It also has won contracts with suppliers—Canadair, Boeing, Grumman and Saab.

**ATA demo.** At the conference. Interleaf demonstrated an application developed for an airline and since “productized” for use at other airlines and aircraft suppliers. The application helps firms automate the process of producing documents that comply with the Airline Transport Association (ATA) guidelines.

The first application is an engineering change order (ECO), a document that is created in response to changes in equipment. Typically, the manufacturer or airline has one person whose job is to obtain approvals for the ECO and coordinate any requested changes. The approval cycle usually involves several people from different departments. The change order must be routed (typically in hard copy) to various people for notification, approval or action, and the coordinator compiles all of the changes into the new release of the ECO. Interleaf developed a product in which the entire user interface that the engineer deals with for an ECO is a form that he fills out. The Interleaf 5-bascd product uses Interleaf’s Relational Document Manager to generate an active Interleaf document from fields in the RDM database. Because of its ability to attach scripts to menu items and fields in a document, Interleaf is able to do such things as automatically fill in certain fields of the ECO when others are entered (enter part number, get pan name); verify the validity of certain fields (entered value must meet certain criteria or user is prompted whether value is correct); and automatically route the ECO when it is finished. After being routed, the same document can find and place in itself a digitized signature when someone in the chain gives approval. Yet the interface for everyone who interacts with the ECO is a self-contained form that is a document *(see photo).*

A similar application is the job instruction card, which tells the maintenance person what specific tasks are required in a maintenance procedure. Today, some firms create these task cards by photocopying parts of the manual and pasting them together into an instruction card. In Interleaf’s software, the maintenance information from which instructions are extracted is kept as a catalog of data files that is tracked in RDM. The header fields that identify the card are also tracked in Oracle. The software automatically retrieves the header information and maintenance instructions, based on the task number(s). Graphics associated with tasks are automatically made available for placement within the card. Thus, the entire process is automated, resulting in a compound electronic document that may be made available in hard copy or electronic form.

Interleaf has also developed an aerospace-specific version of Professional Writer to help authors create aircraft maintenance manuals. (Some airlines republish their own, based on the manuals supplied by the manufacturer; others have the manufacturer do it for them under contract.) The manual itself describes all of the maintenance procedures, following the naming and numbering conventions established by the airline industry. Interleaf took these names and numbers and added them to the standard menus, so that when a writer begins a new task, it may be created by picking its part number or description from the menu. The software then automatically inserts both the item selected and its corresponding name or number, checks their validity through RDM and inserts them in the document. Although it was not shown, presumably it would be possible to further constrain the menus to show only the appropriate subtasks within any given task.

**Grumman example.** An example of a customer-specific application in which the interface is configured for a customer is the Portable Maintenance Aid (PMA), developed by Grumman, also demonstrated at the Conference.

Grumman’s PMA is a rugged, laptop computer designed by Grumman. It is based on a Sparc processor, but it is specially built to withstand severe operating conditions required for some military systems. The PMA runs Unix and is equipped with electronic manuals created in Interleaf 5. The PMA plugs into the data bus of a military vehicle and downloads information directly from the weapon system’s computer. Maintenance technicians, interacting with the PMA through Interleaf-created documents, press on-screen buttons to view step-by-step repair instructions. Scanned-in maintenance manuals are also available and are retrieved by activating hypertext hot buttons.

In this case, the end user docs not employ Interleaf’s popup menus at all. The entire interface is a programmable document that contains “hot zones.” Activating a zone initiates a behind-the-scenes script that brings the appropriate information to the screen.

Texas Instruments, another Interleaf 5 customer, demonstrated what it calls the Table Object Population Systems, an application of Interleaf 5 that fills in, or “populates,” tables within data sheets with information pulled from a product database. TI expects the system to reduce by as much as 40% the time it takes to produce documentation about its semiconductors.

## **Developer's toolkit**

In addition to selling end-user solutions, Interleaf is embarking on a new venture. For the first time, it is entering the programming market with a toolkit for building applications. Just as computer language vendors offer toolkits for creating, compiling and debugging applications written in that language (C, Pascal, etc.), Interleaf is selling a toolkit for building, debugging and running a publishing program. The difference is that its toolkit includes an incredibly robust engine that provides WYSIWYG editing of text and graphics, h&j, pagination, font scaling and rasterizing, translators—in short, everything you need to create a *programmable* compound document editor.

Unlike vendors that license source code to which users add extensions (typically in C), Interleaf allows extensions *independent of the source code.* We believe this is a significant plus for developers. It means that they can develop applicationspecific solutions that do not have to be retooled, debugged and recompiled each time Interleaf updates part of its engine. LISP-based extensions are executed at run-time; they need not be precompiled code. Yet these extensions can do anything from simple macros that may be represented as icons (much like Windows 3.0) to interacting with other programs (databases, spreadsheets, scientific measuring equipment).

------------------------------------------------------------------------

**Interleaf**\
10 Canal Park\
Cambridge, MA 02141\
(617) 577-9800 fax: 494-4826

------------------------------------------------------------------------

------------------------------------------------------------------------

**Base level across all platforms.** The PC (shown here) and Mac versions of Interleaf 5 will offer the same functionality as the Unix ones.

![](/img/seybold-1990-3-010.jpg)

------------------------------------------------------------------------

At this time, the toolkit is intended for independent developers (such as academics), OEMs, sophisticated end users and for use by Interleaf itself.

**Various support levels.** Because it wants to encourage enthusiasts, Interleaf felt it was imperative to offer the toolkit inexpensively to hackers who are not necessarily developers with lots of cash. Thus, it is offering the Methods Toolkit—the full software toolkit and documentation, but without support—for much less than the Developer’s version. (As we said above, it is free to the academic market.) When they run into trouble, those who do not have a support contract will be able to buy support from Interleaf on an hourly basis.

For more formal developers or VARs, Interleaf is offering the Developer’s Toolkit, with documentation, training and support, at a higher price. Obviously, developers choosing that option will be given a higher level of support than those who try it on their own.

## **Third-party products**

In today’s market, the success of any programming language or toolkit depends on application software, particularly software written by vendors or users other than the toolkit supplier.

Interleaf has always enjoyed a strong relationship with vendors of engineering-related software. With Interleaf 5, it hopes to extend its partnerships to other areas as well. At its press conference, about a dozen or so third-party vendors were on hand to announce their support.

Houghton Mifflin introduced Writer’s Helper, a package for Interleaf 5 that includes Houghton Mifflin’s CorrectSpell spelling checker, online *American Heritage* dictionary and *Roget's Thesaurus* and CorrecText, HM’s grammar checker. Thedictionary includes definitions, so you can look up words by their meaning. It will also show anagrams.

Xerox announced a cooperative marketing agreement whereby the two companies will recommend each other’s products. For Interleaf, this means being able to offer the new DocuTech Production Publisher, a high-speed Xerox printer *(see story later in this issue for details).* For Xerox, it means being able to offer Interleaf software—an interesting move considering Xerox’s recent introduction of GlobalView—the porting of its ViewPoint software to Sun hardware.

Apple was present to offer its support in anticipation of the new Mac Interleaf 5 next year. Presumably, that product will take full advantage of the new features in System 7.

In addition, there were companies that represent specific applications:

- Cadre, IDE, Lockheed and the Software Productivity Consortium announced support for Interleaf with their computer-aided software engineering (CASE) tools.
- Lotus was happy that Interleaf will support live links to Lotus 1-2-3, version 3. The links will even support values attached to them *(eg.,* if greater than 5, then get data).
- IBM endorsed Interleaf in conjunction with its CASE tools for the RS-6000.
- Database Publishing introduced an SQL database product that links Interleaf 5 to databases.
- Design Automation stated its intent to support Interleaf with its petroleum engineering software.

## **Conclusion**

In its seven-year history, Interleaf has earned a reputation for technological innovations that have redefined electronic publishing. For several years, it has been the dominant player in the compound document editor market, and it still has a larger installed base on Unix workstations than any other publishing vendor. But Interleaf’s vision of becoming the corporate standard for electronic publishing—with corporations buying a turnkey Interleaf system for every desk—has been blurred by the success of mass-market software such as PageMaker and Ventura, which offer some of the same features. And in the Unix market, it faces stiff competition from FrameMaker and a growing list of new competitors (DECwrite, ArborText’s The Publisher and, soon, Ventura). In anticipation, Interleaf left the turnkey system business a year ago, and it now relies solely on software and services for revenues. The transition has been difficult, but Interleaf has proven that it is no has-been. Its software sales alone this year have matched its turnkey sales of last year.

Interleaf 5 continues Interleaf’s tradition of unbridled innovation. Believing that the value of merging text and graphics would diminish as that ability becomes commonplace in less-expensive, mass-market products, Interleaf has moved on to new, uncharted territory, creating a new type of publishing application (the programmable compound document editor) and in active documents redefining what is meant by an electronic document. Without question, the publishing market is beginning to look beyond the problems of merging text and graphics to a new set of problems, such as document management, database-oriented publishing and content-based retrieval. In these areas, Interleaf is not without competition. ArborText introduced programmable objects a year ago. Datalogics has been hard at work integrating Pager with Oracle and SGML-tagged databases. Digital has an agreement with Verity to bring content-based retrieval to all of its products running on a network. But regardless of its fate, Interleaf 5 has opened up a whole new realm of possibilities, and by popularizing the concept of active documents, will almost surely leave its mark on the industry.

Interleaf 5 is also a foremost example of extendible software that enables clever end users or system integrators to tie a publishing package with other programs. The use of Quark Xpress in the newspaper industry is the best-known example of this trend. Interleaf 5 is the first product designed specifically to address these emerging issues, and it does so in a way that goes far beyond any previous product.

What remains is for Interleaf to prove that Interleaf 5 works, and that the company can thrive in its new role of software developer *cum* system integrator. It has won several multimillion-dollar contracts based on its technology, and installed a few at customer sites, examples of which were shown at the Conference. But it has yet to begin volume production. When it docs in a few months, Interleaf will have the chance to dispel its skeptics and separate itself from its competition.

*Mark Walter*
