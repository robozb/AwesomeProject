# AwesomeProject

Proper .vscode/launch.json:

```
{
  "configurations": [
    {
      "type": "expo",
      "request": "attach",
      "name": "Debug Expo app",
      // Instead of using `${workspaceFolder}`, use the actual path with the Uppercased drive letter
      "projectRoot": "C:\\Users\\Beci\\Desktop\\ReactXepo\\AwesomeProject",
      "bundlerPort": "8081",
      "bundlerHost": "127.0.0.1"
    }
  ]
}
```
Info: 
- https://github.com/expo/vscode-expo/issues/226#issuecomment-1705432200
- https://github.com/expo/vscode-expo


  
