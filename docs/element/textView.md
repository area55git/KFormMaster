The Text View form element is used for a readonly text value field.

## Example

### Kotlin
```kotlin
textView(1) {
    value = "Example"
}
```

### Java
```java
List<BaseFormElement<?>> elements = new ArrayList<>();
TextViewBuilder textView = new TextViewBuilder(1);
textView.setValue("Example");
elements.add(textView.build());
```