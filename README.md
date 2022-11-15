<h1 align="center">Password Manager</h1>

## Table of Contents
  - [About](#about)
  - [Usage](#usage)
 
## About
A simple password manager that stores passwords in an encrypted file. This terminal app uses the <a href="https://github.com/charmbracelet/bubbletea">bubbleTea</a> framework for simplistic and modern styling. This resource currently has a few bugs that need to be ironed out before release.
><img width="500" alt="Screen Shot 2022-05-03 at 11 19 43 AM" src="https://user-images.githubusercontent.com/65473702/166483155-8af31501-b9f7-4b78-8183-5e3e71128cd1.png">
When a user enters their information, PasswordManger encrypts the data so that it cannot be accessed unless the user requests it. I am working to try and get TouchID or other recognition systems implemented for added security. The data is stored in a YAML file on the system. It is an encrypted file but is formatted for easy reading.  
  
**YAML Decrypted Example:**
```
Reddit:
  Username: awesomeSauce234
  Password: 48!*f2hfdsj%
```

> The encrypted file is essentially unreadable which is the point. A user won't even be able to access this file so it does not need to be legible. All information can be accessed from the CLI application.

## Usage
1. Launch the app in terminal using `go run passwordManager.go`
2. Follow along with the prompts
