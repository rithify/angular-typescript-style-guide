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
- 
```
```

- student.service.ts

```typescript
@Injectable({ providedIn: 'root' })
export class StudentService {
  form;
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
