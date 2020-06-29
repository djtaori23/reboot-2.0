# Problem #2
## Play with directory: 

### i) Create a directory without name from command line
#### Answer: 
```
mkdir ' '
```
>> by putting space between single inverted commas with mkdir, we can make a folder with no name.
>> Open files and in Home directory you can see a directory with no name.
### OR
```
mkdir ''$'\n'
```
>> by putting space between single inverted commas with mkdir, we can make a folder with no name.
>> Open files and in Home directory you can see a directory with no name.


### ii) Create a directory with name "-okgoogle"
#### Answer:
```
mkdir -- -okgoogle 
```
>> pass argument '--' with mkdir command which specifies no option and removes the meaning of the operator '-' 
>> Open files and in Home directory you can see a directory with name -okgoogle.
#### OR
```
mkdir ./-okgoogle
```
>> when './' arguement is passed before name of directory it takes literal meaning of '-' operator instead of its special meaning.
>> Open files and in Home directory you can see a directory with name -okgoogle.
