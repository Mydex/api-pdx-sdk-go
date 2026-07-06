# ReferralCommonRequestBodyFields

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ServiceId** | Pointer to **int32** | ID of the service being referred to | [optional] 
**ReferreeBackground** | Pointer to **string** | Background information about the referree | [optional] 
**ReferreeRequirements** | Pointer to **string** | Requirements of the referree | [optional] 
**ReferreeAvailability** | Pointer to [**ReferralCommonRequestBodyFieldsReferreeAvailability**](ReferralCommonRequestBodyFieldsReferreeAvailability.md) |  | [optional] 
**ReferrerName** | Pointer to **string** | Name of the person making the referral | [optional] 
**ServiceName** | Pointer to **string** | Name of the service | [optional] 
**ServiceDescription** | Pointer to **string** | Description of the service | [optional] 
**ServiceUrl** | Pointer to **string** | URL of the service | [optional] 
**ServiceEmail** | Pointer to **string** | Email address of the service | [optional] 
**ContactNumber** | Pointer to **string** | Contact number for the service | [optional] 
**Memo** | Pointer to **string** | Internal memo or notes | [optional] 
**StartTime** | Pointer to **int64** | Start time as a Unix timestamp | [optional] 

## Methods

### NewReferralCommonRequestBodyFields

`func NewReferralCommonRequestBodyFields() *ReferralCommonRequestBodyFields`

NewReferralCommonRequestBodyFields instantiates a new ReferralCommonRequestBodyFields object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReferralCommonRequestBodyFieldsWithDefaults

`func NewReferralCommonRequestBodyFieldsWithDefaults() *ReferralCommonRequestBodyFields`

NewReferralCommonRequestBodyFieldsWithDefaults instantiates a new ReferralCommonRequestBodyFields object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServiceId

`func (o *ReferralCommonRequestBodyFields) GetServiceId() int32`

GetServiceId returns the ServiceId field if non-nil, zero value otherwise.

### GetServiceIdOk

`func (o *ReferralCommonRequestBodyFields) GetServiceIdOk() (*int32, bool)`

GetServiceIdOk returns a tuple with the ServiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceId

`func (o *ReferralCommonRequestBodyFields) SetServiceId(v int32)`

SetServiceId sets ServiceId field to given value.

### HasServiceId

`func (o *ReferralCommonRequestBodyFields) HasServiceId() bool`

HasServiceId returns a boolean if a field has been set.

### GetReferreeBackground

`func (o *ReferralCommonRequestBodyFields) GetReferreeBackground() string`

GetReferreeBackground returns the ReferreeBackground field if non-nil, zero value otherwise.

### GetReferreeBackgroundOk

`func (o *ReferralCommonRequestBodyFields) GetReferreeBackgroundOk() (*string, bool)`

GetReferreeBackgroundOk returns a tuple with the ReferreeBackground field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferreeBackground

`func (o *ReferralCommonRequestBodyFields) SetReferreeBackground(v string)`

SetReferreeBackground sets ReferreeBackground field to given value.

### HasReferreeBackground

`func (o *ReferralCommonRequestBodyFields) HasReferreeBackground() bool`

HasReferreeBackground returns a boolean if a field has been set.

### GetReferreeRequirements

`func (o *ReferralCommonRequestBodyFields) GetReferreeRequirements() string`

GetReferreeRequirements returns the ReferreeRequirements field if non-nil, zero value otherwise.

### GetReferreeRequirementsOk

`func (o *ReferralCommonRequestBodyFields) GetReferreeRequirementsOk() (*string, bool)`

GetReferreeRequirementsOk returns a tuple with the ReferreeRequirements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferreeRequirements

`func (o *ReferralCommonRequestBodyFields) SetReferreeRequirements(v string)`

SetReferreeRequirements sets ReferreeRequirements field to given value.

### HasReferreeRequirements

`func (o *ReferralCommonRequestBodyFields) HasReferreeRequirements() bool`

HasReferreeRequirements returns a boolean if a field has been set.

### GetReferreeAvailability

`func (o *ReferralCommonRequestBodyFields) GetReferreeAvailability() ReferralCommonRequestBodyFieldsReferreeAvailability`

GetReferreeAvailability returns the ReferreeAvailability field if non-nil, zero value otherwise.

### GetReferreeAvailabilityOk

`func (o *ReferralCommonRequestBodyFields) GetReferreeAvailabilityOk() (*ReferralCommonRequestBodyFieldsReferreeAvailability, bool)`

GetReferreeAvailabilityOk returns a tuple with the ReferreeAvailability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferreeAvailability

`func (o *ReferralCommonRequestBodyFields) SetReferreeAvailability(v ReferralCommonRequestBodyFieldsReferreeAvailability)`

SetReferreeAvailability sets ReferreeAvailability field to given value.

### HasReferreeAvailability

`func (o *ReferralCommonRequestBodyFields) HasReferreeAvailability() bool`

HasReferreeAvailability returns a boolean if a field has been set.

### GetReferrerName

`func (o *ReferralCommonRequestBodyFields) GetReferrerName() string`

GetReferrerName returns the ReferrerName field if non-nil, zero value otherwise.

### GetReferrerNameOk

`func (o *ReferralCommonRequestBodyFields) GetReferrerNameOk() (*string, bool)`

GetReferrerNameOk returns a tuple with the ReferrerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferrerName

`func (o *ReferralCommonRequestBodyFields) SetReferrerName(v string)`

SetReferrerName sets ReferrerName field to given value.

### HasReferrerName

`func (o *ReferralCommonRequestBodyFields) HasReferrerName() bool`

HasReferrerName returns a boolean if a field has been set.

### GetServiceName

`func (o *ReferralCommonRequestBodyFields) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *ReferralCommonRequestBodyFields) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *ReferralCommonRequestBodyFields) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.

### HasServiceName

`func (o *ReferralCommonRequestBodyFields) HasServiceName() bool`

HasServiceName returns a boolean if a field has been set.

### GetServiceDescription

`func (o *ReferralCommonRequestBodyFields) GetServiceDescription() string`

GetServiceDescription returns the ServiceDescription field if non-nil, zero value otherwise.

### GetServiceDescriptionOk

`func (o *ReferralCommonRequestBodyFields) GetServiceDescriptionOk() (*string, bool)`

GetServiceDescriptionOk returns a tuple with the ServiceDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceDescription

`func (o *ReferralCommonRequestBodyFields) SetServiceDescription(v string)`

SetServiceDescription sets ServiceDescription field to given value.

### HasServiceDescription

`func (o *ReferralCommonRequestBodyFields) HasServiceDescription() bool`

HasServiceDescription returns a boolean if a field has been set.

### GetServiceUrl

`func (o *ReferralCommonRequestBodyFields) GetServiceUrl() string`

GetServiceUrl returns the ServiceUrl field if non-nil, zero value otherwise.

### GetServiceUrlOk

`func (o *ReferralCommonRequestBodyFields) GetServiceUrlOk() (*string, bool)`

GetServiceUrlOk returns a tuple with the ServiceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceUrl

`func (o *ReferralCommonRequestBodyFields) SetServiceUrl(v string)`

SetServiceUrl sets ServiceUrl field to given value.

### HasServiceUrl

`func (o *ReferralCommonRequestBodyFields) HasServiceUrl() bool`

HasServiceUrl returns a boolean if a field has been set.

### GetServiceEmail

`func (o *ReferralCommonRequestBodyFields) GetServiceEmail() string`

GetServiceEmail returns the ServiceEmail field if non-nil, zero value otherwise.

### GetServiceEmailOk

`func (o *ReferralCommonRequestBodyFields) GetServiceEmailOk() (*string, bool)`

GetServiceEmailOk returns a tuple with the ServiceEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceEmail

`func (o *ReferralCommonRequestBodyFields) SetServiceEmail(v string)`

SetServiceEmail sets ServiceEmail field to given value.

### HasServiceEmail

`func (o *ReferralCommonRequestBodyFields) HasServiceEmail() bool`

HasServiceEmail returns a boolean if a field has been set.

### GetContactNumber

`func (o *ReferralCommonRequestBodyFields) GetContactNumber() string`

GetContactNumber returns the ContactNumber field if non-nil, zero value otherwise.

### GetContactNumberOk

`func (o *ReferralCommonRequestBodyFields) GetContactNumberOk() (*string, bool)`

GetContactNumberOk returns a tuple with the ContactNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactNumber

`func (o *ReferralCommonRequestBodyFields) SetContactNumber(v string)`

SetContactNumber sets ContactNumber field to given value.

### HasContactNumber

`func (o *ReferralCommonRequestBodyFields) HasContactNumber() bool`

HasContactNumber returns a boolean if a field has been set.

### GetMemo

`func (o *ReferralCommonRequestBodyFields) GetMemo() string`

GetMemo returns the Memo field if non-nil, zero value otherwise.

### GetMemoOk

`func (o *ReferralCommonRequestBodyFields) GetMemoOk() (*string, bool)`

GetMemoOk returns a tuple with the Memo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemo

`func (o *ReferralCommonRequestBodyFields) SetMemo(v string)`

SetMemo sets Memo field to given value.

### HasMemo

`func (o *ReferralCommonRequestBodyFields) HasMemo() bool`

HasMemo returns a boolean if a field has been set.

### GetStartTime

`func (o *ReferralCommonRequestBodyFields) GetStartTime() int64`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *ReferralCommonRequestBodyFields) GetStartTimeOk() (*int64, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *ReferralCommonRequestBodyFields) SetStartTime(v int64)`

SetStartTime sets StartTime field to given value.

### HasStartTime

`func (o *ReferralCommonRequestBodyFields) HasStartTime() bool`

HasStartTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


