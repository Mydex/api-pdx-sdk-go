# TimelineSingleItemResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **int32** |  | [optional] 
**TimelineItem** | Pointer to [**TimelineSingleItemResponseTimelineItem**](TimelineSingleItemResponseTimelineItem.md) |  | [optional] 

## Methods

### NewTimelineSingleItemResponse

`func NewTimelineSingleItemResponse() *TimelineSingleItemResponse`

NewTimelineSingleItemResponse instantiates a new TimelineSingleItemResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimelineSingleItemResponseWithDefaults

`func NewTimelineSingleItemResponseWithDefaults() *TimelineSingleItemResponse`

NewTimelineSingleItemResponseWithDefaults instantiates a new TimelineSingleItemResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *TimelineSingleItemResponse) GetSuccess() int32`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *TimelineSingleItemResponse) GetSuccessOk() (*int32, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *TimelineSingleItemResponse) SetSuccess(v int32)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *TimelineSingleItemResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetTimelineItem

`func (o *TimelineSingleItemResponse) GetTimelineItem() TimelineSingleItemResponseTimelineItem`

GetTimelineItem returns the TimelineItem field if non-nil, zero value otherwise.

### GetTimelineItemOk

`func (o *TimelineSingleItemResponse) GetTimelineItemOk() (*TimelineSingleItemResponseTimelineItem, bool)`

GetTimelineItemOk returns a tuple with the TimelineItem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimelineItem

`func (o *TimelineSingleItemResponse) SetTimelineItem(v TimelineSingleItemResponseTimelineItem)`

SetTimelineItem sets TimelineItem field to given value.

### HasTimelineItem

`func (o *TimelineSingleItemResponse) HasTimelineItem() bool`

HasTimelineItem returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


