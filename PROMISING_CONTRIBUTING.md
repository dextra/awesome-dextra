# Contributing to Promising 🏗 Projects 

## Introduction

The list for promising projects should be a space to show up your initiative for the FOSS community. Projects needs time to be evolved until being ready for public audience. While you are working on this, you may apply for this list of promising projects, which - once open for public - can be promoted to the [Awesome Dextra](./README.md) list.

That way, your project gets visibility and others might get aware of your project, such you can receive help and hints from
your colleagues.

## Contribution Guidelines

To contribute to this list, and add your own project, you need to follow this guide. First thing is to see if your project meets to following criteria:

 - Repositories must be created or maintained by a Dextra employee by the time the project is submitted.
 - Repositories must be ongoing projects aka WIPs. There are no minimum stars, commit frequency, or things like that, but it must be a real project. 
 - The person must have created, or be a member of the Repository.
 - Open Source and licensed under one of the [Open Source Licenses](https://opensource.org/licenses)

Examples of *promising* projects in our vision

 - Projects with a __future__ value for the community, i.e. apps, libs, frameworks etc.
 - No need to be published yet, as it is a _Work in Progress_
 - Ongoing development, i.e. last commit should not be more than __six__ month ago

 
Examples of projects __not considered__ promising in our vision

 - Simple proof of concept projects, or test repositories
 - Personal projects that has little or no use for the community, like personal portfolios, etc
 - Repositories used for personal studies or even forked repositories from online courses
 - Staled/Discontinued Development, i.e. last commit is more than __six__ months ago 


#### To sum up, an open source project which _might_ have relevance to other people in the community once it is ready to be published

If your project meets those criterias, then it's time to fork this repository and [send us a pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## Guideline for new projects

The changes on [PROMISING.md](./PROMISING.md) must follow the guide line to be accepted.

> Almost identical to the [README.md format](./README.md)

The project must be under a category, i.e. programming language, 
and if a category doesn't exist, it can be [created](#Guideline for new categories) 

The new added line _must_ respect the following format:

```
 - [Project name](project link) - A short project description. ROLE_TYPE: [Person name](Person github profile link)
```

`ROLE_TYPE` can be one of:
 - `Author`: when the person is the original author of that project
 - `Co-Author`: when the person is one of the authors of that project with multiple creators/authors
 - `Maintainer`: when the person is part of the team of the project, or has a significant degree of responsibility of that project.

In case of multiple contributors you can add them separated by comma and using plural name, e.g.
```
Authors: [Oliver Hager](ohager@mail.com), [Erick Zanardo](ezanardo@mail.com)
```

## Guideline for new categories 

If a category is missing feel free to add one. Categories are (as of the time of writing) almost programming languages.
When adding, you need to add a reference in the index  in __alphabetical order__  and following this format:

```
 - [Category](#reference-)  
```
> For some reasons the reference name must end with `-`

Furthermore, add a headline with a nice and representing logo of that category (colorful READMEs are best)
The logo (svg, jpg, png) should be added to `./media` folder.

```
<h1>Category<img style="margin: 4px 0 0 4px" height="32" src="media/category-logo.svg" alt="Category Logo"/></h1>
```

---

Entries, both categories and the entry list must be in alphabetical order.

---

## Promotion to Awesome List

Once you think that your project is mature enough (i.e. reached a release candidate status) and was publicly released 
then you may apply for the [Awesome Dextra](./README.md) listing, by simply moving your project from the [Promising List](./PROMISING.md) 
into the [Awesome List](./README.md) by opening a pull request.
