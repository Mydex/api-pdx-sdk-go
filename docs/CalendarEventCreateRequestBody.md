# CalendarEventCreateRequestBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | **string** | Title of the event | 
**Description** | Pointer to **string** | Detailed description of the event | [optional] 
**StartTimestamp** | **int64** | Start date and time as Unix timestamp | 
**EndTimestamp** | **int64** | End date and time as Unix timestamp | 
**Status** | **string** | Status of the event | [default to "TENTATIVE"]
**Organiser** | Pointer to **string** | Creator of the event | [optional] 
**Attendee** | Pointer to **string** | Person attending the event | [optional] 
**Location** | Pointer to **string** | Event location | [optional] 
**Type** | Pointer to **NullableString** | Type of event | [optional] 

## Methods

### NewCalendarEventCreateRequestBody

`func NewCalendarEventCreateRequestBody(title string, startTimestamp int64, endTimestamp int64, status string, ) *CalendarEventCreateRequestBody`

NewCalendarEventCreateRequestBody instantiates a new CalendarEventCreateRequestBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCalendarEventCreateRequestBodyWithDefaults

`func NewCalendarEventCreateRequestBodyWithDefaults() *CalendarEventCreateRequestBody`

NewCalendarEventCreateRequestBodyWithDefaults instantiates a new CalendarEventCreateRequestBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *CalendarEventCreateRequestBody) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CalendarEventCreateRequestBody) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CalendarEventCreateRequestBody) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetDescription

`func (o *CalendarEventCreateRequestBody) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CalendarEventCreateRequestBody) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CalendarEventCreateRequestBody) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CalendarEventCreateRequestBody) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetStartTimestamp

`func (o *CalendarEventCreateRequestBody) GetStartTimestamp() int64`

GetStartTimestamp returns the StartTimestamp field if non-nil, zero value otherwise.

### GetStartTimestampOk

`func (o *CalendarEventCreateRequestBody) GetStartTimestampOk() (*int64, bool)`

GetStartTimestampOk returns a tuple with the StartTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTimestamp

`func (o *CalendarEventCreateRequestBody) SetStartTimestamp(v int64)`

SetStartTimestamp sets StartTimestamp field to given value.


### GetEndTimestamp

`func (o *CalendarEventCreateRequestBody) GetEndTimestamp() int64`

GetEndTimestamp returns the EndTimestamp field if non-nil, zero value otherwise.

### GetEndTimestampOk

`func (o *CalendarEventCreateRequestBody) GetEndTimestampOk() (*int64, bool)`

GetEndTimestampOk returns a tuple with the EndTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTimestamp

`func (o *CalendarEventCreateRequestBody) SetEndTimestamp(v int64)`

SetEndTimestamp sets EndTimestamp field to given value.


### GetStatus

`func (o *CalendarEventCreateRequestBody) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CalendarEventCreateRequestBody) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CalendarEventCreateRequestBody) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetOrganiser

`func (o *CalendarEventCreateRequestBody) GetOrganiser() string`

GetOrganiser returns the Organiser field if non-nil, zero value otherwise.

### GetOrganiserOk

`func (o *CalendarEventCreateRequestBody) GetOrganiserOk() (*string, bool)`

GetOrganiserOk returns a tuple with the Organiser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganiser

`func (o *CalendarEventCreateRequestBody) SetOrganiser(v string)`

SetOrganiser sets Organiser field to given value.

### HasOrganiser

`func (o *CalendarEventCreateRequestBody) HasOrganiser() bool`

HasOrganiser returns a boolean if a field has been set.

### GetAttendee

`func (o *CalendarEventCreateRequestBody) GetAttendee() string`

GetAttendee returns the Attendee field if non-nil, zero value otherwise.

### GetAttendeeOk

`func (o *CalendarEventCreateRequestBody) GetAttendeeOk() (*string, bool)`

GetAttendeeOk returns a tuple with the Attendee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttendee

`func (o *CalendarEventCreateRequestBody) SetAttendee(v string)`

SetAttendee sets Attendee field to given value.

### HasAttendee

`func (o *CalendarEventCreateRequestBody) HasAttendee() bool`

HasAttendee returns a boolean if a field has been set.

### GetLocation

`func (o *CalendarEventCreateRequestBody) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *CalendarEventCreateRequestBody) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *CalendarEventCreateRequestBody) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *CalendarEventCreateRequestBody) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetType

`func (o *CalendarEventCreateRequestBody) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CalendarEventCreateRequestBody) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CalendarEventCreateRequestBody) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CalendarEventCreateRequestBody) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *CalendarEventCreateRequestBody) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *CalendarEventCreateRequestBody) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


