# ST3 syntax for Spark query plan 'language'

### Overview
This is a syntax file that enables syntax highlighting for Spark query plan
output in Sublime Text 3.

Spark query plan 'language' is not a real language so contexts were applied
somewhat arbitrary to achieve a more readable look of query plan outputs.

### Installation
In Sublime Text 3 go to `Preferences -> Browse Packages` menu to open a folder
with installed packages. Copy `SparkQueryPlan.sublime-syntax` to the `User` subfolder.
`Spark Query Plan` should now appear in the list of available syntaxes under
`View -> Syntax` menu.

### Comments
One can add comments to the query plan. Comments start with `/*` and end with `*/`.
