### **1. Tên File**

| Loại File | Quy tắc đặt tên | Ví dụ |
| --- | --- | --- |
| **Component** | `kebab-case.component.ts` | `user-profile.component.ts` |
| **Module** | `kebab-case.module.ts` | `user.module.ts` |
| **Service** | `kebab-case.service.ts` | `auth.service.ts` |
| **Directive** | `kebab-case.directive.ts` | `highlight.directive.ts` |
| **Pipe** | `kebab-case.pipe.ts` | `date-format.pipe.ts` |
| **Guard** | `kebab-case.guard.ts` | `auth.guard.ts` |
| **Interceptor** | `kebab-case.interceptor.ts` | `http-error.interceptor.ts` |
| **Model/Interface** | `kebab-case.model.ts` hoặc `.interface.ts` | `user.model.ts`, `user.interface.ts` |
| **Enum** | `kebab-case.enum.ts` | `role.enum.ts` |

---

### 📌 **2. Tên Component**

| Tiêu chí | Quy tắc đặt tên | Ví dụ |
| --- | --- | --- |
| **Class Name** | PascalCase + `Component` | `export class UserProfileComponent {}` |
| **Selector** | `app-` + `kebab-case` | `<app-user-profile></app-user-profile>` |
| **Template & Styles** | Trùng tên với file `.ts` | `user-profile.component.html`, `user-profile.component.scss` |
| **Chỉ đặt component trong thư mục nếu phức tạp** | Mỗi component có thư mục riêng nếu nó có nhiều file | `/user-profile/user-profile.component.ts` |
| **Không đặt prefix như `ng-`, `angular-`** | Tránh trùng với Angular core | ✅ `app-user-profile` (✔)  ❌ `ng-user-profile` (✘) |

---

### 🔥 **Tóm tắt**

- **Tên file:** **kebab-case**, có hậu tố phù hợp (`.component.ts`, `.service.ts`, `.module.ts`, v.v.).
- **Tên component class:** PascalCase + `Component` (Ví dụ: `UserProfileComponent`).
- **Selector của component:** `app-` + `kebab-case` (Ví dụ: `<app-user-profile>`).
- **Thư mục component:** Nếu có nhiều file (HTML, SCSS, test...), đặt trong một thư mục riêng.