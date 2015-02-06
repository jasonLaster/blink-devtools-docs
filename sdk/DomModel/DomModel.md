
## DomModel

* @param {!WebInspector.Target} target

+ subclass of WebInspector.SDKModel
+ holds a domAgent, which it talks to for the backend
+ seems to wrap a DomNode - like it'll `requestNode` and do searches...

#### methods

#### Getters
+ existingDocument
+ nodeForId
+ nodeForLocation

#### Commands
+ requestDocument
+ performSearch
+ performSearchPromise
+ searchResult
+ cancelSearch
+ querySelector
+ querySelectorAll
+ highlightDOMNode
+ highlightDOMNodeWithConfig
+ hideDOMNodeHighlight
+ highlightDOMNodeForTwoSeconds
+ _setDocument
+ _setDetachedRoot
+ _setChildNodes
+ pushNodeToFrontend
+ pushNodeByPathToFrontend
+ pushNodesByBackendIdsToFrontend
+ _buildHighlightConfig
+ undo
+ redo
+ setHighlighter
+ _unbind
+ _markRevision
+ emulateTouchEventObjects
+ markUndoableState
+ suspendModel
+ resumeModel
+ _wrapClientCallback
+ _dispatchWhenDocumentAvailable

#### Event Callbacks
+ _attributeModified
+ _attributeRemoved
+ _inlineStyleInvalidated
+ _shadowHostDistributionInvalidated
+ _loadNodeAttributes
+ _characterDataModified
+ _childNodeInserted
+ _childNodeRemoved
+ _shadowRootPushed
+ _shadowRootPopped
+ _pseudoElementAdded
+ _pseudoElementRemoved
+ setInspectModeEnabled
+ _documentUpdated
+ _childNodeCountUpdated
+ _inspectNodeRequested



