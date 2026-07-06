# CreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **int32** | Indicates success | [optional] 
**LastInsertId** | Pointer to **int32** | ID of the newly created record | [optional] 

## Methods

### NewCreateResponse

`func NewCreateResponse() *CreateResponse`

NewCreateResponse instantiates a new CreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateResponseWithDefaults

`func NewCreateResponseWithDefaults() *CreateResponse`

NewCreateResponseWithDefaults instantiates a new CreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *CreateResponse) GetSuccess() int32`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CreateResponse) GetSuccessOk() (*int32, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CreateResponse) SetSuccess(v int32)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *CreateResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetLastInsertId

`func (o *CreateResponse) GetLastInsertId() int32`

GetLastInsertId returns the LastInsertId field if non-nil, zero value otherwise.

### GetLastInsertIdOk

`func (o *CreateResponse) GetLastInsertIdOk() (*int32, bool)`

GetLastInsertIdOk returns a tuple with the LastInsertId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastInsertId

`func (o *CreateResponse) SetLastInsertId(v int32)`

SetLastInsertId sets LastInsertId field to given value.

### HasLastInsertId

`func (o *CreateResponse) HasLastInsertId() bool`

HasLastInsertId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


