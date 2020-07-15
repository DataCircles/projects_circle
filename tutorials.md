# Tutorial References

This is a curated list of tutorials that are relevant to our data science projects. We will continue to update this list on an as needed basis depending on requests from project participants.  


## Git & GitHub

There is a vast amount of material available to teach you about version control, git, and GitHub.  

A version control system tracks the history of changes to documents, code, and data as people collaborate on projects.  

Git is a distributed version control system commonly used for software development and data science projects. A repository, or Git project, contains the entire collection of files and folders associated with a project, along with each file’s revision history.  

GitHub is a Git hosting repository that provides a bunch of tools, including: command line features; issues (threaded discussions); pull requests; code review; project boards, wiki pages, and apps in the GitHub Marketplace.  

#### [Resources to learn Git](http://try.github.io)  
Includes links to reading, visualization, and [learning lab](https://lab.github.com) course materials, _e.g._ [GitHub cheat sheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf). Produced by GitHub.  

#### [GitHub Guides](https://guides.github.com)
Provides several guides, including: [Documenting your projects on GitHub](https://guides.github.com/features/wikis). Produced by GitHub.

#### [Version Control with Git](http://swcarpentry.github.io/git-novice/)
Provides video lessons, written materials, and cheat sheets like this [interactive cheat sheet](http://ndpsoftware.com/git-cheatsheet.html) about the relationships between workspace, staging area, local repository, upstream repository, and the commands associated with each. 
This carpentry program is from the Data Carpentry lesson program within [The Carpentries](https://carpentries.org) program. Data Carpentry introduces computational skills needed for data management and analysis in all domains of research. 

## Regular Expressions

Regular expressions (regex or regexp) allow you to extract text information by searching for one or more matches of a specific search pattern (_i.e._ a specific sequence of ASCII or Unicode characters).
Regex works in a variety of programming languages, and is used in validation tests, parsing/replacing strings, translating data to other formats, and web scraping.  

#### Common Regular Expression Operators

`[]` defines a range of characters  
`.` matches any character  
`\` escapes (aka nullifies) a special character. For example, a regular expression that found ‘.com’ is `\\.com` because a period is a special character that matches any character
`\d` matches any single digit  
`\w` matches any part of word character (equivalent to `[A-Za-z0-9]`)  
`\s` matches any space, tab, or newline  
`^` start of the line anchor, so what you put after it will only match if they are the first characters of a line  
`$` end of the line anchor, so what you put before it will only match if they are the last characters of a line  
`\b` adds a word boundary, putting this either side of a stops the regular expression matching longer variants of words  
`*` matches the preceding element zero or more times. For example, `ab*c` matches ‘ac’, ‘abc’, ‘abbbc’, etc  
`+` matches the preceding element one or more times. For example, `ab+c` matches ‘abc’, ‘abbbc’ but not ‘ac’  
`?` matches when the preceding character appears zero or one time  
`{VALUE}` matches the preceding character the number of times defined by VALUE and ranges can be specified with `{VALUE,VALUE}`  
`|` the vertical bar (or pipe) means or  

#### [Regex tutorial — A quick cheat sheet by examples](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)  
A short Medium article with a bunch of regex examples.  

#### [Intro to working with data (Regular Expressions)](https://librarycarpentry.org/lc-data-intro/)  
The lesson introduces the regular expression language and how it can be used to match and extract text and to clean data. Produced by [Library Carpentry](https://librarycarpentry.org). Library Carpentry focuses on building software and data skills within library and information-related communities.  

## Web Scraping

#### [Intro to web scraping](https://librarycarpentry.org/lc-webscraping) 
A short workshop introducing how to extract data from webpages using xPath and the Scrapy Python library, along with written materials and [references](https://librarycarpentry.org/lc-webscraping/reference). Produced by [Library Carpentry](https://librarycarpentry.org). Library Carpentry focuses on building software and data skills within library and information-related communities.  
