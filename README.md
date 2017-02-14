# JavaScript-Weather-App <br />
JavaScript in Action <br />
https://developer.mozilla.org/en-US/docs/Web/JavaScript <br />
Two versions of weather app in JavaScript ES5 and JavaScript ES6 <br />
<br />
ES6 IMPORTANT NOTES:<br />
let person = {<br />
    firstname: 'John',<br />
    lastname: 'Doe',<br />
    greet: function() {<br />
        return 'Hello, '+ this.firstname+' '+ this.lastname;<br />
    },<br />
    greet2: () => 'Hello, '+ this.firstname+ ' ' +this.lastname <br />
}<br />
let firstname = 'Jane';<br />
var lastname = 'Smith';<br />
console.log(person.greet()); // Hello John Doe<br />
console.log(person.greet2());// Hello Undefined Smith<br />
