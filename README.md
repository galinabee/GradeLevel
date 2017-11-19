Toscanini.Grader <a name="grader"></a>
Uses Toscanini, Grader assesses the difficulty of an entire score or instrument part within a score.

```javascript
const Grader = require("toscanini/Grader");
const grader = Grader(musicXML); // Create a Grader instance from a musicxml string
grader.assessDynamics();
// outputs a decimal number based on the grading rubrics below...
```
![](https://raw.githubusercontent.com/galinabee/GradeLevel/master/reference_media/grade_level1.png)

![](https://raw.githubusercontent.com/galinabee/GradeLevel/master/reference_media/grade_level1.png)

### assessDynamics(instrumentName)
provides an assessment, grading from 1-6, of dynamics in a score, with instrument specification

### assessDynamicsChoral(instrument)
provides an individual instrument assessment, grading from 1-6, of dynamics for a choral instrument

### assessDynamicsInstrument(instrument)
provides an individual instrument assessment, grading from 1-6, of dynamics for an instrument

### assessMeter(instrumentName)
provides an assessment, grading from 1-6, of meter in a score, with instrument specification

### assessRhythmicComplexity(instrumentName)
provides an assessment, grading from 1-6, of rhythmic complexity in a score, with instrument specification

### assessTempo(instrumentName)
provides an assessment, grading from 1-6, of tempo in a score, with instrument specification

