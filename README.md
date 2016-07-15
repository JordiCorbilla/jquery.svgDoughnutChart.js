# jquery.svgDoughnutChart.js
A Simple SVG doughnut chart

![chart1](https://cloud.githubusercontent.com/assets/7347994/16887210/8c7988a0-4ad0-11e6-9d2d-73e9f00fdd08.png)
![chart2](https://cloud.githubusercontent.com/assets/7347994/16887215/93f452c2-4ad0-11e6-9069-53f7c53f0347.png)

## Installation & Use

*1. Get the script*
-------
Manual Download:
https://github.com/JordiCorbilla/jquery.svgDoughnutChart.js/releases/tag/0.1

Via Nuget:
https://www.nuget.org/packages/jquery.svgDoughnutChart.js/0.1.0

*2. Include the script in your HTML*
-------
```XML
<script src="~/Scripts/Custom/jquery.svgDoughnutChart.js"></script>
```

*3. Create the element in the page*
-------
```XML
<div id="container"></div>
```

*4. Initialise the chart*
-------
```javascript
    $('#container').doughnutChart({
        positiveColor: "red",
        negativeColor: "blue",
        backgroundColor: "white",
        percentage: 52,
        size: 100,
        doughnutSize: 0.35,
        innerText: "52%",
        innerTextOffset: 12,
        Title: "Share of the popular vote",
        positiveText: "52.5% Barack Obama",
        negativeText: "47.5% Others"
    });
```

**Licence**
-------

    The MIT License (MIT)
    
    Copyright (c) 2015 Jordi Corbilla
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
