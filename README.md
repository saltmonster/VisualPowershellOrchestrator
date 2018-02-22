# VisualPowershellOrchestrator

## Purpose
A visual tool for creating powershell scripts from a gui with a timeline based workflow.

### Gui specs
```
+----------------------------------------------------------------+
| file |________________________________________________________x|
|------------|---------------------------------------|-----------|
| Contexts   |            canvas build area          | Functions |
|            |                                       |           |
|            |                                       |           |
|            |                                       |           |
|            |                                       |           |
|            |                                       |           |
|            |                                       |           |
|            |                                       |           |
|            |                                       |           |
|            |                                       |           |
|            |                                       |           |
|            |                                       |           |
|------------|---------------------------------------|-----------|
|                           Selected comp            |  [ RUN ]  |
|                                                    | [ Build ] |
+----------------------------------------------------------------+
```

### Canvas view
```
[ fReadworkdir ] ( log )
       |
       |(iterate)
       |
   [ sftpMove ] ( log )
       |
       |(onComplete)
       |
  [ writeLog ]
```
