### DomNode
+ Wraps a dom element
+ Talks to the backend a lot

+ @extends {WebInspector.SDKObject}
+ @param {!WebInspector.DOMModel} domModel
+ @param {?WebInspector.DOMDocument} doc
+ @param {boolean} isInShadowTree
+ @param {!DOMAgent.Node} payload

#### Internal Properties
+ id
+ ownerDocument
+ _domModel
+ _agent
+ _isInShadowTree
+ nextSibling
+ previousSibling
+ firstChild
+ lastChild
+ parentNode
+ publicId
+ systemId
+ internalSubset
+ name
+ value
+ _nodeType
+ _nodeName
+ _localName
+ _nodeValue
+ _pseudoType
+ _shadowRootType
+ _frameId
+ _shadowRoots
+ _attributes
+ _attributesMap
+ _userProperties
+ _descendantUserPropertyCounters
+ _childNodeCount
+ _children
+ _templateContent
+ _templateContent.parentNode
+ _importedDocument
+ _importedDocument.parentNode
+ _contentDocument
+ _children



#### Methods
+ domModel
+ children
+ hasAttributes
+ childNodeCount
+ hasShadowRoots
+ shadowRoots
+ templateContent
+ importedDocument
+ nodeType
+ nodeName
+ pseudoType
+ hasPseudoElements
+ pseudoElements
+ beforePseudoElement
+ afterPseudoElement
+ isInShadowTree
+ ancestorUserAgentShadowRoot
+ isShadowRoot
+ shadowRootType
+ nodeNameInCorrectCase
+ setNodeName
+ localName
+ nodeValue
+ setNodeValue
+ getAttribute
+ setAttribute
+ setAttributeValue
+ attributes
+ removeAttribute
+ getChildNodes
+ getSubtree
+ getOuterHTML
+ setOuterHTML
+ removeNode
+ copyNode
+ eventListeners
+ path
+ isAncestor
+ isDescendant
+ frameId
+ _setAttributesPayload
+ _insertChild
+ _removeChild
+ _setChildrenPayload
+ _setPseudoElements
+ _renumber
+ _addAttribute
+ _setAttribute
+ _removeAttribute
+ copyTo
+ moveTo
+ isXMLNode
+ _updateChildUserPropertyCountsOnRemoval
+ _updateDescendantUserPropertyCount
+ setUserProperty
+ removeUserProperty
+ getUserProperty
+ descendantUserPropertyCount
+ resolveURL
+ highlight
+ highlightForTwoSeconds
+ resolveToObject
+ boxModel