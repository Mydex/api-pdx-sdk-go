# TimelineItemSecureMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FeatureBlock** | Pointer to **string** | Type of feature block this timeline item belongs to | [optional] 
**FeatureBlockId** | Pointer to **int32** | ID of the feature block | [optional] 
**StartTimestamp** | Pointer to **string** | Formatted start timestamp for display | [optional] 
**ItemTimestamp** | Pointer to **int64** | Raw timestamp of the timeline item | [optional] 
**CreatedTimestamp** | Pointer to **int64** |  | [optional] 
**UpdatedTimestamp** | Pointer to **int64** |  | [optional] 
**ConversationId** | Pointer to **string** | Conversation identifier | [optional] 
**TimeSent** | Pointer to **string** | Timestamp when message was sent | [optional] 
**TimeReceived** | Pointer to **string** | Timestamp when message was received | [optional] 
**MessageFrom** | Pointer to **string** | Sender of the message (present on received messages) | [optional] 
**MessageTo** | Pointer to **string** | Recipient of the message (present on sent messages) | [optional] 
**MessageContent** | Pointer to **string** | Content of the message | [optional] 

## Methods

### NewTimelineItemSecureMessage

`func NewTimelineItemSecureMessage() *TimelineItemSecureMessage`

NewTimelineItemSecureMessage instantiates a new TimelineItemSecureMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimelineItemSecureMessageWithDefaults

`func NewTimelineItemSecureMessageWithDefaults() *TimelineItemSecureMessage`

NewTimelineItemSecureMessageWithDefaults instantiates a new TimelineItemSecureMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFeatureBlock

`func (o *TimelineItemSecureMessage) GetFeatureBlock() string`

GetFeatureBlock returns the FeatureBlock field if non-nil, zero value otherwise.

### GetFeatureBlockOk

`func (o *TimelineItemSecureMessage) GetFeatureBlockOk() (*string, bool)`

GetFeatureBlockOk returns a tuple with the FeatureBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureBlock

`func (o *TimelineItemSecureMessage) SetFeatureBlock(v string)`

SetFeatureBlock sets FeatureBlock field to given value.

### HasFeatureBlock

`func (o *TimelineItemSecureMessage) HasFeatureBlock() bool`

HasFeatureBlock returns a boolean if a field has been set.

### GetFeatureBlockId

`func (o *TimelineItemSecureMessage) GetFeatureBlockId() int32`

GetFeatureBlockId returns the FeatureBlockId field if non-nil, zero value otherwise.

### GetFeatureBlockIdOk

`func (o *TimelineItemSecureMessage) GetFeatureBlockIdOk() (*int32, bool)`

GetFeatureBlockIdOk returns a tuple with the FeatureBlockId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureBlockId

`func (o *TimelineItemSecureMessage) SetFeatureBlockId(v int32)`

SetFeatureBlockId sets FeatureBlockId field to given value.

### HasFeatureBlockId

`func (o *TimelineItemSecureMessage) HasFeatureBlockId() bool`

HasFeatureBlockId returns a boolean if a field has been set.

### GetStartTimestamp

`func (o *TimelineItemSecureMessage) GetStartTimestamp() string`

GetStartTimestamp returns the StartTimestamp field if non-nil, zero value otherwise.

### GetStartTimestampOk

`func (o *TimelineItemSecureMessage) GetStartTimestampOk() (*string, bool)`

GetStartTimestampOk returns a tuple with the StartTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTimestamp

`func (o *TimelineItemSecureMessage) SetStartTimestamp(v string)`

SetStartTimestamp sets StartTimestamp field to given value.

### HasStartTimestamp

`func (o *TimelineItemSecureMessage) HasStartTimestamp() bool`

HasStartTimestamp returns a boolean if a field has been set.

### GetItemTimestamp

`func (o *TimelineItemSecureMessage) GetItemTimestamp() int64`

GetItemTimestamp returns the ItemTimestamp field if non-nil, zero value otherwise.

### GetItemTimestampOk

`func (o *TimelineItemSecureMessage) GetItemTimestampOk() (*int64, bool)`

GetItemTimestampOk returns a tuple with the ItemTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemTimestamp

`func (o *TimelineItemSecureMessage) SetItemTimestamp(v int64)`

SetItemTimestamp sets ItemTimestamp field to given value.

### HasItemTimestamp

`func (o *TimelineItemSecureMessage) HasItemTimestamp() bool`

HasItemTimestamp returns a boolean if a field has been set.

### GetCreatedTimestamp

`func (o *TimelineItemSecureMessage) GetCreatedTimestamp() int64`

GetCreatedTimestamp returns the CreatedTimestamp field if non-nil, zero value otherwise.

### GetCreatedTimestampOk

`func (o *TimelineItemSecureMessage) GetCreatedTimestampOk() (*int64, bool)`

GetCreatedTimestampOk returns a tuple with the CreatedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedTimestamp

`func (o *TimelineItemSecureMessage) SetCreatedTimestamp(v int64)`

SetCreatedTimestamp sets CreatedTimestamp field to given value.

### HasCreatedTimestamp

`func (o *TimelineItemSecureMessage) HasCreatedTimestamp() bool`

HasCreatedTimestamp returns a boolean if a field has been set.

### GetUpdatedTimestamp

`func (o *TimelineItemSecureMessage) GetUpdatedTimestamp() int64`

GetUpdatedTimestamp returns the UpdatedTimestamp field if non-nil, zero value otherwise.

### GetUpdatedTimestampOk

`func (o *TimelineItemSecureMessage) GetUpdatedTimestampOk() (*int64, bool)`

GetUpdatedTimestampOk returns a tuple with the UpdatedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedTimestamp

`func (o *TimelineItemSecureMessage) SetUpdatedTimestamp(v int64)`

SetUpdatedTimestamp sets UpdatedTimestamp field to given value.

### HasUpdatedTimestamp

`func (o *TimelineItemSecureMessage) HasUpdatedTimestamp() bool`

HasUpdatedTimestamp returns a boolean if a field has been set.

### GetConversationId

`func (o *TimelineItemSecureMessage) GetConversationId() string`

GetConversationId returns the ConversationId field if non-nil, zero value otherwise.

### GetConversationIdOk

`func (o *TimelineItemSecureMessage) GetConversationIdOk() (*string, bool)`

GetConversationIdOk returns a tuple with the ConversationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversationId

`func (o *TimelineItemSecureMessage) SetConversationId(v string)`

SetConversationId sets ConversationId field to given value.

### HasConversationId

`func (o *TimelineItemSecureMessage) HasConversationId() bool`

HasConversationId returns a boolean if a field has been set.

### GetTimeSent

`func (o *TimelineItemSecureMessage) GetTimeSent() string`

GetTimeSent returns the TimeSent field if non-nil, zero value otherwise.

### GetTimeSentOk

`func (o *TimelineItemSecureMessage) GetTimeSentOk() (*string, bool)`

GetTimeSentOk returns a tuple with the TimeSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSent

`func (o *TimelineItemSecureMessage) SetTimeSent(v string)`

SetTimeSent sets TimeSent field to given value.

### HasTimeSent

`func (o *TimelineItemSecureMessage) HasTimeSent() bool`

HasTimeSent returns a boolean if a field has been set.

### GetTimeReceived

`func (o *TimelineItemSecureMessage) GetTimeReceived() string`

GetTimeReceived returns the TimeReceived field if non-nil, zero value otherwise.

### GetTimeReceivedOk

`func (o *TimelineItemSecureMessage) GetTimeReceivedOk() (*string, bool)`

GetTimeReceivedOk returns a tuple with the TimeReceived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeReceived

`func (o *TimelineItemSecureMessage) SetTimeReceived(v string)`

SetTimeReceived sets TimeReceived field to given value.

### HasTimeReceived

`func (o *TimelineItemSecureMessage) HasTimeReceived() bool`

HasTimeReceived returns a boolean if a field has been set.

### GetMessageFrom

`func (o *TimelineItemSecureMessage) GetMessageFrom() string`

GetMessageFrom returns the MessageFrom field if non-nil, zero value otherwise.

### GetMessageFromOk

`func (o *TimelineItemSecureMessage) GetMessageFromOk() (*string, bool)`

GetMessageFromOk returns a tuple with the MessageFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageFrom

`func (o *TimelineItemSecureMessage) SetMessageFrom(v string)`

SetMessageFrom sets MessageFrom field to given value.

### HasMessageFrom

`func (o *TimelineItemSecureMessage) HasMessageFrom() bool`

HasMessageFrom returns a boolean if a field has been set.

### GetMessageTo

`func (o *TimelineItemSecureMessage) GetMessageTo() string`

GetMessageTo returns the MessageTo field if non-nil, zero value otherwise.

### GetMessageToOk

`func (o *TimelineItemSecureMessage) GetMessageToOk() (*string, bool)`

GetMessageToOk returns a tuple with the MessageTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageTo

`func (o *TimelineItemSecureMessage) SetMessageTo(v string)`

SetMessageTo sets MessageTo field to given value.

### HasMessageTo

`func (o *TimelineItemSecureMessage) HasMessageTo() bool`

HasMessageTo returns a boolean if a field has been set.

### GetMessageContent

`func (o *TimelineItemSecureMessage) GetMessageContent() string`

GetMessageContent returns the MessageContent field if non-nil, zero value otherwise.

### GetMessageContentOk

`func (o *TimelineItemSecureMessage) GetMessageContentOk() (*string, bool)`

GetMessageContentOk returns a tuple with the MessageContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageContent

`func (o *TimelineItemSecureMessage) SetMessageContent(v string)`

SetMessageContent sets MessageContent field to given value.

### HasMessageContent

`func (o *TimelineItemSecureMessage) HasMessageContent() bool`

HasMessageContent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


