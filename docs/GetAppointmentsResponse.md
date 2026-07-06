# GetAppointmentsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **int32** |  | [optional] 
**Appointments** | Pointer to [**[]CalendarEvent**](CalendarEvent.md) |  | [optional] 

## Methods

### NewGetAppointmentsResponse

`func NewGetAppointmentsResponse() *GetAppointmentsResponse`

NewGetAppointmentsResponse instantiates a new GetAppointmentsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAppointmentsResponseWithDefaults

`func NewGetAppointmentsResponseWithDefaults() *GetAppointmentsResponse`

NewGetAppointmentsResponseWithDefaults instantiates a new GetAppointmentsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetAppointmentsResponse) GetSuccess() int32`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetAppointmentsResponse) GetSuccessOk() (*int32, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetAppointmentsResponse) SetSuccess(v int32)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *GetAppointmentsResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetAppointments

`func (o *GetAppointmentsResponse) GetAppointments() []CalendarEvent`

GetAppointments returns the Appointments field if non-nil, zero value otherwise.

### GetAppointmentsOk

`func (o *GetAppointmentsResponse) GetAppointmentsOk() (*[]CalendarEvent, bool)`

GetAppointmentsOk returns a tuple with the Appointments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppointments

`func (o *GetAppointmentsResponse) SetAppointments(v []CalendarEvent)`

SetAppointments sets Appointments field to given value.

### HasAppointments

`func (o *GetAppointmentsResponse) HasAppointments() bool`

HasAppointments returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


