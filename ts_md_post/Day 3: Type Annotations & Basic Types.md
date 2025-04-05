## ✨ Day 3: Type Annotations & Basic Types 🚀

Welcome to **Day 3** of our TypeScript journey! Today, we’ll explore **Type Annotations** and **Basic Types** in TypeScript. These are the building blocks of TypeScript and will help you write type-safe and maintainable code. Let’s dive in! 🎉

---

### 🔹 What are Type Annotations?

Type annotations allow you to explicitly specify the type of a variable, function, or parameter. This helps TypeScript catch errors at compile time.

#### Syntax:
```typescript
let variableName: Type = value;
```

#### Example:
```typescript
let age: number = 25;
let name: string = "Alice";
let isStudent: boolean = true;
```

---

### 🔹 Basic Types in TypeScript

TypeScript provides several basic types to define the shape of your data.

#### 1. `number`
Represents numeric values (both integers and floating-point numbers).
```typescript
let age: number = 30;
let price: number = 19.99;
```

#### 2. `string`
Represents textual data.
```typescript
let firstName: string = "John";
let greeting: string = `Hello, ${firstName}!`;
```

#### 3. `boolean`
Represents `true` or `false` values.
```typescript
let isLoggedIn: boolean = false;
```

#### 4. `any`
Represents any type of value. Use sparingly as it disables type checking.
```typescript
let randomValue: any = "Hello";
randomValue = 42; // No error
```

#### 5. `unknown`
Represents a value of unknown type. Safer than `any` as it requires type checking before use.
```typescript
let input: unknown = "Hello";
if (typeof input === "string") {
  console.log(input.toUpperCase());
}
```

#### 6. `null` and `undefined`
Represents null and undefined values.
```typescript
let empty: null = null;
let notAssigned: undefined = undefined;
```

#### 7. `void`
Represents the absence of a value, typically used for functions that don’t return anything.
```typescript
function logMessage(message: string): void {
  console.log(message);
}
```

#### 8. `never`
Represents values that never occur, typically used for functions that throw errors or never return.
```typescript
function throwError(message: string): never {
  throw new Error(message);
}
```

---

### 🔹 Type Inference

TypeScript can infer the type of a variable based on its value, so you don’t always need to specify the type explicitly.

### Example:
```typescript
let age = 25; // TypeScript infers 'number'
let name = "Alice"; // TypeScript infers 'string'
```

---

### 🔹 Practical Example: Using Basic Types

Here’s an example that combines multiple basic types:
```typescript
function displayUserInfo(name: string, age: number, isStudent: boolean): void {
  console.log(`Name: ${name}, Age: ${age}, Student: ${isStudent}`);
}

displayUserInfo("Alice", 25, true);
```

---

### 🎯 Conclusion

Type annotations and basic types are the foundation of TypeScript. By mastering these, you can write type-safe and maintainable code. Keep practicing, and happy coding! 🚀