# Skill-Lab-Group-Work

Group Members: Zi Han Ding, Ian Whitfield, Anna Speciale

Our group decided to create a program that asks the user for the year they were born then prints what generation they are in. We included the first input where it takes a name then for the second input we asked what year the user was born. Then with the use of elseif statements, we are able to compare the input to the generation years and print the generation they are born in. 

## Installation

1. Copy the URL of the respository.
2. Go to JupyterLab and open a terminal.
3. In the terminal type git clone and the URL of the respository.

## Usage

Snippet of Code:

```python
print("Hello, "+input("What is your name? ")+"!")
year = int(input("What year were you born in?"))
if year < 1900:
    print("You are very, very, very old.")
elif year < 1928:
    print("You came before the silent generation.")
```

## How to Contribute 

To contribute, fork the repository and send us pull requests and we will approve any code that improves or benefits the program. 

## Code of Conduct

Please read our code of conduct before contributing. 

## License

MIT License. See `LICENSE.md` for details.