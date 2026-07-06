# SecureMessageReceiveRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MessageContent** | **string** | Content of the message | 
**ConversationId** | **string** | ID of the conversation formatted like {context}-{context_id} where context is e.g. &#39;referral&#39; and context_id is the id of the specifc record in that context. | 
**MessageFrom** | **string** | Sender user ID | 

## Methods

### NewSecureMessageReceiveRequest

`func NewSecureMessageReceiveRequest(messageContent string, conversationId string, messageFrom string, ) *SecureMessageReceiveRequest`

NewSecureMessageReceiveRequest instantiates a new SecureMessageReceiveRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSecureMessageReceiveRequestWithDefaults

`func NewSecureMessageReceiveRequestWithDefaults() *SecureMessageReceiveRequest`

NewSecureMessageReceiveRequestWithDefaults instantiates a new SecureMessageReceiveRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessageContent

`func (o *SecureMessageReceiveRequest) GetMessageContent() string`

GetMessageContent returns the MessageContent field if non-nil, zero value otherwise.

### GetMessageContentOk

`func (o *SecureMessageReceiveRequest) GetMessageContentOk() (*string, bool)`

GetMessageContentOk returns a tuple with the MessageContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageContent

`func (o *SecureMessageReceiveRequest) SetMessageContent(v string)`

SetMessageContent sets MessageContent field to given value.


### GetConversationId

`func (o *SecureMessageReceiveRequest) GetConversationId() string`

GetConversationId returns the ConversationId field if non-nil, zero value otherwise.

### GetConversationIdOk

`func (o *SecureMessageReceiveRequest) GetConversationIdOk() (*string, bool)`

GetConversationIdOk returns a tuple with the ConversationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversationId

`func (o *SecureMessageReceiveRequest) SetConversationId(v string)`

SetConversationId sets ConversationId field to given value.


### GetMessageFrom

`func (o *SecureMessageReceiveRequest) GetMessageFrom() string`

GetMessageFrom returns the MessageFrom field if non-nil, zero value otherwise.

### GetMessageFromOk

`func (o *SecureMessageReceiveRequest) GetMessageFromOk() (*string, bool)`

GetMessageFromOk returns a tuple with the MessageFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageFrom

`func (o *SecureMessageReceiveRequest) SetMessageFrom(v string)`

SetMessageFrom sets MessageFrom field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


