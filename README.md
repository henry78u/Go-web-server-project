# Go Web Server Project

A simple Go web server that handles form submissions and serves static files.  
It demonstrates routing, form parsing, and basic HTTP handling in Go.

## Features

- Handles GET and POST requests
- Parses form data
- Serves static HTML files
- Simple routing system

## Tech Stack

- Go (Golang)
- net/http package
- HTML

## Project Structure

Go-web-server-project
├── main.go
├── static/
│   └── index.html
|   |__ form.html
└── README.md

## How to Run

git clone https://github.com/henry78u/Go-web-server-project.git
cd Go-web-server-project
go run main.go

Open:
http://localhost:8000

## Routes

GET  /         → Static homepage  
GET  /hello    → Hello endpoint  
POST /form     → Form handler

## Example

Name: Uchechukwu  
Address: 123 Business St  

Response:

Name - Uchechukwu  
Address - 123 Business St

## Future Improvements

- Add database integration
- Add authentication system
- Improve UI styling

## Author

Built by Uchechukwu Okonkwo