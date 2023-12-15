# Gaming

Add a global Proton compatibility layer profile to prevent maintaining multiple Winepreloaders and Wineservers

## What matches the profile?
This profile matches all steam provided proton versions + custom GE versions in the compatibilitytools.d folder.
It matches the following examples:

```plaintext
/home/joe/.local/share/Steam/compatibilitytools.d/GE-Proton7-55/files/bin/wine64-preloader
/home/jane/.local/share/Steam/compatibilitytools.d/GE-Proton8-25/files/bin/wine64-preloader
/home/bob/.local/share/Steam/steamapps/common/Proton - Experimental/files/bin/wine64-preloader
/home/alice/.local/share/Steam/steamapps/common/Proton 8.0/files/bin/wine64-preloader
```

## What does the profile block?

There are the following rules included in the profile:

| Direction | Action | URL                                    | Reason    |
|-----------|--------|----------------------------------------|-----------|
| Outgoing  | Block  | prod-telemetry.paradox-interactive.com | Telemetry |
|           |        |                                        |           |

[Proton profile](proton-compatibilitylayer.yml)