The components are divided into two categories. 

### Presentational Components

Presentational components are for pure presentational purposes, and can be used by importing and passing required props. 
These components don't hold internal states. 

### Stateful Components 

Stateful Components are complex components that are supposed to be copied and customized to fit the project. 
They have internal states, and ought to be customized on how those states are set. 

The reason those are not pure functional is for efficiency. 
These components are a little complex, using internal state has the benifits of partial rerender, or less rerenders. Thus more efficient. 
