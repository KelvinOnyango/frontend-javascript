# TypeScript Project Documentation

This repository contains a series of TypeScript exercises covering various concepts from basic interfaces to advanced type manipulation.

## Table of Contents
1. [Task 0: Creating a Student Interface](#task-0)
2. [Task 1: Teacher and Director Interfaces](#task-1)
3. [Task 2: Advanced Types](#task-2)
4. [Task 3: Ambient Namespaces](#task-3)
5. [Task 4: Namespace & Declaration Merging](#task-4)
6. [Task 5: Brand Convention & Nominal Typing](#task-5)

---

## <a name="task-0"></a>Task 0: Creating a Student Interface
**Files**: `task_0/js/main.ts`

### Objectives:
- Create a `Student` interface
- Implement two student objects
- Render a table using vanilla JavaScript

### Key Concepts:
- Basic TypeScript interfaces
- DOM manipulation with TypeScript
- Type annotations for variables

---

## <a name="task-1"></a>Task 1: Teacher and Director Interfaces
**Files**: `task_1/js/main.ts`

### Objectives:
1. Create a `Teacher` interface with:
   - Readonly properties
   - Optional properties
   - Dynamic property support
2. Extend to create a `Directors` interface
3. Implement `printTeacher` function
4. Create a `StudentClass` with interfaces

### Key Concepts:
- Interface inheritance
- Readonly properties
- Class interfaces
- Function interfaces

---

## <a name="task-2"></a>Task 2: Advanced Types
**Files**: `task_2/js/main.ts`

### Objectives:
1. Create Director/Teacher interfaces with methods
2. Implement `createEmployee` factory function
3. Add type predicate `isDirector`
4. Create `executeWork` function
5. Implement string literal types for subjects

### Key Concepts:
- Union types
- Type predicates
- String literal types
- Method interfaces

---

## <a name="task-3"></a>Task 3: Ambient Namespaces
**Files**: 
- `task_3/js/interface.ts`
- `task_3/js/crud.d.ts` 
- `task_3/js/main.ts`

### Objectives:
- Create type declarations for CRUD operations
- Implement ambient declarations
- Use triple-slash references
- Type external JavaScript library

### Key Concepts:
- Ambient declarations
- Type definition files
- Module augmentation
- Namespace references

---

## <a name="task-4"></a>Task 4: Namespace & Declaration Merging
**Files**:
- `task_4/js/subjects/*.ts`
- `task_4/js/main.ts`

### Objectives:
1. Organize code using namespaces
2. Use declaration merging to extend interfaces
3. Implement subject-specific classes
4. Demonstrate inheritance

### Key Concepts:
- Namespaces organization
- Declaration merging
- Class inheritance
- Interface extension

---

## <a name="task-5"></a>Task 5: Brand Convention & Nominal Typing
**Files**: `task_5/js/main.ts`

### Objectives:
- Create branded interfaces
- Implement nominally typed functions
- Prevent type mixing

### Key Concepts:
- Nominal typing pattern
- Brand properties
- Type safety enforcement
- Distinct type identities

---

## Setup Instructions
1. Clone the repository
2. Install dependencies in each task folder:
   ```bash
   npm install
   ```
3. Build TypeScript files:
   ```bash
   npm run build
   ```

## Testing
Each task includes example usage in the `main.ts` files that demonstrate the implemented functionality.

## Author
Kelvin Onyango 

ALX Software Engineering Program
