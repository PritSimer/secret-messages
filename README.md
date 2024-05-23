# secret-messages
codecademy//js//beginners//practice
let secretMessage = ['Learning', 'is', 'not', 'about', 'what', 'you', 'get', 'easily', 'the', 'first', 'time,', 'it', 'is', 'about', 'what', 'you', 'can', 'figure', 'out.', '-2015,', 'Chris', 'Pine,', 'Learn', 'JavaScript'];

console.log(secretMessage.length);
secretMessage.pop();

console.log(secretMessage);

console.log(secretMessage.length);

secretMessage.push('to', 'Program');

console.log(secretMessage);

console.log(secretMessage.indexOf('easily'));

secretMessage[7] = 'right';

console.log(secretMessage);

console.log(secretMessage.shift());

console.log(secretMessage);

secretMessage.unshift('Programming');

console.log(secretMessage);

console.log(secretMessage.indexOf('get')); // 6

//console.log(secretMessage.indexOf('time')); // 9 ?

secretMessage.fill('know',6, 11); // fill up to the end, does not include the end index i.e. position 11 is 'it'

console.log(secretMessage);

console.log(secretMessage.join(' '))










