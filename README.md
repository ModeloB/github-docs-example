# Writing Good Documentation

##Step 1 - Using Codeblocks.

![Photo of a Eyeballs](assets/Mihoshi.png)

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code. A good Cloud Engineer uses Codeblock whenever possible.

Because it allow others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks ```
- Not to be confused with the single quotation '''
```ruby
# Define a class named 'Person'
class Person
  # Define the initializer method (constructor)
  def initialize(name, age)
    @name = name
    @age = age
  end

  # Method to display a greeting
  def greet
    puts "Hello! My name is #{@name} and I am #{@age} years old."
  end

  # Method to have a birthday
  def have_birthday
    @age += 1
    puts "Happy birthday! I am now #{@age} years old."
  end
end

# Create an instance of the Person class
person = Person.new("Alice", 30)

# Call methods on the object
person.greet
person.have_birthday
```

-When you can you should attempt to apply syntax highlighting to your codeblocks.


<img width="200" src="https://github.com/user-attachments/assets/d65fee0c-14e8-4592-accf-87b48bfab359" />


Good Cloud Engineers use codeblocks for both code ans errors that appear in the console.


```bash
Traceback (most recent call last):
  File "script.py", line 7, in <module>
    result = divide_numbers(10, 0)
  File "script.py", line 3, in divide_numbers
    return a / b
ZeroDivisionError: division by zero
```

>Here is an example of using a codeblock for an error that appears in bash


# Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#references)
- [x] Finish Step 1
- [x] Finish Step 2
- [x] Finish Step 3

# Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

# Step 5 How to create a table


You can use following format to create tables:

```markdown
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Scorpions | `:scorpion:` | :scorpion:|
| Scorpius | `:scorpius:` | ♏ |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options.[<sup>[2]</sup>](#references)

![Photo of a River and Tree](assets/River.gif)



## References

- [GitHub Flavored Markdown Spec](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links)
- [Autolinked references and URLs](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/autolinked-references-and-urls)
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extentions)](https://github.github.com/gfm/#tables-extension-)<sup>[2]</sup>
