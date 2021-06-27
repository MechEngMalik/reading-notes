# HTML TABLE

The HTML table model allows authors to arrange data -- text, preformatted text, images, links, forms, form fields, other tables, etc. -- into rows and columns of cells.

## Table rows

 may be grouped into a head, foot, and body sections, (via the THEAD, TFOOT and TBODY elements, respectively). Row groups convey additional structural information and may be rendered by user agents in ways that emphasize this structure. User agents may exploit the head/body/foot division to support scrolling of body sections independently of the head and foot sections. When long tables are printed, the head and foot information may be repeated on each page that contains table data.

### Table cells

may either contain "header" informationor or "data  The HTML 4 table model allows authors to label each cell so that non-visual user agents may more easily communicate heading information about the cell to the user. Not only do these mechanisms greatly assist users with visual disabilities, they make it possible for multi-modal wireless browsers with limited display capabilities (e.g., Web-enabled pagers and phones) to handle tables.

ables should not be used purely as a means to layout document content as this may present problems when rendering to non-visual media. Additionally, when used with graphics, these tables may force users to scroll horizontally to view a table designed on a system with a larger display. To minimize these problems, authors should use style sheets to control layout rather than tables.
The HTML table model has been designed so that, with author assistance, user agents may render tables incrementally (i.e., as table rows arrive) rather than having to wait for all the data before beginning to render.

> In order for a user agent to format a table in one pass, authors must tell the user agent:

1 -The number of columns in the table. Please consult the section on calculating the number of columns in a table for details on how to supply this information.

2 -The widths of these columns. Please consult the section on calculating the width of columns for details on how to supply this information.

More precisely, a user agent may render a table in a single pass when the column widths are specified using a combination of COLGROUP and COL elements. If any of the columns are specified in relative or percentage terms (see the section on calculating the width of columns), authors must also specify the width of the table itself.

![link](https://i.stack.imgur.com/VCxSJ.png)

## Java

### Function,Methods and objects

> function: A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output.

> Methods: JavaScript methods are actions that can be performed on objects. A JavaScript method is a property containing a function definition. Methods are functions stored as object properties.

> Function vs methods :
Use this article as a reference sheet for JavaScript methods and functions. Use this article as a reference sheet for JavaScript methods and functions. Function — a set of instructions that perform a task. Method — a set of instructions that are associated with an object.

![link](https://cdn-images-1.medium.com/max/1200/1*rSHmnlUotrjc5lXV1xDtGA.png)

### pair programming

Pair programming is an important technique for developing higher quality code, faster while also reducing risk and spreading knowledge in an organization. With pair programming, two software developers work on one computer, collaborating on the same design, algorithm, code, or test.

> How does pair programming work?
is an agile development technique in which two programmers work together at one workstation. The Driver, writes code and the Observer or Navigator, reviews each line of code as it is typed in. The two programmers switch roles frequently.

> How to pair programe effectively in 6 steps :
1 - Greater efficiency: You have more people who know how the new program works. This means that if one of the pair leaves the company, it will not kill the project. Your team develops better interpersonal and social skills. Team members can learn to communicate with each other, work together, and share information.
2 - Engaged collaboration:When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone Another important aspect of learning to program is knowing when to ask for help.
3 -Learning from fellow students:If you work in a setup where not the whole team is distributed and just one or a few of you are remote, try to include the remote partner in all discussions that are happening in the office. We tend to forget how much we share incidentally just by sitting in the same room.
4 -Social skills:Working remotely with someone you haven't met and do not know creates an additional challenge. On the one hand, pairing is a chance to get closer to each other on a remote team. On the other hand, it's sometimes easy to forget that part of the collaboration. If there is no chance that you meet in person, think about other ways to get to know each other a bit better, e.g. try to have a remote coffee together.
5 -Job interview readiness: step in many interview processes involves pair programming between a current employee and an applican.he ability to work with and learn from others and stellar communication skills are as important to a company than specific technical skills. Pair programming strengthens all of those skills.
6 -Work environment readiness :Work readiness skills include both foundational cognitive skills such as reading for information, applied mathematics, locating information, problem solving, and critical thinking and noncognitive skills, or soft skills, which are defined as personal characteristics and behavioral skills that enhance an individual's.
