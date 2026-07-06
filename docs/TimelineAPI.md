# \TimelineAPI

All URIs are relative to *https://api.mydex.org*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetTimeline**](TimelineAPI.md#GetTimeline) | **Get** /timeline | Retrieve list of timeline items.
[**GetTimelineItem**](TimelineAPI.md#GetTimelineItem) | **Get** /timeline/single-item | Retrieve a single timeline item.



## GetTimeline

> TimelineResponse GetTimeline(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).Execute()

Retrieve list of timeline items.



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
	resp, r, err := apiClient.TimelineAPI.GetTimeline(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TimelineAPI.GetTimeline``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTimeline`: TimelineResponse
	fmt.Fprintf(os.Stdout, "Response from `TimelineAPI.GetTimeline`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTimelineRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 

### Return type

[**TimelineResponse**](TimelineResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTimelineItem

> TimelineSingleItemResponse GetTimelineItem(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).FeatureBlock(featureBlock).FeatureBlockId(featureBlockId).Execute()

Retrieve a single timeline item.



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
	featureBlock := "referrals" // string | The feature block the teimline item belongs to
	featureBlockId := int32(123) // int32 | The specific ID of the record within the specified feature block e.g. if 'referrals' is the feature block, then this should be a specific referral id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TimelineAPI.GetTimelineItem(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).FeatureBlock(featureBlock).FeatureBlockId(featureBlockId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TimelineAPI.GetTimelineItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTimelineItem`: TimelineSingleItemResponse
	fmt.Fprintf(os.Stdout, "Response from `TimelineAPI.GetTimelineItem`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTimelineItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 
 **featureBlock** | **string** | The feature block the teimline item belongs to | 
 **featureBlockId** | **int32** | The specific ID of the record within the specified feature block e.g. if &#39;referrals&#39; is the feature block, then this should be a specific referral id | 

### Return type

[**TimelineSingleItemResponse**](TimelineSingleItemResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

