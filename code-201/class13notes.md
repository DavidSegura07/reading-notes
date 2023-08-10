# Local Storage and How To Use It On Websites

## Why would a developer use local storage for a web application?

The main problem with HTTP as the main transport layer of the Web is that it is stateless. This means that when you use an application and then close it, its state will be reset the next time you open it. If you close an application on your desktop and re-open it, its most recent state is restored.

## What information should not be stored in local storage?

Local storage is not a safe place to store sensitive information. Things like credit card numbers, passwords, or personal identification information should not be stored there. It's also not a good idea to store important data that your app needs to work properly. Local storage is better for storing simple things like user preferences or temporary data. When deciding what to store, always think about keeping people's information safe and secure.

## Local storage can store what type of data? How would you convert it to that type before storing?

Local storage in web browsers can store data as strings. To store different types of data such as numbers, booleans, or objects, you need to convert them to strings using methods like toString() or JSON.stringify() before storing them in local storage.
