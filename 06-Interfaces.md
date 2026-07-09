
# Lesson 6: Interfaces

## Goal

Describe the structure of an object.

```typescript
interface Person {
    name: string;
    age: number;
}
```

Now create an object using the interface.

```typescript
const person: Person = {
    name: "Ganesh",
    age: 43
};
```
### Think of an Interface as

A blueprint.

It tells TypeScript what properties an object should contain.
