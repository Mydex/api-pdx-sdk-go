# TimelineItemCalendarEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FeatureBlock** | Pointer to **string** | Type of feature block this timeline item belongs to | [optional] 
**FeatureBlockId** | Pointer to **int32** | ID of the feature block | [optional] 
**Instance** | Pointer to **string** |  | [optional] 
**Source** | Pointer to **string** |  | [optional] 
**CreatedTimestamp** | Pointer to **string** |  | [optional] 
**UpdatedTimestamp** | Pointer to **string** |  | [optional] 
**ExternalUid** | Pointer to **NullableString** |  | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**StartTimestamp** | Pointer to **string** |  | [optional] 
**EndTimestamp** | Pointer to **string** |  | [optional] 
**Organiser** | Pointer to **NullableString** |  | [optional] 
**Attendee** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to **NullableString** |  | [optional] 
**Location** | Pointer to **NullableString** |  | [optional] 
**Type** | Pointer to **NullableString** |  | [optional] 
**Tags** | Pointer to **NullableString** |  | [optional] 
**Trigger** | Pointer to **NullableString** |  | [optional] 
**Action** | Pointer to **NullableString** |  | [optional] 
**ReminderDescription** | Pointer to **NullableString** |  | [optional] 
**DurationString** | Pointer to **string** |  | [optional] 
**DurationOfEvent** | Pointer to **float32** |  | [optional] 

## Methods

### NewTimelineItemCalendarEvent

`func NewTimelineItemCalendarEvent() *TimelineItemCalendarEvent`

NewTimelineItemCalendarEvent instantiates a new TimelineItemCalendarEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimelineItemCalendarEventWithDefaults

`func NewTimelineItemCalendarEventWithDefaults() *TimelineItemCalendarEvent`

NewTimelineItemCalendarEventWithDefaults instantiates a new TimelineItemCalendarEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFeatureBlock

`func (o *TimelineItemCalendarEvent) GetFeatureBlock() string`

GetFeatureBlock returns the FeatureBlock field if non-nil, zero value otherwise.

### GetFeatureBlockOk

`func (o *TimelineItemCalendarEvent) GetFeatureBlockOk() (*string, bool)`

GetFeatureBlockOk returns a tuple with the FeatureBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureBlock

`func (o *TimelineItemCalendarEvent) SetFeatureBlock(v string)`

SetFeatureBlock sets FeatureBlock field to given value.

### HasFeatureBlock

`func (o *TimelineItemCalendarEvent) HasFeatureBlock() bool`

HasFeatureBlock returns a boolean if a field has been set.

### GetFeatureBlockId

`func (o *TimelineItemCalendarEvent) GetFeatureBlockId() int32`

GetFeatureBlockId returns the FeatureBlockId field if non-nil, zero value otherwise.

### GetFeatureBlockIdOk

`func (o *TimelineItemCalendarEvent) GetFeatureBlockIdOk() (*int32, bool)`

GetFeatureBlockIdOk returns a tuple with the FeatureBlockId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureBlockId

`func (o *TimelineItemCalendarEvent) SetFeatureBlockId(v int32)`

SetFeatureBlockId sets FeatureBlockId field to given value.

### HasFeatureBlockId

`func (o *TimelineItemCalendarEvent) HasFeatureBlockId() bool`

HasFeatureBlockId returns a boolean if a field has been set.

### GetInstance

`func (o *TimelineItemCalendarEvent) GetInstance() string`

GetInstance returns the Instance field if non-nil, zero value otherwise.

### GetInstanceOk

`func (o *TimelineItemCalendarEvent) GetInstanceOk() (*string, bool)`

GetInstanceOk returns a tuple with the Instance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstance

`func (o *TimelineItemCalendarEvent) SetInstance(v string)`

SetInstance sets Instance field to given value.

### HasInstance

`func (o *TimelineItemCalendarEvent) HasInstance() bool`

HasInstance returns a boolean if a field has been set.

### GetSource

`func (o *TimelineItemCalendarEvent) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *TimelineItemCalendarEvent) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *TimelineItemCalendarEvent) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *TimelineItemCalendarEvent) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetCreatedTimestamp

`func (o *TimelineItemCalendarEvent) GetCreatedTimestamp() string`

GetCreatedTimestamp returns the CreatedTimestamp field if non-nil, zero value otherwise.

### GetCreatedTimestampOk

`func (o *TimelineItemCalendarEvent) GetCreatedTimestampOk() (*string, bool)`

GetCreatedTimestampOk returns a tuple with the CreatedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedTimestamp

`func (o *TimelineItemCalendarEvent) SetCreatedTimestamp(v string)`

SetCreatedTimestamp sets CreatedTimestamp field to given value.

### HasCreatedTimestamp

`func (o *TimelineItemCalendarEvent) HasCreatedTimestamp() bool`

HasCreatedTimestamp returns a boolean if a field has been set.

### GetUpdatedTimestamp

`func (o *TimelineItemCalendarEvent) GetUpdatedTimestamp() string`

GetUpdatedTimestamp returns the UpdatedTimestamp field if non-nil, zero value otherwise.

### GetUpdatedTimestampOk

`func (o *TimelineItemCalendarEvent) GetUpdatedTimestampOk() (*string, bool)`

GetUpdatedTimestampOk returns a tuple with the UpdatedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedTimestamp

`func (o *TimelineItemCalendarEvent) SetUpdatedTimestamp(v string)`

SetUpdatedTimestamp sets UpdatedTimestamp field to given value.

### HasUpdatedTimestamp

`func (o *TimelineItemCalendarEvent) HasUpdatedTimestamp() bool`

HasUpdatedTimestamp returns a boolean if a field has been set.

### GetExternalUid

`func (o *TimelineItemCalendarEvent) GetExternalUid() string`

GetExternalUid returns the ExternalUid field if non-nil, zero value otherwise.

### GetExternalUidOk

`func (o *TimelineItemCalendarEvent) GetExternalUidOk() (*string, bool)`

GetExternalUidOk returns a tuple with the ExternalUid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalUid

`func (o *TimelineItemCalendarEvent) SetExternalUid(v string)`

SetExternalUid sets ExternalUid field to given value.

### HasExternalUid

`func (o *TimelineItemCalendarEvent) HasExternalUid() bool`

HasExternalUid returns a boolean if a field has been set.

### SetExternalUidNil

`func (o *TimelineItemCalendarEvent) SetExternalUidNil(b bool)`

 SetExternalUidNil sets the value for ExternalUid to be an explicit nil

### UnsetExternalUid
`func (o *TimelineItemCalendarEvent) UnsetExternalUid()`

UnsetExternalUid ensures that no value is present for ExternalUid, not even an explicit nil
### GetTitle

`func (o *TimelineItemCalendarEvent) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *TimelineItemCalendarEvent) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *TimelineItemCalendarEvent) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *TimelineItemCalendarEvent) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *TimelineItemCalendarEvent) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *TimelineItemCalendarEvent) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetDescription

`func (o *TimelineItemCalendarEvent) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *TimelineItemCalendarEvent) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *TimelineItemCalendarEvent) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *TimelineItemCalendarEvent) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *TimelineItemCalendarEvent) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *TimelineItemCalendarEvent) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetStartTimestamp

`func (o *TimelineItemCalendarEvent) GetStartTimestamp() string`

GetStartTimestamp returns the StartTimestamp field if non-nil, zero value otherwise.

### GetStartTimestampOk

`func (o *TimelineItemCalendarEvent) GetStartTimestampOk() (*string, bool)`

GetStartTimestampOk returns a tuple with the StartTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTimestamp

`func (o *TimelineItemCalendarEvent) SetStartTimestamp(v string)`

SetStartTimestamp sets StartTimestamp field to given value.

### HasStartTimestamp

`func (o *TimelineItemCalendarEvent) HasStartTimestamp() bool`

HasStartTimestamp returns a boolean if a field has been set.

### GetEndTimestamp

`func (o *TimelineItemCalendarEvent) GetEndTimestamp() string`

GetEndTimestamp returns the EndTimestamp field if non-nil, zero value otherwise.

### GetEndTimestampOk

`func (o *TimelineItemCalendarEvent) GetEndTimestampOk() (*string, bool)`

GetEndTimestampOk returns a tuple with the EndTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTimestamp

`func (o *TimelineItemCalendarEvent) SetEndTimestamp(v string)`

SetEndTimestamp sets EndTimestamp field to given value.

### HasEndTimestamp

`func (o *TimelineItemCalendarEvent) HasEndTimestamp() bool`

HasEndTimestamp returns a boolean if a field has been set.

### GetOrganiser

`func (o *TimelineItemCalendarEvent) GetOrganiser() string`

GetOrganiser returns the Organiser field if non-nil, zero value otherwise.

### GetOrganiserOk

`func (o *TimelineItemCalendarEvent) GetOrganiserOk() (*string, bool)`

GetOrganiserOk returns a tuple with the Organiser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganiser

`func (o *TimelineItemCalendarEvent) SetOrganiser(v string)`

SetOrganiser sets Organiser field to given value.

### HasOrganiser

`func (o *TimelineItemCalendarEvent) HasOrganiser() bool`

HasOrganiser returns a boolean if a field has been set.

### SetOrganiserNil

`func (o *TimelineItemCalendarEvent) SetOrganiserNil(b bool)`

 SetOrganiserNil sets the value for Organiser to be an explicit nil

### UnsetOrganiser
`func (o *TimelineItemCalendarEvent) UnsetOrganiser()`

UnsetOrganiser ensures that no value is present for Organiser, not even an explicit nil
### GetAttendee

`func (o *TimelineItemCalendarEvent) GetAttendee() string`

GetAttendee returns the Attendee field if non-nil, zero value otherwise.

### GetAttendeeOk

`func (o *TimelineItemCalendarEvent) GetAttendeeOk() (*string, bool)`

GetAttendeeOk returns a tuple with the Attendee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttendee

`func (o *TimelineItemCalendarEvent) SetAttendee(v string)`

SetAttendee sets Attendee field to given value.

### HasAttendee

`func (o *TimelineItemCalendarEvent) HasAttendee() bool`

HasAttendee returns a boolean if a field has been set.

### SetAttendeeNil

`func (o *TimelineItemCalendarEvent) SetAttendeeNil(b bool)`

 SetAttendeeNil sets the value for Attendee to be an explicit nil

### UnsetAttendee
`func (o *TimelineItemCalendarEvent) UnsetAttendee()`

UnsetAttendee ensures that no value is present for Attendee, not even an explicit nil
### GetStatus

`func (o *TimelineItemCalendarEvent) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TimelineItemCalendarEvent) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TimelineItemCalendarEvent) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *TimelineItemCalendarEvent) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *TimelineItemCalendarEvent) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *TimelineItemCalendarEvent) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetLocation

`func (o *TimelineItemCalendarEvent) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *TimelineItemCalendarEvent) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *TimelineItemCalendarEvent) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *TimelineItemCalendarEvent) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### SetLocationNil

`func (o *TimelineItemCalendarEvent) SetLocationNil(b bool)`

 SetLocationNil sets the value for Location to be an explicit nil

### UnsetLocation
`func (o *TimelineItemCalendarEvent) UnsetLocation()`

UnsetLocation ensures that no value is present for Location, not even an explicit nil
### GetType

`func (o *TimelineItemCalendarEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TimelineItemCalendarEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TimelineItemCalendarEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *TimelineItemCalendarEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *TimelineItemCalendarEvent) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *TimelineItemCalendarEvent) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetTags

`func (o *TimelineItemCalendarEvent) GetTags() string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *TimelineItemCalendarEvent) GetTagsOk() (*string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *TimelineItemCalendarEvent) SetTags(v string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *TimelineItemCalendarEvent) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *TimelineItemCalendarEvent) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *TimelineItemCalendarEvent) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil
### GetTrigger

`func (o *TimelineItemCalendarEvent) GetTrigger() string`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *TimelineItemCalendarEvent) GetTriggerOk() (*string, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *TimelineItemCalendarEvent) SetTrigger(v string)`

SetTrigger sets Trigger field to given value.

### HasTrigger

`func (o *TimelineItemCalendarEvent) HasTrigger() bool`

HasTrigger returns a boolean if a field has been set.

### SetTriggerNil

`func (o *TimelineItemCalendarEvent) SetTriggerNil(b bool)`

 SetTriggerNil sets the value for Trigger to be an explicit nil

### UnsetTrigger
`func (o *TimelineItemCalendarEvent) UnsetTrigger()`

UnsetTrigger ensures that no value is present for Trigger, not even an explicit nil
### GetAction

`func (o *TimelineItemCalendarEvent) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *TimelineItemCalendarEvent) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *TimelineItemCalendarEvent) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *TimelineItemCalendarEvent) HasAction() bool`

HasAction returns a boolean if a field has been set.

### SetActionNil

`func (o *TimelineItemCalendarEvent) SetActionNil(b bool)`

 SetActionNil sets the value for Action to be an explicit nil

### UnsetAction
`func (o *TimelineItemCalendarEvent) UnsetAction()`

UnsetAction ensures that no value is present for Action, not even an explicit nil
### GetReminderDescription

`func (o *TimelineItemCalendarEvent) GetReminderDescription() string`

GetReminderDescription returns the ReminderDescription field if non-nil, zero value otherwise.

### GetReminderDescriptionOk

`func (o *TimelineItemCalendarEvent) GetReminderDescriptionOk() (*string, bool)`

GetReminderDescriptionOk returns a tuple with the ReminderDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReminderDescription

`func (o *TimelineItemCalendarEvent) SetReminderDescription(v string)`

SetReminderDescription sets ReminderDescription field to given value.

### HasReminderDescription

`func (o *TimelineItemCalendarEvent) HasReminderDescription() bool`

HasReminderDescription returns a boolean if a field has been set.

### SetReminderDescriptionNil

`func (o *TimelineItemCalendarEvent) SetReminderDescriptionNil(b bool)`

 SetReminderDescriptionNil sets the value for ReminderDescription to be an explicit nil

### UnsetReminderDescription
`func (o *TimelineItemCalendarEvent) UnsetReminderDescription()`

UnsetReminderDescription ensures that no value is present for ReminderDescription, not even an explicit nil
### GetDurationString

`func (o *TimelineItemCalendarEvent) GetDurationString() string`

GetDurationString returns the DurationString field if non-nil, zero value otherwise.

### GetDurationStringOk

`func (o *TimelineItemCalendarEvent) GetDurationStringOk() (*string, bool)`

GetDurationStringOk returns a tuple with the DurationString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationString

`func (o *TimelineItemCalendarEvent) SetDurationString(v string)`

SetDurationString sets DurationString field to given value.

### HasDurationString

`func (o *TimelineItemCalendarEvent) HasDurationString() bool`

HasDurationString returns a boolean if a field has been set.

### GetDurationOfEvent

`func (o *TimelineItemCalendarEvent) GetDurationOfEvent() float32`

GetDurationOfEvent returns the DurationOfEvent field if non-nil, zero value otherwise.

### GetDurationOfEventOk

`func (o *TimelineItemCalendarEvent) GetDurationOfEventOk() (*float32, bool)`

GetDurationOfEventOk returns a tuple with the DurationOfEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationOfEvent

`func (o *TimelineItemCalendarEvent) SetDurationOfEvent(v float32)`

SetDurationOfEvent sets DurationOfEvent field to given value.

### HasDurationOfEvent

`func (o *TimelineItemCalendarEvent) HasDurationOfEvent() bool`

HasDurationOfEvent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


