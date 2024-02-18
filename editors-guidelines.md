# Editor Guidelines
By Mark Bailey

## Introduction
Outlined here are some basic guidelines on how best we can work together to build the **Clinicians who code - The Opinionated Handbook**. These are not set in stone and we can adapt them to help streamline processes.

## Joint working practices
I fully appreciate that we are all professionals and I would have not asked you to participate in the Clinicians who code course and subsequently this handbook if I did not believe that you could not offer some very valuable and professional insight. I also believe that each and everyone of you would write helpful and professional content. However, we are not just writing this handbook for ourselves, but for others as well. This means others will be reading our content and will want to know that the content is of a certain calibre. Hence, I feel it is important we have a minimum standard and working practices to show others that we are writing a handbook that is worth considering, reading, recommending to others and even perhaps referencing. To that affect, I have outline working practices that I would like us all to follow. Please remember that these can be changed if we feel they are not stringent enough or are **anti-patterns**.

These guidelines are as below:

1. We work in pairs when writing content for the handbook (much like paired programming).
2. Content will be written to the [handbook](https://github.com/clinicians-who-code/clinicians-who-code-the-opinionated-handbook) github repository.
3. All content will be written in non-main / non-master branches.
4. Content will be added to the main branch via a pull request.
5. Each pair will meet every 2 week for 2 hours to write content for the handbook.
6. After each session, the pair will push their new content to their own branch on Github and initiate a pull request.
7. A third person (content checker) will then either accept or reject the pull request.
8. When we start including others from outside our initial group, and perhaps they want to write content by themselves, then we will need two content checkers before we accept a pull request of new content.
9. So overal, there are always 3 people (minimum) that have seen content before it is pulled to the main branch.
10. Any issues you find regarding your content or others can be either discussed via the CWC Signal group or via Gtihub issues.
11. Pairs will be assigned at random and change every 6 weeks.
12. A **content checker** will assigned to each pair and change every 6 weeks.
13. We will have a whole group meeting every 6 weeks.
14. I appreciate work loads and holidays will affect the above regular meetings, and some slack is of course expected.

## Layout of topics
All of the topics we write will be placed in the **handbook/docs/chapters** folder, with subsequent subfolders as needed. Please keep all names of file and folders in lower case and use kebab-style-case. We will use the **handbook/docs/chapters/index.md** file to create an index page for the handbook. We will need to decide at some point the order of the chapters in this index file, perhaps this will depend on topic difficulty (for example if someone was trying to learn about clinical informatics and wanted to read the book from start to finish).

## Writing styles
We will be using markdown and its syntax for this handbook. Please see the [example](clinicians-who-code.org/chapters/example/example.md) for an example of the style. Please reference using hyperlinks, as needed, other sections in this handbook.

## Referencing
I feel it is important that we make sure that what is written in this handbook is of a high quality. Hence, I feel we should consider referencing material. Hyperlinks should be sufficient for this. We will need to have further discussions on how best to do this and how much we should reference. Also, what calibre of material should we reference. Is a blog or personal opinion worth referencing, are we pushing more for academic works? I feel their might be a lack of high calibre acadmic research on a lot of the topics we will be ultimately covering, so referencing may be a difficult process to undertake.

## Public view of the handbook
When a pull request is accepted, **Github actions** will build pages using mkdocs material and then updated pages will be visible at [here](https://clinicians-who-code.org/)