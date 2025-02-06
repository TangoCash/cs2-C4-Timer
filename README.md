# C4 Timer
This plugin adds countdown to c4 bomb explosion to your server.

![image](https://i.imgur.com/rE9S8ag.jpg)

The countdown can look any way you want it to look.
All you have to do is customize the configuration to your liking.

# Config
```
{
  "EnableTimer": true,
  "EnableProgressBar": true,
  "TimerStarting": 45,
  "LeftSideTimer": "-[ ",
  "RightSideTimer": " ]-",
  "EnableColorMessage": true,
  "SidesTimerColor": "45:white",
  "TimeColor": "20:yellow, 10:red, 5:darkred",
  "ProgressBarColor": "20:yellow, 10:red, 5:darkred"
}
```

## Compile Yourself

Clone the project:

```bash
git clone https://github.com/TangoCash/css-C4-Timer.git
```

Go to the project directory

```bash
  cd css-C4-Timer
```

Install dependencies

```bash
  dotnet restore
```

Build debug files (to use on a development game server)

```bash
  dotnet build
```

Build release files (to use on a production game server)

```bash
  dotnet publish
```

