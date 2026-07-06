# ReferralSingleResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **int32** |  | [optional] 
**Referral** | Pointer to [**ReferralSingleResponseReferral**](ReferralSingleResponseReferral.md) |  | [optional] 

## Methods

### NewReferralSingleResponse

`func NewReferralSingleResponse() *ReferralSingleResponse`

NewReferralSingleResponse instantiates a new ReferralSingleResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReferralSingleResponseWithDefaults

`func NewReferralSingleResponseWithDefaults() *ReferralSingleResponse`

NewReferralSingleResponseWithDefaults instantiates a new ReferralSingleResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ReferralSingleResponse) GetSuccess() int32`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ReferralSingleResponse) GetSuccessOk() (*int32, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ReferralSingleResponse) SetSuccess(v int32)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *ReferralSingleResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetReferral

`func (o *ReferralSingleResponse) GetReferral() ReferralSingleResponseReferral`

GetReferral returns the Referral field if non-nil, zero value otherwise.

### GetReferralOk

`func (o *ReferralSingleResponse) GetReferralOk() (*ReferralSingleResponseReferral, bool)`

GetReferralOk returns a tuple with the Referral field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferral

`func (o *ReferralSingleResponse) SetReferral(v ReferralSingleResponseReferral)`

SetReferral sets Referral field to given value.

### HasReferral

`func (o *ReferralSingleResponse) HasReferral() bool`

HasReferral returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


