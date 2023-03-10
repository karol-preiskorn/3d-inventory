# 3d inventory

Project create 3d inventory on stack

- Angular
- Tree
- Neo4j/Oracle
- REST
- Docker

## Angular + Three.js

This project consists of two examples:

1. [Tutorial to render 3D Cube in Angular + Three.js](https://srivastavaanurag79.medium.com/hello-cube-your-first-three-js-scene-in-angular-176c44b9c6c0)
2. [Tutorial to render 3D Model in Angular + Three.js](https://srivastavaanurag79.medium.com/3d-model-three-js-scene-in-angular-7bcbc0d00c31)

We'll learn the fundamentals of Three.js and integrate the Three.js scene in Angular.

## Usage

```bash
git clone <this-repo>

npm install
ng serve

localhost:4200 will render cube
localhost:4200/model will render 3D model
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

P3lease make sure to update tests as appropriate.

## Code guidelines

Not forget about https://github.com/Microsoft/TypeScript/wiki/Coding-guidelines

### Names

- Use PascalCase for type names.
- Do not use I as a prefix for interface names.
- Use PascalCase for enum values.
- Use camelCase for function names.
- Use camelCase for property names and local variables.
- Do not use _ as a prefix for private properties.
- Use whole words in names when possible.

### Components

- 1 file per logical component (e.g. parser, scanner, emitter, checker).
- Do not add new files. :)
- files with .generated.* suffix are auto-generated, do not hand-edit them.

### Types

- Do not export types/functions unless you need to share it across multiple components.
- Do not introduce new types/values to the global namespace.
- Shared types should be defined in types.ts.
- Within a file, type definitions should come first.

### null and undefined

- Use undefined. Do not use null.

### General Assumptions

- Consider objects like Nodes, Symbols, etc. as immutable outside the component that created them. Do not change them.
- Consider arrays as immutable by default after creation.

### Classes

For consistency, do not use classes in the core compiler pipeline. Use function closures instead.

### Flags

More than 2 related Boolean properties on a type should be turned into a flag.

### Comments

Use JSDoc style comments for functions, interfaces, enums, and classes.

### Strings

- Use double quotes for strings.
- All strings visible to the user need to be localized (make an entry in diagnosticMessages.json).

### Diagnostic Messages

- Use a period at the end of a sentence.
- Use indefinite articles for indefinite entities.
- Definite entities should be named (this is for a variable name, type name, etc..).
- When stating a rule, the subject should be in the singular (e.g. "An external module cannot..." instead of "External modules cannot...").
- Use present tense.

## Next todo

- add menu
- add action menu requested rest api to neo4j/Oracle

