---
layout: docs
title: 'WhereClause.equalsIgnoreCase()'
---
### Syntax

    table.where(indexOrPrimKey).equalsIgnoreCase(key)

### Parameters
<table>
<tr><td>indexOrPrimKey: String</td><td>Name of an index or primary key registered in <a href="Version.stores()">Version.stores()</a></td></tr>
<tr><td>key</td><td>Key to compare with. Must be a string</td></tr>
</table>

### Return Value

[Collection](Collection)

### Implementation Details

This method is an extension to the standard indexedDB API and is implemented using an algorithm invented by [David Fahlander](https://github.com/dfahlander/). For more details, please read [this article](http://www.codeproject.com/Articles/744986/How-to-do-some-magic-with-indexedDB)