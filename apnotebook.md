
## Table of Contents
- [Vocab](#vocab)
- [Important blocks](#important-blocks)
- [On the AP Exam](#on-the-ap-exam)
- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)
  - [Headings](#headings)
  - [Text Formatting](#text-formatting)
 







## Vocab
<details>
  <summary>Element</summary>
An element is another name for an item in a list. (If the same value is in the list twice, that counts as two different elements.) Each element has a unique index (position) in the list.
</details>
<details>
  <summary>table</summary>A table is a two-dimensional data structure with rows and columns. If you've used a spreadsheet program, what it displays is a table. In Snap!, a table is implemented as a list of lists, in which each sublist is one row of the table.
</details>
<details><summary>traversing a list </summary>Traversing a list means looking at each item of the list. For each is iterative. That is, it’s repetitive, like for, which can also traverse a list. But unlike for, for each traverses the list without using index numbers.</details>







<details>
  <summary>Abstraction</summary>
    The most fundamental idea in computer science, giving a name to something in a program to make it more readable.
</details>

<details>
  <summary>Procedural abstraction</summary>
    Using a procedure to name an idea, ex. the procedure "who" to the idea of picking an item from the list of people or cats.
</details>

<details>
<summary>How not to do pair programming:
</summary>
</details>
<details>
  <summary> A table is a two-dimensional data structure with rows and columns. If you've used a spreadsheet program, what it displays is a table.

In Snap!, a table is implemented as a list of lists, in which each sublist is one row of the table.
  </summary>
</details>
<details>
<summary> datatype</summary>
A data type is what kind of data something is (number, text string, list, etc.). For example, number is the data type for the first input to item (1) of () and list is the the data type for its second input.
Each programming language provides some primitive data types (data types that are built-in). For example, Snap! provides numbers, text (words and sentences), Booleans (true or false), lists, and some you haven't yet used as data (such as sprites and costumes). This menu shows all of Snap!'s primitive types.








  
</details>
<details>
<summary>abstract data types</summary>
An abstract data type (ADT) is a custom data type that's meaningful to your program. It's not built into the language; you develop it as you code. This is an abstraction because it hides the details inside the constructor and selectors so that programmers working with crossing record think about timestamps and events, not list indices.
The Crossing Record block is the constructor; it constructs one example of the data structure. By naming the pieces of the structure, the constructor ensures you build the structure consistently every time.
The selector blocks like Date, Time, Seed, of crossing record, are the selectors; they each select one piece of the data structure.
The constructor and selector together implement the crossing record abstract data type.
Data abstraction is the creation and use of abstract data types in a program.




  
</details>







## Important Blocks
<details>
  <summary>broadcast</summary>
     Sends a message to all the sprites. To set the message, click the down arrow and select "new..."
</details>

<details>
  <summary>when I receive</summary>
     (Click help on the block to learned more about it in order to complete this definition)
</details>

<details>


<summary>The list expression list{Señora, Ms. C, my cat, Hannah, Jake} would be written as [Señora, Ms. C, my cat, Hannah, Jake]. The items are positioned in the list in the order they appear in the text: "Señora" has index 1, "Ms. C" has index 2, and so on.</summary>

<img width="343" height="27" alt="list-from-who" src="https://github.com/user-attachments/assets/e6dcd6ee-676e-4ad4-8a24-2223d7edf113" />
</details>
<details>


<summary>
The assignment instruction set (shopping list) to (list) would be written as shoppingList ← [] or shoppingList ← [].
The assignment instruction set (shopping list) to {apples, bread, carrots, rice, pasta} would be written as shoppingList ← [apples, bread, carrots, rice, pasta] or shoppingList ← [apples, bread, carrots, rice, pasta]. (In this app, you'll want the shopping list to begin empty, and then the user will add or insert additional grocery items one at a time.)

  
</summary>





<img width="503" height="42" alt="example-list-assignment" src="https://github.com/user-attachments/assets/6fbaa9b9-abe9-4aaf-8bec-6e3b13cdec13" />
<img width="239" height="37" alt="example-blank-list-assignment" src="https://github.com/user-attachments/assets/6de5ed51-31cd-4259-b9b6-c3747f7fa58e" />
  
</details>
<details>

<summary>insert (tomatoes) at (2) of (shopping list) would be written as INSERT(shoppingList, 2, "tomatoes") or INSERT(shoppingList, 2, 'tomatoes').
add (tomatoes) to (shopping list) would be written as APPEND(shoppingList, "tomatoes") or APPEND(shoppingList, 'tomatoes').</summary>
<img width="283" height="37" alt="add-tomatoes-to-shopping-list" src="https://github.com/user-attachments/assets/c96f770e-e72c-4fba-b8ed-24ea9bca23c3" />
<img width="370" height="37" alt="insert-tomatoes-at-2-of-shopping-list" src="https://github.com/user-attachments/assets/4dae056c-aeb0-42ee-a2ab-25fc03bdb449" />
</details>
<details>




<img width="276" height="37" alt="delete-item-2-of-shopping-list" src="https://github.com/user-attachments/assets/dff219f8-4765-4ae1-a7dc-6ee83cc16b95" /> <summary>would be written as REMOVE(shoppingList, 2) or  </summary>
<img width="174" height="23" alt="remove-blocktran" src="https://github.com/user-attachments/assets/4b3ba3f4-e368-40a6-a4fe-9dc4b44bc395" />

</details>
<details>


<summary>When you run this script in Snap!, the second line of code assigns to shopping list 2 the value of shopping list (that is, the same list, not a copy). So, the third line of code modifies both variables:
set(shopping list) to (list(apple)(banana))
set(shopping list 2) to (shopping list)
add (carrot) to (shopping list) shopping list watcher showing the contents of the variable to be apple, banana, carrot; and the shopping list 2 watcher showing the contents of the variable to be apple, banana, carrot

However on the exam, the statement shoppingList2 ← shoppingList makes a copy of the list. So modifying one of them does not modify the other.
The rules for how to use lists and how they behave differ depending on the programming language you are using.</summary>







<img width="319" height="139" alt="example-list-by-reference-stage" src="https://github.com/user-attachments/assets/df369361-8f11-40ae-9ec8-bf7e4013c96c" />
<img width="364" height="107" alt="example-list-by-reference" src="https://github.com/user-attachments/assets/563a92e7-dbb7-4841-bbba-0a972b0045f2" />

</details>



























## On the AP Exam

The script <img width="313" height="88" alt="example-for-each-point" src="https://github.com/user-attachments/assets/dca852c5-ef07-4405-9d5e-e8c2e05708ae" />  would be written as FOR EACH point IN myDrawing
{
    goto(point)
}
or     <img width="223" height="74" alt="for-each-blocktran" src="https://github.com/user-attachments/assets/732eb02d-0b56-4aee-af66-47ea935cd75a" /> The procedure goto() isn't built in to the AP's language so it is written in lower case like other programmer-defined procedures.






























<img width="1006" height="120" alt="image" src="https://github.com/user-attachments/assets/9ec69dbd-9e91-4372-a2d1-eebf01d32b64" />

  - Many languages (and the AP CS Principles Exam) use return instead of report as the name of the command to give a value back at the end of a function call.
  - The exam uses "value of a procedure" to mean the value the procedure returns when called. For example, "the value of double(5)" means 10.













































## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  

This ensures your notes are easy for you (and others) to read later.

---

## Headings

**When to use:** Organize your notebook into sections (like days, topics, or projects).  

- `#` for the notebook title (use once at the top).  

- `##` for each day or major topic.  

- `###` for subsections (like "Notes", "Practice", "Reflections").  

# Example:

# My Coding Notebook

## Day 1

### Notes

### Practice

# Text Formatting

When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

# Example:

**Class** = a blueprint for objects  

*Remember:* always test your code  

Use `System.out.println()` to print

 

# Code Blocks

When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

# Example:

```java

public class Hello {

    public static void main(String[] args) {

        System.out.println("Hello World!");

    }

}

```

# Lists

When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

# Example:

Define the class
Write the main method
Test your program
Variables

- Loops

- Conditionals

 

# Checklists

When to use: Track progress on assignments or tasks.

# Example:

[x] Complete coding warm-up

- [ ] Finish project draft

- [ ] Reflect on learning

 

# Blockquotes

When to use: Call out notes, reminders, or teacher comments.

# Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

# Tables

When to use: Compare values, track progress, or organize data neatly.

# Example:

| Task        | Status   | Notes          |
|--------------|------------|-----------------| 
| Homework 1  | Done #  | Submitted      |
| Homework 2  | Pending  | Needs review   |

 

# Links & Images

When to use: Add references, resources, or visuals.

# Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

To make an image that is a link, paste the image, then add the following before it, replacing website address with the link:

<a href="website address">

And after the image info, add: </a>

# Collapsible Sections

When to use: Hide solutions, extended notes, or extra details.

# Example:

<details>

  <summary>Click to reveal solution</summary>

  

System.out.println("Answer: 42");

</details>

 

# Footnotes

When to use: Add references or side notes without cluttering the page.

# Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

# Style Rules

Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

# Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.
