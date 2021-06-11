# How to set up Keycloak

## 1. Add realm :  DEMO

Add realm with name [ Demo ]

## 2. Add Client

1. select realm : Demo
2. select [ Clients ] 
3. Add Client -> Client ID [ sso-client ]  and Valid Redirect URIs [ http://localhost:4444/login/oauth2/code/keycloak ]


## 3. Add User

1. select Users
2. Add User -> Username [ user ] and Email [ user@test.com ]