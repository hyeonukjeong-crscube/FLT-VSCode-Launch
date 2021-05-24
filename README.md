# FLT-VSCode-Launch

VSCode 쓰는 사람을 위한 launch.json 파일

~~~
{
  "version": "0.2.0",
  "configurations": [
    {
      "name": "web",
      "request": "launch",
      "type": "dart",
      "args": ["-d", "chrome"]
    },
    {
      "name": "device",
      "request": "launch",
      "type": "dart"
    },
    {
      "name": "device-debug",
      "request": "launch",
      "type": "dart",
      "flutterMode": "debug"
    },
    {
      "name": "device-profile",
      "request": "launch",
      "type": "dart",
      "flutterMode": "profile"
    },
    {
        "name": "device-release",
        "request": "launch",
        "type": "dart",
        "flutterMode": "release"
    }
  ]
}
~~~
