# Basic Auth

## Purpose

Demonstrate the use of nginx as a basic auth layer

## Setup instructions

1. Install docker
2. Run `docker-compose up`

## Update /etc/host to include .com.au

```
##
127.0.0.1	localhost
127.0.0.1	localhost.com.au
127.0.0.1	localhost.co.uk
```

## Testing the app

1. Navigate to http://localhost.com.au
2. See page is rendered with service name
3. Navigate to http://localhost.co.uk
4. See page is prompted with login info
5. Enter username: user, password: hello
6. See the same info displayed
