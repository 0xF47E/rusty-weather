# rusty-weather

This is a little cli-tool to display the current weather and forecast for a given place.
It is also possible to search with coordinates.

## Usage

```bash
./rusty-weather --place <placename>
```


## Example

```bash
./rusty-weather --place Berlin
╔════════════════════════════════ Rusty Weather ════════════════════════════════╗
║                                                                               ║
║ Current weather                     "Berlin"                                  ║
║ 10.9°C 0.0mm 13.80kmh             (52.5173885, 13.3951309)                    ║
║                                                                               ║
╠══════════════════════════════════ forecast ═══════════════════════════════════╣
║            Sun      Mon      Tue      Wed      Thu      Fri      Sat          ║
║Max:     11.1°C   14.0°C   16.4°C   15.6°C   17.9°C   12.7°C   12.9°C          ║
║Min:      1.4°C    3.5°C    8.9°C    9.6°C   10.8°C    9.1°C    9.1°C          ║
║Pre:       0.0%    48.0%    60.0%    14.0%    67.0%    30.0%    28.0%          ║
║Win:    14.3kmh  14.5kmh  17.6kmh  11.5kmh  25.2kmh  26.4kmh  22.9kmh          ║
╚═══════════════════════════════════════════════════════════════════════════════╝
```


