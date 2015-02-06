## TreeOutline
+ Wraps TreeElement and
+ Seems to handle expanding and collapsing
+ holding onto a tree element
+ handles keydown

+ subclasses TreeContainerNode
+ @param {!Element} listNode
+ @param {boolean=} nonFocusable+

#### Methods
+ setFocusable
+ getCachedTreeElement
+ _rememberTreeElement
+ _forgetTreeElement
+ _forgetChildrenRecursive
+ _elementExpanded
+ _elementCollapsed
+ _treeKeyDown