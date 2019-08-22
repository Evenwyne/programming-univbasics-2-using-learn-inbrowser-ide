# Programming as Conversation 2: Using Learn In-Browser IDE

## Learning Goals

- Provide the command to run a file through Ruby
- Compare running a Ruby file versus using IRB
- Run a Ruby program in the Learn In-Browser IDE

## Introduction

Thus far, we have been using Ruby's IRB inside of the Learn In-Browser IDE.  As
a quick reminder, IDE stands for Integrated Development Environment: a set of
tools that lets you read, write, and run code.  In "Programming as Conversation
1" we were clicking in the small, black window at the bottom (the Terminal) and
were running IRB there. Here we'll start using the rest of the IDE.

When we were writing simple expressions, we could have a direct conversation
with Ruby in IRB. We didn't really need to save our work as a quick copy and
paste was sufficient to get our world loaded back up.

However, we're going to start writing longer programs now and we're going to be
quite cross if we find our program's code missing. In this lesson, we'll
demonstrate how to create and run a Ruby file.

## Provide the Command to Run a File Through Ruby

To tell Ruby to "read and run" a file, we use the command:

`ruby name_of_file`

By convention, as Ruby developers, we like to put `.rb` at the end of a file
name. It's not required, but it's helpful to remind us that the contents are
meant for **R**u**B**y. Eventually, you might learn dozens of programming
languages, and it's helpful to have a little visual clue about which language
knows how to read the conversation recorded inside.

For example:

`ruby demo.rb`

would be a typical command.

## Compare Running a Ruby File Versus Using IRB

When you run `ruby name_of_file.rb`, it's the same as if you typed in all the
contents of `name_of_file` into IRB. Any `puts` calls will print things out,
any _expression_ will be evaluated, and any _statements_ will be processed
according to the rules of Ruby. Also, if anything goes wrong, Ruby will print
an error message which will tell you which line in the file had the problem.

Remember, Ruby is not your enemy. It's your conversational partner and if you
say something it doesn't understand, it does its best to tell you how to help it
along.

## Run a Ruby Program in the Learn In-Browser IDE

Here's an animation showing how we can create a simple program using the Learn
In-Browser IDE

![Demo Animation](https://curriculum-content.s3.amazonaws.com/programming-univbasics-2/learn-ibide-create-run-ruby-file-sm.gif)

## ALTERNATIVE: Local Development

If you're familiar with the terminal and CLI environment and would prefer to
follow the lessons on your local computer, feel free to do so instead of using
the Learn In-Browser IDE.

We've made this module runnable in the In-Browser IDE so that you don't have to
learn a lot about the CLI environment or install a lot of engineering tools to
get going. In time, we'll teach you to install these, of course. And once in a
Flatiron School cohort, you'll be using them all the time and will leave the
In-Browser IDE behind.

Right now, however, we want to make sure you're focused on "learning Ruby" not
"learning to configure a development environment."

## Conclusion

OK, OK, no more delays! You have your tools: `ruby`, the in-browser IDE. You
know what we're going to study: statements. No more prologue, no more
introductions. We're going to start off by working with statements.
