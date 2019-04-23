<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index) &gt; [@microsoft/ts-command-line](./ts-command-line.md) &gt; [CommandLineParameterWithArgument](./ts-command-line.commandlineparameterwithargument.md)

## CommandLineParameterWithArgument class

The common base class for parameters types that receive an argument.

<b>Signature:</b>

```typescript
export declare abstract class CommandLineParameterWithArgument extends CommandLineParameter 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [argumentName](./ts-command-line.commandlineparameterwithargument.argumentname.md) |  | <code>string</code> | The name of the argument, which will be shown in the command-line help. |

## Remarks

An argument is an accompanying command-line token, such as "123" in the example "--max-count 123".

The constructor for this class is marked as internal. Third-party code should not call the constructor directly or create subclasses that extend the `CommandLineParameterWithArgument` class.
