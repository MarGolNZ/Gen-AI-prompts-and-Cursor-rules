## Storybook Documentation Standards
When creating or updating Storybook documentation for design system components, follow this structure:

### 1. Component Description
Start with a clear, concise description of what the component does and its purpose.

### 2. Features Section
List key features using bullet points with bold headers:
- **Feature Name** : Brief description of the feature
- **Another Feature** : Another brief description

### 3. Props Table
Use a markdown table with these columns:
| Prop | Type | Required | Description |
|------|------|----------|-------------|

### 4. Usage Examples
Provide multiple practical examples:

#### Base Usage
```tsx
<ComponentName prop1="value" prop2={value} />
```

#### With Custom Styling
```tsx
<ComponentName 
  prop1="value" 
  sx={{ customStyle: 'value' }}
/>
```

#### Advanced Usage
```tsx
<ComponentName 
  prop1="value"
  customProp={complexValue}
  sx={{ advanced: 'styling' }}
/>
```

### 5. Styling Section
Explain how to customize different parts:
- **Main Container** : Use `sx` prop for global styling
- **Specific Elements** : Use element-specific sx props (e.g., `headerSx`, `contentSx`)

### 6. Key Principles
- Use French for descriptions (following project conventions)
- Keep examples practical and realistic
- Show different use cases and configurations
- Emphasize host control and flexibility
- Use consistent formatting and naming conventions
- Include all major props with clear descriptions
- Show both simple and complex usage patterns

### 7. Code Quality
- Use proper TypeScript syntax in examples
- Include realistic prop values
- Show proper import statements when relevant
- Use consistent indentation and formatting
- Include comments for complex examples