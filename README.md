# newnotes

This is a python script originally developed by Daniel Rollings to aid in finding scales, modes, and chords to be played on a variety of instruments.

Requirements: python3

TODO:
Fix output formatting

------------------------------------------

Example usage: ./newnotes.py E,A,B

./newnotes.py --help:
```
Usage: newnotes.py [options]
Options:
  -h, --help            show this help message and exit
  -s SCALES, --scales=SCALES
                        Scales to limit to
  -c CHORDS, --chords=CHORDS
                        Chords to limit to
  -k KEYS, --keys=KEYS  Keys to limit to
  -C, --chords-only     Display only chords
  -S, --scales-only     Display only scales
  -F FAMILY, --family=FAMILY
                        Display scales of a family, available types melodic
                        minor harmonic minor persian tunings ancient greek
                        blues exotic major
  -A, --all-scales      Display all scales
  -M, --modal           Include modal scales
  --fingercharts=FINGERCHARTS
                        Print fingercharts
  -I, --intervals       Print fingercharts in intervals
  -f NUMFRETS, --frets=NUMFRETS
                        Frets to display
  --html                Do fingercharts in HTML
  --scala               Print scala output of scales
  --tuning=TUNINGSCALE  Scale to use for intervals
  --thumbjam            Print thumbjam output of scales
  --modes               Include all related modal scales
  --write               Write scales
  --shell               Interactive shell
  --fractional=FRACTIONAL
                        Make a fractional scale with denominator up to this
```
