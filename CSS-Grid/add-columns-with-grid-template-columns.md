<!--Simply creating a grid element doesn't get you very far. You need to define the structure of the grid as well. To add some columns to the grid, use the grid-template-columns property on a grid container as demonstrated below:

.container {
  display: grid;
  grid-template-columns: 50px 50px;
}
This will give your grid two columns that are each 50px wide. The number of parameters given to the grid-template-columns property indicates the number of columns in the grid, and the value of each parameter indicates the width of each column.

Give the grid container three columns that are each 100px wide.-->

<style>
  .d1{background:LightSkyBlue;}
  .d2{background:LightSalmon;}
  .d3{background:PaleTurquoise;}
  .d4{background:LightPink;}
  .d5{background:PaleGreen;}

  .container {
    font-size: 40px;
    width: 100%;
    background: LightGray;
    display: grid;
    <!--Only change code below this line-->
    grid-template-columns: 100px 100px 100px;

    <!--Only change code above this line-->
  }
</style>
