# Code conventions

## Order

```csharp
[public|protected|private|internal]
[abstract|virtual|override|sealed]
static readonly [const] Name
```

## Variables & access modifiers

### Private members

```csharp
private Type _fieldName;

[SerializedField]
private Type serializedField;
```

### Protected members

```csharp
protected Type fieldName;
```

### Public members

```csharp
public Type fieldName;
```

### Static readonly fields

```csharp
static readonly StaticReadonlyField;
```

### Methods

```csharp
MethodName()
```

### Properties

```csharp
PropertyName { get; set; }
```

### Events

```csharp
EventName
```

### Constants

```csharp
ConstantName
```

### Enums

```csharp
enum EnumName
{
	EnumValue1,
	EnumValue2
}
```

### Interfaces

```csharp
interface IName { }
```

### Types

```csharp
TypeName
```
### Namespace

```csharp
namespace NamespaceName.SubNamespace
```

### Local variables

```csharp
[var|Type] variableName;
```

### Parameters

#### Method

```csharp
methodParameter
```

#### Type

```csharp
<TTypeParameter>
```

## Brackets

```csharp
keyword
{
	// Code
}
```
