# \CalendarAPI

All URIs are relative to *https://api.mydex.org*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteCalendarEvent**](CalendarAPI.md#DeleteCalendarEvent) | **Delete** /calendar/delete-event | Supports deleting a calendar-event.
[**GetCalendarAppointments**](CalendarAPI.md#GetCalendarAppointments) | **Get** /calendar/get-appointments | Retrieve appointments for a given context
[**GetCalendarEvents**](CalendarAPI.md#GetCalendarEvents) | **Get** /calendar/get-events | Retrieve calendar events
[**PostCalendarAppointment**](CalendarAPI.md#PostCalendarAppointment) | **Post** /calendar/add-appointment | Supports adding a calendar-appointment.
[**PostCalendarEvent**](CalendarAPI.md#PostCalendarEvent) | **Post** /calendar/add-event | Supports adding a calendar-event.
[**PutCalendarEvent**](CalendarAPI.md#PutCalendarEvent) | **Put** /calendar/update-event | Supports updating a calendar-event.



## DeleteCalendarEvent

> DeleteResponse DeleteCalendarEvent(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).CalendarEventDeleteRequestBody(calendarEventDeleteRequestBody).Execute()

Supports deleting a calendar-event.



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
	calendarEventDeleteRequestBody := *openapiclient.NewCalendarEventDeleteRequestBody(int32(123)) // CalendarEventDeleteRequestBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CalendarAPI.DeleteCalendarEvent(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).CalendarEventDeleteRequestBody(calendarEventDeleteRequestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CalendarAPI.DeleteCalendarEvent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCalendarEvent`: DeleteResponse
	fmt.Fprintf(os.Stdout, "Response from `CalendarAPI.DeleteCalendarEvent`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeleteCalendarEventRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 
 **calendarEventDeleteRequestBody** | [**CalendarEventDeleteRequestBody**](CalendarEventDeleteRequestBody.md) |  | 

### Return type

[**DeleteResponse**](DeleteResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCalendarAppointments

> GetAppointmentsResponse GetCalendarAppointments(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).Context(context).ContextId(contextId).Execute()

Retrieve appointments for a given context



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
	context := "referral" // string | The context this belongs to
	contextId := int32(123) // int32 | The specific ID of the context record

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CalendarAPI.GetCalendarAppointments(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).Context(context).ContextId(contextId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CalendarAPI.GetCalendarAppointments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCalendarAppointments`: GetAppointmentsResponse
	fmt.Fprintf(os.Stdout, "Response from `CalendarAPI.GetCalendarAppointments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCalendarAppointmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 
 **context** | **string** | The context this belongs to | 
 **contextId** | **int32** | The specific ID of the context record | 

### Return type

[**GetAppointmentsResponse**](GetAppointmentsResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCalendarEvents

> GetEventsResponse GetCalendarEvents(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).Execute()

Retrieve calendar events



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
	resp, r, err := apiClient.CalendarAPI.GetCalendarEvents(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CalendarAPI.GetCalendarEvents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCalendarEvents`: GetEventsResponse
	fmt.Fprintf(os.Stdout, "Response from `CalendarAPI.GetCalendarEvents`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCalendarEventsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 

### Return type

[**GetEventsResponse**](GetEventsResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostCalendarAppointment

> CreateResponse PostCalendarAppointment(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).CalendarAppointmentCreateRequestBody(calendarAppointmentCreateRequestBody).Execute()

Supports adding a calendar-appointment.



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
	calendarAppointmentCreateRequestBody := *openapiclient.NewCalendarAppointmentCreateRequestBody("Lunch with Ellen", int64(1754289000), int64(1754289000), "INVITED", "referral", int32(123)) // CalendarAppointmentCreateRequestBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CalendarAPI.PostCalendarAppointment(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).CalendarAppointmentCreateRequestBody(calendarAppointmentCreateRequestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CalendarAPI.PostCalendarAppointment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostCalendarAppointment`: CreateResponse
	fmt.Fprintf(os.Stdout, "Response from `CalendarAPI.PostCalendarAppointment`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostCalendarAppointmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 
 **calendarAppointmentCreateRequestBody** | [**CalendarAppointmentCreateRequestBody**](CalendarAppointmentCreateRequestBody.md) |  | 

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


## PostCalendarEvent

> CreateResponse PostCalendarEvent(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).CalendarEventCreateRequestBody(calendarEventCreateRequestBody).Execute()

Supports adding a calendar-event.



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
	calendarEventCreateRequestBody := *openapiclient.NewCalendarEventCreateRequestBody("Lunch with Ellen", int64(1754289000), int64(1754289000), "INVITED") // CalendarEventCreateRequestBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CalendarAPI.PostCalendarEvent(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).CalendarEventCreateRequestBody(calendarEventCreateRequestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CalendarAPI.PostCalendarEvent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostCalendarEvent`: CreateResponse
	fmt.Fprintf(os.Stdout, "Response from `CalendarAPI.PostCalendarEvent`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostCalendarEventRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 
 **calendarEventCreateRequestBody** | [**CalendarEventCreateRequestBody**](CalendarEventCreateRequestBody.md) |  | 

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


## PutCalendarEvent

> UpdateResponse PutCalendarEvent(ctx).ConnectionToken(connectionToken).Uid(uid).ConId(conId).CalendarEventUpdateRequestBody(calendarEventUpdateRequestBody).Execute()

Supports updating a calendar-event.



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
	calendarEventUpdateRequestBody := *openapiclient.NewCalendarEventUpdateRequestBody(int32(123)) // CalendarEventUpdateRequestBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CalendarAPI.PutCalendarEvent(context.Background()).ConnectionToken(connectionToken).Uid(uid).ConId(conId).CalendarEventUpdateRequestBody(calendarEventUpdateRequestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CalendarAPI.PutCalendarEvent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PutCalendarEvent`: UpdateResponse
	fmt.Fprintf(os.Stdout, "Response from `CalendarAPI.PutCalendarEvent`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPutCalendarEventRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionToken** | **string** | Member&#39;s Connection Key | 
 **uid** | **string** | The unique ID of a mydex member | 
 **conId** | **string** | The connection_id is a shared id between a connection and a member. It is a hyphenated combination of the member UID and the Dedicated Connection NID. | 
 **calendarEventUpdateRequestBody** | [**CalendarEventUpdateRequestBody**](CalendarEventUpdateRequestBody.md) |  | 

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

