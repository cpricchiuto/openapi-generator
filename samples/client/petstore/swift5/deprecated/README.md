# Swift5 API client for PetstoreClient

This is a sample server Petstore server. For this sample, you can use the api key `special-key` to test the authorization filters.

## Overview
This API client was generated by the [OpenAPI Generator](https://openapi-generator.tech) project.  By using the [openapi-spec](https://github.com/OAI/OpenAPI-Specification) from a remote server, you can easily generate an API client.

- API version: 1.0.0
- Package version: 
- Build package: org.openapitools.codegen.languages.Swift5ClientCodegen

## Installation

### Carthage

Run `carthage update`

### CocoaPods

Run `pod install`

## Documentation for API Endpoints

All URIs are relative to *http://petstore.swagger.io/v2*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*PetAPI* | [**addPet**](docs/PetAPI.md#addpet) | **POST** /pet | Add a new pet to the store
*PetAPI* | [**deletePet**](docs/PetAPI.md#deletepet) | **DELETE** /pet/{petId} | Deletes a pet
*PetAPI* | [**findPetsByStatus**](docs/PetAPI.md#findpetsbystatus) | **GET** /pet/findByStatus | Finds Pets by status
*PetAPI* | [**findPetsByTags**](docs/PetAPI.md#findpetsbytags) | **GET** /pet/findByTags | Finds Pets by tags
*PetAPI* | [**getPetById**](docs/PetAPI.md#getpetbyid) | **GET** /pet/{petId} | Find pet by ID
*PetAPI* | [**updatePet**](docs/PetAPI.md#updatepet) | **PUT** /pet | Update an existing pet
*PetAPI* | [**updatePetWithForm**](docs/PetAPI.md#updatepetwithform) | **POST** /pet/{petId} | Updates a pet in the store with form data
*PetAPI* | [**uploadFile**](docs/PetAPI.md#uploadfile) | **POST** /pet/{petId}/uploadImage | uploads an image
*StoreAPI* | [**deleteOrder**](docs/StoreAPI.md#deleteorder) | **DELETE** /store/order/{orderId} | Delete purchase order by ID
*StoreAPI* | [**getInventory**](docs/StoreAPI.md#getinventory) | **GET** /store/inventory | Returns pet inventories by status
*StoreAPI* | [**getOrderById**](docs/StoreAPI.md#getorderbyid) | **GET** /store/order/{orderId} | Find purchase order by ID
*StoreAPI* | [**placeOrder**](docs/StoreAPI.md#placeorder) | **POST** /store/order | Place an order for a pet
*UserAPI* | [**createUser**](docs/UserAPI.md#createuser) | **POST** /user | Create user
*UserAPI* | [**createUsersWithArrayInput**](docs/UserAPI.md#createuserswitharrayinput) | **POST** /user/createWithArray | Creates list of users with given input array
*UserAPI* | [**createUsersWithListInput**](docs/UserAPI.md#createuserswithlistinput) | **POST** /user/createWithList | Creates list of users with given input array
*UserAPI* | [**deleteUser**](docs/UserAPI.md#deleteuser) | **DELETE** /user/{username} | Delete user
*UserAPI* | [**getUserByName**](docs/UserAPI.md#getuserbyname) | **GET** /user/{username} | Get user by user name
*UserAPI* | [**loginUser**](docs/UserAPI.md#loginuser) | **GET** /user/login | Logs user into the system
*UserAPI* | [**logoutUser**](docs/UserAPI.md#logoutuser) | **GET** /user/logout | Logs out current logged in user session
*UserAPI* | [**updateUser**](docs/UserAPI.md#updateuser) | **PUT** /user/{username} | Updated user


## Documentation For Models

 - [ApiResponse](docs/ApiResponse.md)
 - [Category](docs/Category.md)
 - [Order](docs/Order.md)
 - [Pet](docs/Pet.md)
 - [Tag](docs/Tag.md)
 - [User](docs/User.md)


## Documentation For Authorization


## api_key

- **Type**: API key
- **API key parameter name**: api_key
- **Location**: HTTP header

## auth_cookie

- **Type**: API key
- **API key parameter name**: AUTH_KEY
- **Location**: 

## petstore_auth

- **Type**: OAuth
- **Flow**: implicit
- **Authorization URL**: http://petstore.swagger.io/api/oauth/dialog
- **Scopes**: 
 - **write:pets**: modify pets in your account
 - **read:pets**: read your pets


## Author


