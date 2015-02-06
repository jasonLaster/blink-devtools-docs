## TreeElement

+ subclass of TreeContainerNode
+ @param {string|!Node} title
+ @param {?Object=} representedObject
+ @param {boolean=} hasChildren


#### Internal Properties
+ root
+ _hidden
+ _selectable
+ expanded
+ selected
+ hasChildren
+ treeOutline
+ parent
+ previousSibling
+ nextSibling
+ _listItemNode

#### Methods:

#### commands
+ collapse
+ collapseRecursively
+ expand
+ expandRecursively
+ reveal
+ selectOnMouseDown
+ select
+ revealAndSelect
+ deselect
+ traverseNextTreeElement
+ traversePreviousTreeElement

#### getters
+ selectable
+ listItemElement
+ childrenListElement
+ title
+ tooltip
+ revealed
+ isEventWithinDisclosureTriangle
+ hasChildren
+ hidden
+ shouldRefreshChildren
+ elementIdentity

#### Setters
+ setHasChildren

#### event callbacks
+ onpopulate
+ onenter
+ ondelete
+ onspace
+ onattach
+ onexpand
+ oncollapse
+ ondblclick
+ onreveal
+ onselect

#### private methods
+ _setListItemNodeContent
+ _attach
+ _treeElementToggled
+ _handleMouseDown
+ _handleDoubleClick
+ _detach
