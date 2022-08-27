
# Reddit - CLI

A NodeJS CLI that allows to fetch random posts




## Installation

Install Reddit-CLI with npm 

```bash
  npm install reddit -g
```
    
## Usage
 General 
```bash
reddit [COMMAND]
```
To fetch a random post from the Home Section
```bash
reddit homepost
```
To fetch a random post from the Top section
```bash
reddit top
```
To fetch a random post from the Rising section
```bash
reddit rising
```
To fetch a random post from the New section
```bash
reddit new
```
This command initiates a search against the entered value and the type of query you would like
```
reddit search <value> <type>
```
The query type can be 
* post
* subreddit

### Print Command 
Note: This package uses separate commands to print into the command line
Eg.
```bash
reddit phome
reddit ptop
reddit pnew
reddit prising
```
Future Iterations would get a print option to instead implement that
Contributions are Welcome !



