# Components
function Car() {   return &lt;h2>I am a Car!&lt;/h2>; }  function Garage() {   return (     &lt;>       &lt;h1>Who lives in my Garage?&lt;/h1>       &lt;Car />     &lt;/>   ); }  ReactDOM.render(&lt;Garage />, document.getElementById('root'));
