STUDY HALL - Discussion over these topics

------------

## Executable ***
- Bin
- run file
- .exe
- Open a program
- Compile and run it

## Gemfile
----
### holds all the gems that you downloaded and used
- gem 'pry'
- gem 'colorize'
- gem 'httparty'
- **bundle install** 
    - what is it doing?
        - installs all the gems
        - gemfile.lock
        - *where are they getting installed* **
            - installed in seperate directory
            - root directory

## Environment File
- What is it supposed to do?
    - Ties all the first together.
    - pulls together all the files that will be necessary
    - require the relative file in one folder
    - run the file you require the environment file
    - in the run executable you require this file.
    - point of reference is the run file.

## Bin Folder
- Binary 
- holds our executable
- i.e. run file

## Shebang
- line that lets your compiler know that this executables code is going to be in ruby.
- run is text file?
- *#!/usr/local/bin/env ruby?*
- *#!/usr/local/bin/ruby?*
- ** HEY I CAN GO TO THIS **FILE PATH** **

## Require && Require_Relative ***
### Require
- Absolute path
    - the exact location
    - gems
    - in the computer -- outside of your main repo
### Require Relative
- Relative path
    - same file group
    - relative to the current directory. 
    - path - location of the file/directory
    - require relative - needs a file path, so that it can require. 
    - connects it.


class Person
    
    def initialize(name)
        @name = name
    end
end

Person.new("eri")


## Class
- What is a class?
    - Blueprint of the objects
        - bunch of methods
        - class Person -> Has a bunch of methods

## new Method
- we dont code out a method called new.
- we dont access - private
- takes you to where?
- initialize
## Initialize
- What kind of method is initialize?
    - instance method. **
    - initialized the instance with some attributes.
- creating a new obj.

## Methods - Class vs Instance
- Class Method
    - def self.method_name
    - what can i call this method on?
        - on the class itself
    - self.all - give you back all the objects of that class

- Intance methods
    - def method_name
    - What can i call this method on?
        - intance of that class
## Macros - Attr_accessor
- Macro: writes code for you.
- Attr_accessor
    - what type of method?
        - instance
    - reader and writer
    - attr_reader
    - attr_writer
    - MUST BE able to def them yourselves

## Variables Types && Scopes
- SCOPE: where its accessible 
- local
    - cats = "a cat"
    - scope is to the local method
    - accessible wherever it is locally.
- global ** BONUS
    - $cats **
    - scope is anywhere **
- instance **
    - @cat_name => "Jimmin" 
    @cat_name => "Luna"
    - def name
        @cat_name
    - scope is the instance
- class
    - @@all
    - scope is the class

## Self
- what is self?
    - depends on the context
        - where is it being used
        - def intance_method
            - self => instance
        - def self.class_method
            - self => class

## Metaprogramming
- Metaprogramming: Code that writes more code.

## Iterators/Enumerators ***
- each, map/collect, find_all/select, sort
    - iterators over each element of the collection
- return values
    - What do the iterators return

## Return 
- WHats the different between return and puts?
    - puts is a method!
        - outputs information
        - returns nil
    - return just returns from a method
        - last line of code - implicit return
        - explicit return
            - stops at the end.

## Modules
- If you are using it

## D.R.Y
- Dont Repeat Yourself

## SRP 
- Single Responsible Principal

## SOC
- Seperation Of Concerns
