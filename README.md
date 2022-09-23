# Where to start?

![index](https://user-images.githubusercontent.com/39943/191987005-a8c8b723-d817-42f5-b382-294bf272062c.jpg)

I often hear, "I'm interested in programming, where should I start?" This is a difficult question to answer, like how someone may ask "What's the right car for me to buy?" Everyone has different needs, and different cars fulfill different needs. Similarly, there are many different types of programming, each with their own pros and cons.

## I have to pick just one?

I highly recommend picking with one specific language to start and learning the fundamentals. Many programming concepts will carry over. Just like how spoken languages have shared concepts like nouns, adjectives, verbs, and conjunctions; (many) programming langauges have variables, classes, methods, and return values.

**Stick with one programming language so you can learn the fundamentals, and then consider learning more languages later. Trust me, it will be easier that way.**

## Which one should I start with?

My personal belief is that in order to focus on programming fundamentals, it is best to start with a language that makes all the non-fundamentals as easy as possible. There are [hundreds of programming languages](https://en.wikipedia.org/wiki/List_of_programming_languages), though most are more side-hobbies for people that things actually used for work. Some are literally made as jokes, ie: [Brainfuck](https://en.wikipedia.org/wiki/Brainfuck).

[Python](https://en.wikipedia.org/wiki/Python_\(programming_language\)) and [Ruby](https://en.wikipedia.org/wiki/Ruby_\(programming_language\)) are both great languages to start with. They're both easy to read, are quick to setup, and have lots of community support around them.

## Easy to read?

Even if you have perfect 20/20 vision, some programming languages are easier to understand when read. A phrase commonly used is "reads like English". A common way to see what a language looks like is to see what it takes to have the computer print out `"Hello World!"`. Take a look at a few of the examples below.

##### C++

```cpp
#include <iostream.h>

main()
{
    cout << "Hello World!" << endl;
    return 0;
}
```

##### C#

```csharp
namespace HelloWorld
{
    class Hello
    {         
        static void Main(string[] args)
        {
            System.Console.WriteLine("Hello World!");
        }
    }
}
```

##### Brainfuck

```brainfuck
++++++++[>++++[>++>+++>+++>+<<<<-]>+>+>->>+[<]<-]>>.>---.+++++++..+++.>>.<-.<.+++.------.--------.>>+.>++.
```

##### Java

```java
class HelloWorld {
  static public void main( String args[] ) {
    System.out.println( "Hello World!" );
  }
}
```

##### Go

```go
package main
import "fmt"
func main() {
 fmt.Printf("Hello World\n")
}
```

Now compare those to:

##### Python

```python
print("Hello World")
```

##### Ruby

```ruby
puts "Hello World!"
```

## Okay, but where do I learn it?

There are many good online resources for learning programming. While I highly recommend a code school like [Turing](https://turing.edu/), there are many lightweight courses that can be done online first to see if you like programming. Turing themselves host a ["Try Coding"](https://turing.edu/try-coding) event that you can attend for relatively cheap.

_Disclaimer: I'm biased towards Turing as my wife works there._

Online courses include:
* [Udemy](https://www.udemy.com/courses/search/?q=python)
* [Codecademy](https://www.codecademy.com/catalog/language/python)
* [Computer Science 101 through Standford](https://online.stanford.edu/courses/soe-ycscs101-sp-computer-science-101)

## Maybe I can just dip my toes in the pool first?

Sure! Check out Al Sweigart's [Automate the Boring Stuff](https://www.youtube.com/watch?v=1F_OgqRuSdI&list=PL0-84-yl1fUnRuXGFe_F7qSH1LEnn9LkW). The first 15 lessons are free on YouTube, and you can decide if you like them and want to continue with [the rest of his course on Udemy](https://inventwithpython.com/automateudemy) for $13, or maybe you don't like his teaching style and want to try something else.
