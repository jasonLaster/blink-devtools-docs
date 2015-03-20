### InspectorBackendClass.Connection

Used to talk with the DevTools server

#### Sample CallStack
```
InspectorBackendClass.WebSocketConnection._onMessage
InspectorBackendClass.Connection.dispatch
InspectorBackendClass.AgentPrototype.dispatchResponse

```


#### Methods
+ _initialize
+ registerAgentsOn
+ nextMessageId
+ agent
+ agentsMap
+ _wrapCallbackAndSendMessageObject
+ _wrap
+ sendMessage
+ dispatch
+ registerDispatcher
+ runAfterPendingDispatches
+ _executeAfterPendingDispatches
+ _dumpProtocolMessage
+ connectionClosed
+ _runPendingCallbacks
+ _dispatchConnectionErrorResponse
+ isClosed
+ suppressErrorsForDomains
