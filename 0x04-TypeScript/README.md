# 0x04. Typescript

This repository contains several TypeScript tasks aimed at learning TypeScript fundamentals and advanced concepts. Each task is designed to practice different aspects of TypeScript programming.

## Task Summaries

1. **Creating an interface for a student**:
   - Location: [task_0/js/main.ts](task_0/js/main.ts)
   - Description: Defines a TypeScript interface for a student with properties like `firstName`, `lastName`, `age`, and `location`. Implements Vanilla JavaScript to render a table with student information.

2. **Let's build a Teacher interface**:
   - Location: [task_1/js/main.ts](task_1/js/main.ts)
   - Description: Defines a TypeScript interface `Teacher` with specific attribute rules like `firstName` and `lastName`. Introduces options like `fullTimeEmployee`, `yearsOfExperience`, and `location`.

3. **Extending the Teacher class**:
   - Location: [task_1/js/main.ts](task_1/js/main.ts)
   - Description: Extends the `Teacher` interface to `Directors`, adding a new attribute `numberOfReports`.

4. **Printing teachers**:
   - Location: [task_1/js/main.ts](task_1/js/main.ts)
   - Description: Implements a TypeScript function `printTeacher` to format teacher names. Defines an interface `printTeacherFunction` for the function.

5. **Writing a class**:
   - Location: [task_1/js/main.ts](task_1/js/main.ts)
   - Description: Defines a TypeScript class `StudentClass` with constructor arguments `firstName` and `lastName`. Implements methods like `workOnHomework` and `displayName`. Ensures TypeScript error-free build with `npm run build`.

6. **Advanced types Part 1**:
   - Location: [task_2/js/main.ts](task_2/js/main.ts)
   - Description: Introduces TypeScript interfaces `DirectorInterface` and `TeacherInterface`. Implements TypeScript classes `Director` and `Teacher` that fulfill interface requirements. Implements a function `createEmployee` based on salary.

7. **Creating functions specific to employees**:
   - Location: [task_2/js/main.ts](task_2/js/main.ts)
   - Description: Implements TypeScript functions `isDirector` and `executeWork` based on employee type (`Director` or `Teacher`).

8. **String literal types**:
   - Location: [task_2/js/main.ts](task_2/js/main.ts)
   - Description: Defines a TypeScript string literal type `Subjects` allowing values `Math` or `History`. Implements a function `teachClass` that returns subject-specific strings.

9. **Ambient Namespaces**:
   - Location: [task_3/js](task_3/js)
   - Description: Introduces TypeScript ambient declarations and namespaces. Exports `RowID` type and `RowElement` interface. Utilizes `crud.js` for database operations.

10. **Namespace & Declaration merging**:
    - Location: [task_4/js/subjects](task_4/js/subjects)
    - Description: Implements TypeScript namespace `Subjects` and interfaces within. Defines classes `Cpp`, `React`, and `Java` with specific methods and attributes.

11. **Brand convention & Nominal typing**:
    - Location: [task_5/js/main.ts](task_5/js/main.ts)
    - Description: Implements TypeScript interfaces `MajorCredits` and `MinorCredits` with a brand property for uniqueness. Defines functions `sumMajorCredits` and `sumMinorCredits`.

Each task folder contains TypeScript files with detailed implementations as per the specified requirements.

