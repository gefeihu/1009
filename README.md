# 1009
<!doctype html>
<html>
<head>
                <style>
        #container {
            height: 100px;
            width: 100px;
            background-color: black;

        }
                </style>
                <script src="https://d3js.org/d3.v4.min.js"></script>
</head>
<body>
 <body>
<script>
                var width = 500;
                var height = 500;

                //Create SVG element
                var svg = d3.select("body")
                .append("svg")
                .attr("width", width)
                .attr("height", height);

                //Create line element inside SVG
    svg.append("line")
       .attr("x1", 100)
       .attr("x2", 500)
       .attr("y1", 50)
       .attr("y2", 50)
       .attr("stroke", "black")
</script>
</body>
</html>
