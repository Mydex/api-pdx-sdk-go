# ReferralStatusUpdateRequestBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** | ID of the referral to be updated | 
**Status** | **string** | Status the referral is to be updated to | 

## Methods

### NewReferralStatusUpdateRequestBody

`func NewReferralStatusUpdateRequestBody(id int32, status string, ) *ReferralStatusUpdateRequestBody`

NewReferralStatusUpdateRequestBody instantiates a new ReferralStatusUpdateRequestBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReferralStatusUpdateRequestBodyWithDefaults

`func NewReferralStatusUpdateRequestBodyWithDefaults() *ReferralStatusUpdateRequestBody`

NewReferralStatusUpdateRequestBodyWithDefaults instantiates a new ReferralStatusUpdateRequestBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ReferralStatusUpdateRequestBody) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ReferralStatusUpdateRequestBody) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ReferralStatusUpdateRequestBody) SetId(v int32)`

SetId sets Id field to given value.


### GetStatus

`func (o *ReferralStatusUpdateRequestBody) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ReferralStatusUpdateRequestBody) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ReferralStatusUpdateRequestBody) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


