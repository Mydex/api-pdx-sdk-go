# TimelineSingleItemResponseTimelineItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FeatureBlock** | Pointer to **string** | Type of feature block this timeline item belongs to | [optional] 
**FeatureBlockId** | Pointer to **int32** | ID of the feature block | [optional] 
**Instance** | Pointer to **string** |  | [optional] 
**Source** | Pointer to **string** |  | [optional] 
**CreatedTimestamp** | Pointer to **string** |  | [optional] 
**UpdatedTimestamp** | Pointer to **string** |  | [optional] 
**ServiceId** | Pointer to **int32** | The id of the service that the referral relates to | [optional] 
**ServiceName** | Pointer to **string** |  | [optional] 
**ServiceDescription** | Pointer to **string** |  | [optional] 
**ServiceUrl** | Pointer to **string** |  | [optional] 
**ServiceEmail** | Pointer to **string** |  | [optional] 
**ContactName** | Pointer to **string** |  | [optional] 
**ContactTitle** | Pointer to **string** |  | [optional] 
**ContactNumber** | Pointer to **string** |  | [optional] 
**ReferrerName** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **NullableString** |  | [optional] 
**ExternalId** | Pointer to **string** |  | [optional] 
**StartTime** | Pointer to **int64** |  | [optional] 
**EndTime** | Pointer to **int64** |  | [optional] 
**IsProcessed** | Pointer to **bool** |  | [optional] 
**CompleteTime** | Pointer to **int32** |  | [optional] 
**Memo** | Pointer to **string** |  | [optional] 
**Duration** | Pointer to **string** |  | [optional] 
**ReferreeBackground** | Pointer to **string** |  | [optional] 
**ReferreeRequirements** | Pointer to **string** |  | [optional] 
**ReferreeAvailability** | Pointer to **map[string]interface{}** | Availability of the referree in AM/PM slots | [optional] 
**Type** | Pointer to **NullableString** |  | [optional] 
**StartTimestamp** | Pointer to **string** |  | [optional] 
**ItemTimestamp** | Pointer to **int64** | Raw timestamp of the timeline item | [optional] 
**ConversationId** | Pointer to **string** | Conversation identifier | [optional] 
**TimeSent** | Pointer to **string** | Timestamp when message was sent | [optional] 
**TimeReceived** | Pointer to **string** | Timestamp when message was received | [optional] 
**MessageFrom** | Pointer to **string** | Sender of the message (present on received messages) | [optional] 
**MessageTo** | Pointer to **string** | Recipient of the message (present on sent messages) | [optional] 
**MessageContent** | Pointer to **string** | Content of the message | [optional] 
**ExternalUid** | Pointer to **NullableString** |  | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**EndTimestamp** | Pointer to **string** |  | [optional] 
**Organiser** | Pointer to **NullableString** |  | [optional] 
**Attendee** | Pointer to **NullableString** |  | [optional] 
**Location** | Pointer to **NullableString** |  | [optional] 
**Tags** | Pointer to **NullableString** |  | [optional] 
**Trigger** | Pointer to **NullableString** |  | [optional] 
**Action** | Pointer to **NullableString** |  | [optional] 
**ReminderDescription** | Pointer to **NullableString** |  | [optional] 
**DurationString** | Pointer to **string** |  | [optional] 
**DurationOfEvent** | Pointer to **float32** |  | [optional] 

## Methods

### NewTimelineSingleItemResponseTimelineItem

`func NewTimelineSingleItemResponseTimelineItem() *TimelineSingleItemResponseTimelineItem`

NewTimelineSingleItemResponseTimelineItem instantiates a new TimelineSingleItemResponseTimelineItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimelineSingleItemResponseTimelineItemWithDefaults

`func NewTimelineSingleItemResponseTimelineItemWithDefaults() *TimelineSingleItemResponseTimelineItem`

NewTimelineSingleItemResponseTimelineItemWithDefaults instantiates a new TimelineSingleItemResponseTimelineItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFeatureBlock

`func (o *TimelineSingleItemResponseTimelineItem) GetFeatureBlock() string`

GetFeatureBlock returns the FeatureBlock field if non-nil, zero value otherwise.

### GetFeatureBlockOk

`func (o *TimelineSingleItemResponseTimelineItem) GetFeatureBlockOk() (*string, bool)`

GetFeatureBlockOk returns a tuple with the FeatureBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureBlock

`func (o *TimelineSingleItemResponseTimelineItem) SetFeatureBlock(v string)`

SetFeatureBlock sets FeatureBlock field to given value.

### HasFeatureBlock

`func (o *TimelineSingleItemResponseTimelineItem) HasFeatureBlock() bool`

HasFeatureBlock returns a boolean if a field has been set.

### GetFeatureBlockId

`func (o *TimelineSingleItemResponseTimelineItem) GetFeatureBlockId() int32`

GetFeatureBlockId returns the FeatureBlockId field if non-nil, zero value otherwise.

### GetFeatureBlockIdOk

`func (o *TimelineSingleItemResponseTimelineItem) GetFeatureBlockIdOk() (*int32, bool)`

GetFeatureBlockIdOk returns a tuple with the FeatureBlockId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureBlockId

`func (o *TimelineSingleItemResponseTimelineItem) SetFeatureBlockId(v int32)`

SetFeatureBlockId sets FeatureBlockId field to given value.

### HasFeatureBlockId

`func (o *TimelineSingleItemResponseTimelineItem) HasFeatureBlockId() bool`

HasFeatureBlockId returns a boolean if a field has been set.

### GetInstance

`func (o *TimelineSingleItemResponseTimelineItem) GetInstance() string`

GetInstance returns the Instance field if non-nil, zero value otherwise.

### GetInstanceOk

`func (o *TimelineSingleItemResponseTimelineItem) GetInstanceOk() (*string, bool)`

GetInstanceOk returns a tuple with the Instance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstance

`func (o *TimelineSingleItemResponseTimelineItem) SetInstance(v string)`

SetInstance sets Instance field to given value.

### HasInstance

`func (o *TimelineSingleItemResponseTimelineItem) HasInstance() bool`

HasInstance returns a boolean if a field has been set.

### GetSource

`func (o *TimelineSingleItemResponseTimelineItem) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *TimelineSingleItemResponseTimelineItem) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *TimelineSingleItemResponseTimelineItem) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *TimelineSingleItemResponseTimelineItem) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetCreatedTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) GetCreatedTimestamp() string`

GetCreatedTimestamp returns the CreatedTimestamp field if non-nil, zero value otherwise.

### GetCreatedTimestampOk

`func (o *TimelineSingleItemResponseTimelineItem) GetCreatedTimestampOk() (*string, bool)`

GetCreatedTimestampOk returns a tuple with the CreatedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) SetCreatedTimestamp(v string)`

SetCreatedTimestamp sets CreatedTimestamp field to given value.

### HasCreatedTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) HasCreatedTimestamp() bool`

HasCreatedTimestamp returns a boolean if a field has been set.

### GetUpdatedTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) GetUpdatedTimestamp() string`

GetUpdatedTimestamp returns the UpdatedTimestamp field if non-nil, zero value otherwise.

### GetUpdatedTimestampOk

`func (o *TimelineSingleItemResponseTimelineItem) GetUpdatedTimestampOk() (*string, bool)`

GetUpdatedTimestampOk returns a tuple with the UpdatedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) SetUpdatedTimestamp(v string)`

SetUpdatedTimestamp sets UpdatedTimestamp field to given value.

### HasUpdatedTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) HasUpdatedTimestamp() bool`

HasUpdatedTimestamp returns a boolean if a field has been set.

### GetServiceId

`func (o *TimelineSingleItemResponseTimelineItem) GetServiceId() int32`

GetServiceId returns the ServiceId field if non-nil, zero value otherwise.

### GetServiceIdOk

`func (o *TimelineSingleItemResponseTimelineItem) GetServiceIdOk() (*int32, bool)`

GetServiceIdOk returns a tuple with the ServiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceId

`func (o *TimelineSingleItemResponseTimelineItem) SetServiceId(v int32)`

SetServiceId sets ServiceId field to given value.

### HasServiceId

`func (o *TimelineSingleItemResponseTimelineItem) HasServiceId() bool`

HasServiceId returns a boolean if a field has been set.

### GetServiceName

`func (o *TimelineSingleItemResponseTimelineItem) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *TimelineSingleItemResponseTimelineItem) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *TimelineSingleItemResponseTimelineItem) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.

### HasServiceName

`func (o *TimelineSingleItemResponseTimelineItem) HasServiceName() bool`

HasServiceName returns a boolean if a field has been set.

### GetServiceDescription

`func (o *TimelineSingleItemResponseTimelineItem) GetServiceDescription() string`

GetServiceDescription returns the ServiceDescription field if non-nil, zero value otherwise.

### GetServiceDescriptionOk

`func (o *TimelineSingleItemResponseTimelineItem) GetServiceDescriptionOk() (*string, bool)`

GetServiceDescriptionOk returns a tuple with the ServiceDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceDescription

`func (o *TimelineSingleItemResponseTimelineItem) SetServiceDescription(v string)`

SetServiceDescription sets ServiceDescription field to given value.

### HasServiceDescription

`func (o *TimelineSingleItemResponseTimelineItem) HasServiceDescription() bool`

HasServiceDescription returns a boolean if a field has been set.

### GetServiceUrl

`func (o *TimelineSingleItemResponseTimelineItem) GetServiceUrl() string`

GetServiceUrl returns the ServiceUrl field if non-nil, zero value otherwise.

### GetServiceUrlOk

`func (o *TimelineSingleItemResponseTimelineItem) GetServiceUrlOk() (*string, bool)`

GetServiceUrlOk returns a tuple with the ServiceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceUrl

`func (o *TimelineSingleItemResponseTimelineItem) SetServiceUrl(v string)`

SetServiceUrl sets ServiceUrl field to given value.

### HasServiceUrl

`func (o *TimelineSingleItemResponseTimelineItem) HasServiceUrl() bool`

HasServiceUrl returns a boolean if a field has been set.

### GetServiceEmail

`func (o *TimelineSingleItemResponseTimelineItem) GetServiceEmail() string`

GetServiceEmail returns the ServiceEmail field if non-nil, zero value otherwise.

### GetServiceEmailOk

`func (o *TimelineSingleItemResponseTimelineItem) GetServiceEmailOk() (*string, bool)`

GetServiceEmailOk returns a tuple with the ServiceEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceEmail

`func (o *TimelineSingleItemResponseTimelineItem) SetServiceEmail(v string)`

SetServiceEmail sets ServiceEmail field to given value.

### HasServiceEmail

`func (o *TimelineSingleItemResponseTimelineItem) HasServiceEmail() bool`

HasServiceEmail returns a boolean if a field has been set.

### GetContactName

`func (o *TimelineSingleItemResponseTimelineItem) GetContactName() string`

GetContactName returns the ContactName field if non-nil, zero value otherwise.

### GetContactNameOk

`func (o *TimelineSingleItemResponseTimelineItem) GetContactNameOk() (*string, bool)`

GetContactNameOk returns a tuple with the ContactName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactName

`func (o *TimelineSingleItemResponseTimelineItem) SetContactName(v string)`

SetContactName sets ContactName field to given value.

### HasContactName

`func (o *TimelineSingleItemResponseTimelineItem) HasContactName() bool`

HasContactName returns a boolean if a field has been set.

### GetContactTitle

`func (o *TimelineSingleItemResponseTimelineItem) GetContactTitle() string`

GetContactTitle returns the ContactTitle field if non-nil, zero value otherwise.

### GetContactTitleOk

`func (o *TimelineSingleItemResponseTimelineItem) GetContactTitleOk() (*string, bool)`

GetContactTitleOk returns a tuple with the ContactTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactTitle

`func (o *TimelineSingleItemResponseTimelineItem) SetContactTitle(v string)`

SetContactTitle sets ContactTitle field to given value.

### HasContactTitle

`func (o *TimelineSingleItemResponseTimelineItem) HasContactTitle() bool`

HasContactTitle returns a boolean if a field has been set.

### GetContactNumber

`func (o *TimelineSingleItemResponseTimelineItem) GetContactNumber() string`

GetContactNumber returns the ContactNumber field if non-nil, zero value otherwise.

### GetContactNumberOk

`func (o *TimelineSingleItemResponseTimelineItem) GetContactNumberOk() (*string, bool)`

GetContactNumberOk returns a tuple with the ContactNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactNumber

`func (o *TimelineSingleItemResponseTimelineItem) SetContactNumber(v string)`

SetContactNumber sets ContactNumber field to given value.

### HasContactNumber

`func (o *TimelineSingleItemResponseTimelineItem) HasContactNumber() bool`

HasContactNumber returns a boolean if a field has been set.

### GetReferrerName

`func (o *TimelineSingleItemResponseTimelineItem) GetReferrerName() string`

GetReferrerName returns the ReferrerName field if non-nil, zero value otherwise.

### GetReferrerNameOk

`func (o *TimelineSingleItemResponseTimelineItem) GetReferrerNameOk() (*string, bool)`

GetReferrerNameOk returns a tuple with the ReferrerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferrerName

`func (o *TimelineSingleItemResponseTimelineItem) SetReferrerName(v string)`

SetReferrerName sets ReferrerName field to given value.

### HasReferrerName

`func (o *TimelineSingleItemResponseTimelineItem) HasReferrerName() bool`

HasReferrerName returns a boolean if a field has been set.

### GetStatus

`func (o *TimelineSingleItemResponseTimelineItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TimelineSingleItemResponseTimelineItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TimelineSingleItemResponseTimelineItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *TimelineSingleItemResponseTimelineItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *TimelineSingleItemResponseTimelineItem) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *TimelineSingleItemResponseTimelineItem) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetExternalId

`func (o *TimelineSingleItemResponseTimelineItem) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *TimelineSingleItemResponseTimelineItem) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *TimelineSingleItemResponseTimelineItem) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *TimelineSingleItemResponseTimelineItem) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### GetStartTime

`func (o *TimelineSingleItemResponseTimelineItem) GetStartTime() int64`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *TimelineSingleItemResponseTimelineItem) GetStartTimeOk() (*int64, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *TimelineSingleItemResponseTimelineItem) SetStartTime(v int64)`

SetStartTime sets StartTime field to given value.

### HasStartTime

`func (o *TimelineSingleItemResponseTimelineItem) HasStartTime() bool`

HasStartTime returns a boolean if a field has been set.

### GetEndTime

`func (o *TimelineSingleItemResponseTimelineItem) GetEndTime() int64`

GetEndTime returns the EndTime field if non-nil, zero value otherwise.

### GetEndTimeOk

`func (o *TimelineSingleItemResponseTimelineItem) GetEndTimeOk() (*int64, bool)`

GetEndTimeOk returns a tuple with the EndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTime

`func (o *TimelineSingleItemResponseTimelineItem) SetEndTime(v int64)`

SetEndTime sets EndTime field to given value.

### HasEndTime

`func (o *TimelineSingleItemResponseTimelineItem) HasEndTime() bool`

HasEndTime returns a boolean if a field has been set.

### GetIsProcessed

`func (o *TimelineSingleItemResponseTimelineItem) GetIsProcessed() bool`

GetIsProcessed returns the IsProcessed field if non-nil, zero value otherwise.

### GetIsProcessedOk

`func (o *TimelineSingleItemResponseTimelineItem) GetIsProcessedOk() (*bool, bool)`

GetIsProcessedOk returns a tuple with the IsProcessed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsProcessed

`func (o *TimelineSingleItemResponseTimelineItem) SetIsProcessed(v bool)`

SetIsProcessed sets IsProcessed field to given value.

### HasIsProcessed

`func (o *TimelineSingleItemResponseTimelineItem) HasIsProcessed() bool`

HasIsProcessed returns a boolean if a field has been set.

### GetCompleteTime

`func (o *TimelineSingleItemResponseTimelineItem) GetCompleteTime() int32`

GetCompleteTime returns the CompleteTime field if non-nil, zero value otherwise.

### GetCompleteTimeOk

`func (o *TimelineSingleItemResponseTimelineItem) GetCompleteTimeOk() (*int32, bool)`

GetCompleteTimeOk returns a tuple with the CompleteTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompleteTime

`func (o *TimelineSingleItemResponseTimelineItem) SetCompleteTime(v int32)`

SetCompleteTime sets CompleteTime field to given value.

### HasCompleteTime

`func (o *TimelineSingleItemResponseTimelineItem) HasCompleteTime() bool`

HasCompleteTime returns a boolean if a field has been set.

### GetMemo

`func (o *TimelineSingleItemResponseTimelineItem) GetMemo() string`

GetMemo returns the Memo field if non-nil, zero value otherwise.

### GetMemoOk

`func (o *TimelineSingleItemResponseTimelineItem) GetMemoOk() (*string, bool)`

GetMemoOk returns a tuple with the Memo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemo

`func (o *TimelineSingleItemResponseTimelineItem) SetMemo(v string)`

SetMemo sets Memo field to given value.

### HasMemo

`func (o *TimelineSingleItemResponseTimelineItem) HasMemo() bool`

HasMemo returns a boolean if a field has been set.

### GetDuration

`func (o *TimelineSingleItemResponseTimelineItem) GetDuration() string`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *TimelineSingleItemResponseTimelineItem) GetDurationOk() (*string, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *TimelineSingleItemResponseTimelineItem) SetDuration(v string)`

SetDuration sets Duration field to given value.

### HasDuration

`func (o *TimelineSingleItemResponseTimelineItem) HasDuration() bool`

HasDuration returns a boolean if a field has been set.

### GetReferreeBackground

`func (o *TimelineSingleItemResponseTimelineItem) GetReferreeBackground() string`

GetReferreeBackground returns the ReferreeBackground field if non-nil, zero value otherwise.

### GetReferreeBackgroundOk

`func (o *TimelineSingleItemResponseTimelineItem) GetReferreeBackgroundOk() (*string, bool)`

GetReferreeBackgroundOk returns a tuple with the ReferreeBackground field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferreeBackground

`func (o *TimelineSingleItemResponseTimelineItem) SetReferreeBackground(v string)`

SetReferreeBackground sets ReferreeBackground field to given value.

### HasReferreeBackground

`func (o *TimelineSingleItemResponseTimelineItem) HasReferreeBackground() bool`

HasReferreeBackground returns a boolean if a field has been set.

### GetReferreeRequirements

`func (o *TimelineSingleItemResponseTimelineItem) GetReferreeRequirements() string`

GetReferreeRequirements returns the ReferreeRequirements field if non-nil, zero value otherwise.

### GetReferreeRequirementsOk

`func (o *TimelineSingleItemResponseTimelineItem) GetReferreeRequirementsOk() (*string, bool)`

GetReferreeRequirementsOk returns a tuple with the ReferreeRequirements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferreeRequirements

`func (o *TimelineSingleItemResponseTimelineItem) SetReferreeRequirements(v string)`

SetReferreeRequirements sets ReferreeRequirements field to given value.

### HasReferreeRequirements

`func (o *TimelineSingleItemResponseTimelineItem) HasReferreeRequirements() bool`

HasReferreeRequirements returns a boolean if a field has been set.

### GetReferreeAvailability

`func (o *TimelineSingleItemResponseTimelineItem) GetReferreeAvailability() map[string]interface{}`

GetReferreeAvailability returns the ReferreeAvailability field if non-nil, zero value otherwise.

### GetReferreeAvailabilityOk

`func (o *TimelineSingleItemResponseTimelineItem) GetReferreeAvailabilityOk() (*map[string]interface{}, bool)`

GetReferreeAvailabilityOk returns a tuple with the ReferreeAvailability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferreeAvailability

`func (o *TimelineSingleItemResponseTimelineItem) SetReferreeAvailability(v map[string]interface{})`

SetReferreeAvailability sets ReferreeAvailability field to given value.

### HasReferreeAvailability

`func (o *TimelineSingleItemResponseTimelineItem) HasReferreeAvailability() bool`

HasReferreeAvailability returns a boolean if a field has been set.

### GetType

`func (o *TimelineSingleItemResponseTimelineItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TimelineSingleItemResponseTimelineItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TimelineSingleItemResponseTimelineItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *TimelineSingleItemResponseTimelineItem) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *TimelineSingleItemResponseTimelineItem) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *TimelineSingleItemResponseTimelineItem) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetStartTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) GetStartTimestamp() string`

GetStartTimestamp returns the StartTimestamp field if non-nil, zero value otherwise.

### GetStartTimestampOk

`func (o *TimelineSingleItemResponseTimelineItem) GetStartTimestampOk() (*string, bool)`

GetStartTimestampOk returns a tuple with the StartTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) SetStartTimestamp(v string)`

SetStartTimestamp sets StartTimestamp field to given value.

### HasStartTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) HasStartTimestamp() bool`

HasStartTimestamp returns a boolean if a field has been set.

### GetItemTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) GetItemTimestamp() int64`

GetItemTimestamp returns the ItemTimestamp field if non-nil, zero value otherwise.

### GetItemTimestampOk

`func (o *TimelineSingleItemResponseTimelineItem) GetItemTimestampOk() (*int64, bool)`

GetItemTimestampOk returns a tuple with the ItemTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) SetItemTimestamp(v int64)`

SetItemTimestamp sets ItemTimestamp field to given value.

### HasItemTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) HasItemTimestamp() bool`

HasItemTimestamp returns a boolean if a field has been set.

### GetConversationId

`func (o *TimelineSingleItemResponseTimelineItem) GetConversationId() string`

GetConversationId returns the ConversationId field if non-nil, zero value otherwise.

### GetConversationIdOk

`func (o *TimelineSingleItemResponseTimelineItem) GetConversationIdOk() (*string, bool)`

GetConversationIdOk returns a tuple with the ConversationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversationId

`func (o *TimelineSingleItemResponseTimelineItem) SetConversationId(v string)`

SetConversationId sets ConversationId field to given value.

### HasConversationId

`func (o *TimelineSingleItemResponseTimelineItem) HasConversationId() bool`

HasConversationId returns a boolean if a field has been set.

### GetTimeSent

`func (o *TimelineSingleItemResponseTimelineItem) GetTimeSent() string`

GetTimeSent returns the TimeSent field if non-nil, zero value otherwise.

### GetTimeSentOk

`func (o *TimelineSingleItemResponseTimelineItem) GetTimeSentOk() (*string, bool)`

GetTimeSentOk returns a tuple with the TimeSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSent

`func (o *TimelineSingleItemResponseTimelineItem) SetTimeSent(v string)`

SetTimeSent sets TimeSent field to given value.

### HasTimeSent

`func (o *TimelineSingleItemResponseTimelineItem) HasTimeSent() bool`

HasTimeSent returns a boolean if a field has been set.

### GetTimeReceived

`func (o *TimelineSingleItemResponseTimelineItem) GetTimeReceived() string`

GetTimeReceived returns the TimeReceived field if non-nil, zero value otherwise.

### GetTimeReceivedOk

`func (o *TimelineSingleItemResponseTimelineItem) GetTimeReceivedOk() (*string, bool)`

GetTimeReceivedOk returns a tuple with the TimeReceived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeReceived

`func (o *TimelineSingleItemResponseTimelineItem) SetTimeReceived(v string)`

SetTimeReceived sets TimeReceived field to given value.

### HasTimeReceived

`func (o *TimelineSingleItemResponseTimelineItem) HasTimeReceived() bool`

HasTimeReceived returns a boolean if a field has been set.

### GetMessageFrom

`func (o *TimelineSingleItemResponseTimelineItem) GetMessageFrom() string`

GetMessageFrom returns the MessageFrom field if non-nil, zero value otherwise.

### GetMessageFromOk

`func (o *TimelineSingleItemResponseTimelineItem) GetMessageFromOk() (*string, bool)`

GetMessageFromOk returns a tuple with the MessageFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageFrom

`func (o *TimelineSingleItemResponseTimelineItem) SetMessageFrom(v string)`

SetMessageFrom sets MessageFrom field to given value.

### HasMessageFrom

`func (o *TimelineSingleItemResponseTimelineItem) HasMessageFrom() bool`

HasMessageFrom returns a boolean if a field has been set.

### GetMessageTo

`func (o *TimelineSingleItemResponseTimelineItem) GetMessageTo() string`

GetMessageTo returns the MessageTo field if non-nil, zero value otherwise.

### GetMessageToOk

`func (o *TimelineSingleItemResponseTimelineItem) GetMessageToOk() (*string, bool)`

GetMessageToOk returns a tuple with the MessageTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageTo

`func (o *TimelineSingleItemResponseTimelineItem) SetMessageTo(v string)`

SetMessageTo sets MessageTo field to given value.

### HasMessageTo

`func (o *TimelineSingleItemResponseTimelineItem) HasMessageTo() bool`

HasMessageTo returns a boolean if a field has been set.

### GetMessageContent

`func (o *TimelineSingleItemResponseTimelineItem) GetMessageContent() string`

GetMessageContent returns the MessageContent field if non-nil, zero value otherwise.

### GetMessageContentOk

`func (o *TimelineSingleItemResponseTimelineItem) GetMessageContentOk() (*string, bool)`

GetMessageContentOk returns a tuple with the MessageContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageContent

`func (o *TimelineSingleItemResponseTimelineItem) SetMessageContent(v string)`

SetMessageContent sets MessageContent field to given value.

### HasMessageContent

`func (o *TimelineSingleItemResponseTimelineItem) HasMessageContent() bool`

HasMessageContent returns a boolean if a field has been set.

### GetExternalUid

`func (o *TimelineSingleItemResponseTimelineItem) GetExternalUid() string`

GetExternalUid returns the ExternalUid field if non-nil, zero value otherwise.

### GetExternalUidOk

`func (o *TimelineSingleItemResponseTimelineItem) GetExternalUidOk() (*string, bool)`

GetExternalUidOk returns a tuple with the ExternalUid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalUid

`func (o *TimelineSingleItemResponseTimelineItem) SetExternalUid(v string)`

SetExternalUid sets ExternalUid field to given value.

### HasExternalUid

`func (o *TimelineSingleItemResponseTimelineItem) HasExternalUid() bool`

HasExternalUid returns a boolean if a field has been set.

### SetExternalUidNil

`func (o *TimelineSingleItemResponseTimelineItem) SetExternalUidNil(b bool)`

 SetExternalUidNil sets the value for ExternalUid to be an explicit nil

### UnsetExternalUid
`func (o *TimelineSingleItemResponseTimelineItem) UnsetExternalUid()`

UnsetExternalUid ensures that no value is present for ExternalUid, not even an explicit nil
### GetTitle

`func (o *TimelineSingleItemResponseTimelineItem) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *TimelineSingleItemResponseTimelineItem) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *TimelineSingleItemResponseTimelineItem) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *TimelineSingleItemResponseTimelineItem) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *TimelineSingleItemResponseTimelineItem) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *TimelineSingleItemResponseTimelineItem) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetDescription

`func (o *TimelineSingleItemResponseTimelineItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *TimelineSingleItemResponseTimelineItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *TimelineSingleItemResponseTimelineItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *TimelineSingleItemResponseTimelineItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *TimelineSingleItemResponseTimelineItem) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *TimelineSingleItemResponseTimelineItem) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetEndTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) GetEndTimestamp() string`

GetEndTimestamp returns the EndTimestamp field if non-nil, zero value otherwise.

### GetEndTimestampOk

`func (o *TimelineSingleItemResponseTimelineItem) GetEndTimestampOk() (*string, bool)`

GetEndTimestampOk returns a tuple with the EndTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) SetEndTimestamp(v string)`

SetEndTimestamp sets EndTimestamp field to given value.

### HasEndTimestamp

`func (o *TimelineSingleItemResponseTimelineItem) HasEndTimestamp() bool`

HasEndTimestamp returns a boolean if a field has been set.

### GetOrganiser

`func (o *TimelineSingleItemResponseTimelineItem) GetOrganiser() string`

GetOrganiser returns the Organiser field if non-nil, zero value otherwise.

### GetOrganiserOk

`func (o *TimelineSingleItemResponseTimelineItem) GetOrganiserOk() (*string, bool)`

GetOrganiserOk returns a tuple with the Organiser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganiser

`func (o *TimelineSingleItemResponseTimelineItem) SetOrganiser(v string)`

SetOrganiser sets Organiser field to given value.

### HasOrganiser

`func (o *TimelineSingleItemResponseTimelineItem) HasOrganiser() bool`

HasOrganiser returns a boolean if a field has been set.

### SetOrganiserNil

`func (o *TimelineSingleItemResponseTimelineItem) SetOrganiserNil(b bool)`

 SetOrganiserNil sets the value for Organiser to be an explicit nil

### UnsetOrganiser
`func (o *TimelineSingleItemResponseTimelineItem) UnsetOrganiser()`

UnsetOrganiser ensures that no value is present for Organiser, not even an explicit nil
### GetAttendee

`func (o *TimelineSingleItemResponseTimelineItem) GetAttendee() string`

GetAttendee returns the Attendee field if non-nil, zero value otherwise.

### GetAttendeeOk

`func (o *TimelineSingleItemResponseTimelineItem) GetAttendeeOk() (*string, bool)`

GetAttendeeOk returns a tuple with the Attendee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttendee

`func (o *TimelineSingleItemResponseTimelineItem) SetAttendee(v string)`

SetAttendee sets Attendee field to given value.

### HasAttendee

`func (o *TimelineSingleItemResponseTimelineItem) HasAttendee() bool`

HasAttendee returns a boolean if a field has been set.

### SetAttendeeNil

`func (o *TimelineSingleItemResponseTimelineItem) SetAttendeeNil(b bool)`

 SetAttendeeNil sets the value for Attendee to be an explicit nil

### UnsetAttendee
`func (o *TimelineSingleItemResponseTimelineItem) UnsetAttendee()`

UnsetAttendee ensures that no value is present for Attendee, not even an explicit nil
### GetLocation

`func (o *TimelineSingleItemResponseTimelineItem) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *TimelineSingleItemResponseTimelineItem) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *TimelineSingleItemResponseTimelineItem) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *TimelineSingleItemResponseTimelineItem) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### SetLocationNil

`func (o *TimelineSingleItemResponseTimelineItem) SetLocationNil(b bool)`

 SetLocationNil sets the value for Location to be an explicit nil

### UnsetLocation
`func (o *TimelineSingleItemResponseTimelineItem) UnsetLocation()`

UnsetLocation ensures that no value is present for Location, not even an explicit nil
### GetTags

`func (o *TimelineSingleItemResponseTimelineItem) GetTags() string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *TimelineSingleItemResponseTimelineItem) GetTagsOk() (*string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *TimelineSingleItemResponseTimelineItem) SetTags(v string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *TimelineSingleItemResponseTimelineItem) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *TimelineSingleItemResponseTimelineItem) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *TimelineSingleItemResponseTimelineItem) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil
### GetTrigger

`func (o *TimelineSingleItemResponseTimelineItem) GetTrigger() string`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *TimelineSingleItemResponseTimelineItem) GetTriggerOk() (*string, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *TimelineSingleItemResponseTimelineItem) SetTrigger(v string)`

SetTrigger sets Trigger field to given value.

### HasTrigger

`func (o *TimelineSingleItemResponseTimelineItem) HasTrigger() bool`

HasTrigger returns a boolean if a field has been set.

### SetTriggerNil

`func (o *TimelineSingleItemResponseTimelineItem) SetTriggerNil(b bool)`

 SetTriggerNil sets the value for Trigger to be an explicit nil

### UnsetTrigger
`func (o *TimelineSingleItemResponseTimelineItem) UnsetTrigger()`

UnsetTrigger ensures that no value is present for Trigger, not even an explicit nil
### GetAction

`func (o *TimelineSingleItemResponseTimelineItem) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *TimelineSingleItemResponseTimelineItem) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *TimelineSingleItemResponseTimelineItem) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *TimelineSingleItemResponseTimelineItem) HasAction() bool`

HasAction returns a boolean if a field has been set.

### SetActionNil

`func (o *TimelineSingleItemResponseTimelineItem) SetActionNil(b bool)`

 SetActionNil sets the value for Action to be an explicit nil

### UnsetAction
`func (o *TimelineSingleItemResponseTimelineItem) UnsetAction()`

UnsetAction ensures that no value is present for Action, not even an explicit nil
### GetReminderDescription

`func (o *TimelineSingleItemResponseTimelineItem) GetReminderDescription() string`

GetReminderDescription returns the ReminderDescription field if non-nil, zero value otherwise.

### GetReminderDescriptionOk

`func (o *TimelineSingleItemResponseTimelineItem) GetReminderDescriptionOk() (*string, bool)`

GetReminderDescriptionOk returns a tuple with the ReminderDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReminderDescription

`func (o *TimelineSingleItemResponseTimelineItem) SetReminderDescription(v string)`

SetReminderDescription sets ReminderDescription field to given value.

### HasReminderDescription

`func (o *TimelineSingleItemResponseTimelineItem) HasReminderDescription() bool`

HasReminderDescription returns a boolean if a field has been set.

### SetReminderDescriptionNil

`func (o *TimelineSingleItemResponseTimelineItem) SetReminderDescriptionNil(b bool)`

 SetReminderDescriptionNil sets the value for ReminderDescription to be an explicit nil

### UnsetReminderDescription
`func (o *TimelineSingleItemResponseTimelineItem) UnsetReminderDescription()`

UnsetReminderDescription ensures that no value is present for ReminderDescription, not even an explicit nil
### GetDurationString

`func (o *TimelineSingleItemResponseTimelineItem) GetDurationString() string`

GetDurationString returns the DurationString field if non-nil, zero value otherwise.

### GetDurationStringOk

`func (o *TimelineSingleItemResponseTimelineItem) GetDurationStringOk() (*string, bool)`

GetDurationStringOk returns a tuple with the DurationString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationString

`func (o *TimelineSingleItemResponseTimelineItem) SetDurationString(v string)`

SetDurationString sets DurationString field to given value.

### HasDurationString

`func (o *TimelineSingleItemResponseTimelineItem) HasDurationString() bool`

HasDurationString returns a boolean if a field has been set.

### GetDurationOfEvent

`func (o *TimelineSingleItemResponseTimelineItem) GetDurationOfEvent() float32`

GetDurationOfEvent returns the DurationOfEvent field if non-nil, zero value otherwise.

### GetDurationOfEventOk

`func (o *TimelineSingleItemResponseTimelineItem) GetDurationOfEventOk() (*float32, bool)`

GetDurationOfEventOk returns a tuple with the DurationOfEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationOfEvent

`func (o *TimelineSingleItemResponseTimelineItem) SetDurationOfEvent(v float32)`

SetDurationOfEvent sets DurationOfEvent field to given value.

### HasDurationOfEvent

`func (o *TimelineSingleItemResponseTimelineItem) HasDurationOfEvent() bool`

HasDurationOfEvent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


