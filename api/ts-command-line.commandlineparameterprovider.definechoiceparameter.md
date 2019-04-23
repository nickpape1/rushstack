<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index) &gt; [@microsoft/ts-command-line](./ts-command-line.md) &gt; [CommandLineParameterProvider](./ts-command-line.commandlineparameterprovider.md) &gt; [defineChoiceParameter](./ts-command-line.commandlineparameterprovider.definechoiceparameter.md)

## CommandLineParameterProvider.defineChoiceParameter() method

Defines a command-line parameter whose value must be a string from a fixed set of allowable choices (similar to an enum).

<b>Signature:</b>

```typescript
defineChoiceParameter(definition: ICommandLineChoiceDefinition): CommandLineChoiceParameter;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  definition | <code>ICommandLineChoiceDefinition</code> |  |

<b>Returns:</b>

`CommandLineChoiceParameter`

## Remarks

Example: example-tool --log-level warn
