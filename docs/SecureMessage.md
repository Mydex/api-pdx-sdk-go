# SecureMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Message ID | [optional] 
**ConversationId** | Pointer to **string** | Conversation identifier | [optional] 
**MessageTo** | Pointer to **string** | Recipient of the message (present on sent messages) | [optional] 
**MessageFrom** | Pointer to **string** | Sender of the message (present on received messages) | [optional] 
**TimeSent** | Pointer to **string** | Timestamp when message was sent | [optional] 
**TimeReceived** | Pointer to **string** | Timestamp when message was received | [optional] 
**MessageContent** | Pointer to **string** | Content of the message | [optional] 
**Status** | Pointer to **string** | Message status | [optional] 

## Methods

### NewSecureMessage

`func NewSecureMessage() *SecureMessage`

NewSecureMessage instantiates a new SecureMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSecureMessageWithDefaults

`func NewSecureMessageWithDefaults() *SecureMessage`

NewSecureMessageWithDefaults instantiates a new SecureMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SecureMessage) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SecureMessage) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SecureMessage) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SecureMessage) HasId() bool`

HasId returns a boolean if a field has been set.

### GetConversationId

`func (o *SecureMessage) GetConversationId() string`

GetConversationId returns the ConversationId field if non-nil, zero value otherwise.

### GetConversationIdOk

`func (o *SecureMessage) GetConversationIdOk() (*string, bool)`

GetConversationIdOk returns a tuple with the ConversationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversationId

`func (o *SecureMessage) SetConversationId(v string)`

SetConversationId sets ConversationId field to given value.

### HasConversationId

`func (o *SecureMessage) HasConversationId() bool`

HasConversationId returns a boolean if a field has been set.

### GetMessageTo

`func (o *SecureMessage) GetMessageTo() string`

GetMessageTo returns the MessageTo field if non-nil, zero value otherwise.

### GetMessageToOk

`func (o *SecureMessage) GetMessageToOk() (*string, bool)`

GetMessageToOk returns a tuple with the MessageTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageTo

`func (o *SecureMessage) SetMessageTo(v string)`

SetMessageTo sets MessageTo field to given value.

### HasMessageTo

`func (o *SecureMessage) HasMessageTo() bool`

HasMessageTo returns a boolean if a field has been set.

### GetMessageFrom

`func (o *SecureMessage) GetMessageFrom() string`

GetMessageFrom returns the MessageFrom field if non-nil, zero value otherwise.

### GetMessageFromOk

`func (o *SecureMessage) GetMessageFromOk() (*string, bool)`

GetMessageFromOk returns a tuple with the MessageFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageFrom

`func (o *SecureMessage) SetMessageFrom(v string)`

SetMessageFrom sets MessageFrom field to given value.

### HasMessageFrom

`func (o *SecureMessage) HasMessageFrom() bool`

HasMessageFrom returns a boolean if a field has been set.

### GetTimeSent

`func (o *SecureMessage) GetTimeSent() string`

GetTimeSent returns the TimeSent field if non-nil, zero value otherwise.

### GetTimeSentOk

`func (o *SecureMessage) GetTimeSentOk() (*string, bool)`

GetTimeSentOk returns a tuple with the TimeSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSent

`func (o *SecureMessage) SetTimeSent(v string)`

SetTimeSent sets TimeSent field to given value.

### HasTimeSent

`func (o *SecureMessage) HasTimeSent() bool`

HasTimeSent returns a boolean if a field has been set.

### GetTimeReceived

`func (o *SecureMessage) GetTimeReceived() string`

GetTimeReceived returns the TimeReceived field if non-nil, zero value otherwise.

### GetTimeReceivedOk

`func (o *SecureMessage) GetTimeReceivedOk() (*string, bool)`

GetTimeReceivedOk returns a tuple with the TimeReceived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeReceived

`func (o *SecureMessage) SetTimeReceived(v string)`

SetTimeReceived sets TimeReceived field to given value.

### HasTimeReceived

`func (o *SecureMessage) HasTimeReceived() bool`

HasTimeReceived returns a boolean if a field has been set.

### GetMessageContent

`func (o *SecureMessage) GetMessageContent() string`

GetMessageContent returns the MessageContent field if non-nil, zero value otherwise.

### GetMessageContentOk

`func (o *SecureMessage) GetMessageContentOk() (*string, bool)`

GetMessageContentOk returns a tuple with the MessageContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageContent

`func (o *SecureMessage) SetMessageContent(v string)`

SetMessageContent sets MessageContent field to given value.

### HasMessageContent

`func (o *SecureMessage) HasMessageContent() bool`

HasMessageContent returns a boolean if a field has been set.

### GetStatus

`func (o *SecureMessage) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SecureMessage) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SecureMessage) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SecureMessage) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


