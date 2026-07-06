# \SecureMessagesAPI

All URIs are relative to *https://api.mydex.org*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetSecureMessageConversation**](SecureMessagesAPI.md#GetSecureMessageConversation) | **Get** /secure-messages/conversation | Retrieve all secure messages for a given conversation.
[**PostSecureMessageReceive**](SecureMessagesAPI.md#PostSecureMessageReceive) | **Post** /secure-messages/receive | Supports sending a message to the member&#39;s PDS.
[**PostSecureMessageSend**](SecureMessagesAPI.md#PostSecureMessageSend) | **Post** /secure-messages/send | Supports sending a message from the member&#39;s PDS.



## GetSecureMessageConversation

> SecureMessageConversationResponse GetSecureMessageConversation(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).ConversationId(conversationId).Execute()

Retrieve all secure messages for a given conversation.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	connectionToken := "abc123xyz456" // string | Member's Connection Key
	uid := "1234" // string | The unique ID of a mydex member
	conId := "1234-67890" // string | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID.
	conversationId := "referral-123" // string | The specific ID of the conversation that groups messages together

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecureMessagesAPI.GetSecureMessageConversation(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).ConversationId(conversationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecureMessagesAPI.GetSecureMessageConversation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSecureMessageConversation`: SecureMessageConversationResponse
	fmt.Fprintf(os.Stdout, "Response from `SecureMessagesAPI.GetSecureMessageConversation`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSecureMessageConversationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 
 **conversationId** | **string** | The specific ID of the conversation that groups messages together | 

### Return type

[**SecureMessageConversationResponse**](SecureMessageConversationResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostSecureMessageReceive

> CreateResponse PostSecureMessageReceive(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).SecureMessageReceiveRequest(secureMessageReceiveRequest).Execute()

Supports sending a message to the member's PDS.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	connectionToken := "abc123xyz456" // string | Member's Connection Key
	uid := "1234" // string | The unique ID of a mydex member
	conId := "1234-67890" // string | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID.
	secureMessageReceiveRequest := *openapiclient.NewSecureMessageReceiveRequest("Hello, how can I help?", "referral-123", "Eric789") // SecureMessageReceiveRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecureMessagesAPI.PostSecureMessageReceive(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).SecureMessageReceiveRequest(secureMessageReceiveRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecureMessagesAPI.PostSecureMessageReceive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostSecureMessageReceive`: CreateResponse
	fmt.Fprintf(os.Stdout, "Response from `SecureMessagesAPI.PostSecureMessageReceive`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostSecureMessageReceiveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 
 **secureMessageReceiveRequest** | [**SecureMessageReceiveRequest**](SecureMessageReceiveRequest.md) |  | 

### Return type

[**CreateResponse**](CreateResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostSecureMessageSend

> CreateResponse PostSecureMessageSend(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).SecureMessageSendRequest(secureMessageSendRequest).Execute()

Supports sending a message from the member's PDS.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	connectionToken := "abc123xyz456" // string | Member's Connection Key
	uid := "1234" // string | The unique ID of a mydex member
	conId := "1234-67890" // string | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID.
	secureMessageSendRequest := *openapiclient.NewSecureMessageSendRequest("Hello, how can I help?", "referral-123", "Amanda123") // SecureMessageSendRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecureMessagesAPI.PostSecureMessageSend(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).SecureMessageSendRequest(secureMessageSendRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecureMessagesAPI.PostSecureMessageSend``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostSecureMessageSend`: CreateResponse
	fmt.Fprintf(os.Stdout, "Response from `SecureMessagesAPI.PostSecureMessageSend`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostSecureMessageSendRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 
 **secureMessageSendRequest** | [**SecureMessageSendRequest**](SecureMessageSendRequest.md) |  | 

### Return type

[**CreateResponse**](CreateResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

