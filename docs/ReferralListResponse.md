# ReferralListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **int32** |  | [optional] 
**Referrals** | Pointer to [**[]ReferralListResponseReferralsInner**](ReferralListResponseReferralsInner.md) |  | [optional] 

## Methods

### NewReferralListResponse

`func NewReferralListResponse() *ReferralListResponse`

NewReferralListResponse instantiates a new ReferralListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReferralListResponseWithDefaults

`func NewReferralListResponseWithDefaults() *ReferralListResponse`

NewReferralListResponseWithDefaults instantiates a new ReferralListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ReferralListResponse) GetSuccess() int32`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ReferralListResponse) GetSuccessOk() (*int32, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ReferralListResponse) SetSuccess(v int32)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *ReferralListResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetReferrals

`func (o *ReferralListResponse) GetReferrals() []ReferralListResponseReferralsInner`

GetReferrals returns the Referrals field if non-nil, zero value otherwise.

### GetReferralsOk

`func (o *ReferralListResponse) GetReferralsOk() (*[]ReferralListResponseReferralsInner, bool)`

GetReferralsOk returns a tuple with the Referrals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferrals

`func (o *ReferralListResponse) SetReferrals(v []ReferralListResponseReferralsInner)`

SetReferrals sets Referrals field to given value.

### HasReferrals

`func (o *ReferralListResponse) HasReferrals() bool`

HasReferrals returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


