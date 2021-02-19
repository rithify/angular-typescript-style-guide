- student.model.ts

```typescript
export interface Student {
  name?: string;
  student_id?: string;
  current_year?: AcademicYear;
  generation?: number;
  department?: string;
}
```
- student.component.ts

```typescript
  export class StudentComponent {
    
  }
```
- student.const.ts

```
export const STUDENT_FORM: Student = [
  {
    name: null,
    student_id: null,
    current_year: null,
    generation: null,
    department: null
  }
];
```

- student.service.ts

```typescript
@Injectable({ providedIn: 'root' })
export class StudentService {
  form: Student[];
  baseForm;
  
  get() {}
  
  create() {}
  
  update() {}
  
  delete() {}
}
```

- student.enum.ts

```typescript
export enum StudentDepartment {
  COMPUTER_SCIENCE = 'COMPUTER_SCIENCE'
}
```
