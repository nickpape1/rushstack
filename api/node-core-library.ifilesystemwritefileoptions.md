<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index) &gt; [@microsoft/node-core-library](./node-core-library.md) &gt; [IFileSystemWriteFileOptions](./node-core-library.ifilesystemwritefileoptions.md)

## IFileSystemWriteFileOptions interface

The options for FileSystem.writeFile()

<b>Signature:</b>

```typescript
export interface IFileSystemWriteFileOptions 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [convertLineEndings](./node-core-library.ifilesystemwritefileoptions.convertlineendings.md) | <code>NewlineKind</code> | If specified, will normalize line endings to the specified style of newline. Defaults to <code>NewlineKind.None</code>. |
|  [encoding](./node-core-library.ifilesystemwritefileoptions.encoding.md) | <code>Encoding</code> | If specified, will change the encoding of the file that will be written. Defaults to <code>&quot;utf8&quot;</code>. |
|  [ensureFolderExists](./node-core-library.ifilesystemwritefileoptions.ensurefolderexists.md) | <code>boolean</code> | If true, will ensure the folder is created before writing the file. Defaults to <code>false</code>. |
