<template>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Amatic+SC&display=swap" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Gruppo&display=swap" rel="stylesheet">
  <br>
  <div style="background: transparent; border-radius: 25px;">
    <h1 class="PadderTop" style="font-family: 'Gruppo', cursive;  align-self: center; color: #908e8b ">Wedding Photography Pricing and Packages</h1>
  </div>
  <div>
  <img class="Sizer" style=" font-family: 'Amatic SC', cursive; padding-top: 5px;" src="@/assets/WhiteBox.png" />
  <img class="Sizer" style=" font-family: 'Amatic SC', cursive; padding-top: 5px;" src="@/assets/BlueBox.png" />
    <br>
  <img class="Sizer-Yellow" style=" font-family: 'Amatic SC', cursive; bottom: 15px" src="@/assets/YellowBox.png" />
    <br>
    <br>
    <p class="Padder" style="font-family: 'Gruppo', cursive;  align-self: center; color: #908e8b ">If you find that these packages do not meet your requirements then I’m happy to tailor you a more bespoke package and quote.</p>
    <p></p>
    <img style="height: 150px" src="@/assets/arrow.png" />
    <p></p>
    <img  style="padding: 50px; height: 350px;" src="@/assets/Offers.png"/>
    <p class="Padder" style="font-family: 'Gruppo', cursive;  align-self: center; color: #908e8b; padding-bottom: 10px;  ">Travel Costs Apply After A 40 Mile Radius Of Oswaldtwistle.</p>

  </div>
</template>

<script>


</script>

<style>
.Sizer{
  height: 400px;
}
.Sizer-Yellow{
  height: 400px;
}
.Padder{
  padding-left: 25px;
  font-size: 32px;
}
.PadderTop{
  padding-left: 25px;
  font-size: 50px;
}
@media only screen and (max-width: 500px) {
  .Sizer {
    height: 250px;
    width: 350px;
  }
  .Sizer-Yellow{
    height: 250px;
    width: 350px;
    padding-right: 20px;
  }
  .Padder{
    padding-left: 0px;
    font-size: 22px;
  }
  .PadderTop{
    font-size: 30px;
    padding-left: 0px;
  }
}
</style>