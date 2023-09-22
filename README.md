# Github Docs Example

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share code**.
A good **Cloud Engineer** uses CodeBlocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- in order to create codeblocks in markdown you need to use three backticks(`)
- not to be confused with single quotations (')

```
# Ruby code that calculates the factorial of a number using a recursive function
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate the factorial of 5
result = factorial(5)
puts "Factorial of 5 is #{result}"
```


- when you can you should attempt to apply syntax highlighting to your code blocks

``` ruby
# Ruby code that calculates the factorial of a number using a recursive function
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate the factorial of 5
result = factorial(5)
puts "Factorial of 5 is #{result}"
```

- Make note of where the backtick keyboard key is located.
- It should appear above the tab key,
- but it may vary based on your keyboard layout.
