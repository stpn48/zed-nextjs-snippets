
# **zed-nextjs-snippets**  
✨ _Powerful Next.js snippets for the Zed editor_ ✨

### 🚀 **Supercharge your Next.js development** with these time-saving snippets for the Zed editor. Speed up your coding workflow and ensure consistency across your projects. Whether you're building components, server actions, or managing state, these snippets got you covered.

---

### 🧩 **Available Snippets**

#### **🔧 `rc` - Create Component**
Instantly scaffold a functional component in your Next.js project.

```tsx
type Props = {};

export function Component({}: Props) {
  return <div>/* Your content here */</div>;
}
```

#### **⚡ `rcc` - Create Client Component**
Generate a client-side component with `"use client"` at the top for server-side rendering control.

```tsx
"use client";

type Props = {};

export function Component({}: Props) {
  return <div>/* Your content here */</div>;
}
```

#### **🌐 `sa` - Create Server Action**
Create an asynchronous server action with the `"use server"` directive.

```tsx
"use server";

export async function Action() {
  // Your server logic here
}
```

#### **🔌 `uc` - `"use client"`**
Quickly insert the `"use client"` directive to specify that the file should be treated as a client component.

```tsx
"use client";
```

#### **🔄 `us` - `useState` Hook**
Simplify your state management by using this snippet to create a state variable and its setter.

```tsx
const [state, setState] = useState<Type>(initialState);
```

#### **🔄 `ue` - `useEffect` Hook**
Instantly add a `useEffect` hook to manage side effects in your component.

```tsx
useEffect(() => {
  // Side effect logic here
}, [dependencies]);
```

---

### 🎉 **Why Use Zed Snippets?**
- **Speed**: Save time by avoiding repetitive coding tasks.
- **Consistency**: Maintain a clean and consistent codebase across your Next.js projects.
- **Focus**: Spend more time solving problems, not typing boilerplate.

---

### 🔧 **Installation**

To install these snippets, simply copy them into your Zed snippet directory:

1. Navigate to `~/.config/zed/snippets`
2. Paste the snippets.json file into the folder.
3. Enjoy !

### 📂 **Folder Structure** (Example)

```bash
~/.config/zed/snippets/
  └── nextjs-snippets.json
```

---

### 📝 **Contributing**

If you’d like to contribute or suggest new snippets, feel free to open a Pull Request! Let’s make Next.js development even more efficient together.

---

### 👨‍💻 **License**

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.
