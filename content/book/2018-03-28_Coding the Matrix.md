---
title: "Coding the Matrix"
url: "Coding the Matrix"
editor_options: 
  chunk_output_type: inline
date: 2018-06-25
thumbnail: "img/banner/coding_the_matrix.jpg"
categories:
  - "post"
tags: 
  - ""
draft: false
---
## Lab 1: Introduction to Python—sets, lists, dictionaries, and comprehensions

Python provides some simple data structures for grouping together multiple values, and integrates them with the rest of the language. These data structures are called collections. 

### Sets

A set is an unordered collection in which each value occurs at most once. You can use curly braces to give an expression whose value is a set. Python prints sets using curly braces.

{{< highlight python >}}>>> {2, 1, 3}
{1, 2, 3}
{{< /highlight >}}

#### Set comprehensions

Python provides for expressions called comprehensions that let you build collections out of other collections. We will be using comprehensions a lot because they are useful in constructing an expression whose value is a collection, and they mimic traditional mathematical notation. Here’s an example:

{{< highlight python >}}>>> {2*x for x in {1,2,3} }
{2, 4, 6}
{{< /highlight >}}

### Lists

Python represents sequences of values using lists. In a list, order is significant and repeated elements are allowed. The notation for lists uses square brackets instead of curly braces. The empy list is represented by `[]`.
{{< highlight python >}}>>> [1,1+1,3,2,3]
[1, 2, 3, 2, 3]{{< /highlight >}}

#### Slices

**Slices**: A slice of a list is a new list consisting of a consecutive subsequence of elements of the old list, namely those indexed by a range of integers. The range is specified by a colon-separated pair `i : j` consisting of the index i as the first element and j as one past the index of the last element. Thus `mylist[1:3]` is the list consisting of elements 1 and 2 of mylist.

**Prefixes**: If the first element i of the pair is 0, it can be omitted, so `mylist[:2]` consists of the first 2 elements of mylist. This notation is useful for obtaining a prefix of a list.

**Suffixes**: If the second element j of the pair is the length of the list, it can be omitted, so `mylist[1:]` consists of all elements of mylist except element 0.

**Slices that skip**:You can use a colon-separated triple `a:b:c` if you want the slice to include every cth element. For example, here is how you can extract from L the list consisting of even-indexed elements and the list consisting of odd-indexed elements:

### Tuples
Like a list, a tuple is an ordered sequence of elements. However, tuples are immutable so they can be elements of sets. The notation for tuples is the same as that for lists except that ordinary parentheses are used instead of square brackets.

#### IF

{{< highlight python >}}⟨expression⟩ if ⟨condition⟩ else ⟨expression⟩{{< /highlight >}}

Source <a href="https://orga.cat/posts/most-useful-git-commands" target="_blank">orga.cat/posts/most-useful-git-commands</a>