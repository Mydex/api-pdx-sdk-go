# CalendarAppointmentCreateRequestBody

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
**Context** | **string** | The context the appointment belongs to e.g. a referral | 
**ContextId** | **int32** | The id of the specific context record that this appointment relates to e.g. the referral id | 

## Methods

### NewCalendarAppointmentCreateRequestBody

`func NewCalendarAppointmentCreateRequestBody(title string, startTimestamp int64, endTimestamp int64, status string, context string, contextId int32, ) *CalendarAppointmentCreateRequestBody`

NewCalendarAppointmentCreateRequestBody instantiates a new CalendarAppointmentCreateRequestBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCalendarAppointmentCreateRequestBodyWithDefaults

`func NewCalendarAppointmentCreateRequestBodyWithDefaults() *CalendarAppointmentCreateRequestBody`

NewCalendarAppointmentCreateRequestBodyWithDefaults instantiates a new CalendarAppointmentCreateRequestBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *CalendarAppointmentCreateRequestBody) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CalendarAppointmentCreateRequestBody) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CalendarAppointmentCreateRequestBody) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetDescription

`func (o *CalendarAppointmentCreateRequestBody) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CalendarAppointmentCreateRequestBody) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CalendarAppointmentCreateRequestBody) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CalendarAppointmentCreateRequestBody) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetStartTimestamp

`func (o *CalendarAppointmentCreateRequestBody) GetStartTimestamp() int64`

GetStartTimestamp returns the StartTimestamp field if non-nil, zero value otherwise.

### GetStartTimestampOk

`func (o *CalendarAppointmentCreateRequestBody) GetStartTimestampOk() (*int64, bool)`

GetStartTimestampOk returns a tuple with the StartTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTimestamp

`func (o *CalendarAppointmentCreateRequestBody) SetStartTimestamp(v int64)`

SetStartTimestamp sets StartTimestamp field to given value.


### GetEndTimestamp

`func (o *CalendarAppointmentCreateRequestBody) GetEndTimestamp() int64`

GetEndTimestamp returns the EndTimestamp field if non-nil, zero value otherwise.

### GetEndTimestampOk

`func (o *CalendarAppointmentCreateRequestBody) GetEndTimestampOk() (*int64, bool)`

GetEndTimestampOk returns a tuple with the EndTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTimestamp

`func (o *CalendarAppointmentCreateRequestBody) SetEndTimestamp(v int64)`

SetEndTimestamp sets EndTimestamp field to given value.


### GetStatus

`func (o *CalendarAppointmentCreateRequestBody) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CalendarAppointmentCreateRequestBody) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CalendarAppointmentCreateRequestBody) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetOrganiser

`func (o *CalendarAppointmentCreateRequestBody) GetOrganiser() string`

GetOrganiser returns the Organiser field if non-nil, zero value otherwise.

### GetOrganiserOk

`func (o *CalendarAppointmentCreateRequestBody) GetOrganiserOk() (*string, bool)`

GetOrganiserOk returns a tuple with the Organiser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganiser

`func (o *CalendarAppointmentCreateRequestBody) SetOrganiser(v string)`

SetOrganiser sets Organiser field to given value.

### HasOrganiser

`func (o *CalendarAppointmentCreateRequestBody) HasOrganiser() bool`

HasOrganiser returns a boolean if a field has been set.

### GetAttendee

`func (o *CalendarAppointmentCreateRequestBody) GetAttendee() string`

GetAttendee returns the Attendee field if non-nil, zero value otherwise.

### GetAttendeeOk

`func (o *CalendarAppointmentCreateRequestBody) GetAttendeeOk() (*string, bool)`

GetAttendeeOk returns a tuple with the Attendee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttendee

`func (o *CalendarAppointmentCreateRequestBody) SetAttendee(v string)`

SetAttendee sets Attendee field to given value.

### HasAttendee

`func (o *CalendarAppointmentCreateRequestBody) HasAttendee() bool`

HasAttendee returns a boolean if a field has been set.

### GetLocation

`func (o *CalendarAppointmentCreateRequestBody) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *CalendarAppointmentCreateRequestBody) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *CalendarAppointmentCreateRequestBody) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *CalendarAppointmentCreateRequestBody) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetContext

`func (o *CalendarAppointmentCreateRequestBody) GetContext() string`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *CalendarAppointmentCreateRequestBody) GetContextOk() (*string, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *CalendarAppointmentCreateRequestBody) SetContext(v string)`

SetContext sets Context field to given value.


### GetContextId

`func (o *CalendarAppointmentCreateRequestBody) GetContextId() int32`

GetContextId returns the ContextId field if non-nil, zero value otherwise.

### GetContextIdOk

`func (o *CalendarAppointmentCreateRequestBody) GetContextIdOk() (*int32, bool)`

GetContextIdOk returns a tuple with the ContextId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContextId

`func (o *CalendarAppointmentCreateRequestBody) SetContextId(v int32)`

SetContextId sets ContextId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


