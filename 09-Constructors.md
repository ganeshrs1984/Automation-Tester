
# Lesson 9: Constructors

## Goal

Initialize objects easily.

Without constructor:

```typescript
let person = new Person();

person.name = "Ganesh";
person.age = 43;
```

With constructor:

```typescript
class Person {

    constructor(
        public name: string,
        public age: number
    ) {}

}
```
