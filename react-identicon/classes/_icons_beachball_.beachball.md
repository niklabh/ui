[Polkadot JS UI libraries](../README.md) › [Globals](../globals.md) › ["icons/Beachball"](../modules/_icons_beachball_.md) › [Beachball](_icons_beachball_.beachball.md)

# Class: Beachball <**S, SS**>

## Type parameters

▪ **S**

▪ **SS**

## Hierarchy

* PureComponent‹[Props](../interfaces/_types_.props.md)›

  ↳ **Beachball**

## Index

### Methods

* [UNSAFE_componentWillMount](_icons_beachball_.beachball.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_icons_beachball_.beachball.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_icons_beachball_.beachball.md#optional-unsafe_componentwillupdate)
* [componentDidCatch](_icons_beachball_.beachball.md#optional-componentdidcatch)
* [componentDidMount](_icons_beachball_.beachball.md#optional-componentdidmount)
* [componentDidUpdate](_icons_beachball_.beachball.md#optional-componentdidupdate)
* [componentWillMount](_icons_beachball_.beachball.md#optional-componentwillmount)
* [componentWillReceiveProps](_icons_beachball_.beachball.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_icons_beachball_.beachball.md#optional-componentwillunmount)
* [componentWillUpdate](_icons_beachball_.beachball.md#optional-componentwillupdate)
* [getSnapshotBeforeUpdate](_icons_beachball_.beachball.md#optional-getsnapshotbeforeupdate)
* [render](_icons_beachball_.beachball.md#render)
* [shouldComponentUpdate](_icons_beachball_.beachball.md#optional-shouldcomponentupdate)

## Methods

### `Optional` UNSAFE_componentWillMount

▸ **UNSAFE_componentWillMount**(): *void*

*Inherited from [Beachball](_icons_beachball_.beachball.md).[UNSAFE_componentWillMount](_icons_beachball_.beachball.md#optional-unsafe_componentwillmount)*

Defined in node_modules/@types/react/index.d.ts:660

Called immediately before mounting occurs, and before `Component#render`.
Avoid introducing any side-effects or subscriptions in this method.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use componentDidMount or the constructor instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#initializing-state

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillReceiveProps

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹[Props](../interfaces/_types_.props.md)›, `nextContext`: any): *void*

*Inherited from [Beachball](_icons_beachball_.beachball.md).[UNSAFE_componentWillReceiveProps](_icons_beachball_.beachball.md#optional-unsafe_componentwillreceiveprops)*

Defined in node_modules/@types/react/index.d.ts:692

Called when the component may be receiving new props.
React may call this even if props have not changed, so be sure to compare new and existing
props if you only want to handle changes.

Calling `Component#setState` generally does not trigger this method.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use static getDerivedStateFromProps instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#updating-state-based-on-props

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹[Props](../interfaces/_types_.props.md)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹[Props](../interfaces/_types_.props.md)›, `nextState`: Readonly‹S›, `nextContext`: any): *void*

*Inherited from [Beachball](_icons_beachball_.beachball.md).[UNSAFE_componentWillUpdate](_icons_beachball_.beachball.md#optional-unsafe_componentwillupdate)*

Defined in node_modules/@types/react/index.d.ts:720

Called immediately before rendering when new props or state is received. Not called for the initial render.

Note: You cannot call `Component#setState` here.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use getSnapshotBeforeUpdate instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#reading-dom-properties-before-an-update

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹[Props](../interfaces/_types_.props.md)› |
`nextState` | Readonly‹S› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` componentDidCatch

▸ **componentDidCatch**(`error`: Error, `errorInfo`: ErrorInfo): *void*

*Inherited from [Beachball](_icons_beachball_.beachball.md).[componentDidCatch](_icons_beachball_.beachball.md#optional-componentdidcatch)*

Defined in node_modules/@types/react/index.d.ts:589

Catches exceptions generated in descendant components. Unhandled exceptions will cause
the entire component tree to unmount.

**Parameters:**

Name | Type |
------ | ------ |
`error` | Error |
`errorInfo` | ErrorInfo |

**Returns:** *void*

___

### `Optional` componentDidMount

▸ **componentDidMount**(): *void*

*Inherited from [Beachball](_icons_beachball_.beachball.md).[componentDidMount](_icons_beachball_.beachball.md#optional-componentdidmount)*

Defined in node_modules/@types/react/index.d.ts:568

Called immediately after a component is mounted. Setting state here will trigger re-rendering.

**Returns:** *void*

___

### `Optional` componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: Readonly‹[Props](../interfaces/_types_.props.md)›, `prevState`: Readonly‹S›, `snapshot?`: SS): *void*

*Inherited from [Beachball](_icons_beachball_.beachball.md).[componentDidUpdate](_icons_beachball_.beachball.md#optional-componentdidupdate)*

Defined in node_modules/@types/react/index.d.ts:631

Called immediately after updating occurs. Not called for the initial render.

The snapshot is only present if getSnapshotBeforeUpdate is present and returns non-null.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹[Props](../interfaces/_types_.props.md)› |
`prevState` | Readonly‹S› |
`snapshot?` | SS |

**Returns:** *void*

___

### `Optional` componentWillMount

▸ **componentWillMount**(): *void*

*Inherited from [Beachball](_icons_beachball_.beachball.md).[componentWillMount](_icons_beachball_.beachball.md#optional-componentwillmount)*

Defined in node_modules/@types/react/index.d.ts:646

Called immediately before mounting occurs, and before `Component#render`.
Avoid introducing any side-effects or subscriptions in this method.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use componentDidMount or the constructor instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#initializing-state

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Returns:** *void*

___

### `Optional` componentWillReceiveProps

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹[Props](../interfaces/_types_.props.md)›, `nextContext`: any): *void*

*Inherited from [Beachball](_icons_beachball_.beachball.md).[componentWillReceiveProps](_icons_beachball_.beachball.md#optional-componentwillreceiveprops)*

Defined in node_modules/@types/react/index.d.ts:675

Called when the component may be receiving new props.
React may call this even if props have not changed, so be sure to compare new and existing
props if you only want to handle changes.

Calling `Component#setState` generally does not trigger this method.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use static getDerivedStateFromProps instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#updating-state-based-on-props

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹[Props](../interfaces/_types_.props.md)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` componentWillUnmount

▸ **componentWillUnmount**(): *void*

*Inherited from [Beachball](_icons_beachball_.beachball.md).[componentWillUnmount](_icons_beachball_.beachball.md#optional-componentwillunmount)*

Defined in node_modules/@types/react/index.d.ts:584

Called immediately before a component is destroyed. Perform any necessary cleanup in this method, such as
cancelled network requests, or cleaning up any DOM elements created in `componentDidMount`.

**Returns:** *void*

___

### `Optional` componentWillUpdate

▸ **componentWillUpdate**(`nextProps`: Readonly‹[Props](../interfaces/_types_.props.md)›, `nextState`: Readonly‹S›, `nextContext`: any): *void*

*Inherited from [Beachball](_icons_beachball_.beachball.md).[componentWillUpdate](_icons_beachball_.beachball.md#optional-componentwillupdate)*

Defined in node_modules/@types/react/index.d.ts:705

Called immediately before rendering when new props or state is received. Not called for the initial render.

Note: You cannot call `Component#setState` here.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use getSnapshotBeforeUpdate instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#reading-dom-properties-before-an-update

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹[Props](../interfaces/_types_.props.md)› |
`nextState` | Readonly‹S› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹[Props](../interfaces/_types_.props.md)›, `prevState`: Readonly‹S›): *SS | null*

*Inherited from [Beachball](_icons_beachball_.beachball.md).[getSnapshotBeforeUpdate](_icons_beachball_.beachball.md#optional-getsnapshotbeforeupdate)*

Defined in node_modules/@types/react/index.d.ts:625

Runs before React applies the result of `render` to the document, and
returns an object to be given to componentDidUpdate. Useful for saving
things such as scroll position before `render` causes changes to it.

Note: the presence of getSnapshotBeforeUpdate prevents any of the deprecated
lifecycle events from running.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹[Props](../interfaces/_types_.props.md)› |
`prevState` | Readonly‹S› |

**Returns:** *SS | null*

___

###  render

▸ **render**(): *React.ReactNode*

*Defined in [packages/react-identicon/src/icons/Beachball.tsx:11](https://github.com/polkadot-js/ui/blob/9579e6b7/packages/react-identicon/src/icons/Beachball.tsx#L11)*

**Returns:** *React.ReactNode*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹[Props](../interfaces/_types_.props.md)›, `nextState`: Readonly‹S›, `nextContext`: any): *boolean*

*Inherited from [Beachball](_icons_beachball_.beachball.md).[shouldComponentUpdate](_icons_beachball_.beachball.md#optional-shouldcomponentupdate)*

Defined in node_modules/@types/react/index.d.ts:579

Called to determine whether the change in props and state should trigger a re-render.

`Component` always returns true.
`PureComponent` implements a shallow comparison on props and state and returns true if any
props or states have changed.

If false is returned, `Component#render`, `componentWillUpdate`
and `componentDidUpdate` will not be called.

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹[Props](../interfaces/_types_.props.md)› |
`nextState` | Readonly‹S› |
`nextContext` | any |

**Returns:** *boolean*
