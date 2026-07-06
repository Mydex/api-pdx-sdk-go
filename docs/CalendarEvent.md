# CalendarEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
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
**ContextName** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCalendarEvent

`func NewCalendarEvent() *CalendarEvent`

NewCalendarEvent instantiates a new CalendarEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCalendarEventWithDefaults

`func NewCalendarEventWithDefaults() *CalendarEvent`

NewCalendarEventWithDefaults instantiates a new CalendarEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CalendarEvent) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CalendarEvent) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CalendarEvent) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CalendarEvent) HasId() bool`

HasId returns a boolean if a field has been set.

### GetInstance

`func (o *CalendarEvent) GetInstance() string`

GetInstance returns the Instance field if non-nil, zero value otherwise.

### GetInstanceOk

`func (o *CalendarEvent) GetInstanceOk() (*string, bool)`

GetInstanceOk returns a tuple with the Instance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstance

`func (o *CalendarEvent) SetInstance(v string)`

SetInstance sets Instance field to given value.

### HasInstance

`func (o *CalendarEvent) HasInstance() bool`

HasInstance returns a boolean if a field has been set.

### GetSource

`func (o *CalendarEvent) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CalendarEvent) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CalendarEvent) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *CalendarEvent) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetCreatedTimestamp

`func (o *CalendarEvent) GetCreatedTimestamp() string`

GetCreatedTimestamp returns the CreatedTimestamp field if non-nil, zero value otherwise.

### GetCreatedTimestampOk

`func (o *CalendarEvent) GetCreatedTimestampOk() (*string, bool)`

GetCreatedTimestampOk returns a tuple with the CreatedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedTimestamp

`func (o *CalendarEvent) SetCreatedTimestamp(v string)`

SetCreatedTimestamp sets CreatedTimestamp field to given value.

### HasCreatedTimestamp

`func (o *CalendarEvent) HasCreatedTimestamp() bool`

HasCreatedTimestamp returns a boolean if a field has been set.

### GetUpdatedTimestamp

`func (o *CalendarEvent) GetUpdatedTimestamp() string`

GetUpdatedTimestamp returns the UpdatedTimestamp field if non-nil, zero value otherwise.

### GetUpdatedTimestampOk

`func (o *CalendarEvent) GetUpdatedTimestampOk() (*string, bool)`

GetUpdatedTimestampOk returns a tuple with the UpdatedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedTimestamp

`func (o *CalendarEvent) SetUpdatedTimestamp(v string)`

SetUpdatedTimestamp sets UpdatedTimestamp field to given value.

### HasUpdatedTimestamp

`func (o *CalendarEvent) HasUpdatedTimestamp() bool`

HasUpdatedTimestamp returns a boolean if a field has been set.

### GetExternalUid

`func (o *CalendarEvent) GetExternalUid() string`

GetExternalUid returns the ExternalUid field if non-nil, zero value otherwise.

### GetExternalUidOk

`func (o *CalendarEvent) GetExternalUidOk() (*string, bool)`

GetExternalUidOk returns a tuple with the ExternalUid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalUid

`func (o *CalendarEvent) SetExternalUid(v string)`

SetExternalUid sets ExternalUid field to given value.

### HasExternalUid

`func (o *CalendarEvent) HasExternalUid() bool`

HasExternalUid returns a boolean if a field has been set.

### SetExternalUidNil

`func (o *CalendarEvent) SetExternalUidNil(b bool)`

 SetExternalUidNil sets the value for ExternalUid to be an explicit nil

### UnsetExternalUid
`func (o *CalendarEvent) UnsetExternalUid()`

UnsetExternalUid ensures that no value is present for ExternalUid, not even an explicit nil
### GetTitle

`func (o *CalendarEvent) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CalendarEvent) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CalendarEvent) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *CalendarEvent) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *CalendarEvent) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *CalendarEvent) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetDescription

`func (o *CalendarEvent) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CalendarEvent) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CalendarEvent) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CalendarEvent) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CalendarEvent) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CalendarEvent) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetStartTimestamp

`func (o *CalendarEvent) GetStartTimestamp() string`

GetStartTimestamp returns the StartTimestamp field if non-nil, zero value otherwise.

### GetStartTimestampOk

`func (o *CalendarEvent) GetStartTimestampOk() (*string, bool)`

GetStartTimestampOk returns a tuple with the StartTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTimestamp

`func (o *CalendarEvent) SetStartTimestamp(v string)`

SetStartTimestamp sets StartTimestamp field to given value.

### HasStartTimestamp

`func (o *CalendarEvent) HasStartTimestamp() bool`

HasStartTimestamp returns a boolean if a field has been set.

### GetEndTimestamp

`func (o *CalendarEvent) GetEndTimestamp() string`

GetEndTimestamp returns the EndTimestamp field if non-nil, zero value otherwise.

### GetEndTimestampOk

`func (o *CalendarEvent) GetEndTimestampOk() (*string, bool)`

GetEndTimestampOk returns a tuple with the EndTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTimestamp

`func (o *CalendarEvent) SetEndTimestamp(v string)`

SetEndTimestamp sets EndTimestamp field to given value.

### HasEndTimestamp

`func (o *CalendarEvent) HasEndTimestamp() bool`

HasEndTimestamp returns a boolean if a field has been set.

### GetOrganiser

`func (o *CalendarEvent) GetOrganiser() string`

GetOrganiser returns the Organiser field if non-nil, zero value otherwise.

### GetOrganiserOk

`func (o *CalendarEvent) GetOrganiserOk() (*string, bool)`

GetOrganiserOk returns a tuple with the Organiser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganiser

`func (o *CalendarEvent) SetOrganiser(v string)`

SetOrganiser sets Organiser field to given value.

### HasOrganiser

`func (o *CalendarEvent) HasOrganiser() bool`

HasOrganiser returns a boolean if a field has been set.

### SetOrganiserNil

`func (o *CalendarEvent) SetOrganiserNil(b bool)`

 SetOrganiserNil sets the value for Organiser to be an explicit nil

### UnsetOrganiser
`func (o *CalendarEvent) UnsetOrganiser()`

UnsetOrganiser ensures that no value is present for Organiser, not even an explicit nil
### GetAttendee

`func (o *CalendarEvent) GetAttendee() string`

GetAttendee returns the Attendee field if non-nil, zero value otherwise.

### GetAttendeeOk

`func (o *CalendarEvent) GetAttendeeOk() (*string, bool)`

GetAttendeeOk returns a tuple with the Attendee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttendee

`func (o *CalendarEvent) SetAttendee(v string)`

SetAttendee sets Attendee field to given value.

### HasAttendee

`func (o *CalendarEvent) HasAttendee() bool`

HasAttendee returns a boolean if a field has been set.

### SetAttendeeNil

`func (o *CalendarEvent) SetAttendeeNil(b bool)`

 SetAttendeeNil sets the value for Attendee to be an explicit nil

### UnsetAttendee
`func (o *CalendarEvent) UnsetAttendee()`

UnsetAttendee ensures that no value is present for Attendee, not even an explicit nil
### GetStatus

`func (o *CalendarEvent) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CalendarEvent) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CalendarEvent) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CalendarEvent) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *CalendarEvent) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *CalendarEvent) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetLocation

`func (o *CalendarEvent) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *CalendarEvent) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *CalendarEvent) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *CalendarEvent) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### SetLocationNil

`func (o *CalendarEvent) SetLocationNil(b bool)`

 SetLocationNil sets the value for Location to be an explicit nil

### UnsetLocation
`func (o *CalendarEvent) UnsetLocation()`

UnsetLocation ensures that no value is present for Location, not even an explicit nil
### GetType

`func (o *CalendarEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CalendarEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CalendarEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CalendarEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *CalendarEvent) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *CalendarEvent) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetTags

`func (o *CalendarEvent) GetTags() string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *CalendarEvent) GetTagsOk() (*string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *CalendarEvent) SetTags(v string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *CalendarEvent) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *CalendarEvent) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *CalendarEvent) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil
### GetTrigger

`func (o *CalendarEvent) GetTrigger() string`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *CalendarEvent) GetTriggerOk() (*string, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *CalendarEvent) SetTrigger(v string)`

SetTrigger sets Trigger field to given value.

### HasTrigger

`func (o *CalendarEvent) HasTrigger() bool`

HasTrigger returns a boolean if a field has been set.

### SetTriggerNil

`func (o *CalendarEvent) SetTriggerNil(b bool)`

 SetTriggerNil sets the value for Trigger to be an explicit nil

### UnsetTrigger
`func (o *CalendarEvent) UnsetTrigger()`

UnsetTrigger ensures that no value is present for Trigger, not even an explicit nil
### GetAction

`func (o *CalendarEvent) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *CalendarEvent) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *CalendarEvent) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *CalendarEvent) HasAction() bool`

HasAction returns a boolean if a field has been set.

### SetActionNil

`func (o *CalendarEvent) SetActionNil(b bool)`

 SetActionNil sets the value for Action to be an explicit nil

### UnsetAction
`func (o *CalendarEvent) UnsetAction()`

UnsetAction ensures that no value is present for Action, not even an explicit nil
### GetReminderDescription

`func (o *CalendarEvent) GetReminderDescription() string`

GetReminderDescription returns the ReminderDescription field if non-nil, zero value otherwise.

### GetReminderDescriptionOk

`func (o *CalendarEvent) GetReminderDescriptionOk() (*string, bool)`

GetReminderDescriptionOk returns a tuple with the ReminderDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReminderDescription

`func (o *CalendarEvent) SetReminderDescription(v string)`

SetReminderDescription sets ReminderDescription field to given value.

### HasReminderDescription

`func (o *CalendarEvent) HasReminderDescription() bool`

HasReminderDescription returns a boolean if a field has been set.

### SetReminderDescriptionNil

`func (o *CalendarEvent) SetReminderDescriptionNil(b bool)`

 SetReminderDescriptionNil sets the value for ReminderDescription to be an explicit nil

### UnsetReminderDescription
`func (o *CalendarEvent) UnsetReminderDescription()`

UnsetReminderDescription ensures that no value is present for ReminderDescription, not even an explicit nil
### GetContextName

`func (o *CalendarEvent) GetContextName() string`

GetContextName returns the ContextName field if non-nil, zero value otherwise.

### GetContextNameOk

`func (o *CalendarEvent) GetContextNameOk() (*string, bool)`

GetContextNameOk returns a tuple with the ContextName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContextName

`func (o *CalendarEvent) SetContextName(v string)`

SetContextName sets ContextName field to given value.

### HasContextName

`func (o *CalendarEvent) HasContextName() bool`

HasContextName returns a boolean if a field has been set.

### SetContextNameNil

`func (o *CalendarEvent) SetContextNameNil(b bool)`

 SetContextNameNil sets the value for ContextName to be an explicit nil

### UnsetContextName
`func (o *CalendarEvent) UnsetContextName()`

UnsetContextName ensures that no value is present for ContextName, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


