## Contributing

To contribute to this list, and add your own project, you need to follow this guide. First thing is to see if your project meets to following criteria:

 - Repositories must be created or maintained by a Dextra employee by the time the project is submitted.
 - Repositories must be real projects. There are no minimum stars, commit frequency, or things like that, but it must be a real project. 
 - The person must have created, or be a member of the Repository.

Examples of real projects in our vision

 - Published packages/libraries/frameworks (Published meaning people can use this on their own project, using the available publishing method for the platform it is built on)
 - Open Source apps
 - Reusable template projects, like bootstrappers
 - Original proof of concepts projects, that is used on tutorials/articles

Examples of projects __not considered__ real in our vision

 - Simple proof of concept projects, or test repositories
 - Personal projects that has little or no use for the community, like personal portfolios, etc
 - Repositories used for personal studies or even forked repositories from online courses

#### To sum up, a project which has relevance to other people in the community.

If your project meets those criterias, then is time to fork this repository and [send us an pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## Guideline for new projects

The changes on README.md must follow the following guide line to be accepted.

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
