# TIL-Today-I-Learned
Here is a new repo I have created to share things I am learning from one to another day.

**Github Markdown**<br/>
[Anchored headings](#create-anchored-markdown-link)<br/>
**ReactJS**<br/>
[Compound components pattern](#compound-component-pattern)<br/>

### Create Anchored Markdown Link
To create a link to some part of your README.MD file just follow the instructions in the following [gist](https://gist.github.com/asabaylus/3071099)

### Compound Component Pattern
An approach when creating reactjs components to achive maximum configurational flexibility : all the inner parts of the components are passed to it as **_this.props.children_**. The props and state values sharing is implemented with the React.cloneElement method of the React API (passed as the second argument). There is also a possibility to share the data with creating parent component's **_context_**. A great talk on the topic can be found [here](https://www.reddit.com/r/reactjs/comments/6pgemq/great_talk_workshop_by_ryan_florence_on_using_the/).
