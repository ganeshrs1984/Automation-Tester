
# Lesson 12: Methods or Functions or Behaviour

## Goal

Add behavior to a class.

```typescript
class Person {

    constructor(
        public name: string,
        public age: number
    ) {}

    introduce() {
        console.log("Hi, I'm " + this.name);
    }

}
```

Methods are simply functions that belong to a class.
