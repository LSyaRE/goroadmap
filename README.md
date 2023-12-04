# Go roadmap: tutorial for begginers

## How to initialize a local repository

First we put this into a terminal

```bash
git init 
```

Second we create a commit with the following commands

```bash
# if you create a README file
git add README.md

# or 
git add .

# finally 
git commit -m "first commit"
```

or simply  use

```bash
git commit -a -m "first commit"
```

## Go terminal commands

### Init Golang project

We start a project with the following command. The command should be called into a empty folder.

```
go mod init projectname
```

### Run command

We run the project with the following command.

```
go run .\src\index.go
```
