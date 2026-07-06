# CalendarEventCommonRequestBodyFields

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | Pointer to **string** | Title of the event | [optional] 
**Description** | Pointer to **string** | Detailed description of the event | [optional] 
**StartTimestamp** | Pointer to **int64** | Start date and time as Unix timestamp | [optional] 
**EndTimestamp** | Pointer to **int64** | End date and time as Unix timestamp | [optional] 
**Status** | Pointer to **string** | Status of the event | [optional] [default to "TENTATIVE"]
**Organiser** | Pointer to **string** | Creator of the event | [optional] 
**Attendee** | Pointer to **string** | Person attending the event | [optional] 
**Location** | Pointer to **string** | Event location | [optional] 

## Methods

### NewCalendarEventCommonRequestBodyFields

`func NewCalendarEventCommonRequestBodyFields() *CalendarEventCommonRequestBodyFields`

NewCalendarEventCommonRequestBodyFields instantiates a new CalendarEventCommonRequestBodyFields object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCalendarEventCommonRequestBodyFieldsWithDefaults

`func NewCalendarEventCommonRequestBodyFieldsWithDefaults() *CalendarEventCommonRequestBodyFields`

NewCalendarEventCommonRequestBodyFieldsWithDefaults instantiates a new CalendarEventCommonRequestBodyFields object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *CalendarEventCommonRequestBodyFields) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CalendarEventCommonRequestBodyFields) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CalendarEventCommonRequestBodyFields) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *CalendarEventCommonRequestBodyFields) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetDescription

`func (o *CalendarEventCommonRequestBodyFields) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CalendarEventCommonRequestBodyFields) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CalendarEventCommonRequestBodyFields) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CalendarEventCommonRequestBodyFields) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetStartTimestamp

`func (o *CalendarEventCommonRequestBodyFields) GetStartTimestamp() int64`

GetStartTimestamp returns the StartTimestamp field if non-nil, zero value otherwise.

### GetStartTimestampOk

`func (o *CalendarEventCommonRequestBodyFields) GetStartTimestampOk() (*int64, bool)`

GetStartTimestampOk returns a tuple with the StartTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTimestamp

`func (o *CalendarEventCommonRequestBodyFields) SetStartTimestamp(v int64)`

SetStartTimestamp sets StartTimestamp field to given value.

### HasStartTimestamp

`func (o *CalendarEventCommonRequestBodyFields) HasStartTimestamp() bool`

HasStartTimestamp returns a boolean if a field has been set.

### GetEndTimestamp

`func (o *CalendarEventCommonRequestBodyFields) GetEndTimestamp() int64`

GetEndTimestamp returns the EndTimestamp field if non-nil, zero value otherwise.

### GetEndTimestampOk

`func (o *CalendarEventCommonRequestBodyFields) GetEndTimestampOk() (*int64, bool)`

GetEndTimestampOk returns a tuple with the EndTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTimestamp

`func (o *CalendarEventCommonRequestBodyFields) SetEndTimestamp(v int64)`

SetEndTimestamp sets EndTimestamp field to given value.

### HasEndTimestamp

`func (o *CalendarEventCommonRequestBodyFields) HasEndTimestamp() bool`

HasEndTimestamp returns a boolean if a field has been set.

### GetStatus

`func (o *CalendarEventCommonRequestBodyFields) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CalendarEventCommonRequestBodyFields) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CalendarEventCommonRequestBodyFields) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CalendarEventCommonRequestBodyFields) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetOrganiser

`func (o *CalendarEventCommonRequestBodyFields) GetOrganiser() string`

GetOrganiser returns the Organiser field if non-nil, zero value otherwise.

### GetOrganiserOk

`func (o *CalendarEventCommonRequestBodyFields) GetOrganiserOk() (*string, bool)`

GetOrganiserOk returns a tuple with the Organiser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganiser

`func (o *CalendarEventCommonRequestBodyFields) SetOrganiser(v string)`

SetOrganiser sets Organiser field to given value.

### HasOrganiser

`func (o *CalendarEventCommonRequestBodyFields) HasOrganiser() bool`

HasOrganiser returns a boolean if a field has been set.

### GetAttendee

`func (o *CalendarEventCommonRequestBodyFields) GetAttendee() string`

GetAttendee returns the Attendee field if non-nil, zero value otherwise.

### GetAttendeeOk

`func (o *CalendarEventCommonRequestBodyFields) GetAttendeeOk() (*string, bool)`

GetAttendeeOk returns a tuple with the Attendee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttendee

`func (o *CalendarEventCommonRequestBodyFields) SetAttendee(v string)`

SetAttendee sets Attendee field to given value.

### HasAttendee

`func (o *CalendarEventCommonRequestBodyFields) HasAttendee() bool`

HasAttendee returns a boolean if a field has been set.

### GetLocation

`func (o *CalendarEventCommonRequestBodyFields) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *CalendarEventCommonRequestBodyFields) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *CalendarEventCommonRequestBodyFields) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *CalendarEventCommonRequestBodyFields) HasLocation() bool`

HasLocation returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


