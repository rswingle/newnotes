# newnotes

This is a python script originally developed by Daniel Rollings to aid in finding scales, modes, and chords to be played on a variety of instruments.

Requirements: python3

TODO:
Fix output formatting

------------------------------------------
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

```Example Usage "./newnotes.py E,A,B" will produce:
Matches scales:
        C major              C  D  E  F  G  A  B  C
        Db minor             Db Eb E  Gb Ab A  B  Db
        D major              D  E  Gb G  A  B  Db D
        D major pentatonic   D  E  Gb A  B  D
        E major              E  Gb Ab A  B  Db Eb E
        E major minor        E  Gb Ab A  B  C  D  E
        E minor              E  Gb G  A  B  C  D  E
        E minor pentatonic   E  G  A  B  D  E
        Gb minor             Gb Ab A  B  Db D  E  Gb
        Gb minor pentatonic  Gb A  B  Db E  Gb
        G major              G  A  B  C  D  E  Gb G
        G major pentatonic   G  A  B  D  E  G
        A major              A  B  Db D  E  Gb Ab A
        A major minor        A  B  Db D  E  F  G  A
        A major pentatonic   A  B  Db E  Gb A
        A minor              A  B  C  D  E  F  G  A
        B major minor        B  Db Eb E  Gb G  A  B
        B minor              B  Db D  E  Gb G  A  B
        B minor pentatonic   B  D  E  Gb A  B
```

