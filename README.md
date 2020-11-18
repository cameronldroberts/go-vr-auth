### Authentication in Golang with JWTs

### Environment variables that hold Auth0 details 
```
export AUD=<AUDIENCE> `options.Audience`
export ISS=<> `options.Authority`
```
### Running the project 
Link it with an active Auth0 account - https://auth0.com/signup

cd into `static/`
```
npm i
npm start
```

In a seperate terminal start the Go code with the following
cd into the root of the project 
```
go get 
go run . 
```

Following along with this blog - https://auth0.com/blog/authentication-in-golang/