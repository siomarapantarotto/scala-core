# UNDER CONSTRUCTION!

# Scala reminders collection!

# Table of contents
- [UNDER CONSTRUCTION!](#under-construction)
- [Scala reminders collection!](#scala-reminders-collection)
- [Table of contents](#table-of-contents)
- [Introduction to Scala Basics](#introduction-to-scala-basics)
- [Overview](#overview)
- [Environment and Installation](#environment-and-installation)
- [Plugin with Eclipse](#plugin-with-eclipse)
- [Plugin with IntelliJ Idea](#plugin-with-intellij-idea)
- [First Program](#first-program)
- [Identifiers](#identifiers)
- [Keywords](#keywords)
- [Datatypes](#datatypes)
- [Basic Literals](#basic-literals)
- [Escape Sequences](#escape-sequences)
- [Variable Declaration](#variable-declaration)
- [Variable Type Inference](#variable-type-inference)
- [Statements and Expressions](#statements-and-expressions)
- [Values and Variables](#values-and-variables)
- [Nested Expression Block](#nested-expression-block)
- [Basic Class in Scala](#basic-class-in-scala)
- [Extending a Scala Class](#extending-a-scala-class)
- [Singleton Objects](#singleton-objects)
- [Companion Objects](#companion-objects)
- [Arithmetic Operators](#arithmetic-operators)
- [Relational Operators](#relational-operators)
- [Logical Operators](#logical-operators)
- [Bitwise Operators](#bitwise-operators)
- [Assignment Operators](#assignment-operators)
- [Operators Precedence](#operators-precedence)
- [If else Statement](#if-else-statement)
- [If else Expression](#if-else-expression)
- [While loop](#while-loop)
- [Do While loop](#do-while-loop)
- [For Loop](#for-loop)
- [Break Statement](#break-statement)
- [Breaking Nested Loops](#breaking-nested-loops)
- [The Infinite Loop](#the-infinite-loop)
- [Function Introduction](#function-introduction)
- [Recursion](#recursion)
- [Functions with Default Arguments](#functions-with-default-arguments)
- [Functions with Named Arguments](#functions-with-named-arguments)
- [Function with Variable Arguments](#function-with-variable-arguments)
- [First Class Functions](#first-class-functions)
- [Functions Vs Methods](#functions-vs-methods)
- [Named Reusable Expressions](#named-reusable-expressions)
- [Nested Functions](#nested-functions)
- [Anonymous Function](#anonymous-function)
- [Currying Function](#currying-function)
- [Closure](#closure)
- [Closure Example](#closure-example)
- [Strings](#strings)
- [String Methods Part1](#string-methods-part1)
- [String Methods Part 2](#string-methods-part-2)
- [Declaring and Processing Array Variables](#declaring-and-processing-array-variables)
- [Concatenation of Arrays and Multi Dimensional Arrays](#concatenation-of-arrays-and-multi-dimensional-arrays)
- [Collections](#collections)
- [Lists](#lists)
- [Creating Uniform Lists](#creating-uniform-lists)
- [Tabulating a Function](#tabulating-a-function)
- [List Methods](#list-methods)
- [Sets](#sets)
- [Basic Operations on Set](#basic-operations-on-set)
- [Set Methods](#set-methods)
- [Map \[K, V\]](#map-k-v)
- [Different Operations on Map](#different-operations-on-map)
- [Map Methods](#map-methods)
- [Tuples](#tuples)
- [Operations on Scala Tuples](#operations-on-scala-tuples)
- [Options](#options)
- [Using getOrElse() Method](#using-getorelse-method)
- [Using isEmpty() Method](#using-isempty-method)
- [Iterator](#iterator)
- [Iterator Methods](#iterator-methods)
- [Introduction to Scala Traits](#introduction-to-scala-traits)
- [Value Classes and Universal Traits](#value-classes-and-universal-traits)
- [When to Use Traits?](#when-to-use-traits)
- [Matching Using Case Classes](#matching-using-case-classes)
- [Forming Regular Expressions](#forming-regular-expressions)
- [More on Regular Expressions](#more-on-regular-expressions)
- [Throwing Exceptions](#throwing-exceptions)
- [The Finally Clause](#the-finally-clause)
- [Extractors](#extractors)
- [Pattern Matching with Extractors](#pattern-matching-with-extractors)
- [Reading a Line from Command Line](#reading-a-line-from-command-line)
- [Reading and Writing File Content](#reading-and-writing-file-content)
- [Thanks and how to contribute](#thanks-and-how-to-contribute)

# Introduction to Scala Basics
# Overview
# Environment and Installation
# Plugin with Eclipse
# Plugin with IntelliJ Idea
# First Program
# Identifiers

All Scala components require an identifier, which is the name used to identify components such as variables, functions, classes, objects, or packages. 

The identifier is a string of characters that can include letters, digits, and some special characters.

Here are the rules for Scala identifiers:

<ul>
<li>An identifier is a name given to a variable, method, class, object, or package.</li>
<li>An identifier can contain alphanumeric characters, dollar sign ($) or underscore (_).</li>
<li>The first character of an identifier must be a letter, underscore, or dollar sign.</li>
<li>Subsequent characters can be a letter, digit, underscore, or dollar sign.</li>
<li>Identifiers are case-sensitive, which means that myVar and myvar are two different identifiers.</li>
<li>Identifiers cannot be a reserved keyword in Scala, such as if, while, class, object, etc.</li>
<li>Scala allows Unicode characters in identifiers, including letters and digits, but it's recommended to use only ASCII characters for better readability.</li>
<li>Scala follows the camel case convention for naming identifiers, where the first word is in lowercase and subsequent words are in uppercase. For example, myVariableName, myMethodName.</li>
</ul>

Here are the categories for Scala identifiers:
<ul>
<li>Aplhanumeric Identifiers</li>
<li>Operator Identifiers</li>
<li>Mixed Identifiers</li>
<li>Literal Identifiers</li>
</ul>

// Valid Scala identifiers
<br>val myVariable = 3
<br>def myFunction(x: Int) = x * x
<br>class MyClass
<br>object MyObject
<br>package myPackage
<br>val π = 3.14

// Invalid Scala identifiers
<br>val 123variable = 123 // Cannot start with a digit
<br>def my-function(x: Int) = x * 2 // Cannot use hyphen
<br>class new = MyClass // Cannot use the 'new' reserved keyword
<br>val #hello = "Hello" // Cannot use the '#' special character
 
# Keywords
# Datatypes
# Basic Literals
# Escape Sequences
# Variable Declaration
# Variable Type Inference
# Statements and Expressions
# Values and Variables
# Nested Expression Block
# Basic Class in Scala
# Extending a Scala Class
# Singleton Objects
# Companion Objects
# Arithmetic Operators
# Relational Operators
# Logical Operators
# Bitwise Operators
# Assignment Operators
# Operators Precedence
# If else Statement
# If else Expression
# While loop
# Do While loop
# For Loop
# Break Statement
# Breaking Nested Loops
# The Infinite Loop
# Function Introduction
# Recursion
# Functions with Default Arguments
# Functions with Named Arguments
# Function with Variable Arguments
# First Class Functions
# Functions Vs Methods
# Named Reusable Expressions
# Nested Functions
# Anonymous Function
# Currying Function
# Closure
# Closure Example
# Strings
# String Methods Part1
# String Methods Part 2
# Declaring and Processing Array Variables
# Concatenation of Arrays and Multi Dimensional Arrays
# Collections
# Lists
# Creating Uniform Lists
# Tabulating a Function
# List Methods
# Sets
# Basic Operations on Set
# Set Methods
# Map [K, V]
# Different Operations on Map
# Map Methods
# Tuples
# Operations on Scala Tuples
# Options
# Using getOrElse() Method
# Using isEmpty() Method
# Iterator
# Iterator Methods
# Introduction to Scala Traits
# Value Classes and Universal Traits
# When to Use Traits?
# Matching Using Case Classes
# Forming Regular Expressions
# More on Regular Expressions
# Throwing Exceptions
# The Finally Clause
# Extractors
# Pattern Matching with Extractors
# Reading a Line from Command Line
# Reading and Writing File Content

# Thanks and how to contribute

Thanks for viewing this repo! Contributions are more than welcome.

Feel free to contact me for more information.

<!-- FOOTER (Author / Visit My Online Resume / Download My PDF Resume) -->
<hr>
<p align='center'>
  <a href="#"><img
      src="https://img.shields.io/badge/author-%C2%A9%20Siomara%20Cintia%20Pantarotto.%20All%20rights%20reserved.-008080?style=social"></a>&nbsp;&nbsp;
  <a href="https://siomara.com.br/"><img
      src="https://img.shields.io/badge/visit-My Online Resume-008080?style=social"></a>&nbsp;&nbsp;
  <a href="https://siomara.com.br/ResumePANTAROTTO.pdf"><img
      src="https://img.shields.io/badge/download-My PDF Resume-008080?style=social"></a>
</p>



