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
```
