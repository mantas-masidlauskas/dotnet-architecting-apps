# Requirements Gathering

![Table 1-1: Families of quality characteristics according to ISO/IEC 9126](https://raw.githubusercontent.com/fmoliveira/dotnet-architecting-apps/master/LessonsLearned/img/table_1-1.png)

A simple but effective practice to process functional requirements is grouping them by categories, as described earlier in Table 1-1. What we usually do is create a Microsoft Office Excel document with one tab for each category. Next we go through the actual list of requirements we gathered from interviews and simply map each to an existing category.

When done, we read it back and stop on all those tabs that are either empty or that have just one or two requirements. If no requirements are found, say, under the attribute of portability, we stop and wonder if we know enough about it and if we asked enough questions. Having no explicit portability requirement might mean that portability is not a requirement, or it could mean we just don’t know about it.

In particular, portability relates to the software’s ability to be used within different environments. Having no such requirements, say, in a service back end should immediately raise the question of whether the back end should be usable only from web clients or whether support also for iOS and Android clients is essential.

# References
* [ISO/IEC 9126-1:2001: Software engineering | Product quality|- Part 1: Quality model](http://www.iso.org/iso/catalogue_detail.htm?csnumber=22749)
* [ISO/IEC 25010:2011: Systems and software engineering | Systems and software Quality Requirements and Evaluation (SQuaRE) | System and software quality models](http://www.iso.org/iso/catalogue_detail.htm?csnumber=35733)
