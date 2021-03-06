# simple-react-button
A beautiful and simple button component

### Installation
```sh
npm install --save simple-react-button
```
### Usage
```javascript
import Button from 'simple-react-button';
// then in your render function
render() {
    return(
        <div>
            <Button color="#9b59b6" full style={{fontSize: '13px'}}>
                Click Me
            </Button>
        </div>
    );
}
// And that's all for now
```

### Props
#### `style`
You can provide your own inline custom style to Button.
```javascript
<Button style={{fontSize: '13px'}}>
    Click Me
</Button>
```
#### `full`
If button will be a full button .. or a hollow button .. you have to try it out yourself.
```javascript
<Button full>
    Click Me
</Button>
```
#### `color`
Default color of the button ...
```javascript
<Button color="#9b59b6" full>
    Click Me
</Button>
```
#### `round`
Render a rounded button
```javascript
<Button color="#9b59b6" round>
    Click Me
</Button>
```
#### `onClick`
You can easily call any function on Click.
```javascript
<Button color="#9b59b6" full onClick={() => {console.log('Hey I Worked')}}>
    Click Me
</Button>
```


### About Me

 * [My website](http://manojsinghnegi.com) (manojsinghnegi.com)
 * [Github](http://github.com/manojsinghnegiwd) (@manojsinghnegiwd)
 * [Twitter](http://twitter.com/manojnegiwd) (@manojnegiwd)