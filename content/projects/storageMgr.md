---
title: "Storage Manager for file I/O operations"
description: "Associated with Illinois Institute of Technology"
dateString: Jan 2023 - Feb 2023
draft: false
tags: ["C", "Database"]
showToc: false
weight: 205
--- 

## Description
The purpose of this project is to implement a simple storage manager - a module that is capable of reading blocks from a file on disk into memory and writing blocks from memory to a file on disk. The storage manager deals with pages of fixed size. In addition to reading and writing pages from a file, it provides methods for creating, opening, and closing files. The storage manager maintains several types of information for an open file: The number of total pages in the file, the current page position (for reading and writing), the file name, and a POSIX file descriptor or FILE pointer. Error codes are maintained in a separate file dberror.h and test cases are implemented from test_helper.h.

The main functionalities include initializing, creating, opening, closing and destroying page files. The read functionalities are reading first page, last page, previous page, next page and current page from a block. Apart from the above there are also methods to writeBlock, appending empty block and ensuring the capacity of the page. 
* The above methods are explained in detail in the README file of below git link.