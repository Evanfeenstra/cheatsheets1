# react!

### Component

**class component:**
```js
class Thingy extends React.Component {

    state={
        text:'hello!'
    }

    render() {
        const {something} = this.props
        return (<div style={{height:40}} className="app">
            {this.state.text}
            <LittleThingy name={this.state.text} 
                changeText={text=> this.setState({text})}
            />
        </div>)
    }
}
```

Now you can change state with:
```js
this.setState({text: ''})
```

**function component (no state)**
```js
function LittleThingy(props) {
    return <div onClick={()=>props.changeText('newText')}>
        {props.name}
    </div>
}
```

To use a component:
```js
<LittleThingy name="evan" number={4} />
```

Props can be anything, a string, a number, or even a function!