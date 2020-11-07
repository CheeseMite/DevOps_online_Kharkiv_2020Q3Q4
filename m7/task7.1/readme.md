# Task7.1

```python
def fizzbuzz() :
    for num in range(1,101) :
        if (num % 15 == 0) :
            print("FizzBuzz")
        elif (num % 3 == 0) :
            print("Fizz")
        elif (num % 5 == 0) :
            print("Buzz")


def count_vowels(word) :
    vowels = "aeiou"
    counter = 0
    for leter in word:
        if ( leter.lower() in vowels) :
            counter+=1 
    return counter


if __name__ == "__main__":
    fizzbuzz()
    print(count_vowels("something"))
```