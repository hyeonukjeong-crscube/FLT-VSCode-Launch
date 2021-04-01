# FLT-VSCode-Launch

VSCode 쓰는 사람을 위한 launch.json 파일

{
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [
        {
            "name": "web",
            "request": "launch",
            "type": "dart",
            "args": ["-d","chrome"]
        },
        {
            "name": "device",
            "request": "launch",
            "type": "dart",
        }
    ]
}
