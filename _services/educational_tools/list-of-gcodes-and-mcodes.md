---
title: "List of G-codes and Commonly Used M-Codes"
featured: true
weight: 2
layout: content
---



{% include caption.html
    caption = "Table 1: G-Codes"    
%}

| Code  | Function                                |
|:-----:|:----------------------------------------|
|  G00  | Positioning at rapid travel             |
|  G01  | Linear interpolation using a feed rate  |
|  G02  | Circular interpolation (CW)             |
|  G03  | Circular interpolation (CCW)            |
|  G04  | Dwell                                   |
|  G09  | Exact stop                              |
|  G10  | Data setting                            |
|  G17  | Select $X-Y$ plane                      |
|  G18  | Select $Z-X$ plane                      |
|  G19  | Select $Z-Y$ plane                      |
|  G20  | Imperial units (inches)                 |
|  G21  | Metric units (millimeter)               |
|  G22  | Stored stroke limit setting             |
|  G23  | Stored stroke limit cancel              |
|  G27  | Reference point return check            |
|  G28  | Return to reference point               |
|  G29  | Return from reference point             |
|  G30  | 2nd, 3rd, or 4th reference point return |
| G30.1 | Floating reference point return         |
|  G31  | Skip/probe function                     |
|  G40  | Cancel cutter compensation              |
|  G41  | Cutter compensation left                |
|  G42  | Cutter compensation right               |
|  G43  | Tool length compensation $(+)$          |
|  G44  | Tool length compensation $(-)$          |
|  G45  | Tool position offset increase           |
|  G46  | Tool position offset decrease           |
|  G47  | Tool position offset double increase    |
|  G48  | Tool position offset double decrease    |
|  G49  | Tool length compensation cancel         |
|  G50  | Reset all scale factors to 1.0          |
|  G51  | Set axis data input scale factors       |
| G50.1 | Programmable mirror image cancel        |
| G51.1 | Programmable mirror image               |
|  G52  | Local coordinate system setting         |
|  G53  | Machine coordinate system setting       |
|  G54  | Work coordinate system 1 selection      |
|  G55  | Work coordinate system 2 selection      |
|  G56  | Work coordinate system 3 selection      |
|  G57  | Work coordinate system 4 selection      |
|  G58  | Work coordinate system 5 selection      |
|  G59  | Work coordinate system 6 selection      |
|  G60  | Single direction positioning            |
|  G61  | Exact stop mode                         |
|  G62  | Automatic corner overide                |
|  G63  | Tapping mode                            |
|  G64  | Cutting mode                            |
|  G65  | Macro call                              |
|  G66  | Macro modal call                        |
|  G67  | Macro modal call cancel                 |
|  G68  | Coordinate rotation                     |
|  G69  | Coordinate rotation cancel              |
| G72.1 | Rotation copy                           |
| G72.2 | Parallel copy                           |
|  G73  | Pattern Repeating Cycle                 |
|  G74  | Left hand tapping Mill                  |
|  G74  | Face grooving cycle                     |
|  G76  | Fine boring cycle                       |
|  G80  | Cancel cycles                           |
|  G81  | Drill cycle                             |
|  G82  | Drill cycle with dwell                  |
|  G83  | Peck drilling cycle                     |
|  G84  | Tapping cycle                           |
| G84.2 | Rigid tapping cycle                     |
| G84.3 | Rigid counter tapping cycle             |
|  G85  | Boring cylce                            |
|  G86  | Boring cycle (spindle stop, rapid out)  |
|  G87  | Backboring cycle                        |
|  G88  | Boring cycle (manual return)            |
|  G89  | Boring cycle (with dwell)               |
|  G90  | Absolute programming                    |
|  G91  | Incremental programming                 |
|  G92  | Alternation of work-coordinate system   |
| G92.1 | Work coordinate preset                  |
|  G98  | Canned cycle initial point return       |
|  G99  | Canned cycle reference point return     |




{% include caption.html
    caption = "Table 2. Commonly used M-codes"    
%}

| Code | Function                  |
|:----:|:--------------------------|
|  M0  | Program stop              |
|  M1  | Optional stop             |
|  M2  | End of program            |
|  M3  | Spindle CW start          |
|  M4  | Spindle CCW start         |
|  M5  | Spindle stop              |
|  M6  | Automatic tool change     |
|  M7  | Mist coolant on           |
|  M8  | Flood coolant on          |
|  M9  | Coolant off               |
| M10  | 4th axis clamp            |
| M11  | 4th axis unclamp          |
| M12  | 5th axis clamp            |
| M13  | 5th axis unclamp          |
| M19  | Spindle orientation stop  |
| M30  | End of program and rewind |
