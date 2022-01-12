# ReactBasic
Learning Reactjs
example:
<div id="mydiv"></div>

    <script type="text/babel">
      function Hello() {
        return <h1>Hello World!</h1>;
      }
      ReactDOM.render(<Hello />, document.getElementById('mydiv'))
    </script>
    // ReactDOM.render(element, container[, callback])
    // Render a React element into the DOM in the supplied container
