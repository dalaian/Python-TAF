# Part I
This is the solution for the part one of the assessment

## Requisites
You need Python in your computer to run the scripts

### How to install python
You have several ways to install python

You can download it from https://www.python.org/downloads/mac-osx/

Or, if you are on Mac, you can install it if you have brew or npm

brew command
```
brew install python
```

npm command
```
npm install python -g
```


### Main
To run the code through the command line be sure you are under the the folder **part_one**

Run the code as follow and it will print in the console what was asked in the document
```
python main.py
```

By default, it executes the script using the file "data/max_edge_case.txt",
which is a file pretty similar to the one given in the assessment

But you can run it using a different file adding the file path as a parameter as follows:
```
python main.py <file_path>
```

For instance
```
python main.py data/min_edge_case.txt
```

### Unit Tests
As specified in the document, you can run positive and negatives tests to the code

To run the tests, be sure you are in the folder **part_one/tests**

Run the positive tests as follows
```
python -m unittest positive_tests
```

Run the negative tests as follows
```
python -m unittest negative_tests
```
Certain assumptions were implemented to have negative tests, check the details in __utils/utils.get_largest_word()__