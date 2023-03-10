# Application-Web-Design


## ACTIVIDAD 1

Name: Josue Orozco Fregoso

Matricula: 02981723 

Degree: Ing de Desarrollo de Software 

Semester: 6 

Class: Diseño de aplicaciones web 

Teacher: Erik Ezequiel Carrillo Moo

---

## Tarea 1

### MarkDown Tags:

---

#### Heading tags: 

---

"#" for heading 1 and "######" heading 6

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6


#### Alternate Syntax: 

---

Heading 1 = under the heading text

Heading 2 - under the heading text

#### Bold Text: 

---

Using ** or __ in between a word or phrase the text will be become bold

This is **bold text**

#### Italic Text: 

---

Using * or _ in between a word or phrase the text will be become italic

This is *Italic text*

#### Blockquotes:

---

To create a blockquote, add a > in front of a paragraph.

> this is a block quote

To create a nested blockquote add two >> in front of a paragraph.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.


#### Code Blocks:

---

Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.

1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.

#### Ordered Lists:

---

By adding a Number + . will start a ordered list

1. item 1
2. item 2
3. item 3


#### Unordered Lists:

---

By using -, *, or + we can create an Unordered list

- item 1
- item 2
- item 3

#### Denoting Words:

---

To denote a word we enclose a word or phrase with '

At the command prompt, type `nano`.

#### Links:

---

To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) and then follow it immediately with the URL in parentheses (e.g., (https://duckduckgo.com)).

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

---

### Git Commands:

### Check the status of a local repository.

    git status -s

### Add individual files or globally.

    git add .
  
  > This will add files into the stage.

### Add comments to the commit.

    git commit -m "commit message goes here"

  > It is necesry to add files into the stage first before doing a commit.

### Upload your changes to the remote repository.

    git push

  > it it necesary to do the last two steps (add and commit)
 
### Create, browse, and delete branches.

1. Create

        git checkout -b (name of branch)

2. Browse

        git checkout (name of a existing branch)

3. Delete

        git branch --delete (name of branch)

  > NOTICE: You can delete the branch you are currently on.


### Roll back a repository to a specific commit.

1. Find commit history log

        git log --oneline

2. look for the ID of the commit version you want to roll back too and copy it

3. RollBack

        git reset --hard (commit version ID)
