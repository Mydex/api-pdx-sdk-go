# \ReferralsAPI

All URIs are relative to *https://api.mydex.org*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAllReferrals**](ReferralsAPI.md#GetAllReferrals) | **Get** /referrals/read-all | Retrieve rall referrals for a given member.
[**GetSingleReferral**](ReferralsAPI.md#GetSingleReferral) | **Get** /referrals/read-single | Retrieve a single referral by id for a given member.
[**PostSelfReferral**](ReferralsAPI.md#PostSelfReferral) | **Post** /referrals/self-refer | Supports self-referral.
[**UpdateReferralStatus**](ReferralsAPI.md#UpdateReferralStatus) | **Put** /referrals/update-status | Supports updating the status of a referral.



## GetAllReferrals

> ReferralListResponse GetAllReferrals(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).Execute()

Retrieve rall referrals for a given member.



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReferralsAPI.GetAllReferrals(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReferralsAPI.GetAllReferrals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllReferrals`: ReferralListResponse
	fmt.Fprintf(os.Stdout, "Response from `ReferralsAPI.GetAllReferrals`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAllReferralsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 

### Return type

[**ReferralListResponse**](ReferralListResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSingleReferral

> ReferralSingleResponse GetSingleReferral(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).Id(id).Execute()

Retrieve a single referral by id for a given member.



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
	id := "1234" // string | The record id requested.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReferralsAPI.GetSingleReferral(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).Id(id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReferralsAPI.GetSingleReferral``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSingleReferral`: ReferralSingleResponse
	fmt.Fprintf(os.Stdout, "Response from `ReferralsAPI.GetSingleReferral`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSingleReferralRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 
 **id** | **string** | The record id requested. | 

### Return type

[**ReferralSingleResponse**](ReferralSingleResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostSelfReferral

> CreateResponse PostSelfReferral(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).SelfReferralRequestBody(selfReferralRequestBody).Execute()

Supports self-referral.



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
	selfReferralRequestBody := *openapiclient.NewSelfReferralRequestBody(int32(1)) // SelfReferralRequestBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReferralsAPI.PostSelfReferral(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).SelfReferralRequestBody(selfReferralRequestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReferralsAPI.PostSelfReferral``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostSelfReferral`: CreateResponse
	fmt.Fprintf(os.Stdout, "Response from `ReferralsAPI.PostSelfReferral`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostSelfReferralRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 
 **selfReferralRequestBody** | [**SelfReferralRequestBody**](SelfReferralRequestBody.md) |  | 

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


## UpdateReferralStatus

> UpdateResponse UpdateReferralStatus(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).ReferralStatusUpdateRequestBody(referralStatusUpdateRequestBody).Execute()

Supports updating the status of a referral.



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
	referralStatusUpdateRequestBody := *openapiclient.NewReferralStatusUpdateRequestBody(int32(123), "Rejected") // ReferralStatusUpdateRequestBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReferralsAPI.UpdateReferralStatus(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).ReferralStatusUpdateRequestBody(referralStatusUpdateRequestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReferralsAPI.UpdateReferralStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateReferralStatus`: UpdateResponse
	fmt.Fprintf(os.Stdout, "Response from `ReferralsAPI.UpdateReferralStatus`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateReferralStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 
 **referralStatusUpdateRequestBody** | [**ReferralStatusUpdateRequestBody**](ReferralStatusUpdateRequestBody.md) |  | 

### Return type

[**UpdateResponse**](UpdateResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

