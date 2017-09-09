# Creating Music with Code

## Setup

### System Dependencies
The demonstration in this repository assumes you are running the following
software on your development machine.

- MacOS with Python
- Homebrew (https://brew.sh/)

### Software Dependencies
Setup a Python virtual environment.

Navigate to the repository root and create your environment.

```
virtualenv venv
```

Once the virtual environment has completed, start the virtual environment.

```
source venv/bin/activate
```

Then install the Python requirements.

```
pip install -r requirements.txt
```

### MIDI Player Dependencies
You can use any MIDI player you'd like. Since we love the command line and this
is a demonstration of creating music with code, we shy away from a traditional
GUI and use a command line MIDI player call Timidity.

You can install Timidity on your computer by opening your Terminal/Command Line
and entering the following command.

```
brew install timidity
```

## Demonstration

### Generating the demonstration .MID
To hear the demonstration audio, open your Terminal/Command Line and enter the
following commands.

```
python test.py
```

This will generate a MIDI file in your repository called `major-scale.mid`.

### Listening to your MIDI
To listen to your MIDI you can open your Terminal/Command Line and enter the
following commands.

```
timidity major-scale.mid
```
