<div align="center">
    <br/>
    <br/>
  <h1>
    📱
    <br />
    react-use-native
    <br />
  </h1>
    <h5>The <a href="https://www.npmjs.com/package/react-use">react-use</a> fork for react-native</h5>
    <br />
It doesn't depend on 'react-dom'.
    <br />
A better choice for React Native development for native apps only.
    <br />
    <br />
  <sup>
    <br />
    <br />
    <br />
    Collection of essential <a href="https://reactjs.org/docs/hooks-intro.html">React Hooks</a>.</em>
    <em>Port of</em> <a href="https://github.com/streamich/libreact"><code>libreact</code></a>.
    <br />
    Translations: <a href="https://github.com/zenghongtu/react-use-chinese/blob/master/README.md">🇨🇳 汉语</a>
  </sup>
  <br />
  <br />
  <br />
  <br />
  <pre>npm i <a href="https://www.npmjs.com/package/react-use-native">react-use-native</a></pre>
  <br />
  <br />
  <br />
  <br />
  <br />
</div>

- [**Animations**](./docs/Animations.md)
  - [`useRaf`](./docs/useRaf.md) &mdash; re-renders component on each `requestAnimationFrame`.
  - [`useInterval`](./docs/useInterval.md) &mdash; re-renders component on a set interval using `setInterval`.
  - [`useTimeout`](./docs/useTimeout.md) &mdash; re-renders component after a timeout.
  - [`useTimeoutFn`](./docs/useTimeoutFn.md) &mdash; calls given function after a timeout. [![][img-demo]](https://streamich.github.io/react-use/?path=/story/animation-usetimeoutfn--demo)
  - [`useUpdate`](./docs/useUpdate.md) &mdash; returns a callback, which re-renders component when called.
    <br/>
    <br/>
- [**Side-effects**](./docs/Side-effects.md)
  - [`useAsync`](./docs/useAsync.md), [`useAsyncFn`](./docs/useAsyncFn.md), and [`useAsyncRetry`](./docs/useAsyncRetry.md) &mdash; resolves an `async` function.
  - [`useDebounce`](./docs/useDebounce.md) &mdash; debounces a function. [![][img-demo]](https://streamich.github.io/react-use/?path=/story/side-effects-usedebounce--demo)
  - [`useError`](./docs/useError.md) &mdash; error dispatcher. [![][img-demo]](https://streamich.github.io/react-use/?path=/story/side-effects-useerror--demo)
  - [`useRafLoop`](./docs/useRafLoop.md) &mdash; calls given function inside the RAF loop.
  - [`useThrottle` and `useThrottleFn`](./docs/useThrottle.md) &mdash; throttles a function. [![][img-demo]](https://streamich.github.io/react-use/?path=/story/side-effects-usethrottle--demo)
    <br/>
    <br/>
- [**Lifecycles**](./docs/Lifecycles.md)
  - [`useEffectOnce`](./docs/useEffectOnce.md) &mdash; a modified [`useEffect`](https://reactjs.org/docs/hooks-reference.html#useeffect) hook that only runs once.
  - [`useLifecycles`](./docs/useLifecycles.md) &mdash; calls `mount` and `unmount` callbacks.
  - [`useMountedState`](./docs/useMountedState.md) and [`useUnmountPromise`](./docs/useUnmountPromise.md) &mdash; track if component is mounted.
  - [`usePromise`](./docs/usePromise.md) &mdash; resolves promise only while component is mounted.
  - [`useLogger`](./docs/useLogger.md) &mdash; logs in console as component goes through life-cycles.
  - [`useMount`](./docs/useMount.md) &mdash; calls `mount` callbacks.
  - [`useUnmount`](./docs/useUnmount.md) &mdash; calls `unmount` callbacks.
  - [`useUpdateEffect`](./docs/useUpdateEffect.md) &mdash; run an `effect` only on updates.
  - [`useIsomorphicLayoutEffect`](./docs/useIsomorphicLayoutEffect.md) &mdash; `useLayoutEffect` that that works on server.
  - [`useDeepCompareEffect`](./docs/useDeepCompareEffect.md), [`useShallowCompareEffect`](./docs/useShallowCompareEffect.md), and [`useCustomCompareEffect`](./docs/useCustomCompareEffect.md)
    <br/>
    <br/>
- [**State**](./docs/State.md)
  - [`createMemo`](./docs/createMemo.md) &mdash; factory of memoized hooks.
  - [`createReducer`](./docs/createReducer.md) &mdash; factory of reducer hooks with custom middleware.
  - [`createReducerContext`](./docs/createReducerContext.md) and [`createStateContext`](./docs/createStateContext.md) &mdash; factory of hooks for a sharing state between components.
  - [`useDefault`](./docs/useDefault.md) &mdash; returns the default value when state is `null` or `undefined`.
  - [`useGetSet`](./docs/useGetSet.md) &mdash; returns state getter `get()` instead of raw state.
  - [`useGetSetState`](./docs/useGetSetState.md) &mdash; as if [`useGetSet`](./docs/useGetSet.md) and [`useSetState`](./docs/useSetState.md) had a baby.
  - [`useLatest`](./docs/useLatest.md) &mdash; returns the latest state or props
  - [`usePrevious`](./docs/usePrevious.md) &mdash; returns the previous state or props. [![][img-demo]](https://codesandbox.io/s/fervent-galileo-krgx6)
  - [`usePreviousDistinct`](./docs/usePreviousDistinct.md) &mdash; like `usePrevious` but with a predicate to determine if `previous` should update.
  - [`useObservable`](./docs/useObservable.md) &mdash; tracks latest value of an `Observable`.
  - [`useRafState`](./docs/useRafState.md) &mdash; creates `setState` method which only updates after `requestAnimationFrame`. [![][img-demo]](https://streamich.github.io/react-use/?path=/story/state-userafstate--demo)
  - [`useSetState`](./docs/useSetState.md) &mdash; creates `setState` method which works like `this.setState`. [![][img-demo]](https://codesandbox.io/s/n75zqn1xp0)
  - [`useStateList`](./docs/useStateList.md) &mdash; circularly iterates over an array. [![][img-demo]](https://codesandbox.io/s/bold-dewdney-pjzkd)
  - [`useToggle` and `useBoolean`](./docs/useToggle.md) &mdash; tracks state of a boolean. [![][img-demo]](https://codesandbox.io/s/focused-sammet-brw2d)
  - [`useCounter` and `useNumber`](./docs/useCounter.md) &mdash; tracks state of a number. [![][img-demo]](https://streamich.github.io/react-use/?path=/story/state-usecounter--demo)
  - [`useList`](./docs/useList.md) ~and [`useUpsert`](./docs/useUpsert.md)~ &mdash; tracks state of an array. [![][img-demo]](https://codesandbox.io/s/wonderful-mahavira-1sm0w)
  - [`useMap`](./docs/useMap.md) &mdash; tracks state of an object. [![][img-demo]](https://codesandbox.io/s/quirky-dewdney-gi161)
  - [`useSet`](./docs/useSet.md) &mdash; tracks state of a Set. [![][img-demo]](https://codesandbox.io/s/bold-shtern-6jlgw)
  - [`useQueue`](./docs/useQueue.md) &mdash; implements simple queue.
  - [`useStateValidator`](./docs/useStateValidator.md) &mdash; tracks state of an object. [![][img-demo]](https://streamich.github.io/react-use/?path=/story/state-usestatevalidator--demo)
  - [`useStateWithHistory`](./docs/useStateWithHistory.md) &mdash; stores previous state values and provides handles to travel through them. [![][img-demo]](https://streamich.github.io/react-use/?path=/story/state-usestatewithhistory--demo)
  - [`useMultiStateValidator`](./docs/useMultiStateValidator.md) &mdash; alike the `useStateValidator`, but tracks multiple states at a time. [![][img-demo]](https://streamich.github.io/react-use/?path=/story/state-usemultistatevalidator--demo)
  - [`useMediatedState`](./docs/useMediatedState.md) &mdash; like the regular `useState` but with mediation by custom function. [![][img-demo]](https://streamich.github.io/react-use/?path=/story/state-usemediatedstate--demo)
  - [`useFirstMountState`](./docs/useFirstMountState.md) &mdash; check if current render is first. [![][img-demo]](https://streamich.github.io/react-use/?path=/story/state-usefirstmountstate--demo)
  - [`useRendersCount`](./docs/useRendersCount.md) &mdash; count component renders. [![][img-demo]](https://streamich.github.io/react-use/?path=/story/state-userenderscount--demo)
  - [`createGlobalState`](./docs/createGlobalState.md) &mdash; cross component shared state.[![][img-demo]](https://streamich.github.io/react-use/?path=/story/state-createglobalstate--demo)
  - [`useMethods`](./docs/useMethods.md) &mdash; neat alternative to `useReducer`. [![][img-demo]](https://streamich.github.io/react-use/?path=/story/state-usemethods--demo)
    <br/>
    <br/>
- [**Miscellaneous**]()
  - [`useEnsuredForwardedRef`](./docs/useEnsuredForwardedRef.md) and [`ensuredForwardRef`](./docs/useEnsuredForwardedRef.md) &mdash; use a React.forwardedRef safely. [![][img-demo]](https://streamich.github.io/react-use/?path=/story/state-useensuredforwardedref--demo)

<br />
<br />
<br />
<br />
<br />
<br />
<br />

<p align="center">
  <a href="./docs/Usage.md"><strong>Usage</strong></a> &mdash; how to import.
  <br />
  <a href="./LICENSE"><strong>Unlicense</strong></a> &mdash; public domain.
  <br />
  <a href="https://opencollective.com/react-use/contribute"><strong>Support</strong></a> &mdash; add yourself to backer list below.
</p>

<br />
<br />
<br />
<br />
<br />

[img-demo]: https://img.shields.io/badge/demo-%20%20%20%F0%9F%9A%80-green.svg

<div align="center">
  <h1>Contributors</h1>
</div>

<br />
<br />

<a href="https://github.com/streamich/react-use/graphs/contributors"><img src="https://opencollective.com/react-use/contributors.svg?width=890&button=false" /></a>

<br />
<br />
<br />
<br />
<br />
