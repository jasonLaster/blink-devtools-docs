
#### instance methods:
#### Callbacks
+ wasShown
+ willHide
+ onTextChanged
+ onTextEditorContentLoaded
+ onHidePopover
+ onKeyDown
+ onSourceMappingChanged
+ onUISourceCodeContentChanged
+ handleGutterClick

#### Commands
+ dispose
+ populateLineGutterContextMenu
+ populateTextAreaContextMenu
+ setExecutionLine
+ clearExecutionLine

#### Helpers
+ workingCopyChanged
+ workingCopyCommitted
+ didMergeToVM
+ didDivergeFromVM
+ updateDivergedInfobar
+ getPopoverAnchor
+ resolveObjectForPopover
+ createConditionElement
+ updateLinesWithoutMappingHighlight
+ updateScriptFile
+ continueToLine
+ updateInfobars
+ registerShortcuts
+ addCurrentSelectionToWatch
+ innerAddToWatch
+ evaluateSelectionInConsole

##### Infobar
+ showDivergedInfobar
+ hideDivergedInfobar
+ showBlackboxInfobarIfNeeded
+ hideBlackboxInfobar

##### Console
+ evaluateInConsole
+ consoleMessageAdded
+ consoleMessageRemoved
+ sourceFrameMessage
+ consoleMessagesCleared

##### Breakpoints
+ restoreBreakpointsIfConsistentScripts
+ restoreBreakpointsAfterEditing
+ removeAllBreakpoints
+ addBreakpointDecoration
+ removeBreakpointDecoration
+ editBreakpointCondition
+ shouldIgnoreExternalBreakpointEvents
+ breakpointAdded
+ breakpointRemoved
+ toggleBreakpoint
+ createNewBreakpoint
+ setBreakpoint
+ toggleBreakpointOnCurrentLine
+ muteBreakpointsWhileEditing
+ supportsEnabledBreakpointsWhileEditing
