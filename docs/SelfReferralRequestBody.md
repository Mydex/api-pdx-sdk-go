# SelfReferralRequestBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ServiceId** | **int32** | ID of the service being referred to | 
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

### NewSelfReferralRequestBody

`func NewSelfReferralRequestBody(serviceId int32, ) *SelfReferralRequestBody`

NewSelfReferralRequestBody instantiates a new SelfReferralRequestBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSelfReferralRequestBodyWithDefaults

`func NewSelfReferralRequestBodyWithDefaults() *SelfReferralRequestBody`

NewSelfReferralRequestBodyWithDefaults instantiates a new SelfReferralRequestBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServiceId

`func (o *SelfReferralRequestBody) GetServiceId() int32`

GetServiceId returns the ServiceId field if non-nil, zero value otherwise.

### GetServiceIdOk

`func (o *SelfReferralRequestBody) GetServiceIdOk() (*int32, bool)`

GetServiceIdOk returns a tuple with the ServiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceId

`func (o *SelfReferralRequestBody) SetServiceId(v int32)`

SetServiceId sets ServiceId field to given value.


### GetReferreeBackground

`func (o *SelfReferralRequestBody) GetReferreeBackground() string`

GetReferreeBackground returns the ReferreeBackground field if non-nil, zero value otherwise.

### GetReferreeBackgroundOk

`func (o *SelfReferralRequestBody) GetReferreeBackgroundOk() (*string, bool)`

GetReferreeBackgroundOk returns a tuple with the ReferreeBackground field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferreeBackground

`func (o *SelfReferralRequestBody) SetReferreeBackground(v string)`

SetReferreeBackground sets ReferreeBackground field to given value.

### HasReferreeBackground

`func (o *SelfReferralRequestBody) HasReferreeBackground() bool`

HasReferreeBackground returns a boolean if a field has been set.

### GetReferreeRequirements

`func (o *SelfReferralRequestBody) GetReferreeRequirements() string`

GetReferreeRequirements returns the ReferreeRequirements field if non-nil, zero value otherwise.

### GetReferreeRequirementsOk

`func (o *SelfReferralRequestBody) GetReferreeRequirementsOk() (*string, bool)`

GetReferreeRequirementsOk returns a tuple with the ReferreeRequirements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferreeRequirements

`func (o *SelfReferralRequestBody) SetReferreeRequirements(v string)`

SetReferreeRequirements sets ReferreeRequirements field to given value.

### HasReferreeRequirements

`func (o *SelfReferralRequestBody) HasReferreeRequirements() bool`

HasReferreeRequirements returns a boolean if a field has been set.

### GetReferreeAvailability

`func (o *SelfReferralRequestBody) GetReferreeAvailability() ReferralCommonRequestBodyFieldsReferreeAvailability`

GetReferreeAvailability returns the ReferreeAvailability field if non-nil, zero value otherwise.

### GetReferreeAvailabilityOk

`func (o *SelfReferralRequestBody) GetReferreeAvailabilityOk() (*ReferralCommonRequestBodyFieldsReferreeAvailability, bool)`

GetReferreeAvailabilityOk returns a tuple with the ReferreeAvailability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferreeAvailability

`func (o *SelfReferralRequestBody) SetReferreeAvailability(v ReferralCommonRequestBodyFieldsReferreeAvailability)`

SetReferreeAvailability sets ReferreeAvailability field to given value.

### HasReferreeAvailability

`func (o *SelfReferralRequestBody) HasReferreeAvailability() bool`

HasReferreeAvailability returns a boolean if a field has been set.

### GetReferrerName

`func (o *SelfReferralRequestBody) GetReferrerName() string`

GetReferrerName returns the ReferrerName field if non-nil, zero value otherwise.

### GetReferrerNameOk

`func (o *SelfReferralRequestBody) GetReferrerNameOk() (*string, bool)`

GetReferrerNameOk returns a tuple with the ReferrerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferrerName

`func (o *SelfReferralRequestBody) SetReferrerName(v string)`

SetReferrerName sets ReferrerName field to given value.

### HasReferrerName

`func (o *SelfReferralRequestBody) HasReferrerName() bool`

HasReferrerName returns a boolean if a field has been set.

### GetServiceName

`func (o *SelfReferralRequestBody) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *SelfReferralRequestBody) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *SelfReferralRequestBody) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.

### HasServiceName

`func (o *SelfReferralRequestBody) HasServiceName() bool`

HasServiceName returns a boolean if a field has been set.

### GetServiceDescription

`func (o *SelfReferralRequestBody) GetServiceDescription() string`

GetServiceDescription returns the ServiceDescription field if non-nil, zero value otherwise.

### GetServiceDescriptionOk

`func (o *SelfReferralRequestBody) GetServiceDescriptionOk() (*string, bool)`

GetServiceDescriptionOk returns a tuple with the ServiceDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceDescription

`func (o *SelfReferralRequestBody) SetServiceDescription(v string)`

SetServiceDescription sets ServiceDescription field to given value.

### HasServiceDescription

`func (o *SelfReferralRequestBody) HasServiceDescription() bool`

HasServiceDescription returns a boolean if a field has been set.

### GetServiceUrl

`func (o *SelfReferralRequestBody) GetServiceUrl() string`

GetServiceUrl returns the ServiceUrl field if non-nil, zero value otherwise.

### GetServiceUrlOk

`func (o *SelfReferralRequestBody) GetServiceUrlOk() (*string, bool)`

GetServiceUrlOk returns a tuple with the ServiceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceUrl

`func (o *SelfReferralRequestBody) SetServiceUrl(v string)`

SetServiceUrl sets ServiceUrl field to given value.

### HasServiceUrl

`func (o *SelfReferralRequestBody) HasServiceUrl() bool`

HasServiceUrl returns a boolean if a field has been set.

### GetServiceEmail

`func (o *SelfReferralRequestBody) GetServiceEmail() string`

GetServiceEmail returns the ServiceEmail field if non-nil, zero value otherwise.

### GetServiceEmailOk

`func (o *SelfReferralRequestBody) GetServiceEmailOk() (*string, bool)`

GetServiceEmailOk returns a tuple with the ServiceEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceEmail

`func (o *SelfReferralRequestBody) SetServiceEmail(v string)`

SetServiceEmail sets ServiceEmail field to given value.

### HasServiceEmail

`func (o *SelfReferralRequestBody) HasServiceEmail() bool`

HasServiceEmail returns a boolean if a field has been set.

### GetContactNumber

`func (o *SelfReferralRequestBody) GetContactNumber() string`

GetContactNumber returns the ContactNumber field if non-nil, zero value otherwise.

### GetContactNumberOk

`func (o *SelfReferralRequestBody) GetContactNumberOk() (*string, bool)`

GetContactNumberOk returns a tuple with the ContactNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactNumber

`func (o *SelfReferralRequestBody) SetContactNumber(v string)`

SetContactNumber sets ContactNumber field to given value.

### HasContactNumber

`func (o *SelfReferralRequestBody) HasContactNumber() bool`

HasContactNumber returns a boolean if a field has been set.

### GetMemo

`func (o *SelfReferralRequestBody) GetMemo() string`

GetMemo returns the Memo field if non-nil, zero value otherwise.

### GetMemoOk

`func (o *SelfReferralRequestBody) GetMemoOk() (*string, bool)`

GetMemoOk returns a tuple with the Memo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemo

`func (o *SelfReferralRequestBody) SetMemo(v string)`

SetMemo sets Memo field to given value.

### HasMemo

`func (o *SelfReferralRequestBody) HasMemo() bool`

HasMemo returns a boolean if a field has been set.

### GetStartTime

`func (o *SelfReferralRequestBody) GetStartTime() int64`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *SelfReferralRequestBody) GetStartTimeOk() (*int64, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *SelfReferralRequestBody) SetStartTime(v int64)`

SetStartTime sets StartTime field to given value.

### HasStartTime

`func (o *SelfReferralRequestBody) HasStartTime() bool`

HasStartTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


