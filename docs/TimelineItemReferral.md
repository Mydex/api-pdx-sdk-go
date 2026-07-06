# TimelineItemReferral

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FeatureBlock** | Pointer to **string** | Type of feature block this timeline item belongs to | [optional] 
**FeatureBlockId** | Pointer to **int32** | ID of the feature block record i.e. the referral id | [optional] 
**Instance** | Pointer to **string** |  | [optional] 
**Source** | Pointer to **string** | The context within which this record was created i.e. the specific connection | [optional] 
**CreatedTimestamp** | Pointer to **int64** |  | [optional] 
**UpdatedTimestamp** | Pointer to **int64** |  | [optional] 
**ServiceId** | Pointer to **int32** | The id of the service that the referral relates to | [optional] 
**ServiceName** | Pointer to **string** |  | [optional] 
**ServiceDescription** | Pointer to **string** |  | [optional] 
**ServiceUrl** | Pointer to **string** |  | [optional] 
**ServiceEmail** | Pointer to **string** |  | [optional] 
**ContactName** | Pointer to **string** |  | [optional] 
**ContactTitle** | Pointer to **string** |  | [optional] 
**ContactNumber** | Pointer to **string** |  | [optional] 
**ReferrerName** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
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
**Type** | Pointer to **string** |  | [optional] 
**StartTimestamp** | Pointer to **string** |  | [optional] 

## Methods

### NewTimelineItemReferral

`func NewTimelineItemReferral() *TimelineItemReferral`

NewTimelineItemReferral instantiates a new TimelineItemReferral object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimelineItemReferralWithDefaults

`func NewTimelineItemReferralWithDefaults() *TimelineItemReferral`

NewTimelineItemReferralWithDefaults instantiates a new TimelineItemReferral object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFeatureBlock

`func (o *TimelineItemReferral) GetFeatureBlock() string`

GetFeatureBlock returns the FeatureBlock field if non-nil, zero value otherwise.

### GetFeatureBlockOk

`func (o *TimelineItemReferral) GetFeatureBlockOk() (*string, bool)`

GetFeatureBlockOk returns a tuple with the FeatureBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureBlock

`func (o *TimelineItemReferral) SetFeatureBlock(v string)`

SetFeatureBlock sets FeatureBlock field to given value.

### HasFeatureBlock

`func (o *TimelineItemReferral) HasFeatureBlock() bool`

HasFeatureBlock returns a boolean if a field has been set.

### GetFeatureBlockId

`func (o *TimelineItemReferral) GetFeatureBlockId() int32`

GetFeatureBlockId returns the FeatureBlockId field if non-nil, zero value otherwise.

### GetFeatureBlockIdOk

`func (o *TimelineItemReferral) GetFeatureBlockIdOk() (*int32, bool)`

GetFeatureBlockIdOk returns a tuple with the FeatureBlockId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureBlockId

`func (o *TimelineItemReferral) SetFeatureBlockId(v int32)`

SetFeatureBlockId sets FeatureBlockId field to given value.

### HasFeatureBlockId

`func (o *TimelineItemReferral) HasFeatureBlockId() bool`

HasFeatureBlockId returns a boolean if a field has been set.

### GetInstance

`func (o *TimelineItemReferral) GetInstance() string`

GetInstance returns the Instance field if non-nil, zero value otherwise.

### GetInstanceOk

`func (o *TimelineItemReferral) GetInstanceOk() (*string, bool)`

GetInstanceOk returns a tuple with the Instance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstance

`func (o *TimelineItemReferral) SetInstance(v string)`

SetInstance sets Instance field to given value.

### HasInstance

`func (o *TimelineItemReferral) HasInstance() bool`

HasInstance returns a boolean if a field has been set.

### GetSource

`func (o *TimelineItemReferral) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *TimelineItemReferral) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *TimelineItemReferral) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *TimelineItemReferral) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetCreatedTimestamp

`func (o *TimelineItemReferral) GetCreatedTimestamp() int64`

GetCreatedTimestamp returns the CreatedTimestamp field if non-nil, zero value otherwise.

### GetCreatedTimestampOk

`func (o *TimelineItemReferral) GetCreatedTimestampOk() (*int64, bool)`

GetCreatedTimestampOk returns a tuple with the CreatedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedTimestamp

`func (o *TimelineItemReferral) SetCreatedTimestamp(v int64)`

SetCreatedTimestamp sets CreatedTimestamp field to given value.

### HasCreatedTimestamp

`func (o *TimelineItemReferral) HasCreatedTimestamp() bool`

HasCreatedTimestamp returns a boolean if a field has been set.

### GetUpdatedTimestamp

`func (o *TimelineItemReferral) GetUpdatedTimestamp() int64`

GetUpdatedTimestamp returns the UpdatedTimestamp field if non-nil, zero value otherwise.

### GetUpdatedTimestampOk

`func (o *TimelineItemReferral) GetUpdatedTimestampOk() (*int64, bool)`

GetUpdatedTimestampOk returns a tuple with the UpdatedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedTimestamp

`func (o *TimelineItemReferral) SetUpdatedTimestamp(v int64)`

SetUpdatedTimestamp sets UpdatedTimestamp field to given value.

### HasUpdatedTimestamp

`func (o *TimelineItemReferral) HasUpdatedTimestamp() bool`

HasUpdatedTimestamp returns a boolean if a field has been set.

### GetServiceId

`func (o *TimelineItemReferral) GetServiceId() int32`

GetServiceId returns the ServiceId field if non-nil, zero value otherwise.

### GetServiceIdOk

`func (o *TimelineItemReferral) GetServiceIdOk() (*int32, bool)`

GetServiceIdOk returns a tuple with the ServiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceId

`func (o *TimelineItemReferral) SetServiceId(v int32)`

SetServiceId sets ServiceId field to given value.

### HasServiceId

`func (o *TimelineItemReferral) HasServiceId() bool`

HasServiceId returns a boolean if a field has been set.

### GetServiceName

`func (o *TimelineItemReferral) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *TimelineItemReferral) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *TimelineItemReferral) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.

### HasServiceName

`func (o *TimelineItemReferral) HasServiceName() bool`

HasServiceName returns a boolean if a field has been set.

### GetServiceDescription

`func (o *TimelineItemReferral) GetServiceDescription() string`

GetServiceDescription returns the ServiceDescription field if non-nil, zero value otherwise.

### GetServiceDescriptionOk

`func (o *TimelineItemReferral) GetServiceDescriptionOk() (*string, bool)`

GetServiceDescriptionOk returns a tuple with the ServiceDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceDescription

`func (o *TimelineItemReferral) SetServiceDescription(v string)`

SetServiceDescription sets ServiceDescription field to given value.

### HasServiceDescription

`func (o *TimelineItemReferral) HasServiceDescription() bool`

HasServiceDescription returns a boolean if a field has been set.

### GetServiceUrl

`func (o *TimelineItemReferral) GetServiceUrl() string`

GetServiceUrl returns the ServiceUrl field if non-nil, zero value otherwise.

### GetServiceUrlOk

`func (o *TimelineItemReferral) GetServiceUrlOk() (*string, bool)`

GetServiceUrlOk returns a tuple with the ServiceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceUrl

`func (o *TimelineItemReferral) SetServiceUrl(v string)`

SetServiceUrl sets ServiceUrl field to given value.

### HasServiceUrl

`func (o *TimelineItemReferral) HasServiceUrl() bool`

HasServiceUrl returns a boolean if a field has been set.

### GetServiceEmail

`func (o *TimelineItemReferral) GetServiceEmail() string`

GetServiceEmail returns the ServiceEmail field if non-nil, zero value otherwise.

### GetServiceEmailOk

`func (o *TimelineItemReferral) GetServiceEmailOk() (*string, bool)`

GetServiceEmailOk returns a tuple with the ServiceEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceEmail

`func (o *TimelineItemReferral) SetServiceEmail(v string)`

SetServiceEmail sets ServiceEmail field to given value.

### HasServiceEmail

`func (o *TimelineItemReferral) HasServiceEmail() bool`

HasServiceEmail returns a boolean if a field has been set.

### GetContactName

`func (o *TimelineItemReferral) GetContactName() string`

GetContactName returns the ContactName field if non-nil, zero value otherwise.

### GetContactNameOk

`func (o *TimelineItemReferral) GetContactNameOk() (*string, bool)`

GetContactNameOk returns a tuple with the ContactName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactName

`func (o *TimelineItemReferral) SetContactName(v string)`

SetContactName sets ContactName field to given value.

### HasContactName

`func (o *TimelineItemReferral) HasContactName() bool`

HasContactName returns a boolean if a field has been set.

### GetContactTitle

`func (o *TimelineItemReferral) GetContactTitle() string`

GetContactTitle returns the ContactTitle field if non-nil, zero value otherwise.

### GetContactTitleOk

`func (o *TimelineItemReferral) GetContactTitleOk() (*string, bool)`

GetContactTitleOk returns a tuple with the ContactTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactTitle

`func (o *TimelineItemReferral) SetContactTitle(v string)`

SetContactTitle sets ContactTitle field to given value.

### HasContactTitle

`func (o *TimelineItemReferral) HasContactTitle() bool`

HasContactTitle returns a boolean if a field has been set.

### GetContactNumber

`func (o *TimelineItemReferral) GetContactNumber() string`

GetContactNumber returns the ContactNumber field if non-nil, zero value otherwise.

### GetContactNumberOk

`func (o *TimelineItemReferral) GetContactNumberOk() (*string, bool)`

GetContactNumberOk returns a tuple with the ContactNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactNumber

`func (o *TimelineItemReferral) SetContactNumber(v string)`

SetContactNumber sets ContactNumber field to given value.

### HasContactNumber

`func (o *TimelineItemReferral) HasContactNumber() bool`

HasContactNumber returns a boolean if a field has been set.

### GetReferrerName

`func (o *TimelineItemReferral) GetReferrerName() string`

GetReferrerName returns the ReferrerName field if non-nil, zero value otherwise.

### GetReferrerNameOk

`func (o *TimelineItemReferral) GetReferrerNameOk() (*string, bool)`

GetReferrerNameOk returns a tuple with the ReferrerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferrerName

`func (o *TimelineItemReferral) SetReferrerName(v string)`

SetReferrerName sets ReferrerName field to given value.

### HasReferrerName

`func (o *TimelineItemReferral) HasReferrerName() bool`

HasReferrerName returns a boolean if a field has been set.

### GetStatus

`func (o *TimelineItemReferral) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TimelineItemReferral) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TimelineItemReferral) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *TimelineItemReferral) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetExternalId

`func (o *TimelineItemReferral) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *TimelineItemReferral) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *TimelineItemReferral) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *TimelineItemReferral) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### GetStartTime

`func (o *TimelineItemReferral) GetStartTime() int64`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *TimelineItemReferral) GetStartTimeOk() (*int64, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *TimelineItemReferral) SetStartTime(v int64)`

SetStartTime sets StartTime field to given value.

### HasStartTime

`func (o *TimelineItemReferral) HasStartTime() bool`

HasStartTime returns a boolean if a field has been set.

### GetEndTime

`func (o *TimelineItemReferral) GetEndTime() int64`

GetEndTime returns the EndTime field if non-nil, zero value otherwise.

### GetEndTimeOk

`func (o *TimelineItemReferral) GetEndTimeOk() (*int64, bool)`

GetEndTimeOk returns a tuple with the EndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTime

`func (o *TimelineItemReferral) SetEndTime(v int64)`

SetEndTime sets EndTime field to given value.

### HasEndTime

`func (o *TimelineItemReferral) HasEndTime() bool`

HasEndTime returns a boolean if a field has been set.

### GetIsProcessed

`func (o *TimelineItemReferral) GetIsProcessed() bool`

GetIsProcessed returns the IsProcessed field if non-nil, zero value otherwise.

### GetIsProcessedOk

`func (o *TimelineItemReferral) GetIsProcessedOk() (*bool, bool)`

GetIsProcessedOk returns a tuple with the IsProcessed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsProcessed

`func (o *TimelineItemReferral) SetIsProcessed(v bool)`

SetIsProcessed sets IsProcessed field to given value.

### HasIsProcessed

`func (o *TimelineItemReferral) HasIsProcessed() bool`

HasIsProcessed returns a boolean if a field has been set.

### GetCompleteTime

`func (o *TimelineItemReferral) GetCompleteTime() int32`

GetCompleteTime returns the CompleteTime field if non-nil, zero value otherwise.

### GetCompleteTimeOk

`func (o *TimelineItemReferral) GetCompleteTimeOk() (*int32, bool)`

GetCompleteTimeOk returns a tuple with the CompleteTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompleteTime

`func (o *TimelineItemReferral) SetCompleteTime(v int32)`

SetCompleteTime sets CompleteTime field to given value.

### HasCompleteTime

`func (o *TimelineItemReferral) HasCompleteTime() bool`

HasCompleteTime returns a boolean if a field has been set.

### GetMemo

`func (o *TimelineItemReferral) GetMemo() string`

GetMemo returns the Memo field if non-nil, zero value otherwise.

### GetMemoOk

`func (o *TimelineItemReferral) GetMemoOk() (*string, bool)`

GetMemoOk returns a tuple with the Memo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemo

`func (o *TimelineItemReferral) SetMemo(v string)`

SetMemo sets Memo field to given value.

### HasMemo

`func (o *TimelineItemReferral) HasMemo() bool`

HasMemo returns a boolean if a field has been set.

### GetDuration

`func (o *TimelineItemReferral) GetDuration() string`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *TimelineItemReferral) GetDurationOk() (*string, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *TimelineItemReferral) SetDuration(v string)`

SetDuration sets Duration field to given value.

### HasDuration

`func (o *TimelineItemReferral) HasDuration() bool`

HasDuration returns a boolean if a field has been set.

### GetReferreeBackground

`func (o *TimelineItemReferral) GetReferreeBackground() string`

GetReferreeBackground returns the ReferreeBackground field if non-nil, zero value otherwise.

### GetReferreeBackgroundOk

`func (o *TimelineItemReferral) GetReferreeBackgroundOk() (*string, bool)`

GetReferreeBackgroundOk returns a tuple with the ReferreeBackground field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferreeBackground

`func (o *TimelineItemReferral) SetReferreeBackground(v string)`

SetReferreeBackground sets ReferreeBackground field to given value.

### HasReferreeBackground

`func (o *TimelineItemReferral) HasReferreeBackground() bool`

HasReferreeBackground returns a boolean if a field has been set.

### GetReferreeRequirements

`func (o *TimelineItemReferral) GetReferreeRequirements() string`

GetReferreeRequirements returns the ReferreeRequirements field if non-nil, zero value otherwise.

### GetReferreeRequirementsOk

`func (o *TimelineItemReferral) GetReferreeRequirementsOk() (*string, bool)`

GetReferreeRequirementsOk returns a tuple with the ReferreeRequirements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferreeRequirements

`func (o *TimelineItemReferral) SetReferreeRequirements(v string)`

SetReferreeRequirements sets ReferreeRequirements field to given value.

### HasReferreeRequirements

`func (o *TimelineItemReferral) HasReferreeRequirements() bool`

HasReferreeRequirements returns a boolean if a field has been set.

### GetReferreeAvailability

`func (o *TimelineItemReferral) GetReferreeAvailability() map[string]interface{}`

GetReferreeAvailability returns the ReferreeAvailability field if non-nil, zero value otherwise.

### GetReferreeAvailabilityOk

`func (o *TimelineItemReferral) GetReferreeAvailabilityOk() (*map[string]interface{}, bool)`

GetReferreeAvailabilityOk returns a tuple with the ReferreeAvailability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferreeAvailability

`func (o *TimelineItemReferral) SetReferreeAvailability(v map[string]interface{})`

SetReferreeAvailability sets ReferreeAvailability field to given value.

### HasReferreeAvailability

`func (o *TimelineItemReferral) HasReferreeAvailability() bool`

HasReferreeAvailability returns a boolean if a field has been set.

### GetType

`func (o *TimelineItemReferral) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TimelineItemReferral) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TimelineItemReferral) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *TimelineItemReferral) HasType() bool`

HasType returns a boolean if a field has been set.

### GetStartTimestamp

`func (o *TimelineItemReferral) GetStartTimestamp() string`

GetStartTimestamp returns the StartTimestamp field if non-nil, zero value otherwise.

### GetStartTimestampOk

`func (o *TimelineItemReferral) GetStartTimestampOk() (*string, bool)`

GetStartTimestampOk returns a tuple with the StartTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTimestamp

`func (o *TimelineItemReferral) SetStartTimestamp(v string)`

SetStartTimestamp sets StartTimestamp field to given value.

### HasStartTimestamp

`func (o *TimelineItemReferral) HasStartTimestamp() bool`

HasStartTimestamp returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


