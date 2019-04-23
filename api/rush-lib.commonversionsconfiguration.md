<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [CommonVersionsConfiguration](./rush-lib.commonversionsconfiguration.md)

## CommonVersionsConfiguration class

Use this class to load and save the "common/config/rush/common-versions.json" config file. This config file stores dependency version information that affects all projects in the repo.

<b>Signature:</b>

```typescript
export declare class CommonVersionsConfiguration 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [allowedAlternativeVersions](./rush-lib.commonversionsconfiguration.allowedalternativeversions.md) |  | <code>Map&lt;string, ReadonlyArray&lt;string&gt;&gt;</code> | A table that stores, for a given dependency, a list of SemVer ranges that will be accepted by "rush check" in addition to the normal version range. |
|  [filePath](./rush-lib.commonversionsconfiguration.filepath.md) |  | <code>string</code> | Get the absolute file path of the common-versions.json file. |
|  [preferredVersions](./rush-lib.commonversionsconfiguration.preferredversions.md) |  | <code>Map&lt;string, string&gt;</code> | A table that specifies a "preferred version" for a dependency package. |
|  [xstitchPreferredVersions](./rush-lib.commonversionsconfiguration.xstitchpreferredversions.md) |  | <code>Map&lt;string, string&gt;</code> | A table of specifies preferred versions maintained by the XStitch tool. |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [getAllPreferredVersions()](./rush-lib.commonversionsconfiguration.getallpreferredversions.md) |  | Returns the union of preferredVersions and xstitchPreferredVersions. |
|  [loadFromFile(jsonFilename)](./rush-lib.commonversionsconfiguration.loadfromfile.md) | <code>static</code> | Loads the common-versions.json data from the specified file path. If the file has not been created yet, then an empty object is returned. |
|  [save()](./rush-lib.commonversionsconfiguration.save.md) |  | Writes the "common-versions.json" file to disk, using the filename that was passed to loadFromFile(). |
