---
title: How to Work with Tables in Excel vs Google Sheets
date: 2024-07-02T17:27:11.000Z
author: Eamonn Cottrell
authorURL: https://www.freecodecamp.org/news/author/eamonn/
originalURL: https://www.freecodecamp.org/news/excel-vs-google-sheets-tables/
translator: ""
reviewer: ""
---

/ [#spreadsheets][1]

<!-- more -->

# How to Work with Tables in Excel vs Google Sheets

![Eamonn Cottrell](https://www.freecodecamp.org/news/content/images/size/w60/2023/09/Linkedin-Creator-Banners.jpg)

[Eamonn Cottrell][2]

  ![How to Work with Tables in Excel vs Google Sheets](https://www.freecodecamp.org/news/content/images/size/w2000/2024/07/4.jpg)

Google Sheets recently released an all new feature: tables.

Well, _new_ is a bit of an overstatement. Excel has had proper tables for many, many years, and it's been a point of contention in the spreadsheet community.

In this article, I'll break down what exactly tables are, why they're important, and then see how Google Sheet's new tables stack up against Microsoft Excel's.

Here is a video walkthrough of everything we'll cover:

<iframe width="356" height="200" src="https://www.youtube.com/embed/vBp5mveYZZ4?feature=oembed" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen="" title="Microsoft Excel vs Google Sheets Tables [NEW for 2024]" name="fitvid0"></iframe>

## What's a Table?

A table is a way of structuring and formatting data in a spreadsheet. It groups together rows and columns of data so that they can be more easily filtered, grouped, and analyzed.

Many people would look at the following bit of data and wrongly assume that it's already in a table.

![image-103](https://www.freecodecamp.org/news/content/images/2024/06/image-103.png)

Data in Excel

This is merely well organized rows and columns of data in Excel. Each column is a separate category of information, that is ids, names, emails, job titles, and salaries.

Each row represents one entry of that data. So, you'd put your id, name, email, job title and salary going left to right in a row.

Simple, yes?

A table contains all the same data, but by formatting it as a table we can unlock a whole lot of additional functionality.

The first of which is the appearance itself. When we create a table, Excel immediately colors our data with a dark header row and bands of alternating colors.

![image-104](https://www.freecodecamp.org/news/content/images/2024/06/image-104.png)

Table in Excel

Sheets does the same thing, as we can see below.

![image-105](https://www.freecodecamp.org/news/content/images/2024/06/image-105.png)

Table in Google Sheets

So, a table is simply a way of managing and grouping data more easily. But it goes much further than just formatting, as we'll see.

## Why are Tables Important?

Tables help reduce errors. When dealing with data, we are always making sure the data is clean and that we don't have errors in our formulas.

Tables help keep things orderly simply by being structured and formatted well. But as we'll see in the formula section in a moment, they also allow us to reduce errors in formulas by dynamically calculating things for us

## How to Create a Table in Excel and Sheets

In Microsoft Excel, creating a table is as easy as clicking anywhere in the data range and pressing `CTRL + T`. Immediately, Excel will predict the data range for the table and ask you to confirm this.

![image-106](https://www.freecodecamp.org/news/content/images/2024/06/image-106.png)

Excel table data range

Alternatively, you can find the same create table option from the Insert Menu in the Ribbon at the top.

![table](https://www.freecodecamp.org/news/content/images/2024/06/table.png)

Excel insert menu

Over in Sheets, you'll need to either right click in a cell in the data range, or select the option from the Format menu to Convert to Table.

![sheets](https://www.freecodecamp.org/news/content/images/2024/06/sheets.png)

Convert to table options in Google Sheets

One caveat in Sheets: if you right click in a cell, you have to select the whole data range for it to convert to a table. Whereas, if you select Format - Convert to table from the menu, it is (like Excel) smart enough to predict the whole data range.

A small thing. But Excel takes the prize for ease of creation.

![right-click](https://www.freecodecamp.org/news/content/images/2024/06/right-click.png)

Convert to table in Google Sheets

**⭐Winner: EXCEL**

## How to Format Tables in Excel and Sheets

As we saw initially, some formatting is done as soon as we create a table.

From here, though, both programs allow for further customization.

In Sheets, we can select the dropdown in the top left next to the table name to access a few options immediately. For the most part, we can simply change the alternating colors of the table.

![sheets-format](https://www.freecodecamp.org/news/content/images/2024/06/sheets-format.png)

Formatting options in Google Sheets

If we select Custom, it opens up the full alternating colors menu that is also accessible through the Format menu. This gives us more control over the colors, but it's all aesthetic.

![image-110](https://www.freecodecamp.org/news/content/images/2024/06/image-110.png)

Alternating colors menu in Google Sheets

Meanwhile in Excel, we have the same options with a few more toggle selections for styling. For instance, we can check the first column to bold the text in the id column or we toggle between banded columns and/or rows.

And on the far right of the Table Design tab in the Ribbon, there are a ton of prebuilt styles that we can toggle on and off.

![format-excel](https://www.freecodecamp.org/news/content/images/2024/06/format-excel.png)

Table design in Excel

Both programs give plenty of options here, and this is mostly to make the tables look good. But Excel comes out on top with more options.

**⭐Winner: EXCEL**

## How to Sort Tables in Excel and Google Sheets

In both programs, there is a dropdown toggle button in each of the header row's cells. Selecting this in Excel allows us to sort ascending or descending...or even by color.

![sort](https://www.freecodecamp.org/news/content/images/2024/06/sort.png)

sort in excel

For instance, if we have some of our data using a blue font color, we can actually sort it by that color:

![sort-color](https://www.freecodecamp.org/news/content/images/2024/06/sort-color.png)

Sort by color in Excel

What about Google Sheets? Yep, same deal there. It will also detect when different colors are used and allow you to do the same type of sorting.

![sheets-sorting-options-1](https://www.freecodecamp.org/news/content/images/2024/06/sheets-sorting-options-1.png)

Sort by color in Sheets

Excel does have a Custom Sorting dialog box that can drill down into more detail. For instance, you can add levels of sorting.

Using our color example, we can first sort by the blue font colors in the email color and then by the red font colors in the job title column.

![double-sort](https://www.freecodecamp.org/news/content/images/2024/06/double-sort.png)

Multiple column sorting in Excel

Google Sheets can do the same thing, but not from the header drop downs. The header drop down sorting is restricted to one row at a time in Sheets.

But, if you select the entire table's data range and then `Data - Sort Range - Advanced range sorting options`, you are able to sort by multiple columns in Google Sheets.

![advanced-sort-google-sheets](https://www.freecodecamp.org/news/content/images/2024/06/advanced-sort-google-sheets.png)

Advanced sorting in Google Sheets

Sheets' advanced sorting is not as powerful as Excel's, though. You are only able to sort ascending or descending by value. Excel takes the cake on this one by a hair.

![google-sheets-muiltiple-row-sorting](https://www.freecodecamp.org/news/content/images/2024/06/google-sheets-muiltiple-row-sorting.png)

**⭐Winner: EXCEL**

## How to Filter Tables in Excel and Google Sheets

Filtering works exactly the same as sorting. In both programs, click the dropdown selector in the header row to see the options for filtering.

In both programs, we have the same options. We can filter by color just like in our sorting. We can filter by values by either selecting all, none, or individual values. And we can filter by condition.

Here's Google Sheet's menu:

![image-113](https://www.freecodecamp.org/news/content/images/2024/06/image-113.png)

Filtering in Google Sheets

And here's Excel's menu. All the same options are available. Both programs allow for custom filter formulas to be entered as well.

![image-112](https://www.freecodecamp.org/news/content/images/2024/06/image-112.png)

Filtering in Excel

**⭐Winner: TIE**

## How to Use Tables in Formulas in Excel and Google Sheets

One of the big reasons to use tables lies in formulas. Whether you use Excel or Sheets, you are likely taking advantage of built-in functions and the ability to create custom formulas for analyzing your data.

By holding your data in a table, your formulas can reference that data dynamically.

Meaning, if you add rows of data to your table, any formulas referencing those table values will update automatically.

The risk of breaking things by adding data decreases dramatically with the use of tables.

Here's a simple example. If we wanted to combine the first and last names into one cell, we could concatenate them with this formula `=Salary[first_name]&" "&Salary[last_name]`.

In Excel, we reference a table by its name, in this case, `Salary`. Then within brackets, we reference a column name, `[last_name]`.

![image-115](https://www.freecodecamp.org/news/content/images/2024/06/image-115.png)

Spill formula in Excel

We can do the exact same in Sheets.

![image-116](https://www.freecodecamp.org/news/content/images/2024/06/image-116.png)

Formula referencing in Sheets

There's one powerful difference, though. In Excel, the formula will spill down. Meaning, we only have to write it once at the very top, but because it sees that we're referencing values in a table, it will spill down to every row in the table.

In Google Sheets, we still have to drag the formula down.

Now, sometimes, we may not want things to spill down. In this case we can use different syntax in Excel. Instead of the column name within brackets, we can add an @ sign and another set of brackets. This tells Excel to only make the calculation on one row:

![image-117](https://www.freecodecamp.org/news/content/images/2024/06/image-117.png)

Formula referencing in Excel

Excel flexes on this one. It's much more powerful to use tables in formulas in Excel than in Sheets.

**⭐Winner: EXCEL**

## How to Change Table Range in Excel and Google Sheets

What if we want to extend our table or remove data from it? Both Google Sheets and Excel allow us to do this easily.

Say we want to add a column for the full name of a person. In both programs, if we simply type in `full_name` in G1 to the right of our last column, that column will become a part of the table's data range.

Anytime we type in an adjacent column or row to our table data, the programs will assume the table needs to extend to include it.

Then, we can use a version of the formula from our previous example to insert the full names. Now that we are inside of the table, though, it's not necessary to include the title of the table in our formula.

Now, all that's needed in Excel is `=[@[first_name]]&" "&[@[last_name]]`.

![image-119](https://www.freecodecamp.org/news/content/images/2024/06/image-119.png)

Reference table columns in Excel

For Google Sheets, it's the same inside the table as outside it: `=Table2[first]&" "&Table2[last]`. Sheets also requires us to drag the formula down. It does not handle spilling like Excel (yet).

![image-118](https://www.freecodecamp.org/news/content/images/2024/06/image-118.png)

Reference table columns in Sheets

To add columns within a table, we can right click the column name and select insert.

![image-120](https://www.freecodecamp.org/news/content/images/2024/06/image-120.png)

Insert column in Excel

Google has a slight edge here in that you can select whether to insert to the left or the right, whereby Excel only inserts to the left.

![image-121](https://www.freecodecamp.org/news/content/images/2024/06/image-121.png)

Insert column Google Sheets

Inserting rows is exactly the same. Excel allows for inserting rows above, while Sheets allows you to select above or below.

![image-122](https://www.freecodecamp.org/news/content/images/2024/06/image-122.png)

Inserting rows Google Sheets

In both programs, deleting rows and columns is as simple as selecting the row(s) or column(s), right clicking, and selecting delete.

In Excel you have the added benefit of a keyboard shortcut. `CTRL + -` will delete the selected rows or columns.

Both programs will also allow you to convert a table back to a regular data range. In Excel, it's the `Convert to Range` button in the `Table Design` tab of the menu

![convert](https://www.freecodecamp.org/news/content/images/2024/07/convert.png)

Convert to Range option in Excel

And in Google Sheets, it's the `Revert to unformatted data` option from the table dropdown menu.

![revert](https://www.freecodecamp.org/news/content/images/2024/07/revert.png)

Revert to unformatted data option in Sheets

**⭐Winner: TIE**

## How to Add a Total Row in a Table

There's a good chance you'll want to total up the amounts in a column. How easy is this to add in a table?

You can do it in both programs, but...

Excel makes it incredibly easy. There's a toggle option for this in the Table Design menu in the Ribbon. Toggle this on, and a Total row is automatically included and calculated at the bottom.

![total-row](https://www.freecodecamp.org/news/content/images/2024/06/total-row.png)

Total row in Excel

Can you do the same in Sheets?

Yes, you've just got to do it yourself.

![image-124](https://www.freecodecamp.org/news/content/images/2024/06/image-124.png)

Total row in Sheets

**⭐Winner: EXCEL**

## Who Wins?

Well, it's no surprise that Excel comes out on top. Sheets users (myself included) have a lot to be excited about with the ability to finally create proper tables. By and large, the functionality is just as powerful as Excel.

And much like many features compared between the two programs, Sheets can probably get the job done for most use cases.

Excel, as per normal, simply does more and does it a little bit better.

I'm Eamonn, and I'll help you **get good at spreadsheets**. Join my free newsletter, [Got Sheet, here][3].

---

![Eamonn Cottrell](https://www.freecodecamp.org/news/content/images/size/w60/2023/09/Linkedin-Creator-Banners.jpg)

[Eamonn Cottrell][4]

I make coding and spreadsheet tutorials on YouTube, freeCodeCamp and LinkedIn. I run ultras for fun.

---

If you read this far, thank the author to show them you care. Say Thanks

Learn to code for free. freeCodeCamp's open source curriculum has helped more than 40,000 people get jobs as developers. [Get started][5]

[1]: /news/tag/spreadsheets/
[2]: /news/author/eamonn/
[3]: https://www.gotsheet.xyz/subscribe
[4]: /news/author/eamonn/
[5]: https://www.freecodecamp.org/learn/