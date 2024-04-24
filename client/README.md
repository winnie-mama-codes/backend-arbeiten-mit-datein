# Simple React Form Template

![React Starter Form Demo](src/assets/react-form-demo.gif)

- This is a simple template for a React form.
- The filled information is logged to the console.
- It is meant to be used as a starting point for a form that submits data to a server.



##  Server Erwarten, dass Daten in einem bestimmten Format gesendet werden, wie zum Beispiel JSON (JavaScript Object Notation).



## Von React zum Server verwenden wir JSON.stringify, um JavaScript-Objekte in einen JSON-String zu konvertieren, damit sie über das Netzwerk gesendet werden können. Ein Beispiel:

```javascript
const data = { name: 'John', age: 30 };
const jsonData = JSON.stringify(data); // Konvertiert das JavaScript-Objekt in einen JSON-String
```



```javascript 

const jsonString = '{"name":"John","age":30}';
const parsedData = JSON.parse(jsonString); // Konvertiert den JSON-String in ein JavaScript-Objekt
```