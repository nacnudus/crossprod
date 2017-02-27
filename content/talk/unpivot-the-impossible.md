+++
date = "2017-01-29T17:30:00"
math = true
title = "Unpivot the Impossible"
abstract = "Make complex tables machine-readable with unpivotr and tidyxl"
abstract_short = "Make complex tables machine-readable with unpivotr and tidyxl"
event = "EdinbR: The Edinburgh R Usergroup"
event_url = "http://edinbr.org/edinbr/2016/10/15/Oct-meeting.html"
location = "Edinburgh, United Kingdom"
selected = false
url_pdf = ""
url_slides = "https://www.slideshare.net/DuncanGarmonsway/unpivot-the-impossible-with-r-packages-tidyxl-and-unpivotr"
url_video = ""
+++

Tables with multi-level headers and formatting that encodes information are good
for humans but bad for computers. But two new R packages can take you from
spreadsheet-import-hell to tidy-data-heaven:

* [tidyxl](https://nacnudus.github.io/tidyxl) imports .xlsx (Excel)
  spreadsheets, including formatting, without lossy coercion into ill-fitting
  tabular structures
* [unpivotr](https://nacnudus.github.io/unpivotr) provides tools for converting
  tables with complex or irregular layouts to a standard columnar structure.

In this talk I motivate the use of human intelligence rather than artificial
intelligence to untangle difficult data layouts, demonstrate how proximity is
more expressive than position when associating data cells with headers, and
survey related developments in this area.
