foo
===

Can I get some description please
  on more than one line, if possible.

foo.bar() 
-----------------------------
I so cool

Deprecated: Not a good function

**Returns**: Boolean | null, I so cool

foo.testNamed(file, optional) 
-----------------------------
This is a test function
  with a description on multiple lines

**Parameters**

**file**: String | null, filename to parse
                       this parsing thing is funny business

**optional**: Boolean | null, Changes behavior

**Fires**: module:foo#event:one_thing

**Fires**: module:foo#event:another

**Fires**: module:foo#event:booyah


foo.testAnonynous() 
-----------------------------
function without name

**Returns**: String, the result

foo.testAnon2() 
-----------------------------
second function without name

**Returns**: String, the result

foo.func1(a, b) 
-----------------------------
Can I get some description please
  on more than one line, if possible.

**Parameters**

**a**: the first param

**b**: the second param

**Returns**: the result

foo.func2(c, d) 
-----------------------------
Can I get some description please
  on more than one line, if possible.

**Parameters**

**c**: the first param

**d**: the second param

**Returns**: the other result

foo.testDeprecated() 
-----------------------------
This is a deprecated function.

Deprecated: Because I said so


SampleClass
===
This is a class

foo.SampleClass.func1(a, b) 
-----------------------------
A method in the class

**Parameters**

**a**: the first param

**b**: the second param

**Returns**: the result
foo.SampleClass.testAnonynous() 
-----------------------------
function without name

**Returns**: String, the result
foo.SampleClass.testNamed(file, optional) 
-----------------------------
This is a test method
    with a description on multiple lines

**Parameters**

**file**: String | null, filename to parse
                         this parsing thing is funny business

**optional**: Boolean | null, Changes behavior

**Fires**: module:foo#event:one_thing

**Fires**: module:foo#event:another

**Fires**: module:foo#event:booyah



---

*(c) 2012 Blah Blah Blah*

**License:** MIT Joe Schmo

**Overview:** What's up?

**Version:** 1.0.1
