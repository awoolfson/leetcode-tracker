# leetcode tracker
## a tool for tracking progress on leetcode
#### by Auden Woolfson

This is script in python for scraping the popular website leetcode and updating an excel spreadsheet with information on a specific problem. It requires the URL of the desired problem and the filepath to the excel spreadsheet the user wants to update.

The spreadsheet used must be formatted in a specific way. Here is a table that illustrates that formatting:

|A|B|C|D|E|F|G|
|-|-|-|-|-|-|-|
| | | | | | | |
|-|-|-|-|-|-|-|
| |Name|Difficulty|Related Topics|Solution|Notes|URL|
| |Two Sum|Easy|Array, Hash Table|Store numbers in dictionary and check the difference|very easy|https://leetcode.com/problems/two-sum/|

To be clear, the cell that reads Name should be in row 2 column B.

The arguments for this script follow:

|argument|function|
|--------|--------|
|-u|URL for the leetcode page|
|-x|filepath to the xl workbook|
|-s|text for solution column|
|-n|text for notes column|
|--sheet|name of the sheet in the workbook (default: Sheet1)|
