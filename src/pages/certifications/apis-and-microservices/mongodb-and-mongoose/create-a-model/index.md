---
title: Create a Model
---
## Create a Model

There are 3 things to do in this challenge. You can click each item to see the code.

<details>
  <summary>Assign Mongoose Schema to a variable. This is not necessary but will make your code easier to read.</summary>

```javascript
const Schema = mongoose.Schema;
```
</details>
<details>
  <summary>Create Person schema.</summary>

```javascript
const personSchema = new Schema({
  name: { type: String, required: true },
  age: Number,
  favoriteFoods:   [String]
});
```
**Note**: If you choose to skip the first step, you have to use `mongoose.Schema` instead of `Schema`.
</details>
<details>
  <summary>Create Person model from the schema.</summary>

```javascript
const Person = mongoose.model('Person', personSchema);
```
</details>
