# Component Lifecycle / useEffect Hook

## Effects hook

**What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?**

Within a React class you have to make 2 methods for the rendering lifecycle. However with hooks React will remember the function passed.

**When using the useEffect Hook:**
  **What does useEffect do?**

  By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we’ll refer to it as our “effect”), and call it later after performing the DOM updates. In this effect, we set the document title, but we could also perform data fetching or call some other imperative API.

  From [Using the Effect Hook](https://legacy.reactjs.org/docs/hooks-effect.html)

  **Why is useEffect called inside a component?**

  Placing useEffect inside the component lets us access the count state variable (or any props) right from the effect. We don’t need a special API to read it — it’s already in the function scope. Hooks embrace JavaScript closures and avoid introducing React-specific APIs where JavaScript already provides a solution.

  From [Using the Effect Hook](https://legacy.reactjs.org/docs/hooks-effect.html)

**Explain the importance of properly implementing effects with Cleanup**

An example would be For we might want to set up a subscription to some external data source. In that case, it is important to clean up so that we don’t introduce a memory leak.

From [Using the Effect Hook](https://legacy.reactjs.org/docs/hooks-effect.html)

## Things I want to know more about

This was a dry read I hope it exxplained more thoroughly today.

[Back to Home](../README.md)
