# TimelineResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **int32** |  | [optional] 
**Timeline** | Pointer to [**[]TimelineResponseTimelineInner**](TimelineResponseTimelineInner.md) | Array of timeline items, which can be calendar events, referrals, or secure messages | [optional] 

## Methods

### NewTimelineResponse

`func NewTimelineResponse() *TimelineResponse`

NewTimelineResponse instantiates a new TimelineResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimelineResponseWithDefaults

`func NewTimelineResponseWithDefaults() *TimelineResponse`

NewTimelineResponseWithDefaults instantiates a new TimelineResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *TimelineResponse) GetSuccess() int32`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *TimelineResponse) GetSuccessOk() (*int32, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *TimelineResponse) SetSuccess(v int32)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *TimelineResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetTimeline

`func (o *TimelineResponse) GetTimeline() []TimelineResponseTimelineInner`

GetTimeline returns the Timeline field if non-nil, zero value otherwise.

### GetTimelineOk

`func (o *TimelineResponse) GetTimelineOk() (*[]TimelineResponseTimelineInner, bool)`

GetTimelineOk returns a tuple with the Timeline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeline

`func (o *TimelineResponse) SetTimeline(v []TimelineResponseTimelineInner)`

SetTimeline sets Timeline field to given value.

### HasTimeline

`func (o *TimelineResponse) HasTimeline() bool`

HasTimeline returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


