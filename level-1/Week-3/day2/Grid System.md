```html
   <div class="container">

        <!-- Bootstrap grid system uses a series of containers, rows, and columns to layout and align content -->

        <!-- Start of the first row -->

        <div class="row">

            <!-- Creating a column that spans 4 out of the 12 total columns in the grid -->

            <!-- Col-md-4 means this column will take up 4 columns on medium or larger devices -->

            <div class="col-md-4" style="background-color: lavender;">Column 1</div>

  

            <!-- Another column, also spanning 4 columns -->

            <div class="col-md-4" style="background-color: lavenderblush;">Column 2</div>

  

            <!-- The last column in this row, also spanning 4 columns -->

            <div class="col-md-4" style="background-color: lightcyan;">Column 3</div>

        </div>

        <!-- End of the first row -->

  

        <!-- Start of the second row -->

        <div class="row">

            <!-- This column will automatically adjust its size to take the full width of the row on extra small devices -->

            <!-- On medium devices, it will use 6 out of 12 columns -->

            <div class="col-12 col-md-6" style="background-color: lightyellow;">Column 4</div>

  

            <!-- This column will also adjust to full width on small screens -->

            <!-- Takes up the remaining space on medium and larger screens -->

            <div class="col-12 col-md-6" style="background-color: lightgreen;">Column 5</div>

        </div>

        <!-- End of the second row -->

    </div>
```