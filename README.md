
# Monkey Programming Language & Interpreter

This is a Project for Interpreter "Monkey" Programming Language using Go Language. Of course, this is not production ready, this is for educational purposes only.




## Chapter 1 - Lexer
The first thing we built our first simple Lexing in ```lexer.go``` 


In our first ever Lexing step, we need to initialize our list of Token. You can see Monkey Programming Language Token in `token.go`
## Chapter 2 - Parser
TO DO
## Usage/Examples
1. First, clone the repo
```shell
git clone git@github.com:GerinAryoPrasetia/monkey-interpreter.git
```
2. Run
```shell
go run main.go
```
3. Insert in Command
example :
```shell
>> let foo = bar + joe
```
4. Output
```shell
>> let foo = bar + 1;
{Type:LET Literal:let}
{Type:IDENT Literal:foo}
{Type:= Literal:=}
{Type:IDENT Literal:bar}
{Type:+ Literal:+}
{Type:INT Literal:1}
{Type:; Literal:;}
```
Of course, this code doesn't make any sense. Because, this is our first step, we just create the `lexer.go` we only tokenize the input.
